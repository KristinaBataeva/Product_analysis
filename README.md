# Product_analysis
Здесь представлены проекты, связанные с продуктовой аналитикой.

## Small_ml
Папка с небольшими ml проектами.

## AB_tests
Папка с проектами, посвящёнными анализу результатов AB тестов.


<h3><a href="https://github.com/KristinaBataeva/Product_analysis/blob/main/DAGS_ETL_report_and_alert.ipynb">DAGS_ETL_report_and_alert</a></h3>
Даги, отражающие состояние продукта. Первый даг ETL, собирает данные из таблиц, считает метрики по срезам и загружает их в таблицу в ClickHouse, заранее созданную для этих целей. Второй даг - это ежедневный отчет по метрикам продукта с помощью бота в тг. Третий даг - даг-алерт, находящий аномалии и сообщающий о них с помощью того же бота в тг.

  ---
<h3><a href="https://github.com/KristinaBataeva/Product_analysis/blob/main/EDA_mobile.ipynb">EDA_mobile</a></h3>
Тестовое, выполненное для одной из компаний. Необходимо проанализировать использование фильтров пользователями на страницах городов. Выяснила, что оплата наличными может являться лишним фильтром. По сути это небольшое EDA, для проверки одного из пунктов использовался t-test. 

  ---
<h3><a href="https://github.com/KristinaBataeva/Product_analysis/blob/main/ebay_API_EDA.ipynb">ebay_API_EDA</a></h3>
Тестовое, выполненное для одной из компаний. Задачей было освоить eBay APi (я выбрала Finding), собрать какие угодно данные и сделать EDA. Небольшой искусственный эксперимент с помощью bootstrap прилагается.

  ---
<h3><a href="https://github.com/KristinaBataeva/Product_analysis/blob/main/taxi_churn.ipynb">taxi_churn</a></h3>
Есть данные о такси-компании (uber), которая хочет изучить отток водителей и посмотреть, какие есть различия между водителями, которые покидают сервис, и которые остаются. Были выявлены различия для таких водителей по городам, устройствам, и активности в первые 30 дней после установки сервиса. По условию задачи следовало использовать лишь непараметрические методы: Манна-Уитни, Краскела-Уоллиса, а также хи-квадра для анализа частот категориальных переменных.

  ---
<h3><a href="https://github.com/KristinaBataeva/Product_analysis/blob/main/RFM.ipynb">RFM</a></h3>
Проведение RFM сегментации и ответ на ряд вопросов, связанных с этими сегментами.
