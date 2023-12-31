# Проект: Отток клиентов

## Описание проекта

Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.
Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Нам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. 
Необходимо построить модель с предельно большим значением F1-меры. 
Дополнительно нужно измерить AUC-ROC, сравнивайте её значение с F1-мерой.

## План работы
Загрузить и подготовьть данные. Пояснить порядок действий.
Исследовать баланс классов, обучить модель без учёта дисбаланса. 
Улучшить качество модели, учитывая дисбаланс классов. Обучить разные модели и найти лучшую. 
Провести финальное тестирование.

## Описание данных

Признаки
RowNumber — индекс строки в данных
CustomerId — уникальный идентификатор клиента
Surname — фамилия
CreditScore — кредитный рейтинг
Geography — страна проживания
Gender — пол
Age — возраст
Tenure — сколько лет человек является клиентом банка
Balance — баланс на счёте
NumOfProducts — количество продуктов банка, используемых клиентом
HasCrCard — наличие кредитной карты
IsActiveMember — активность клиента
EstimatedSalary — предполагаемая зарплата
Целевой признак
Exited — факт ухода клиента

## Вывод
В данном исследовании мы изучили и подготовили данные, Исследовали баланс классов и обучили модель сначала без учета дизбаланса, а потом и с учетом. Нашли, что при увеличении выборки модель случайного леса показывает наибольшее значение А1. Проверили на этой модели тестовую выборку. Значение F1-метрики на на тестовой модели 0,589 а площадь под кривой 0,84, что приближается к 1, то есть доля истинно-положительных ответов достаточно высока.
