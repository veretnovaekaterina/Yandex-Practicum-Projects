# Проект : Рекомендация тарифов

## Описание проекта

Оператор мобильной связи «Мегалайн» выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра».

## Задача

Необходимо построить модель для задачи классификации, которая выберет подходящий тариф. 
Построить модель с максимально большим значением accuracy. Чтобы сдать проект успешно, нужно довести долю правильных ответов по крайней мере до 0.75. 
Инструкция по выполнению проекта

## План работ

Разделить исходные данные на обучающую, валидационную и тестовую выборки.
Исследовать качество разных моделей, меняя гиперпараметры. Описать выводы исследования.
Проверить качество модели на тестовой выборке.
Дополнительное задание: проверьте модели на вменяемость. 

## Описание данных
Каждый объект в наборе данных — это информация о поведении одного пользователя за месяц. 
Известно:
сalls — количество звонков,
minutes — суммарная длительность звонков в минутах,
messages — количество sms-сообщений,
mb_used — израсходованный интернет-трафик в Мб,
is_ultra — каким тарифом пользовался в течение месяца («Ультра» — 1, «Смарт» — 0).

## Вывод

Мы исследовали качество разных моделей. Самое низкое значение accurasy у нас плучитось на модели Логичкская регрессия.Самое высокое на модели Случайный лес.
