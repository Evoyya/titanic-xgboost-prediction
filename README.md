![Python](https://img.shields.io/badge/Python-3.10+-blue)
![XGBoost](https://img.shields.io/badge/XGBoost-Latest-orange)
![License](https://img.shields.io/badge/License-MIT-green)

# 🚢 Titanic Survival Prediction: XGBoost

Проект машинного обучения для предсказания выживаемости пассажиров Титаника с использованием градиентного бустинга (XGBoost) и современных пайплайнов Scikit-Learn.

## Результаты

- **ROC-AUC:** 0.8763 ± 0.0238
- **Accuracy:** 0.88

## Технологии

- **Python 3.10+**
- **XGBoost** — градиентный бустинг
- **Scikit-Learn** — пайплайны, кросс-валидация, подбор гиперпараметров
- **Pandas/Numpy** — обработка данных
- **Matplotlib/Seaborn** — визуализация

## Особенности решения

1. **ColumnTransformer** для автоматической обработки числовых и категориальных признаков
2. Сравнение **GridSearchCV vs RandomizedSearchCV**
3. **Early Stopping** для предотвращения переобучения
4. Production-ready пайплайн без утечки данных

## Быстрый старт

### Установка зависимостей
```bash
pip install -r requirements.txt
```
### Запуск notebook
```bash
 jupyter notebook XGBoosting_Titanic.ipynb
```
## Структура 
```bash
titanic-xgboost-prediction/
├── XGBoosting_Titanic.ipynb   # Основной ноутбук
├── README.md                   # Описание проекта
├── requirements.txt            # Зависимости
└── .gitignore                  # Игнорируемые файлы
```
## Процесс работы
1. EDA (Exploratory Data Analysis) — анализ данных
2. Preprocessing Pipeline — автоматическая обработка
3. Model Training — обучение XGBoost
4. Hyperparameter Tuning — оптимизация параметров
5. Evaluation — оценка качества модели
6. Final Pipeline - финальный Pipeline
7. Saving the model - сохранение итоговой модели 

## Важность признаков
| # | Признак   | Важность |
|--:|:----------|---------:|
| 1 | Sex_male  | 57.0%    |
| 2 | Pclass    | 17.1%    |
| 3 | Age       | 5.5%     |
| 4 | SibSp     | 4.9%     |

## 📝 Источник данных
Датасет Titanic из Kaggle

## Автор
Evoyya
