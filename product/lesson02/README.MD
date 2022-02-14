# Agile. Scrum
## Основы технологических стеков. 
В любом технологическом стеке есть стандартный алгоритм знакомства с технологией:
* Организация рабочего места: запуск редактора кода и возможность запускать соответствующий код
* Типовой код: простой код, который можно запустить и он показывает основную функциональность соответствующего технологического стека
* Набор задач, решив которые начинающий разработчик в данном технологическом стеке познакомится с основными особенностями
* Обзор типовых проектов: на примере которых вы сможете разобраться как создавать проекты

### Рабочее место
Можно выделить 2 типа рабочих мест: он-лайн и офф-лайн
* **офф-лайн рабочее место** - позволяет эффективно работать и быстро создавать программное обеспечение. Минусом такого варианта организации рабочего места могут быть сложности с настройкой программ на вашем локальном компьютере.
* **он-лайн рабочее место** - ограничивает скорость работы, но, гарантирует работу сервиса, т.к. она не зависит от операционных систем и настроек компьютера.

#### Он-лайн рабочие места по технологическим стекам

|№|Направление разработки|Сервисы для типовых проектов|
|---|---|---|
|1|FrontEnd|  https://replit.com/ , https://codepen.io/  |
|2|BackEnd| https://www.pythonanywhere.com/ (Python), https://schoolsw3.com/php/phptryit.php (PHP)  |
|3|Mobile|http://online.swiftplayground.run/ (Swift) https://play.kotlinlang.org/ (Kotlin) |
|4|GameDev| https://replit.com/ (C#),  |
|5|IoT| htps://www.pythonanywhere.com/ (Python) , https://thingsboard.io/  (IoT)  |
|6|Data Processing| htps://www.pythonanywhere.com/ (Python)    |
|7|Design| https://www.photopea.com/ |
|8|Programming4kids|https://blockly.games/puzzle?lang=ru  <br> https://catrobat.org/our-apps/  <br> https://www.figma.com/ <br> https://logojoy.com/ <br>https://www.remove.bg/ru |


https://iotji.io/solutions-ua/ 


#### Офф-лайн рабочие места по технологическим стекам
|№|Направление разработки|Сервисы для типовых проектов|
|---|---|---|
|1|FrontEnd| https://code.visualstudio.com/  |
|2|BackEnd| https://code.visualstudio.com/ , https://www.jetbrains.com/ru-ru/pycharm-edu/ , https://www.python.org/downloads/ (Python) <br>  https://www.apachefriends.org/download.html  , https://ospanel.io/ ,  https://code.visualstudio.com/  |
|3|Mobile|https://www.jetbrains.com/objc/ , https://developer.apple.com/swift/ (Swift) , hhttps://www.jetbrains.com/idea/ (Kotlin) |
|4|GameDev| https://visualstudio.microsoft.com/ru/downloads/ , https://unity.com/ (C#),  |
|5|IoT| hhttps://code.visualstudio.com/ , https://www.jetbrains.com/ru-ru/pycharm-edu/ , https://www.python.org/downloads/ (Python)   |
|6|Data Processing| https://code.visualstudio.com/ , https://www.jetbrains.com/ru-ru/pycharm-edu/ , https://www.python.org/downloads/ (Python)     |
|7|Design| https://www.adobe.com/products/photoshop/free-trial-download.html , https://www.adobe.com/products/illustrator/free-trial-download.html , https://www.figma.com/ |


### Типовой код

* [FrontEnd (Tilda)](https://github.com/mikh-maksi/teachersup/tree/main/product/lesson02/fe_tilda)
* [FrontEnd (Создание сайта)](https://github.com/mikh-maksi/teachersup/tree/main/product/lesson02/fe)
* [Python (создание Телеграм-бота)](https://github.com/mikh-maksi/teachersup/tree/main/product/lesson02/python)
* [GameDev (C# - текстова игра)](https://github.com/mikh-maksi/teachersup/tree/main/product/lesson02/gamedev)
* [Design](https://drive.google.com/file/d/1SnSrA2AePeEHeya12BoKhNv2lo9wWQsU/view)

## Планирование проекта. 
Как спланировать проект?   
Основным вопросом, на который нужно ответить при планировании проекта является вопрос: "Какую проблему мы решаем?". Расписанный по пунктам ответ на этот вопрос будет первоначальным планом соответствующего проекта.  
После того, как мы ответили на вопрос о том, какую проблему мы решаем нам необходимо визуализировать работу реализуемого проекта необходимо **создать прототип** (макет). Самым простым инструментом прототипирования является листок и ручка, но также существует большое количество он-лайн сервисов, которые позволяют создать прототип: https://draw.io/ , https://www.figma.com/ , https://www.invisionapp.com/ .
После создания прототипа важным элементом является описание его функциональности. Для этого - важно проставить на прототипе номера зон и под соответствующими номерами **описать функционал**.
После описания функционала важно выделить **MVP** (minimum value product) - создание какого наименьшего набора элементов будет иметь ценность при сохранении концепции проекта.
Остальной список добавления функицональности должен учитывать расширение **MVP** - создавая дополнительную ценность с каждым новым релизом (добавлением элементов).

|#|Действие|Требование к описанию этапа|
|---|---|---|
|1|Какую проблему решаем?|1 предложение|
|2|Как решаем основную проблему?|последовательность действий|
|3|Какова структура проекта?|Список страниц/экранов проекта|
|4|Как будет выглядеть интерфейс проекта?|Созданные прототипы страниц/экранов<br> https://draw.io/ , https://www.figma.com/ , https://www.invisionapp.com/|
|5|Опишите функционал проекта|На прототипе указать цифрами основные функциональные элементы. Составить нумерованный список, в котором каждый элемент является описание функционального элемента, отмеченного цифрой на прототипе|
|6|Создание MVP|Опишите ту функциональность проекта, при реализации которой проект уже будет давать результат, но затраты на его реализацию будут минимальными|
|7|Опишите последовательность реализации проекта|Список функций, которые будут реализованы после реализации MVP.|

## Связь проекта с учебной программой. 
Желательно, чтобы проект, который реализуется, опирался на пункты учебной программы. Для этого важно - определить какие элементы позволят реализовать **MVP** и далее развивать его. При этом, определив знания по какой теме необходимы для реализации проекта.

## Основы менеджмента. 
## Манифест Agile. 
## Процедуры и артефакты Scrum. 

## Инструменты индикации прогресса проекта. 
## Лидерство по Адизесу. 
## Мотивация по Маслоу. 
## Дашборд проекта. 
## Таск-трекер Trello.

