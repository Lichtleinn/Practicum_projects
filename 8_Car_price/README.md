# Определение стоимости автомобилей

## Данные
Признаки автомобилей:
- DateCrawled — дата скачивания анкеты из базы
- VehicleType — тип автомобильного кузова
- RegistrationYear — год регистрации автомобиля
- Gearbox — тип коробки передач
- Power — мощность (л. с.)
- Model — модель автомобиля
- Kilometer — пробег (км)
- RegistrationMonth — месяц регистрации автомобиля
- FuelType — тип топлива
- Brand — марка автомобиля
- Repaired — была машина в ремонте или нет
- DateCreated — дата создания анкеты
- NumberOfPictures — количество фотографий автомобиля
- PostalCode — почтовый индекс владельца анкеты (пользователя)
- LastSeen — дата последней активности пользователя
- Price — цена (евро)
  
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
