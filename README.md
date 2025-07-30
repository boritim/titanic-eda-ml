# Titanic EDA + ML

Исследование данных пассажиров Titanic и предсказание выживания с помощью логистической регрессии.

## Используемые технологии

- Jupyter Notebook
- pandas, seaborn, matplotlib
- scikit-learn

## Что в проекте

- Исследование данных (EDA)
- Визуализация зависимостей (возраст, пол, класс)
- Предобработка: обработка пропусков, кодирование
- ML модель и оценка её качества

## Запуск

```bash
git clone https://github.com/boritim/titanic-eda-ml.git
cd titanic-eda-ml

python -m venv venv
source venv/bin/activate

pip install -r requirements.txt
jupyter notebook
```

## Данные

Используется [датасет Titanic с Kaggle](https://www.kaggle.com/competitions/titanic/data).
Поместите файл `train.csv` в папку `data/` перед запуском.