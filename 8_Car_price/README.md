# Определение стоимости автомобилей

## Данные
Признаки автомобилей
  
## Задача
Построить модель, которая предсказывает стоимоть подержанных автомобилей на основе технических характеристик, комплектации, года выпуска. Критерии, которые важны заказчику:
- качество предсказания
- время обучения модели
- время предсказания модели

## Используемые библиотеки
*pandas, numpy, sklearn, matplotlib, seaborn, datetime, time, math, scipy, phik, catboost, lightgbm*

## Используемые методы
*LinearRegression, LogisticRegression, DecisionTreeClassifier, DecisionTreeRegressor, RandomForestClassifier, RandomForestRegressor, ExtraTreesRegressor, CatBoostClassifier, CatBoostRegressor, LGBMRegressor, Pool, cv, train_test_split, Pipeline, SimpleImputer, OneHotEncoder, OrdinalEncoder, LabelEncoder, StandardScaler, MinMaxScaler, RobustScaler, normaltest, shapiro, anderson, qqplot, RandomizedSearchCV*

## Метрики
*root_mean_squared_error*

## Выводы

По точности предсказаний лидирует LGBMRegressor. Однако, у него самое долгое время обучения и предсказания.

На втором месте по точности (с незначительной разницей) CatBoostRegressor, при этом время обучения и предсказания у него значительно ниже, чем у LGBMRegressor. Из рассмотренных вариантов по времени - это 3-е место.

Наиболее быстрая по времени, но наименее подходящая по точности предсказания LinearRegressor.

Оптимальной моделью по группе параметров является CatBoostRegressor.
