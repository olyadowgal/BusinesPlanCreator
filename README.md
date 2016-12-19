# BusinesPlanCreator
<h1>Програмний продукт для забезпечення процедури автоматизованого створення бізнес плану</h1> 
Необхідно створити експертну систему яка дозволяє:<br>
1.	На основі даних, що вводить користувач запропонувати на вибір галузь діяльності для бізнесу користувача. Галузі повинні бути посортовані так, як треба користувачу, тобто в залежності від того, який показник для нього є головним користувач самостійно може обрати сортування галузей. <br>
2.	Під час вибору користувач повинен отримати розгорнуту інформацію про вид підприємницької діяльності.<br>
3.	Після того як користувач вибере діяльність і введе дані, що необхідні для формування плану програма вибере необхідний шаблон бізнес плану.<br>
4.	Програма видає на виході файл з готовим бізнес планом. Бізнес план у форматі xls і з введеними формулами, тому при зміні параметрів не буде необхідності заново відкривати програму.<br>
Документації, книги та шаблони знаходяться у папці на Дропбоксі за посиланням: https://www.dropbox.com/sh/i18jy83fpjuw2t9/AAA6n58HvS7K2PKXjsK-HWkFa?dl=0

<h1>Методологічні пояснення</h1>
https://ukrstat.org/uk/operativ/operativ2012/sze/sze_met.html

<h1>Архітектура програмного продукту, хто за неї відповідає та особливості частин</h1>

<h2>Парсер сайту /ukrstat.org</h2>
Автори Інна Бакум та Ірина Маленко

<i>виконано</i>

Окремий програмний продукт, який формує json файли з статистичними даними, доступними за наступними посиланнями:
Кількість підприємств
http://ukrstat.org/uk/operativ/operativ2013/fin/kp_ed/kp_ed_u/kp_ed_u_2015.htm  
Кількість суб’єктів господарювання
http://ukrstat.org/uk/operativ/operativ2014/fin/osp/ksg/ksg_u/ksg_u_14.htm  
Кількість зайнятих працівників
http://ukrstat.org/uk/operativ/operativ2014/fin/osp/kzp/kzp_u/kzp_u_14.htm  
Рентабельність
https://ukrstat.org/uk/operativ/operativ2016/fin/rodp/rodp_ed/rodp_ed_u/rodp_ed_0116_u.htm  
Обсяг реалізованої продукції
https://ukrstat.org/uk/operativ/operativ2013/fin/kp_ed/kp_ed_u/orp_ed_u_2015.htm  
Обсяг виробленої продукції
https://ukrstat.org/uk/operativ/operativ2015/fin/ovpp/ovpp_2014_u.htm  
Чистий прибуток (збиток)
https://ukrstat.org/uk/operativ/operativ2016/fin/chpr/chpr_ed/chpr_ed_u/chpr_ed_0116_u.htm  
Витрати на персонал
https://ukrstat.org/uk/operativ/operativ2013/fin/kp_ed/kp_ed_u/vpp_ed_u_2015.htm  

<h2>UI та основні класи програми</h2>

Автори Владислав Старіков та Ольга Довгаль 

<i>у розробці</i>

Розробка інтерфейсу користувача та структори класів у програмному продукті

<h2>Збирач бізнес плану</h2>

Автор Микола Мельников

<i>у розробці</i>

Частина основного програмного продукту який збирає готовий бізнес план.

<h2>Оформлення шаблону бізнес плану</h2>

Автор Юлія Литвин

<i>виконано</i>

Шаблон бізнес плану у форматі xls, для подальшої роботи з ним користувача.
Шаблон знаходиться за посиланням - https://www.dropbox.com/s/t3j61j9jd1317gb/bp.xlsx?dl=0

<h2> Оформлення документацій та патенту, тестування </h2>

Автори Черняк Сергій та Тертичний Денис

<i>у розробці</i>

Оформлення документації та патенту, виявлення помилок.
