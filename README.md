Titanic Survival Prediction — Random Forest
📌 Описание
Проект по предсказанию выживания пассажиров Титаника с помощью модели Random Forest Classifier.
Данные взяты из классического соревнования Kaggle Titanic (https://www.kaggle.com/c/titanic).
Модель обучается на данных train.csv и делает прогнозы для тестового набора test.csv.
📂 Структура проекта
titanic_project/ │ ├── titanic_notebook.ipynb # Jupyter Notebook с кодом обучения и анализа ├── train.csv # Датасет для обучения ├── test.csv # Датасет для тестирования ├── titanic_model.pkl # Сохранённая обученная модель ├── requirements.txt # Список библиотек для установки └── README.md # Этот файл 
⚙️ Установка и запуск
Клонируйте репозиторий:
git clone https://github.com/USERNAME/titanic_project.git cd titanic_project 
Создайте виртуальное окружение и установите зависимости:
python3 -m venv venv source venv/bin/activate # Для Windows: venv\Scripts\activate pip install -r requirements.txt 
Запустите Jupyter Notebook:
jupyter notebook 
Откройте titanic_notebook.ipynb и выполните ячейки по порядку.
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
