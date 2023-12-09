#  ***Проект: Анализ резюме из HeadHunter***   
![](https://toplogos.ru/images/logo-hh-ru.png)
## Оглавление
[1. Описание проекта](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/README.md#Описание-проекта)   
[2. Краткая информация о данных](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/README.md#Краткая-информация-о-данных)   
[3. Этапы работы над проектом](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/README.md#Этапы-работы-над-проектом)   
[4. Результат](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/README.md#Результат)
 
 ### Описание проекта
 Компания HeadHunter хочет построить модель, которая бы автоматически определяла примерный уровень заработной платы, подходящей пользователю, исходя из информации, которую он указал о себе. Но,прежде чем построить модель, данные необходимо преобразовать, исследовать и очистить. В этом и состоит наша задача.

 :arrow_up:[к оглавлению](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/README.md#Оглавление)

 ### Краткая информация о данных  
 [*Ссылка на диск с основной базой данных*](https://drive.google.com/file/d/14CxzJpfj_ozSiok9l-cAlREVmAa116-G/view?usp=drive_link)
 - dst-3.0_16_1_hh_database.csv - база данных соискателей с сайта hh.ru   
 - ExchangeRates.csv - таблица с курсами иностранных валют

  :arrow_up:[к оглавлению](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/README.md#Оглавление)

  ### Этапы работы над проектом
  - [Исследование структуры данных](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/solutions.ipynb#research)
  - [Преобразование данных](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/solutions.ipynb#section-10)
  - [Исследование зависимостей в данных](https://github.com/ArtemYanot/ -ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/solutions.ipynb#cell15)   
    #### Ссылки на графики, поддерживаемые и не поддерживаеммые платформой GitHub вместе с выводами:
    - [Графики распределения признака ''Возраст''](https://htmlpreview.github.io/?https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/Charts/Графики_распределения_признака_''Возраст''.html)
        - [Вывод](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/solutions.ipynb#conclusion1)
    - [Графики распределения признака ''Опыт работы (месяц)''](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/Charts/Графики_распределения_признака_''Опыт_работы_месяц''.html)
        - [Вывод](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/solutions.ipynb#conclusion2)
     - [Графики распределения признака ''ЗП (руб)''](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/Charts/Графики_распределения_признака_''ЗП_руб''.html)
        - [Вывод](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/solutions.ipynb#conclusion3)
     - [Диаграмма медианной желаемой ЗП от уровня образования](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/Charts/Диаграмма_медианной_желаемой_ЗП_от_уровня_образования.html)
        - [Вывод](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/solutions.ipynb#conclusion4)            
     - [Распеределение желаемой ЗП в зависимости от города](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/Charts/Распеределение_желаемой_ЗП_в_зависимости_от_города.html)
        - [Вывод](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/solutions.ipynb#conclusion5)       
     - [Зависимость медианной желаемой ЗП от готовности к переезду и готовности к командировкам](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/Charts/Зависимость_медианной_желаемой_ЗП_от_готовности_к_переезду_и_готовности.html)
        - [Вывод](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/solutions.ipynb#conclusion6)    
     - [Тепловая карта зависимостит медианной желаемой ЗП от Возраста и Образования](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/solutions.ipynb#heatmap)
        - [Вывод](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/solutions.ipynb#conclusion7)
     - [Зависимость опыта работы от возраста](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/Charts/Зависимость_опыта_работы_от_возраста.html)
        - [Вывод](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/solutions.ipynb#conclusion8)
     - [Распеределение желаемой ЗП в зависимости от пола соискателя](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/Charts/Распеределение_желаемой_ЗП_в_зависимости_от_пола_соискателя.html)
        - [Вывод](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/solutions.ipynb#conclusion9)
     - [Зависимость медианной желаемой ЗП от города и желания работать удалённо](Диаграмма_медианной_желаемой_ЗП_от_уровня_образования.html)
        - [Вывод](conclusion10)

  - [Очистка данных](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/solutions.ipynb#clear)

   :arrow_up:[к оглавлению](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/README.md#Оглавление)

### Результат
В результате мы получили преобразованную базу данных, в которой отсутствуют аномальные значения, тепрь на её основе можно построить необходимую модель. Также мы произвели поиск зависемойстей между некоторымми данными и отобразили их с помощью графиков.

  :arrow_up:[к оглавлению](https://github.com/ArtemYanot/-ANALYSIS-OF-RESUMES-FROM-HEADHUNTER/tree/main/README.md#Оглавление)



