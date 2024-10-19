Итоговый учебный проект по курсу «Глубокое обучение и нейронные сети».

Цель: применение моделей машинного обучения для предсказания сердечно-сосудистых заболеваний, а также обучение собственной модели.
Представленные данные содержат 600 000 записей в обучающем наборе и 400 000 в тестовом. Каждая запись содержит ID пациента и 13 признаков:

Age (возраст);
Sex (пол);
Resting_blood_pressure (артериальное давление в состоянии покоя);
Serum_cholestoral (уровень холестерина в крови mg/dl);
Fasting_blood_sugar (анализ глюкозы в крови натощак (> 120 mg/dl));
Maximum_heart_rate_achieved (максимальная частота сердечных сокращений);
Exercise_induced_angina (стенокардия при нагрузке);
Oldpeak (депрессия ST-сегмента);
Slope (наклон пикового сегмента ST при физической нагрузке);
Number_of_major_vessels (количество крупных сосудов (0-3), окрашенных с помощью флюороскопии);
Resting_electrocardiographic_results (результаты электрокардиографических исследований в покое: 0, 1, 2);
Thal (3 = норма; 6 = фиксированный дефект; 7 = обратимый дефект);
Chest_bin (боль в груди от 1 до 4).
Проект выполнен на языке Python в Google Colab с использованием следующих библиотек:

pandas;
seaborn;
matplotlib;
sklearn;
tabulate;
scipy;
PyTorch.
В предложенной для изучения статье Victor Chang и соавторы обсуждают построение системы обнаружения заболеваний сердца на основе искусственного интеллекта с использованием алгоритмов машинного обучения и возможности предсказать, разовьется ли у человека острый коронарный синдром.
В разделе методологии исследования подробно расписан механизм алгоритма случайный лес, который считается гибким, универсальным и простым в использовании в машинном обучении. Даже без настройки гиперпараметров в большинстве случаев достигает превосходных результатов. Приведено обоснование использования именно этого алгоритма.
Пошагово объяснено, как проводился разведочный анализ данных, подготовка (очистка) данных и машинное обучение. Расписано, какое программное обеспечение и окружение использовалось в проекте. На рисунках визуализированы этапы разведочного анализа данных, настройки параметров и интерпретации данных.
Кроме этого, обсуждается важность соблюдения кибербезопасности при проведении подобных исследований и расчетов.

Final educational project for the course "Deep Learning and Neural Networks".

Objective: to apply machine learning models for predicting cardiovascular diseases, as well as to train a custom model. The presented data contains 600,000 records in the training set and 400,000 in the test set. Each record contains the patient ID and 13 features:

Age (age);
Sex (gender);
Resting_blood_pressure (resting blood pressure);
Serum_cholestoral (serum cholesterol level in mg/dl);
Fasting_blood_sugar (fasting blood sugar test (> 120 mg/dl));
Maximum_heart_rate_achieved (maximum heart rate achieved);
Exercise_induced_angina (exercise-induced angina);
Oldpeak (depression of the ST segment);
Slope (slope of the peak ST segment during exercise);
Number_of_major_vessels (number of major vessels (0-3) colored by fluoroscopy);
Resting_electrocardiographic_results (resting electrocardiographic results: 0, 1, 2);
Thal (3 = normal; 6 = fixed defect; 7 = reversible defect);
Chest_bin (chest pain from 1 to 4).
The project is implemented in Python using Google Colab with the following libraries:

pandas;
seaborn;
matplotlib;
sklearn;
tabulate;
scipy;
PyTorch.
In the article proposed for study, Victor Chang et al. discuss the development of a heart disease detection system based on artificial intelligence using machine learning algorithms and the possibility of predicting whether a person will develop acute coronary syndrome. The methodology section of the research details the mechanism of the random forest algorithm, which is considered flexible, universal, and easy to use in machine learning. Even without hyperparameter tuning, it achieves excellent results in most cases. Justification for the use of this algorithm is provided. A step-by-step explanation of how exploratory data analysis, data preparation (cleaning), and machine learning were conducted is given. The software and environment used in the project are described. The stages of exploratory data analysis, parameter tuning, and data interpretation are visualized in the figures. Additionally, the importance of maintaining cybersecurity during such research and
