# Исследование данных о российском кинопрокате

Заказчик исследования данного исследования — Министерство культуры Российской Федерации. Данные опубликованы на портале открытых данных Министерства культуры. Набор данных содержит информацию о прокатных удостоверениях, сборах и государственной поддержке фильмов, а также информацию с сайта КиноПоиск

**Цели:**
- Выявление текущих трендов на российском рынке кинопроката
- Оценка интереса зрителей к фильмам с государственной поддержкой

**Задачи:**  
- Предобработка данных  
- Исследовательский анализ данных
  
**Стек:**  Pandas, Matplotlib, NumPy, Seaborn
  
**Ход работы:**  
- Загрузка данных и объединение таблиц
- Предобработка данных
- Генерация новых признаков
- Исследовательский анализ данных:
  - Общее исследование фильмов
  - Исследование фильмов которые получили государственную поддержку
  
**Выводы:**
Общее исследование:
1. Прокат:
- Наиболее полно информация о прокате фильмов представленна в период с 2015 по 2019 гг;
- Наибольшее количество фильмов в прокате в 2019г, наименьшее в 2017г;
2. Сборы:
- Наибольший объем сборов наблюдается в 2018 г, наименьший в 2010;
- С 2015 наблюдается резкий скачок в увеличении сборов;
- В период с 2015 по 2109 г наблюдается значительное отличие среднего показателя объемов сборов от медианного;
3. Возрастые ограничения:
- в 2016 году значительный рост сборов на фильмы возрастным ограничением 6+ и 0+;  
Предположительно, основной причиной роста показателей с 2015 года является полнота предоставленных данных. Во вторых, в этот период выходили фильмы способствующие росту объемов сборов.

Исследование фильмов с господдержкой:

4. Окупаемость:
- В целом фильмы с господдержкой не окупаются, за исключением жанров: комедия и спорт. Имеют коэффициенты окупаемости 1.5 ти 2.4.
5. Объем финансирования:
- Наибольший объем финансироания приходится на художественное кино и является невозвратными средствами;
6. Источник финансирования:
- Основной источник финансирования  - фонд кино.
