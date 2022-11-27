# Название проекта: Прогнозирование оттока клиектов Телеком компании
## Описание проекта
Телекомуникационная компания хочет научиться прогнозировать отток клиентов. 
<br>Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. 
<br>Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах.
## Цель проекта
- Построить модель для прогнозирования оттока клиентов
- Уровень **ROC-AUC** должен быть не ниже **0.86**
## Ход исследования
- Предобработка данных
- Объединение датафреймов, исследование общей таблицы
- Разделение на выборки (test_size = 25%)
- Применение техник кодирования с учётом моделей, которые будут использованы
- Масштабирование данных (при необходимости)
- Обучение трёх моделей на тренировочной выборке (подбор гиперпараметров)
- Выбор оптимальной модели (по результатам кросс-валидации, метрика ROC-AUC)
- Проверка качества лучшей модели на тестовой выборке (три метрики: ROC-AUC, Recall, Precision), формирование матрицы ошибок и выявление важности признаков
- Отчёт
## Используемые инструменты
- Python
- pandas
- numpy
- matplotlib
- seaborn
- phik
- time
- scikit-learn
- catboost