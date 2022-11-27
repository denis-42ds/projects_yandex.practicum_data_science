# Название проекта: Выбор локации для скважины
## Описание проекта
Добывающей компании «ГлавРосГосНефть» нужно решить, где бурить новую скважину.
<br>Нам предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, 
<br>где измерили качество нефти и объём её запасов. 
<br>Проанализируйте возможную прибыль и риски техникой Bootstrap.

<br>Шаги для выбора локации:

- В избранном регионе ищут месторождения, для каждого определяют значения признаков;
- Строят модель и оценивают объём запасов;
- Выбирают месторождения с самым высокими оценками значений. Количество месторождений зависит от бюджета компании и стоимости разработки одной скважины;
- Прибыль равна суммарной прибыли отобранных месторождений.

<br>Условия задачи:

- Для обучения модели подходит только линейная регрессия (остальные — недостаточно предсказуемые).
- При разведке региона исследуют 500 точек, из которых с помощью машинного обучения выбирают 200 лучших для разработки.
- Бюджет на разработку скважин в регионе — 10 млрд рублей.
- При нынешних ценах один баррель сырья приносит 450 рублей дохода. Доход с каждой единицы продукта составляет 450 тыс. рублей, поскольку объём указан в тысячах баррелей.
- После оценки рисков нужно оставить лишь те регионы, в которых вероятность убытков меньше 2.5%. Среди них выбирают регион с наибольшей средней прибылью.
## Цель проекта
- Необходимо построить модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль
## Ход исследования
- Загрузка и подготовка данных
- Обучение и проверка модели для каждого региона
- Поготовка к расчёту прибыли
- Написание функцию для расчёта прибыли по выбранным скважинам и предсказаниям модели
- Расчёт рисков и прибыли для каждого региона
- Заключение
## Используемые инструменты
- Python
- pandas
- numpy
- scikit-learn