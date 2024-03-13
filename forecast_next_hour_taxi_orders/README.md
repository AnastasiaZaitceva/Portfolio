## Задача для компании такси <br/>

[HTML](./forecast_next_hour_taxi_orders.html)
[ipynb](./forecast_next_hour_taxi_orders.ipynb)

***
#### Задача:

Компания собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Необходимо построить модель для такого предсказания.

В качестве метрики использовать RMSE, ее значение на тестовой выборке должно быть не больше 48.

***
#### Навыки и инструменты:

* python
* pandas
* matplotlib
* shap
* xgboost
* sklearn.model_selection.TimeSeriesSplit
* sklearn.linear_model.LinearRegression
* sklearn.model_selection.cross_val_score
* sklearn.metrics.mean_squared_error
* statsmodels.tsa.seasonal.seasonal_decompose
* statsmodels.tsa.stattools.adfuller
* statsmodels.graphics.tsaplots.plot_pacf

***
#### Общий вывод:
* Проведен анализ и предобработка данных.
* Опробованы две модели линейной регрессии (LinearRegression и xgboost). Обоснован выбор оптимальной модели.
* Проведен анализ важности признаков.
* Полученные результаты работы, выводы и рекомендации заказчику упакованы в краткий вывод/отчет в конце тетради.
