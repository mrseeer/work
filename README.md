Задание: в качестве тестового задания мы предоставляем вам датасет online_shoppers_intention.csv, который содержит информацию о посетителях интернет-магазина и их поведении на сайте. Необходимо проанализировать данный датасет, определив какие действия могут привести к конверсии и создать классификатор на основе ваших гипотез.
В качестве ответа необходимо предоставить Jupyter Notebook с вашим анализом и модель машинного обучения, которая сможет предсказывать, приносят ли действия пользователя Revenue или нет.
Для выполнения задания необходимо использовать Python и библиотеки на ваш выбор.

Executive summary:
1. Использован Pyhon 3, библиотеки numpy, pandas, matplotlib, sklearn.
2. Проведен анализ и построена модель  - ссылка.
3. Основное действие пользователя, влияющее на конверсию - посещение сайта.

Что было сделано в ходе выполнения проекта:
1. Проведена предобработка данных - проверка на пропущенные значения в данных, названия колонок приведены в нижний регистр (для лучшей читабельности), изменены типы данных колонок Revenue и Weekend, проверка на дубликаты (дубликаты были обнаружены, но они не могут быть удалены, т.к. их удаление может повлиять на конечный результат исследования);
2. Анализ данных - построены диаграммы зависимости прибыли от действий посетителя, посчитана линейная корреляция (нет необходимости использовать нелинейную корреляцию);
3. Обучение моделей - значения в столбцах Month и Visitor_type были переведены из категориальных в количественные для будущего использования в моделях, выделен целевой признак (Revenue), разделение датасета на обучающий и тестовый наборы, было проведено масштабирование данных. Далее, были обучены модели LinearRegression и RandomForestClassifier, подобраны гиперпараметры и оценена точность предсказания. Наиболее высокая точность у модели RandomForestClassifier.


****************************************************************************


Task: as a test task, we provide you with the online_shoppers_intention.csv dataset, which contains information about online store visitors and their behavior on the site. It is necessary to analyze this dataset, determining which actions can lead to conversion and create a classifier based on your hypotheses. As an answer, you need to provide Jupyter Notebook with your analysis and a machine learning model that can predict whether the user's actions bring Revenue or not. To complete the task, you need to use Python and the libraries of your choice.

Executive summary:

1. Used Python 3, numpy, pandas, matplotlib, sklearn libraries.
2. The analysis was carried out and a reference model was built.
3. The main user action affecting the conversion is visiting the site.

What was done during the project:
1. Data preprocessing was carried out - checking for missing values in the data, column names are given in lower case (for better readability), data types of Revenue and Weekend columns were changed, checking for duplicates (duplicates were detected, but they cannot be deleted, because their deletion may affect the final result of the study);
2. Data analysis - diagrams of profit dependence on visitor actions are constructed, linear correlation is calculated (there is no need to use nonlinear correlation);
3. Model training - the values in the Month and Visitor_type columns were transferred from categorical to quantitative for future use in models, the target attribute (Revenue) was allocated, the dataset was divided into training and test sets, data was scaled. Next, LinearRegression and RandomForestClassifier models were trained, hyperparameters were selected and prediction accuracy was evaluated. The RandomForestClassifier model has the highest accuracy.
