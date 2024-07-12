# Возраст покупателей по фото

## Данные

Набор фотографий людей с указанием возраста

## Задача

Построить модель нейронной сети, которая по фотографии определит приблизительный возраст человека.

## Используемые библиотеки
*pandas, numpy, tensorflow, PIL*

## Используемые методы
*LinearRegression, LogisticRegression, OneVsRestClassifier, train_test_split, StandardScaler, OneHotEncoder, keras, Sequential, Conv2D, Flatten, Dense, AvgPool2D, GlobalAveragePooling2D, Adam, ImageDataGenerator, ResNet50, Image*

## Метрики
*accuracy_score, precision_score, recall_score, r2_score, mean_squared_error, mean_absolute_error*

## Выводы

Для решения задачи была обучена модель ResNet50
Применена архитектура модели: backbone (без заморозки) + Top
В модели использованы предобученные веса
Метрика МАЕ модели = 6,29 на 10 эпохах
