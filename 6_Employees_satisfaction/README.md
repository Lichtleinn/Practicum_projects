# Удовлетворенность сотрудников работой в компании

## Данные

Данные заказчика с признаками:
- уникальный идентификатор сотрудника;
- dept — отдел, в котором работает сотрудник;
- level — уровень занимаемой должности;
- workload — уровень загруженности сотрудника;
- employment_years — длительность работы в компании (в годах);
- last_year_promo — показывает, было ли повышение за последний год;
- last_year_violations — показывает, нарушал ли сотрудник трудовой договор за последний год;
- supervisor_evaluation — оценка качества работы сотрудника, которую дал руководитель;
- salary — ежемесячная зарплата сотрудника;
- job_satisfaction_rate — уровень удовлетворённости сотрудника работой в компании, целевой признак.

## Задача

1. Построить модель, которая сможет предсказать уровень удовлетворённости сотрудника на основе данных заказчика. 
2. Построить модель, которая сможет на основе данных заказчика предсказать то, что сотрудник уволится из компании.
   
## Используемые библиотеки
*pandas, numpy, sklearn, matplotlib, seaborn, plotly.express, math, os, scipy, statsmodels, phik*

## Используемые методы
*LinearRegression, LogisticRegression, KNeighborsClassifier, SVC, DecisionTreeClassifier, DecisionTreeRegressor, RandomForestRegressor, ExtraTreesRegressor, train_test_split, Pipeline, ColumnTransformer, OneHotEncoder, OrdinalEncoder, LabelEncoder, StandardScaler, MinMaxScaler, RobustScaler, PowerTransformer, PolynomialFeatures, normaltest, shapiro, anderson, qqplot, f_classif, pearsonr, phik_matrix, plot_correlation_matrix, RandomizedSearchCV, permutation_importance, ConfusionMatrixDisplay*

## Метрики
*symmetric mean absolute percentage error, confusion_matrix, cross_val_score*
