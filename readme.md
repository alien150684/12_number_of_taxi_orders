# Прогнозирование количества заказов такси

## Задача проекта
Разработка модели для предсказания  количества заказов такси на следующий час.

## Аннотация проекта
Компания такси собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. В рамках проекта обучено несколько моделей: линейная регрессия, CatBoost. Проведено сравнение моделей с помощью метрики RMSE, значение которой не должно превышать 48. Лучшие результаты показала модель CatBoost.

## Ключевые слова проекта
временной ряд, декомпозиция, линейная регрессия, градиентный бустинг

## Описание данных

Признак
-	datetime — дата и время

Целевой признак
- num_orders — количество заказов такси

## Статус проекта
Завершён.