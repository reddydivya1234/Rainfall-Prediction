# Rainfall Prediction Using Machine Learning

## 📌 Project Overview
This project aims to predict rainfall based on historical weather data using three different machine learning algorithms: **Logistic Regression**,and **Support Vector Machine (SVM)**. The goal is to build a reliable model that can determine whether it will rain tomorrow based on various atmospheric features.

## 📁 Dataset
- **Source:** [Rainfall.csv](./Rainfall.csv)
- **Attributes:** Includes various weather features such as temperature, humidity, wind speed, and others across different locations and dates in Australia.
- **Target Variable:** `RainTomorrow` (Yes/No)

## 🧪 Preprocessing Steps
- Handled missing values through imputation.
- Encoded categorical features using Label Encoding.
- Scaled features using StandardScaler for appropriate model convergence.
  
## 🤖 Models Used

### 1. Logistic Regression
- A baseline classification model.
- Used to provide a reference accuracy for comparison.

### 2. Support Vector Machine (SVM)
- Applied with linear and RBF kernels.
- Tuned for regularization parameter `C`.

## 📊 Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Precision, Recall, F1-Score

## 📈 Results

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression| ~81.0%   |
| SVM                | ~83.0%   |

## 🚀 How to Run
1. Clone this repository:
    git clone https://github.com/reddydivya1234/Rainfall-Prediction.git
    cd rainfall-prediction
2. Install required packages:
   pip install pandas numpy scikit-learn xgboost matplotlib seaborn
3. Run the script:
   python rainfall_prediction.py
   
## 🛠️ Requirements
 • Python 3.x
 • pandas
 • numpy
 • scikit-learn
 • seaborn
 • matplotlib
