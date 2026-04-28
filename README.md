# Credit Risk Prediction

Проект по предсказанию вероятности дефолта заёмщика.

## Описание

Бинарная классификация: предсказываем, допустит ли заёмщик дефолт по кредиту (`loan_status`: 0 — нет, 1 — да).

## Стек

- Python, pandas, numpy
- scikit-learn (LogisticRegression, RandomForestClassifier, GridSearchCV, ColumnTransformer)
- matplotlib / seaborn (визуализация)

## Что сделано

### 1. EDA
- Анализ распределений числовых и категориальных признаков
- Проверка пропущенных значений
- Анализ корреляций и дисбаланса классов

### 2. Предобработка
- `ColumnTransformer`: `StandardScaler` для числовых признаков, `OneHotEncoder` для категориальных
- Разбивка на train/test (80/20)
