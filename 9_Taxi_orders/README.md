# Прогнозирование заказов такси

## Данные

Исторические данные о заказах такси в аэропортах по минутам

## Задача

Построить модель для определения числа привлекаемых на маршруты водителейна основе данных о количестве заказов в ближайший час 

## Используемые библиотеки
*pandas, numpy, sklearn, matplotlib, seaborn, math, statsmodels, scipy, datetime, date, time, phik, catboost, lightgbm, itertools*

## Используемые методы
*LinearRegression, DecisionTreeRegressor, RandomForestRegressor, ExtraTreesRegressor, CatBoostRegressor, LGBMRegressor, HistGradientBoostingRegressor, ElasticNet, Lasso, Ridge, train_test_split, Pipeline, OneHotEncoder, OrdinalEncoder, LabelEncoder, StandardScaler, MinMaxScaler, RobustScaler, PowerTransformer, normaltest, shapiro, anderson, qqplot, RandomizedSearchCV, permutation_importance, seasonal_decompose, adfuller, TimeSeriesSplit*

## Метрики
*mean_squared_error, mean_absolute_error, root_mean_squared_error*

## Выводы

Лучшая модель: HistGradientBoostingRegressor
Значение RMSE  на тестовой выборке: 38.7201, что соответствует условиям задачи

Модель уловила основные закономерности, в целом выглядит довольно не плохо.

Но пиковые значения (значения выше 200 заказов в час, а также минимальные значения) она не предсказывает.
