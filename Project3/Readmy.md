# Исследование объявлений о продаже квартир

## Задача проекта

Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир

## Описание задачи

На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра. Проведена предобработка данных. Добавлены новые данные. Построены гистограммы, боксплоты, диаграммы рассеивания

## Вывод

Цены на недвижимость и количество предложений будут расти по направлению к центру. За близость к историческому центру придется заплатить больше. Так же на стоимость повлияет метраж и количество комнат. А вот выбор этажа может съэкономить, первый этаж обойдется дешевле всех, на втором месте - последний, золотая середина скидок не сделает. Среднее время продажи 178 дней. Медианное время продажи 94 дня. Некоторые квартиры продавались сразу после публикации, а некоторые квартиры "висели" в публикации до четырех лет. Быстрыми продажами можно считать квартиры, которые продавались в течение 45 дней. Медленными - 228 дней. В десяти населенных пунктах с наибольшим числом объявлений самый дорогой квадратный метр жилья в Санкт-Петербурге, самый дешевый в Выборге. Самая высокая стоимость квадратного метра в Зеленогорске, самая низкая в деревне Старополье.

В ходе исследования мы провели изучение и обработку данных: нашли и изучили пропущенные значения в столбцах, устранили некоторые пропуски, заполнили пропущенные значения там, где это возможно, рассмотрели типы данных в столбцах и зпреобразовали их там, где это было необходимо. Изучили уникальные значения в столбце с названиями населенных пунктов и исправили неявные дубликаты (поменяли ё на е и городской поселок на поселок городского типа).

