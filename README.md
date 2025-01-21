# **Wine Quality Prediction**  

This project focuses on predicting the quality of wines using machine learning techniques based on their physicochemical properties. The dataset, sourced from the UCI Machine Learning Repository, includes red and white wine samples with chemical attributes and quality ratings ranging from 0 to 10.  

### **Objective**  
The goal was to build an accurate predictive model to classify wine quality, assisting manufacturers and tasters in quality assessment.  

### **Dataset Features**  
1. Fixed Acidity  
2. Volatile Acidity  
3. Citric Acid  
4. Residual Sugar  
5. Chlorides  
6. Free Sulfur Dioxide  
7. Total Sulfur Dioxide  
8. Density  
9. pH  
10. Sulphates  
11. Alcohol  
12. Quality (Target variable)  

### **Key Steps**  
1. **Data Preprocessing**:  
   - Handled missing values and scaled numerical features.  
   - Explored data to identify correlations and feature importance.  

2. **Model Development**:  
   - Tested multiple machine learning models: Logistic Regression, Random Forest, Gradient Boosting (e.g., XGBoost), and SVM.  
   - Performed hyperparameter tuning for optimization.  

3. **Evaluation**:  
   - Assessed models using metrics like Accuracy, F1-Score, and ROC-AUC.  
   - Addressed class imbalance using SMOTE and class-weight adjustments.  

### **Results**  
The final model achieved an accuracy of ~85%, with strong generalization on unseen data.  

### **Conclusion**  
This project demonstrates the use of machine learning in classifying wine quality based on chemical properties. It offers insights into how data science can optimize quality control in the wine industry.  

Feel free to explore the repository for code, insights, and analysis! 😊
Data Source: https://archive.ics.uci.edu/dataset/186/wine+quality
