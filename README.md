# Портфолио проектов
[Диплом об окончании курсов Data Science](Sergey%20Polushkin_20222DS00778.pdf)
|Название проекта| Описание | Ссылка |Комментраий|
|----------------|----------|--------|-----------|
|Прогнозирование оттока клиентов «Ниединогоразрыва.ком».|Оператор связи «Ниединогоразрыва.ком» хочет научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах.|[Telecom clients leave](Telecom%20clients%20leave%20prediction.ipynb)|pandas, matplotlib, seaborn, sklearn, CatBoost, LogisticRegression, RandomForest, Pipeline, OneHotEncoding, StandartScaler, GridSearchCV, Regularization, classification, class balance|
|Исследование надежности заемщиков.|Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов. Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.|[Non payments risk](Non%20payments%20risk.ipynb)|pandas|
|Исследование объявлений о продаже квартир|В вашем распоряжении данные сервиса Яндекс Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. Ваша задача — установить параметры. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность.| [Real Estate SPB](Real%20Estate%20SPB.ipynb)|pandas, numpy, matplotlib|
|Определение перспективного тарифа для телеком-компании|"Мегалайн" - федеральный оператор связи. Клиентам предлагают два тарифных плана: «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег.Вам предстоит сделать предварительный анализ тарифов на небольшой выборке клиентов. В вашем распоряжении данные 500 пользователей «Мегалайна»: кто они, откуда, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018 год. Нужно проанализировать поведение клиентов и сделать вывод — какой тариф лучше.|[Mobile Tariff Analysis](Mobile%20Tariff%20Analysis.ipynb)|pandas, numpy, matplotlib, seaborn, sklearn, **ttest**|
|Анализ продаж игр|Заказчик интернет-магазин «Стримчик», который продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.|[Games Analysis](Games%20Analysis.ipynb)|pandas, numpy, matplotlib, seaborn, ttest|
|Рекомендация тарифов|Оператор мобильной связи «Мегалайн» выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра»|[Tariff Recommendation](Tariff%20Recommendation.ipynb)|pandas, numpy, seaborn, sklearn, classification, class balance|
|Прогнозирование оттока клиентов банка|Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Вам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. Постройте модель с предельно большим значением F1-меры. Чтобы сдать проект успешно, нужно довести метрику до 0.59. Проверьте F1-меру на тестовой выборке самостоятельно. Дополнительно измеряйте AUC-ROC, сравнивайте её значение с F1-мерой.|[Bank Clients Leave](Bank%20Clients%20Leave.ipynb)|pandas, numpy, seaborn, sklearn, DesisionTree, RandomForest, LogisticRegression,  classification, class balance|
|Выбор локации для скважины|Заказчик - добывающая компания «ГлавРосГосНефть». Нужно решить, где бурить новую скважину. Шаги для выбора локации обычно такие: • В избранном регионе собирают характеристики для скважин: качество нефти и объём её запасов; • Строят модель для предсказания объёма запасов в новых скважинах; • Выбирают скважины с самыми высокими оценками значений; • Определяют регион с максимальной суммарной прибылью отобранных скважин. Вам предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Постройте модель для определения региона, где добыча принесёт наибольшую прибыль. Проанализируйте возможную прибыль и риски техникой Bootstrap. |[Well Placement](Well%20Placement.ipynb)|pandas, sklearn, LinearRegression, Bootstrap|
|Предсказание коэффициента восстановления золота из золотосодержащей руды|Подготовьте прототип модели машинного обучения для «Цифры». Компания разрабатывает решения для эффективной работы промышленных предприятий. Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. В вашем распоряжении данные с параметрами добычи и очистки. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.|[Gold Recovery](Gold%20Recovery.ipynb)|pandas, sklearn, GridSearchCV, LinearRegression, DesisionTree, seaborn| 
|Защита персональных данных клиентов|Вам нужно защитить данные клиентов страховой компании «Хоть потоп». Разработайте такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обоснуйте корректность его работы. Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. Подбирать наилучшую модель не требуется. Признаки: пол, возраст и зарплата застрахованного, количество членов его семьи.
Целевой признак: количество страховых выплат клиенту за последние 5 лет.|[Personal Data Protection](Personal%20Data%20Protection.ipynb)|pandas, numpy, sklearn, crossvalidation|
