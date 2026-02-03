# Customer Churn Prediction System

A Machine Learning project that predicts whether a customer is likely to leave a service (churn) based on historical data. This project applies data preprocessing, visualization, model training, and hyperparameter tuning to build an accurate predictive model.

---

##  Project Overview

Customer churn is a critical problem for businesses. Retaining existing customers is often more cost-effective than acquiring new ones.  

This project builds a classification model using machine learning algorithms to identify customers who are likely to churn, enabling companies to take proactive retention measures.

---

## Key Features

- Data cleaning and preprocessing  
- Handling missing values using median strategy  
- Encoding categorical variables  
- Exploratory Data Analysis (EDA) with visualizations  
- Feature selection  
- Train-test split for unbiased evaluation  
- Model training using multiple algorithms  
- Hyperparameter tuning with GridSearchCV  
- Performance evaluation using accuracy and ROC curve  

---

## Tech Stack

- **Language:** Python  
- **Libraries:**  
  - Pandas  
  - NumPy  
  - Matplotlib  
  - Scikit-learn  

---

## Machine Learning Models Used

- Decision Tree Classifier  
- Random Forest Classifier  (Primary Model)  
- Support Vector Machine (SVM)  
- Naive Bayes  

Random Forest was selected due to its strong performance and ability to handle feature variability.

---

## ⚙️ Workflow

1. Load dataset  
2. Remove unnecessary columns  
3. Check and handle missing values  
4. Encode categorical features  
5. Perform data visualization  
6. Separate features and target variable  
7. Split data into training and testing sets  
8. Train machine learning models  
9. Tune hyperparameters for Random Forest  
10. Evaluate using accuracy and ROC curve  

---

## Model Performance

- Achieved strong prediction accuracy using Random Forest.
- ROC curve used to visualize classification performance.

*(You can update this section with your actual accuracy score.)*

---

##  How to Run the Project

### 1️ Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
