# Удовлетворенность сотрудников работой в компании

## Данные

Данные заказчика о сотрудниках и степени их удовлетворенности работой

## Задача

1. Построить модель, которая сможет предсказать уровень удовлетворённости сотрудника на основе данных заказчика. 
2. Построить модель, которая сможет на основе данных заказчика предсказать то, что сотрудник уволится из компании.
   
## Используемые библиотеки
*pandas, numpy, sklearn, matplotlib, seaborn, plotly.express, math, os, scipy, statsmodels, phik*

## Используемые методы
*LinearRegression, LogisticRegression, KNeighborsClassifier, SVC, DecisionTreeClassifier, DecisionTreeRegressor, RandomForestRegressor, ExtraTreesRegressor, train_test_split, Pipeline, ColumnTransformer, OneHotEncoder, OrdinalEncoder, LabelEncoder, StandardScaler, MinMaxScaler, RobustScaler, PowerTransformer, PolynomialFeatures, normaltest, shapiro, anderson, qqplot, f_classif, pearsonr, phik_matrix, plot_correlation_matrix, RandomizedSearchCV, permutation_importance, ConfusionMatrixDisplay*

## Метрики
*symmetric mean absolute percentage error, confusion_matrix, cross_val_score*

## Выводы

Определены:
- портрет среднего сотрудника компании
- факторы, влияющие не степень удовлетворенности работой
- портрет среднего уволившегося сотрудника

Лучшей моделью для 1 задачи стал RandomForestRegressor
Метрика SMAPE на тестовых данных: 12.43

Лучшей моделью для 2 задачи стал DecisionTreeClassifier
Метрика ROC-AUC на тестовой выборке: 0.93

Приведены рекомендации для улучшения степеи удовлетворенности сотрудников работой в компании
