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
titanic-xgboost-prediction/
├── XGBoosting_Titanic.ipynb   # Основной ноутбук
├── README.md                   # Описание проекта
├── requirements.txt            # Зависимости
└── .gitignore                  # Игнорируемые файлы

## Процесс работы
EDA (Exploratory Data Analysis) — анализ данных

Feature Engineering — создание признаков

Preprocessing Pipeline — автоматическая обработка

Model Training — обучение XGBoost

Hyperparameter Tuning — оптимизация параметров

Evaluation — оценка качества модели

## Важность признаков
| Признак  | Важность |
| -------- | -------- |
| Sex_male | 57.0%    |
| Pclass   | 17.1%    |
| Age      | 5.5%     |
| SibSp    | 4.9%     |

## 📝 Источник данных
Датасет Titanic из Kaggle

## Автор
Evoyya
