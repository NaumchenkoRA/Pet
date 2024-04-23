Техническое задание по проекту: 
Аналитика ДТП по предоставленным данным

Описание

Работа над задачей исследования данных о дорожно-транспортных происшествиях (ДТП).

Заказчиком (Оунером задачи) выступает проект «Карта ДТП» https://dtp-stat.ru/ — некоммерческий проект, посвященный проблеме дорожно-транспортных происшествий в России. Это платформа сбора данных о ДТП, бесплатный и открытый сервис аналитики ДТП.

Цель проекта - провести глубокий анализ данных, сформулировать и проверить гипотезы, опираясь на доступные признаки.

Задачи
1.	Провести исследовательский анализ данных о ДТП.
2.	Сформулировать и проверить не менее трех гипотез, основываясь на имеющихся признаках.
3.	*Провести анализ ДТП по всем датасетам, представленным на сайте.
4.	**Построить дашборд используя любой удобный инструмент, с учетом того, что дашборд может быть опубликован
Возможные гипотезы (или мифы) о ДТП:
●	Всему виной пьяные водители, надо усилить наказание
●	Безопасность на дорогах растет для каждого из участников
●	В личном автомобиле ехать безопаснее чем в автобусе
●	Если пешеходы не будут нарушать, то не будут гибнуть
●	Низкая скорость не влияет на тяжесть ДТП
Описание данных
●	данные в формате geojson с сайта https://dtp-stat.ru/opendata
Примечание: для каждого субъекта РФ - свой geojson. 

Этапы выполнения проекта
1. Загрузка и первичная обработка информации методами geopandas и/или json. Участник выбирает один/несколько субъектов РФ и загружает соответствующие geojson или парсит данные. 
2. Проведение исследовательского анализа данных - предобработка, EDA, визуализация, оценка корреляции, формулировка и проверка гипотез (либо построение дашборда). 
3. Формулирование выводов по полученным результатам. 

Результат выполнения проекта: 

1. Тетрадь Jupyter Notebook или ссылка на колаб.
2. ** Ссылка на дашборд.

Стек технологий
geopandas, json, seaborn, plotly, matplolib, pandas.
