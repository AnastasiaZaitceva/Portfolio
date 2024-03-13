## Задача для сервиса по продаже автомобилей <br/>

[HTML](./determination_model_market_value.html)
[ipynb](./determination_model_market_value.ipynb)

***
#### Задача:

Сервис по продаже автомобилей с пробегом разрабатывает приложение, чтобы привлечь новых клиентов. В нём можно будет узнать рыночную стоимость своего автомобиля.

Необходимо построить модель, которая умеет её определять. В нашем распоряжении данные о технических характеристиках, комплектации и ценах других автомобилей.

Критерии, которые важны заказчику:

* качество предсказания (метрика RMSE < 2500);
* время обучения модели;
* время предсказания модели.

***
#### Навыки и инструменты:

* python
* pandas
* numpy
* seaborn
* shap
* time
* matplotlib
* catboost.CatBoostRegressor
* lightgbm.LGBMRegressor
* sklearn.tree.DecisionTreeRegressor
* sklearn.dummy.DummyRegressor
* sklearn.compose.ColumnTransformer
* sklearn.metrics.mean_squared_error
* sklearn.preprocessing.OneHotEncoder
* sklearn.preprocessing.StandardScaler
* category_encoders.m_estimate.MEstimateEncoder
* sklearn.model_selection.GridSearchCV

***
#### Общий вывод:
* Проведен анализ и предобработка данных.
* Проведено обучение 3 разных моделей для предсказания рыночной стоимости автомобиля.
* Обоснован выбор наилучшей модели и проведена ее проверка на тестовых данных.
* Проведен анализ важности признаков.
* Полученные результаты работы, выводы и рекомендации заказчику упакованы в краткий вывод/отчет в конце тетради.
