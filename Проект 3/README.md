# Прогнозирование инсульта головного мозга 🧠

Этот проект представляет собой решение задачи прогнозирования инсульта головного мозга с использованием методов машинного обучения. Проект включает в себя полный анализ данных, предобработку и обучение различных моделей для предсказания вероятности инсульта.

## Основные характеристики

- **Тип задачи**: Бинарная классификация
- **Размер датасета**: 4981 запись
- **Количество признаков**: 11 (после предобработки)
- **Точность предсказания**: 95.05%

## Структура проекта

```text
brain_stroke_prediction/
├── data/
│   └── brain_stroke.csv
├── notebooks/
│   ├── 1_data_analysis.ipynb
│   ├── 2_feature_engineering.ipynb
│   └── 3_modeling.ipynb
├── src/
│   ├── preprocessing.py
│   └── models.py
└── README.md
```

## Технические требования

```python
import numpy as np 
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import sklearn
import warnings
```

## Основные результаты

1. **Анализ данных**:
  - Выявлены ключевые факторы риска инсульта:
    - Гипертония
    - Сердечно-сосудистые заболевания
    - Возраст (выше 40 лет)
    - Статус курения




2. **Предобработка данных**:
  - Нормализация признаков
  - Категоризация возраста
  - Кодирование категориальных переменных
  - Стратифицированное разделение на обучающую и тестовую выборки



