# Прогнозирование твердости сплавов с использованием машинного обучения

![Python](https://img.shields.io/badge/Python-3.12%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## 🔍 Обзор
Проект разрабатывает модель машинного обучения для предсказания твердости сплавов по шкале Виккерса (HV) на основе их химического состава. 
Используя Random Forest и графовые представления, был достигнут R² = 0.81.

## 🚀 Особенности
- Графовое представление состава сплавов
- Random Forest с MAE = 68.37 HV
- Подробная оценка метрик (RMSE, MAE, R²)
- План улучшений: веса ребер и т.д.

## 📊 Результаты
| Метрика | Значение |
|---------|----------|
| R²      | 0.81     |
| MAE     | 68.37    |
| RMSE    | 92.36    |

## 🛠 Стек
- Python 3.12+
- Scikit-learn
- NetworkX (для графов)
- Pandas/Numpy
