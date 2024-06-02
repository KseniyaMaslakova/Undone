# ЖК Undone
Мы хотим посмотреть, какие параметры больше всего влияют на класс недвижимости исходя из рельных данных на [сайте единой информационной системы жилищного строительства](https://xn--80az8a.xn--d1aqf.xn--p1ai/). По каждому объекту есть информация о высоте потолков, общей жилой площади, парковках, инфраструктуры для маломобильных лиц, разных параметров благоустройства; мы попытаемся оценить что все-таки наибольшим образом формирует класс недвижимости и не переоценен ли он.

1. Мы скачали с сайта ЕИСЖС более 10тыс HTML-страничек об объектах недвижимости: [[01] - data_download.ipynb](https://github.com/KseniyaMaslakova/Undone/blob/8c8e0b6237742662c60f75735d84bc19e8031ae3/%5B01%5D%20-%20data_download.ipynb); скачанные HTML-странички можно посмотреть по [ссылке](https://drive.google.com/uc?id=1KaiWg6ulE-u0NU8IQelMKl1iCShJO9rZ)
2. Парсинг собранных HTML-страничек: [[02] - parse_data.ipynb](https://github.com/KseniyaMaslakova/Undone/blob/8c3f7d0d573bd9deb824306f85081440b578aea9/%5B02%5D%20-%20parse_data.ipynb)
3. Предобработка данных и создание новых признаков: [[03] - preanalysis.ipynb](https://github.com/KseniyaMaslakova/Undone/blob/ef177fe20a6da6ebd253f4e32fc8c2a31d6968da/%5B03%5D%20-%20preanalysis.ipynb))
4. EDA и визуализации: [[04] - EDA+visualisation.ipynb](https://github.com/KseniyaMaslakova/Undone/blob/c8e006b59ae0076f7badf7ec0749a5e4c3b6ef6d/%5B04%5D%20-%20EDA%2Bvisualisation.ipynb). В конце EDA мы добавили наши гипотезы и предположения по ML.
5. Тестирование гипотез с помощью статистических методов: [[05] - hypothesis_stat_methods.ipynb](https://github.com/KseniyaMaslakova/Undone/blob/57ed937ebbcf6e43e95c48052fb074fa0824e345/%5B5%5D%20-%20hypothesis_stat_methods.ipynb)
6. Машинное обучение: [[06] - ML.ipynb](https://github.com/KseniyaMaslakova/Undone/blob/a910b1e7704dfb8d9aa62d0c13a0596a15171b7a/%5B05%5D%20-%20ML.ipynb)
   
Таблицы с данными:
- [UnDone.csv](https://github.com/KseniyaMaslakova/Undone/blob/4f4adf2c752fa2ce0c0b0a8c868945975f41a029/UnDone.csv) - изначальный необработанный датасет
- [Residential.csv](https://github.com/KseniyaMaslakova/Undone/blob/4f4adf2c752fa2ce0c0b0a8c868945975f41a029/Residential.csv) - обработанный датасет, на основе которго делались визуализации и строились гипотезы
- [final.csv](https://github.com/KseniyaMaslakova/Undone/blob/4f4adf2c752fa2ce0c0b0a8c868945975f41a029/final.csv) - финальный датасет, который использовался при проверке гипотез и машинном обучении



