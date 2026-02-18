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
