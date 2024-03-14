## Задача прогноза оттока клиентов для оператора связи <br/>

[HTML](./customer_churn_forecast.html)
[ipynb](./customer_churn_forecast.ipynb)

***
#### Задача:

Оператор связи хочет бороться с оттоком клиентов. Для этого его сотрудники начнут предлагать промокоды и специальные условия всем, кто планирует отказаться от услуг связи. Чтобы заранее находить таких пользователей, оператору необходима модель, которая будет предсказывать, разорвёт ли абонент договор. 

В нашем распоряжении данные, собранные командой оператора (персональные данные о некоторых клиентах, информация об их тарифах и услугах). Необходимо обучить на этих данных модель для прогноза оттока клиентов.

***
#### Навыки и инструменты:

* python
* pandas
* numpy 
* phik
* shap
* matplotlib
* sklearn.compose.make_column_transformer
* sklearn.preprocessing.OneHotEncoder
* sklearn.preprocessing.StandardScaler
* lightgbm.LGBMClassifier
* sklearn.linear_model.LogisticRegression 
* sklearn.ensemble.RandomForestClassifier
* sklearn.metrics.roc_curve
* sklearn.metrics.roc_auc_score,
* sklearn.metrics.accuracy_score,
* sklearn.metrics.confusion_matrix
* sklearn.model_selection.RepeatedStratifiedKFold
* sklearn.model_selection.cross_validate
* sklearn.model_selection.cross_val_predict,
* sklearn.model_selection.GridSearchCV

***
#### Общий вывод:
* Проанализированы имеющиеся данные и взаимосвязи между ними.
* Выделены и обработаны необходимые для моделирования признаки.
* Проведено обучение 3 разных моделей бинарной классификации для предсказания разорвёт ли абонент договор.
* Обоснован выбор наилучшей модели и проведена ее проверка на тестовых данных.
* Проведен анализ важности признаков.
* Проведен анализ качества выбранной модели в разрезе требований бизнеса.
* Полученные результаты работы, выводы и рекомендации заказчику упакованы в краткий вывод/отчет в конце тетради. 
