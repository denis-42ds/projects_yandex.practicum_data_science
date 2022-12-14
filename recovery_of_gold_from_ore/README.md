# Название проекта: Восстановление золота из руды
## Статус проекта: завершён
## Описание проекта
Необходимо подготовить прототип модели машинного обучения для «Цифры». 
<br>Компания разрабатывает решения для эффективной работы промышленных предприятий.
<br>Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. 
<br>Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.
## Цель проекта
- Подбор модели машинного обучения для предсказания количества золота в руде
## Ход исследования
- Изучение данных.
- Подготовка данных.
- Анализ данных.
- Написание функции для расчёта метрики **sMAPE**
- Обучение моделей
- Тестирование лучшей модели
- Заключение
## Используемые инструменты
- Python
- pandas
- numpy
- matplotlib
- scikit-learn
## Заключение:
<br>Лучшей моделью для выполнения поставленной задачи оказалась модель Случайного Леса с параметрами: 
<br>количество деревьев 61, глубина 5, полученное итоговое sMAPE на тестовой выборке получилось равным 9.88