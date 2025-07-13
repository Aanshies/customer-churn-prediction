# 📉 ChurnGuard: Customer Churn Prediction

**ChurnGuard** is a machine learning project focusing on predicting customer churn using classification algorithms on structured customer data. The model is built in Python with feature engineering, EDA, and achieves ~80% accuracy using Random Forest on test data.

## 📜 Table of Contents

-Project Overview

-Features

-Installation

-Dataset

-Usage

-Running Predictions

-Training the Model

-Model Details

-Data Preprocessing

-Feature Encoding

-Model Training

-Model Evaluation

-Google Colab Notebook

-Contributing

-License

## 🚀 Project Overview

ChurnGuard helps telecom companies predict which customers are likely to churn by analyzing customer demographics, usage patterns, and service details. This project leverages data preprocessing, EDA, and Random Forest Classification to train a churn prediction model capable of providing actionable insights.

## 🌟 Features

-EDA Visualization: Understand churn distribution and feature relationships.

-Feature Engineering: Label encoding, handling missing data, and feature scaling.

-Classification Model: Uses Random Forest for robust classification.

-Evaluation Metrics: Includes accuracy, precision, recall, F1-score, and confusion matrix.

-Deployable Notebook: Easily demo and modify using Google Colab or Jupyter Notebook.

## 🛠 Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/ChurnGuard.git
cd ChurnGuard
```
### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
or use in Google Colab without installing manually.

## 🗂 Dataset
-**Dataset**: Telco Customer Churn Dataset

-**File**: WA_Fn-UseC_-Telco-Customer-Churn.csv

-**Description**: Contains telecom customer details and churn labels.

-Download Dataset on Kaggle

##🚦 Usage

### Running Predictions
To predict churn on new customer data using the trained model:
```bash
python src/predict_churn.py
```
or
Run cells in the Colab notebook for interactive prediction.

### Training the Model
You can retrain the model using the provided Google Colab notebook or Jupyter Notebook.
- [Google Colab Notebook](https://colab.research.google.com/drive/1Vq9zEOtc7d9wNeDrtTXbBk-9ZBawWGnD?authuser=1#scrollTo=NjMmi6U4YNEo)


## 🧩 Model Details

### Data Preprocessing
-**Drop Unnecessary Columns:** (e.g., Customer ID)

-**Convert Data Types:** Convert TotalCharges to numeric.

-**Handle Missing Values:** Replace NaNs with median or zero.

-**Encode Categorical Variables:** Using Label Encoding.

### Feature Encoding & Scaling
Features are scaled where necessary for certain algorithms and encoded for training.

### Model Training
The model's performance is evaluated using the following metrics:

- **Accuracy:** Measures the percentage of correct predictions.
- **Precision:** Measures the proportion of true positive results among all positive predictions.
- **Recall:** Measures the proportion of true positive results among all actual positives.
- **F1-score:** The harmonic mean of precision and recall.
- **ROC-AUC:** Measures the area under the receiver opera


## 🤝 Contributing
Contributions to ChurnGuard are welcome!

1.Fork the repository

2.Create a new branch (feature/YourFeature)

3.Commit your changes

4.Push to your branch

5.Create a Pull Request

## 📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

## ⚠️ Warning (Educational Use)
This project uses public datasets and free-tier resources for learning and demonstration purposes only. It is not intended for production use without appropriate validation and adaptation for specific business requirements.
