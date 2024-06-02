# ЖК Undone
Мы хотим посмотреть, какие параметры больше всего влияют на класс недвижимости исходя из рельных данных на [сайте единой информационной системы жилищного строительства](https://xn--80az8a.xn--d1aqf.xn--p1ai/). По каждому объекту есть информация о высоте потолков, общей жилой площади, парковках, инфраструктуры для маломобильных лиц, разных параметров благоустройства; мы попытаемся оценить что все-таки наибольшим образом формирует класс недвижимости и не переоценен ли он.

1. Мы скачали с сайта ЕИСЖС более 10тыс HTML-страничек об объектах недвижимости: [[01] - data_download.ipynb](https://github.com/KseniyaMaslakova/Undone/blob/8c8e0b6237742662c60f75735d84bc19e8031ae3/%5B01%5D%20-%20data_download.ipynb); скачанные HTML-странички можно посмотреть по [ссылке](https://drive.google.com/uc?id=1KaiWg6ulE-u0NU8IQelMKl1iCShJO9rZ)
2. Парсинг собранных HTML-страничек: [[02] - parse_data.ipynb](https://github.com/KseniyaMaslakova/Undone/blob/60ed5e178face1ad05273af0f00b0f9c010e58a5/%5B02%5D_parse_data.ipynb)
3. Предобработка данных и создание новых признаков: [[03] - preanalysis.ipynb](https://github.com/KseniyaMaslakova/Undone/blob/ef177fe20a6da6ebd253f4e32fc8c2a31d6968da/%5B03%5D%20-%20preanalysis.ipynb))
4. EDA и визуализации: [[04] - EDA+visualisation.ipynb](https://github.com/KseniyaMaslakova/Undone/blob/c8e006b59ae0076f7badf7ec0749a5e4c3b6ef6d/%5B04%5D%20-%20EDA%2Bvisualisation.ipynb). В конце EDA мы добавили наши гипотезы и предположения по ML.
5. Машинное обучение: [[05] - ML](https://github.com/KseniyaMaslakova/Undone/blob/a910b1e7704dfb8d9aa62d0c13a0596a15171b7a/%5B05%5D%20-%20ML.ipynb)
   

