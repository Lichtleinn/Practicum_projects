# Металлургический комбинат

## Данные

Данные состоят из нескольких файлов, полученных из разных источников.

данные об электродах
- номер партии
- Начало нагрева дугой — время начала нагрева
- Конец нагрева дугой — время окончания нагрева
- Активная мощность — значение активной мощности
- Реактивная мощность — значение реактивной мощности

данные о подаче сыпучих материалов (объём)
- номер партии
- Bulk 1 … Bulk 15 — объём подаваемого материала
  
данные о подаче сыпучих материалов (время)
- номер партии
- Bulk 1 … Bulk 15 — время подачи материала

данные о продувке сплава газом
- номер партии
- Газ 1 — объём подаваемого газа

результаты измерения температуры
- номер партии
- Время замера — время замера
- Температура — значение температуры

данные о проволочных материалах (объём)
- номер партии
- Wire 1 … Wire 15 — объём подаваемых проволочных материалов

данные о проволочных материалах (время)
- номер партии
- Wire 1 … Wire 15 — время подачи проволочных материалов

## Задача

Построить модель предсказания температуры сплава с учетом заданных факторов и набора лигирующих добавок.

## Используемые библиотеки
*pandas, numpy, sklearn, matplotlib, seaborn, plotly.express, statsmodels, math, scipy, math, phik, shap, datetime, catboost, lightgbm*

## Используемые методы
*DummyRegressor, LinearRegression, LogisticRegression, DecisionTreeClassifier, DecisionTreeRegressor, SVC, ElasticNet, Lasso, Ridge, CatBoostClassifier, CatBoostRegressor, HistGradientBoostingRegressor, RandomForestRegressor, ExtraTreesRegressor, train_test_split, OneHotEncoder, OrdinalEncoder, LabelEncoder, StandardScaler, SimpleImputer, normaltest, shapiro, anderson, qqplot, Pipeline, permutation_importance, GridSearchCV, RandomizedSearchCV*

## Метрики
*mean_absolute_error, r2_score*
