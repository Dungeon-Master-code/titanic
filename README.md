Titanic Survival Prediction — Random Forest

📌 Описание
Проект по предсказанию выживания пассажиров Титаника с помощью модели Random Forest Classifier.
Данные взяты из классического соревнования Kaggle Titanic (https://www.kaggle.com/c/titanic).
Модель обучается на данных train.csv и делает прогнозы для тестового набора test.csv.


📊 Результаты

Accuracy: 82%
Precision: 0.83 (класс 0), 0.80 (класс 1)
Recall: 0.87 (класс 0), 0.76 (класс 1)
F1-score: 0.85 (класс 0), 0.78 (класс 1)

Матрица ошибок:
[[91 14] [18 56]] 

🛠 Используемые библиотеки

pandas
numpy
scikit-learn
joblib
