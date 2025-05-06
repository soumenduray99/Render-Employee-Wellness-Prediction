# Employee Health Prediction Model  

## 📌 Problem Statement  
Rende Technical Solutions has lost a key employee, raising serious concerns about employee health 🏥. The company wants to identify those who may need medical treatment by analyzing various attributes stored in their database 📊. By predicting health risks, organizations can take proactive steps to improve well-being and productivity 💡. The objective is to develop a model that helps detect employees in need of treatment, ensuring a healthier workforce 💼✨.

## 🎯 Objective  
The goal is to help organizations understand factors affecting employee health and well-being 🏥. By building accurate predictive models 📊, companies can identify areas needing intervention and design targeted wellness programs 🏋️‍♂️. This will improve employee health and productivity 💼. The objective is to predict if an employee needs treatment based on test data 🔍.

## 📊 Train-Test Split for Employee Health Prediction  
Given the dataset size and potential class imbalance, an 80/20 split is ideal:  
* **80% Training (40,000 rows)** — Provides ample data for model learning.  
* **20% Testing (10,000 rows)** — Ensures a sizable evaluation set for accurate performance measurement.  

This split helps build a robust model while maintaining a reliable test set for evaluation. 🚀📉  

## 📊 Model Performance Analysis  
The table presents the accuracy, train, and test scores for different machine learning models used for employee health prediction. Here's a summary of the top 4 models based on their performance:  

| Model              | Train Score | Test Score | Observation                                                                 |
|--------------------|-------------|------------|-----------------------------------------------------------------------------|
| 🏆 **Best Model: Random Forest** | 0.999000    | 0.998933   | It has the highest accuracy among all models, indicating superior performance in classification. |
| 🥈 **Second Best: KNN**          | 0.999229    | 0.998600   | Very close to Random Forest, but slightly lower accuracy.                   |
| 🥉 **Third Best: XGBoost**       | 0.996400    | 0.995533   | A strong model, but slightly behind Random Forest and KNN.                  |
| **Decision Tree (⭐ High but Overfitting)** | 0.977912    | 0.977200   | Good accuracy but prone to overfitting.                                     |

## 📌 Key Takeaways  
* ✅ **Random Forest** is the best model based on accuracy and generalization.  
* 📉 **KNN** and **XGBoost** are strong contenders, but slightly behind.  
* ⚠️ **Decision Tree** overfits, while **GradientBoost** is a balanced choice with lower accuracy.  
* ❌ **AdaBoost** and **Logistic Regression** underperform, making them less suitable. 😊  

## 🛠️ Setup and Execution Instructions  

### 1. ⚙️ Environment Setup  
Install required Python libraries:  
* pandas  
* numpy  
* matplotlib  
* seaborn  
* scikit-learn  
* xgboost  
* randomforest  
* imblearn  

### 2. ▶️ Execution Steps  
* Load the dataset.  
* Perform data preprocessing (handling missing values, feature encoding, etc.).  
* Split the dataset into **80% Training** and **20% Testing** sets.  
* Train the different models (Random Forest, KNN, XGBoost, Decision Tree).  
* Evaluate the models' performance using **Train Score** and **Test Score** metrics.  
* Choose the best-performing model based on the analysis.  

### 3. ✅ Model Evaluation  
Evaluate the models using the following performance metrics:  
* **Accuracy**  
* **Precision**  
* **Recall**  
* **F1 Score**

## 📚 Conclusion  
The **Random Forest** model outperforms other models, providing a reliable method for predicting employee health risks. By identifying employees at risk early, organizations can take preventative measures, ensuring a healthier workforce and improving overall productivity.  

By refining model selection, the company can implement targeted wellness programs to ensure the well-being of employees.

