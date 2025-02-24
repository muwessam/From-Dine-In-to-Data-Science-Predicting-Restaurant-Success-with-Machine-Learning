# **Zomato Ratings: Predicting Restaurant Success with Machine Learning**

## **Project Overview**
This project aims to analyze and predict restaurant ratings on Zomato using machine learning. By preprocessing data, applying various classification models, and using ensemble techniques, we identify key factors influencing restaurant success.

## **Dataset**
- **Source:** Zomato restaurant dataset
- **Features:** Restaurant details, cuisines, ratings, and other attributes
- **Target Variable:** Binary classification of restaurant ratings (high vs. low)

## **Key Steps**
### **1. Data Preprocessing**
- Handled missing values and null entries
- Encoded categorical variables (e.g., cuisines)
- Scaled numerical features where necessary

### **2. Exploratory Data Analysis (EDA)**
- Identified trends in restaurant ratings
- Visualized the distribution of top cuisines and restaurant attributes

### **3. Model Training & Evaluation**
- Applied multiple classification models:
  - **Decision Tree**
  - **Random Forest**
  - **Logistic Regression**
  - **Bagging Classifier** (Decision Tree as base estimator)
- Compared models using:
  - **Accuracy**
  - **F1-score**
  - **ROC-AUC Score**

### **4. Ensemble Learning: Bagging**
- Implemented a Bagging Classifier to improve model stability
- Evaluated its performance against standalone models

### **5. Model Visualization & Insights**
- Plotted **ROC curves** for model comparisons
- Analyzed **feature importance** for decision-making insights

## **Results & Insights**
- Decision Tree performed well, and Bagging improved stability
- Cuisines and restaurant attributes significantly impact ratings
- Machine learning can effectively predict restaurant success

## **How to Run the Project**
1. Install dependencies:  
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
2. Load and preprocess the dataset.
3. Train models and evaluate performance.
4. Visualize results using ROC curves and feature importance plots.

## **Future Improvements**
- Apply Boosting techniques for further improvement
- Use a larger dataset for better generalization
- Integrate additional restaurant features

---
This project demonstrates the power of machine learning in analyzing restaurant ratings and predicting success factors. 🚀🍽️

