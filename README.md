# yandex_prakticum_projects
Проекты в рамках курса Яндекс-практикум
<table>
    <tr>
        <th>Проект</th>
        <th>Задачи проекта</th>
        <th>Описание проекта</th>
        <th>Навыки и инструменты</th>
    </tr>
    <tr>
        <td>Анализ бизнес показателей развлекательного приложения Procrastinate Pro+</td>
        <td>Задача для маркетингового аналитика развлекательного приложения Procrastinate Pro+. Несмотря на огромные вложения в рекламу, последние несколько месяцев компания терпит убытки. Ваша задача — разобраться в причинах и помочь компании выйти в плюс.</td>
        <td>Проведен анализ данных от ProcrastinatePRO+. Рассчитаны различные метрики, использован когортный анализ: LTV, CAC, Retention rate, DAU, WAU, MAU и т.д. Использованы уже написанные ранее функции расчёта метрик. Сделаны правильные выводы по полученным данным</td>
        <td>Matplotlib, Pandas, Python, Seaborn, когортный анализ, продуктовые метрики, юнит-экономика. Обработка данных, статистический тест, LTV, CAC, когортный анализ</td>
    </tr>
    <tr>
        <td>Исследование опроса клиентов телекомунникационной компании. Презентация . Дашборд.</td>
        <td>Исследование данных с результатами опроса, отражающего текущий уровень потребительской лояльности (NPS) клиентов телекоммуникационной компании.</td>
        <td>Заказчик этого исследования — большая телекоммуникационная компания, которая оказывает услуги на территории всего СНГ.Задача определить текущий уровень потребительской лояльности, или NPS (от англ. Net Promoter Score), среди клиентов из России.
Чтобы определить уровень лояльности, клиентам задавали классический вопрос: «Оцените по шкале от 1 до 10 вероятность того, что вы порекомендуете компанию друзьям и знакомым».
Компания провела опрос и попросила меня подготовить дашборд с его итогами. Большую базу данных для такой задачи разворачивать не стали и выгрузили данные в SQLite</td>
        <td>выгрузка данных, обработка данных, визуализация данных, построение дашборда, SQL, SQLite, Tableau</td>
    </tr>
    <tr>
         <td>Анализ продаж компьютерных игр</td>
        <td>Используя исторические данные о продажах компьютерных игр, оценки пользователей и экспертов, жанры и платформы, выявить закономерности, определяющие успешность игры</td>
        <td>Выявлены параметры, определяющие успешность игры в разных регионах мира. На основании этого подготовлен отчет для магазина компьютерных игр для планирования рекламных кампаний. Проведена предобработка данных, анализ. Выбран актуальный период для анализа. Составлены портреты пользователей каждого региона. Проверены гипотезы: средние пользовательские рейтинги платформ Xbox One и PC одинаковые; средние пользовательские рейтинги жанров Action и Sports разные. При анализе использовал критерий Стьюдента для независимых выборок.</td>
        <td>Matplotlib, NumPy, Pandas, Python, исследовательский анализ данных, описательная статистика, предобработка данных, проверка статистических гипотез. Обработка данных, histogram, boxplot, статистический тест, критерий Стьюдента, piechart</td>
    </tr>  
   <tr>
     <td>Выпускной проект Анализ АВ теста</td>
        <td>На основе данных о проанализировать воронку продаж, а также оценить корректность и результаты A/B-тестирования.</td>
        <td>В рамках проекта удалось: оценить корректность проведения теста, проанализировать результаты теста. Чтобы оценить корректность проведения теста, проверено: пересечение тестовой аудитории с конкурирующим тестом, выполнение условий Технического задания, совпадение теста и маркетинговых событий, другие проблемы временных границ теста.</td>
        <td>A/B-тестирование, Matplotlib, Pandas, NumPy, Plotly, Python, Seaborn, визуализация данных, проверка статистических гипотез, продуктовые метрики, событийная аналитика.</td>
    </tr>
    <tr>
        <td>Выпускной проект анализ товарного ассортимента интернет магазина. Презентация и дашборд.ipynb</td>
        <td>Предоставлены данные о продажах интернет-магазина товаров для дома

Задача :
Проанализировать ассортимент товаров.
Выявление основного и дополнительного ассортимента товаров
Формулировка и проверка статистических гипотез</td>
        <td>В данном проекте проведен исследовательский анализ данных EDA. Товары разделены на категории: охарактеризованы их основные свойства, проанализированы основные признаки, наиболее сильно влияющие на показатель выручки. Сформулированы и проверены статистические гипотезы. Даны рекомендации для повышения эффективности работы магазина</td>
        <td>Python, Pandas, Scikit-learn, Matplotlib, Seaborn,  классификация,, Tableau, визуализации, презентация по итогам исследования</td>
    </tr>
    <tr>
        <td>Исследование данных о российском кинопрокате для Министерства Культуры.</td>
        <td>Используя данные государственного портала и сервиса “КиноПоиск”, проведите исследование, изучите текущие тренды и визуализируйте полученные результаты.</td>
        <td>Заказчик этого исследования — Министерство культуры Российской Федерации.
Нужно изучить рынок российского кинопроката и выявить текущие тренды. Уделить внимание фильмам, которые получили государственную поддержку. Попробовать ответить на вопрос, насколько такие фильмы интересны зрителю.
Вы будете работать с данными, опубликованными на портале открытых данных Министерства культуры. Набор данных содержит информацию о прокатных удостоверениях, сборах и государственной поддержке фильмов, а также информацию с сайта КиноПоиск.</td>
        <td>
обработка данных, дубликаты, пропуски, категоризация, histogram, scattermatrix, scatterplot</td>
    </tr>
    <tr>   
       <td>Исследование надежности заемщиков</td>
        <td>На основе статистики о платёжеспособности клиентов исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок</td>
        <td>На основе данных кредитного отдела банка исследовала влияние семейного положения и количества детей на факт погашения кредита в срок. Была получена информация о данных. Определены и обработаны пропуски. Заменены типы данных на соответствующие хранящимся данным. Удалены дубликаты.Выделены леммы в значениях столбца Категоризованы данные. Один датафрейм декомпозирован на три.</td>
        <td>Pandas, Python, предобработка данных. Обработка данных, дубликаты, пропуски, категоризация, декомпозиция</td>
    </tr>
    <tr>   
       <td>Исследование объявлений о продаже квартир</td>
        <td>Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир</td>
        <td>На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра. Проведена предобработка данных. Добавлены новые данные. Построены гистограммы, боксплоты, диаграммы рассеивания.</td>
        <td>Matplotlib, Pandas, Python, визуализация данных, исследовательский анализ данных, предобработка данных. Обработка данных, histogram, boxplot, scattermatrix, категоризация, scatterplot, фрод-мониторинг</td>
       </tr>
    <tr>   
       <td>значение 1.9</td>
        <td>значение 2.9</td>
        <td>значение 3.9</td>
        <td>значение 4.9</td>
       </tr>
    <tr>   
       <td>значение 1.10</td>
        <td>значение 2.10</td>
        <td>значение 3.10</td>
        <td>значение 4.10</td>
       </tr>
    <tr>   
       <td>значение 1.11</td>
        <td>значение 2.11</td>
        <td>значение 3.11</td>
        <td>значение 4.11</td>
       </tr>
    <tr>   
       <td>значение 1.12</td>
        <td>значение 2.12</td>
        <td>значение 3.12</td>
        <td>значение 4.12</td>
       </tr>
    <tr>   
       <td>значение 1.13</td>
        <td>значение 2.13</td>
        <td>значение 3.13</td>
        <td>значение 4.13</td>
      
      
