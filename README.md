# 🧠 Классификация цветов на изображениях

Проект по классификации цвета объектов на изображениях из 16 представленных цветов с помощью сверточной нейронной сети (CNN) на TensorFlow/Keras.

## 🚀 Основное

- Удаление фона с помощью OpenCV
- Масштабирование и нормализация изображений
- Обучение CNN для предсказания цвета
- Вывод вероятностей и финального цвета
- Сохранение результатов в `submission.csv`

## 🧪 Модель

- Conv2D → MaxPool → Conv2D → MaxPool → Conv2D → GlobalAvgPool → Dense
- Активация: ReLU + Softmax
- Потери: categorical_crossentropy
- Оптимизатор: Adam

## 📦 Библиотеки
- TensorFlow / Keras
- OpenCV / NumPy / Pandas
- Matplotlib / scikit-learn

🎯 Точность модели на валидации: **~54%**
