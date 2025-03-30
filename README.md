# User-Based Collaborative Filtering for MovieLens

Этот проект реализует модель **User-Based Collaborative Filtering** для рекомендаций фильмов, используя данные из [MovieLens Small Dataset](https://www.kaggle.com/datasets/shubhammehta21/movie-lens-small-latest-dataset/data).

## Описание проекта

Данный проект основан на методе **коллаборативной фильтрации**, который анализирует схожесть между пользователями для предсказания оценок фильмов.

**Основные этапы работы модели:**

1. Загрузка и предобработка данных
2. Разделение данных на тренировочную и тестовую выборки
3. Вычисление **косинусного сходства** между пользователями
4. Генерация рекомендаций на основе схожести пользователей
5. Оценка качества модели

## Используемые библиотеки

- `numpy`
- `pandas`
- `scikit-learn`

## Структура проекта

- `main.ipynb` – основной код с реализацией модели
- `requirements.txt` – список зависимостей
- `.gitignore` – файлы, исключенные из репозитория

## 🚀 Запуск проекта

1. Установите зависимости:
   ```bash
   pip install -r requirements.txt

   ```
2. запустите main.ipynb
