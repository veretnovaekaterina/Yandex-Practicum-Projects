# Проект: Прогнозирование заказов такси

## Описание проекта
Компания «Чётенькое такси» собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Постройте модель для такого предсказания.
Значение метрики RMSE на тестовой выборке должно быть не больше 48.

## План работ
* Загрузить данные и выполнить их ресемплирование по одному часу.
* Проанализировать данные.
* Обучить разные модели с различными гиперпараметрами. Сделайть тестовую выборку размером 10% от исходных данных.
* Проверить данные на тестовой выборке и сделать выводы.

## Выводы:
На переборе параметров лучшее значение метрики у модели CatBoostRegressor() со значением  метрики RMSE на тестовой выборке- 45,93
