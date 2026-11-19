# Разведочный анализ данных (EDA): Кредитные риски

Анализ данных о клиентах банка и их кредитной истории для оценки рисков ухода в дефолт и выявления аномалий.

## Источник данных
Датасет взят с [Kaggle — Credit Risk Dataset](https://www.kaggle.com/datasets/ranadeep/credit-risk-dataset/data).
Для запуска скачайте файл `loan.csv` и поместите его в папку `data/`.

## Что сделано
- Проведена очистка данных: удалены редкие категории (`application_type == 'JOINT'`), столбцы с >20% пропусков и неинформативные признаки с сильным перекосом (>80% одного значения).
- Проанализированы распределения ключевых числовых и категориальных признаков (`loan_amnt`, `funded_amnt`, `int_rate`, `installment` и др.).
- Сформулированы выводы по поведению заёмщиков и структуре кредитного портфеля.

## Стек
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook.

## Запуск проекта
```bash
git clone [https://github.com/](https://github.com/)steppenland/credit-risk-eda.git
cd credit-risk-eda
pip install -r requirements.txt
jupyter notebook