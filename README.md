# Titanic Survival Prediction with TensorFlow (Functional API)

This project predicts whether a Titanic passenger survived or not using tabular data and a Deep Neural Network (DNN) built with TensorFlow's Functional API.

---

## Dataset

- Source: [Kaggle - Titanic](https://www.kaggle.com/competitions/titanic/data)
- Features used:
  - Pclass
  - Sex
  - Age
  - SibSp
  - Parch
  - Fare
  - Embarked

---

## Model Details

- Type: Deep Neural Network (DNN)
- API: TensorFlow Functional API
- Layers:
  - Dense(64) + ReLU + Dropout(0.3)
  - Dense(32) + ReLU + Dropout(0.3)
  - Output: Dense(1) + Sigmoid
- Loss: Binary Crossentropy
- Optimizer: Adam
- Accuracy: Achieved around 81%

---

## Tools & Libraries

- Python
- TensorFlow / Keras
- Pandas / NumPy
- scikit-learn
- Matplotlib
