# Портфолио: Церцвадзе Марика

## Обо мне 

Всем привет! Меня зовут Марика, я начинающий аналитик данных. 
Я люблю работу с цифрами и все, что с ними связано.
По натуре я иследователь, меня увлекают сложные, интересные задачи и поиск их решения.
В этом репозитории я поделилась некоторыми из моих проектов, выполненными во время обучения и практики.
Буду рада общению с единомышленниками и обратной связи.

<br>

## Навыки и технологии
- Инструменты анализа данных: ``SQL``, ``Excel``: 
- Языки программирования и библиотеки: ``HTML``, ``Python`` 
- Системы управления базами данных: ``MySQL``, ``PostgreSQL``
- Средства визуализации данных: ``Excel``

  
## Проекты
<p> Проект 1: Калькулятор юнит-экономики онлайн-школы</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Посчитать юнит-экономику продукта, все основные метрики.</li>
  <li>Создать калькулятор юнит экономики онлайн-школы, по которому можно наглядно и быстро проверять гипотезы. </li>
  <li>Дополнить данные визуализацией основных показателей.</li>
</ol>
  <br>

  
<p>Краткое описание решения:<p>

На основе агрегированных данных по количеству студентов по месяцам, количеству уроков, ценам на уроки, затраты на маркетинг, выручке, ФОТ, высчитала основные метрики. Был разработан калькулятор, при помощи которого можно посмотреть каких значений показателей необходимо достичь, при той или иной цели.


> <a href="Сборка калькулятора юнит-экономики.xlsx">Ссылка на проект</a>



<p>Итоги:<p>
<ol>
  <li>Подготовлен полезный отчет для бинеса, с помощью которого легко составлять прогнозы</li>
  <li>Собраны и визуализированы все основные показатели юнит-экономики онлайн школы</li>
  <li>Составлен план найма новых сотрудников для маштабирования и увеличения количества уроков</li>
</ol>

<br> 


<p> Проект 2: Калькулятор юнит-экономики онлайн-кинотеатра</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Посчитать юнит-экономику продукта и предложить сценарий по настройке параметров для выхода на 25%-ную маржинальность.</li>
  <li>Собрать визуализации основных бизнес-показателей.</li>
  <li>Исследовать данные о пользователях и их поведении.</li>
</ol>
<br>

<p>Краткое описание решения<p>
Высчитала все основные показатели: Retention, LT, LTR, CAC, цену юнита. Построила калькулятор, при помощи которого можно посмотреть какими могут быть показатели, при интересующих нас значениях маржинальности. Создала наглядную визуализацию, для оценки спроса на продукт: какие пользователи, где и в каком объеме смотрят фильмы на платформе.


> [Юнит экономика онлайн кинотеатра.xlsx](https://github.com/Timurika/-Data-Analitics/blob/ec6c49bb073c6c8f7b41470d95dbd93c3d58b4e5/%D0%AE%D0%BD%D0%B8%D1%82%20%D1%8D%D0%BA%D0%BE%D0%BD%D0%BE%D0%BC%D0%B8%D0%BA%D0%B0%20%D0%BE%D0%BD%D0%BB%D0%B0%D0%B8%CC%86%D0%BD%20%D0%BA%D0%B8%D0%BD%D0%BE%D1%82%D0%B5%D0%B0%D1%82%D1%80%D0%B0.xlsx)

 
<p>Итоги:<p>
<ol>
  <li>Было выявлено, что при данных показателях маржинальность продукта составила -94%, что объясняется высокими затратами на запуск проекта.</li>
  <li>Если выходить на 25% маржинальность, необходимо снизить CAC и FC, допустим до 45% и 30% соответственно.</li>
  <li>По графику распределения пользователей по часовым поясам, можно увидеть, что основная часть находится в европейских регионах, в связи с этим, можно подумать о том, как привлечь пользователей из других регионов.</li>
  <li>Так же по графикам, можно проследить поведенческие привычки большинства пользователей и учитывать это при маштабировании. </li>
</ol>

<br> 

<br> 
<p> Проект 3: Когортный анализ онлайн-кинотеатра с помощью SQL</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Анализ показателей абсолютного и относительного базового ретеншен, LT, LTV, LTR по когортам. </li>
  <li>Сделать выводы относительно хороших и плохих когорт с точки зрения LTV.</li>
</ol>

<p>Краткое описание решения<p>
Создала запрос и далее составила сводную таблицу с абсолютным ретеншеном клиентов по месячным когортам, затем расчитала относительный базовый ретеншен. На основании ретеншена рассчитала LT с помощью метода усредненных прямоугольников для каждой когорты. Рассчитала показатели LTR, LTV, на основе которых сделала выводы.

> <a href="Когортный анализ онлайн кинотеатра">Ссылка на проект</a>

  <p>Выводы:<p>
<ol>
  <li>Майская когорта показала самый высокий LTV за счет высокого лайфтайма</li>
  <li>Ноябрьская когорта тоже показала высокое значение LTV, однако за счет низких костов.</li>
  <li>Самый низкий показатель LTV у январьской когорты, из-за высоких костов. </li>
  <li>Так же низкий LTV показала июньская когорта, за счет низкого лайфтайма</li>
</ol>

<br> 
<p>Проект 4: Моделирование изменения балансов студентов</p> 
<p>Что нужно было сделать:<p>

<ol>
  <li>Смоделировать изменение балансов, т.е. количества уроков, которое есть у каждого студента. </li>
  <li>Создать таблицу, где будут балансы каждого студента за каждый день.</li>
  <li>Проверить, всё ли в порядке с данными, составить список гипотез и вопросов к дата-инженерам и владельцам таблиц, чтобы это понять</li>
</ol>
<br>

<p>Краткое описание решения<p>
Написала код, который выводит правильный результат в том виде, в котором была задача. Собрала вопросы к дата-инженерам о достоверности данных в таблицах, выявлены недочеты. Сделала визуализации и на их основании собрала гипотезы.


> <a href="Моделирование изменения балансов студентов.xlsx">Ссылка на проект</a>

 <p>Выводы (итоги):<p>
<ol>
 <li>Получился запрос, который собирает данные о балансах студентов за каждый прожитый ими день.</li>
 <li>Анализируя итоговую таблицу балансов можно сказать, что прирост балансов был равномерным, без существенных колебаний, однако наблюдается ожидаемый спад в летние месяцы и существенный рост с начала сентября по декабрь, что говорит о сезонной зависимости спроса на обучающий продукт.. </li>
 <li>Анализ динамики покупок (даграмма №3) и списаний (диаграмма №4) в разрезе недели показал, что наблюдается тенденция наибольших покупок с пн по чт, а списаний с пт по вс, что так же ожидаемо, студенты учатся в выходные от основной учебы или работы дни. Предлагаю ориентироваться на эти данные при планировании маркетинговых акций следующих периодов.</li>
</ol>

## Контактная информация
- E-mail: ms.rika07@gmail.com
- Telegram: marika_tsertsvadze
