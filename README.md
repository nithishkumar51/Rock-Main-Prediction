# 🧭 Sonar Rock vs Mine Prediction using Machine Learning

This project uses a machine learning model to classify whether an object detected by sonar is a **Rock** or a **Mine** based on sonar signal data.

## 📊 Dataset

The model is trained on the **Sonar Dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Connectionist+Bench+%28Sonar,+Mines+vs.+Rocks%29), which contains:
- 60 numerical features per instance
- Each feature represents the energy within a particular frequency band
- Target label: `M` (Mine) or `R` (Rock)

## 🚀 Features

- Accepts 60 numerical input values
- Scales input data using `StandardScaler`
- Predicts output as either **Rock** or **Mine**
- Built using `Python`, `NumPy`, `Pandas`, and `scikit-learn`
