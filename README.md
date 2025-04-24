# 🧠 Customer Personality Analysis

This project analyzes customer personality data to uncover behavioral patterns and predict how likely a customer is to respond positively to a marketing campaign. It uses machine learning models and visualization tools to explore, model, and evaluate key features influencing customer behavior.

## 📌 Project Goals

- Understand relationships between customer demographics, behavior, and campaign response.
- Build classification models to predict the likelihood of a customer responding.
- Compare model performances using accuracy and other metrics.
- Provide actionable insights to enhance marketing strategies.

## 📊 Dataset

The dataset contains customer data including:

- **Demographics**: Age, Income, Marital Status, etc.
- **Purchasing Behavior**: Amount spent, number of purchases via different channels.
- **Campaign Response**: Binary label indicating response to a campaign (`general_response`).

> *Note: Dataset source was provided as part of a learning project and may be anonymized or synthetic.*

## 🛠️ Tools & Technologies

- **Python**
- **Libraries**: Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, XGBoost
- **Modeling Techniques**: Logistic Regression, Random Forest, XGBoost
- **Evaluation Metrics**: Accuracy, Confusion Matrix, Classification Report
- **Hyperparameter Tuning**: GridSearchCV

## 🚀 Features

- Data cleaning and preprocessing (encoding, scaling, handling missing values).
- Exploratory Data Analysis (EDA) and visualizations.
- Machine learning model comparison with evaluation metrics.
- Hyperparameter tuning to optimize model performance.
- Visualization of predictions vs actuals.

## 🧪 Results

The tuned **Random Forest** model achieved the highest accuracy of **~84.8%**, with insightful precision-recall tradeoffs. It identified high-income and frequent web purchase customers as more likely to respond positively to marketing.


