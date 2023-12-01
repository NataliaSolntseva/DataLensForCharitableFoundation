# DataLensForCharitableFoundation

**Заказчик**: благотворительный фонд "Арифметика добра" ([сайт фонда](https://a-dobra.ru/))

**Цели работ**: построение презентационного дашборда с отражением показателей деятельности фонда на базе свободно-распростанаемой BI-системы DataLens

**Объект исследования**: выгрузка сырых таблиц из CRM-системы фонда в формате xlxs-файлов, загруженных в google-таблицы 

**Используемые инструменты DataLens**: 
- Типы визуализаций:
    - Линейная диаграмма
    - Накопительная диаграмма с областями
    - Столбчатая диаграмма
    - Линейчатая диаграмма
    - Комбинированная диаграмма
    - Таблица
    - Индикатор
    - Фоновая карта с геополигонами
 - Параметры на уровне датасета/чарта/дашборда
 - Вычисляемые поля:
    -  Агрегатные функции (AVG, COUNT, COUNTD, COUNT_IF, COUNTD_IF, MAX, SUM, SUM_IF)
    -  Логические функции (CASE, IF, IFNULL, ISNULL, ZN)
    -  Оконные функции (AVG_IF, RANK_DENSE, RSUM, SUM)
    -  Логические операторы
    -  Строковые функции
    -  Функции даты и времени
    -  Функции для работы с временными рядами
    -  Функции для работы с массивами
    -  Функции преобразования типов

**Дашборд**: [дотупен по ссылке](https://datalens.yandex/eu2e0tghh6q23?tab=ado)

**Лицензия распространения кода проекта**: Apache License 2.0 

**Задачи, которые были решены в ходе исследования**:
  - Создание подключений и загрузка данных из источника в датасеты
  - Предобработка данных:
      - Проверка наименований столбцов датасета и при необходимости их переименование
      - Анализ пропусков в столбцах датасета, оценка возможности их заполнения
      - Проверка корректности типов данных, их изменение при необходимости
      - Проверка дубликатов в датасете (полных и неявных) и при необходимости их удаление
      - Проверка на корреткность и аномалии значений количественных и качественных параметров датасета
      - 
  - Построение дашборда:
     - Планирование структуры дашборда,
     - Выбор типа вузализаций, отражающих основную деятельность фонда
     - Создание дополнительных вычисляемых полей для построения визуализаций
     - Построение чартов, в том числе на основе двух датасетов
      
**Благодартвенное письмо от имени фонда**:
 <img  alt="bpmn" height="600px" src="https://disk.yandex.ru/i/nwWdM7uD0v6avg"/>


