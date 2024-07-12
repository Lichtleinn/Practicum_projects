# Активность пользователей интернет-магазина

## Данные

Данные для работы находятся в нескольких таблицах:
- данные о поведении покупателя на сайте, о коммуникациях с покупателем и его продуктовом поведении
- данные о выручке, которую получает магазин с покупателя, то есть сколько покупатель всего потратил за период взаимодействия с сайтом
- данные о времени (в минутах), которое покупатель провёл на сайте в течение периода
- данные о среднемесячной прибыли покупателя за последние 3 месяца: какую прибыль получает магазин от продаж каждому покупателю

## Задача

Построить модель , которая позволит компании удерживать активность постоянных клиентов с помощью персонализированных предложений. Для этого требуется на основе групп признаков определить уровень финансовой активности клиентов, рассчитать прибыльность клиентов, предсказать изменение активности в следующие 3 месяца, провести сегментацию клиентов, определить ключевой сегмент и разработать рекомендации о персонализированных предложениях.

## Используемые библиотеки
*pandas, numpy, sklearn, matplotlib, seaborn, plotly.express, math, scipy, statsmodels, phik, shap*

## Используемые методы
*DummyClassifier, LinearRegression, LogisticRegression, KNeighborsClassifier, DecisionTreeClassifier, SVC, OneVsRestClassifier, RandomForestClassifier, train_test_split, Pipeline, ColumnTransformer, RandomOverSampler, SMOTE, SMOTENC, SMOTETomek, ADASYN, OneHotEncoder, OrdinalEncoder, LabelEncoder, StandardScaler, MinMaxScaler, RobustScaler, PowerTransformer, PolynomialFeatures, KFold, StratifiedKFold, normaltest, shapiro, anderson, qqplot, f_classif, mutual_info_classif, pearsonr, phik_matrix, plot_correlation_matrix, OptunaSearchCV, GridSearchCV, RandomizedSearchCV, permutation_importance*

## Метрики
*accuracy_score, precision_score, recall_score, r2_score, mean_squared_error, mean_absolute_error, confusion_matrix, cross_val_score*
