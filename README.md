# PracticalProjects

Данные проекты были реализованы в ходе обучения в Яндекс.Практикум по специализации "Аналитик данных".
В проектах для анализа данных был использовн язык Python, SQL, для визуализации - Tableau. 
Были изучены и использованы для решения практических учебных кейсов такие темы как: 
- предобработка данных (работа с пропусками, дубликатами, типами данных)
- исследовательский анализ данных (выявление и анализ аномалий)
- проверка гипотез (A/B тесты)
- расчет бизнес показателей (когортный анализ, юнит-экономика, вороник)
- машинное обучение (модели прогнозирования и кластеризации).

| Название проекта                                                          | Описание                                            | Используемые библиотеки                   |
| :-------------------------------------------------------------------------| :-------------------------------------------------- | :---------------------------------------- |
| Прогнозирование вероятности оттока пользователей для фитнес-центра        | Прогноз оттока, сегментация клиентов фитнес-центра  | pandas, matplotlib, seaborn, scikit-learn |
| Исследования рынка общепита в Москве для принятия решения об открытии кафе| Анализ рынка общепита Москвы, визуализация результатов |pandas, matplotlib, seaborn, plotly     |
| Создание дашборда по пользовательским событиям для Яндекс.Дзен            | Построение дашборда согласно техническому заданию, анализ популярных тем на Яндекс.Дзен| Tableau, PowerPoint|



--------------------------------------------------------------------------------------------------------------


# Прогнозирование вероятности оттока пользователей для фитнес-центра

**Цель**   
Прогнозирование оттока клиентов на основе ML моделей двух типов "с учителем" и "без учителя"

**Результат**  
Проведен сравнительный анализ двух моделей прогнозирования: логистичекая регрессия и случайный лес.  
Сделана сегментация клиентов на основе алгоритма K-means.  
Сформирована матрица-корреляция между признаками.  
Сформирован портрет клиентов, уходящий в отток и даны рекомендации для удержания клиентов.  

**Библиотеки**  
pandas, matplotlib, seaborn, scikit-learn

**Статус**: завершен


------------------------------------------------------------------------------------------------------

# Исследования рынка общепита в Москве для принятия решения об открытии кафе

**Цель**   
анализ рынка общепита Москвы, предоставление выводов и рекомендаций какого формата и где лучше открывать кафе


**Результат** 

Анализ рынка:  
1. Кафе  - самый популярный тип объекта общественного питания (доля рынка= 39,7%)  
2. 80%  объектов не принадлежат сетям  
3. Предприятия быстрого питания (ПБО) примерно в равной доле представлены сетями и несетевыми объектами  
4. 80% объектов имеют до 86 посадочных мест, менее 1% объектов - более 275 мест.  
5. Топ-5 объектов по кол-ву мест: столовая, ресторан, буфет, бар, кафе  
6. В центральном районе есть улицы с 1 объектом общественного питания  
7. Заведения в центре города имеют в среднем от 25 до 50 посадочных мест

Общие рекомендации:  
открывать кафе с кол-ом мест от 25 до 50 в центральном административном округе Москвы

**Библиотеки**:   
pandas, matplotlib, seaborn, plotly

**Инструмент**:   
Jupyter notebook, PowerPoint

**Статус**:  
Проект: завершен

--------------------------------------------------
## Создание дашборда по пользовательским событиям для Яндекс.Дзен

**Цель**:   
сформировать дашборд согласно ТЗ, анализ популярных статей на Яндекс.Дзен

**Результат**:  
Построен дашборд согласно техническому заданию, графически проанализированы данные.  
На основе анализа предоставлены ответы по популярным темам у читаиелей сервиса Яндекс.Дзен.  
Выданы дальнейшие рекомендации по повышению читательской способности мало популярных тем.  

**Инструменты**:   
Tableau, PowerPoint  

**Статус**:  
Проект: завершен

