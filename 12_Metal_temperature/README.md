# Металлургический комбинат

## Данные

Данные состоят из нескольких файлов, полученных из разных источников.

- данные об электродах
- данные о подаче сыпучих материалов (объём)
- данные о подаче сыпучих материалов (время)
- данные о продувке сплава газом
- результаты измерения температуры
- данные о проволочных материалах (объём)
- данные о проволочных материалах (время)

## Задача

Построить модель предсказания температуры сплава с учетом заданных факторов и набора лигирующих добавок.

## Используемые библиотеки
*pandas, numpy, sklearn, matplotlib, seaborn, plotly.express, statsmodels, math, scipy, math, phik, shap, datetime, catboost, lightgbm*

## Используемые методы
*DummyRegressor, LinearRegression, LogisticRegression, DecisionTreeClassifier, DecisionTreeRegressor, SVC, ElasticNet, Lasso, Ridge, CatBoostClassifier, CatBoostRegressor, HistGradientBoostingRegressor, RandomForestRegressor, ExtraTreesRegressor, train_test_split, OneHotEncoder, OrdinalEncoder, LabelEncoder, StandardScaler, SimpleImputer, normaltest, shapiro, anderson, qqplot, Pipeline, permutation_importance, GridSearchCV, RandomizedSearchCV*

## Метрики
*mean_absolute_error, r2_score*

## Выводы

На основе сравнения метрики MAE, была определена лучшая модель: CatBoostRegressor 
Лучшая метрика на тестовой выборке составляет: 5.86
Метрика R2 на тестовой выборке: 0.52 (Однако следует учитывать, что метрика R2 показывает не очень высокие результаты на выборках с большим числом выбросов и разбросом данных. Наш случай именно такой.)
Наиболее существенно определяют конечную тепературу:
- время нагрева
- начальная температура
- интервал между измерениями температур
