# Customer Churn Prediction

## 📌 Overview

This project focuses on predicting customer churn using machine learning techniques. Churn prediction helps businesses identify customers likely to leave, allowing proactive retention strategies.

## 📂 Project Files

## 📊 Dataset Information

- **Dataset Name**: tel\_churn.csv

- **Description**: This dataset contains customer information, including demographic details, service usage, and subscription history, which helps in predicting churn behavior.

- **Key Features**:

  - Customer tenure
  - Monthly charges
  - Total charges
  - Service subscriptions (Internet, Phone, Streaming, etc.)
  - Payment methods
  - Churn status (Yes/No)

- **Churn\_prediction.ipynb** – A Jupyter Notebook implementing the churn prediction model.

- **Churn\_Analysis.ipynb** – Exploratory Data Analysis (EDA) on churn-related data.

## 🛠 Technologies Used

- Python
- Pandas & NumPy (Data Manipulation)
- Seaborn & Matplotlib (Data Visualization)
- Scikit-Learn (Machine Learning Models)

## 🚀 Features

## 🔄 Steps Involved

1. **Data Preprocessing**: Handling missing values, encoding categorical variables, and scaling numerical features.
2. **Exploratory Data Analysis (EDA)**: Understanding patterns, correlations, and visualizing key churn indicators.
3. **Feature Engineering**: Selecting relevant features and creating new predictive variables.
4. **Model Selection & Training**: Using machine learning models to predict churn.
5. **Model Evaluation**: Assessing model performance using accuracy, precision, recall, and AUC-ROC.
6. **Hyperparameter Tuning**: Optimizing model parameters for better performance.

## 📊 Models Used & Accuracy Score

- DecisionTreeClassifier - Accuracy:  80.0%
- Random Forest Classifier – Accuracy: 93.37% (final)

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Customer-Churn-Prediction.git
   ```
2. Open Jupyter Notebook , install dependencies and run **Churn\_Analysis.ipynb** for EDA.
3. Run **Churn\_prediction.ipynb** to train and evaluate the model.

## 📈 Results & Insights

- Understanding factors influencing churn.
- Comparing different machine learning models.
- Suggestions for improving customer retention.

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for improvements.
