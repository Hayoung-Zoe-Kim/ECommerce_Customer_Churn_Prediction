# E-Commerce Customer Churn Prediction

## Project Overview
* Predicted Cutomer Churn for an E-Commerce platform based on customer attributes such as Tenure, recency and cashback amount.
* Executed diverse models such as Logistic Regression, Random Forest and Gradient Boosting to identify key predictors.
* Optimized several models using respective techniques
  : Logistic Regression - finding the optimal threshold that maximizes tpr-fpr, Decision Tree - GridSearchCV, Random Forests - random grid & RandomizedSearchCV

## Resources Used
* dataset : https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction

## EDA
I looked at the distributions of numerical and categorical variables based on the churn result(0 or 1). Below are a few highlights.
![alt text](https://github.com/Hayoung-Zoe-Kim/ECommerce_Customer_Churn_Prediction/blob/main/2.png)
![alt text](https://github.com/Hayoung-Zoe-Kim/ECommerce_Customer_Churn_Prediction/blob/main/3.png)
![alt text](https://github.com/Hayoung-Zoe-Kim/ECommerce_Customer_Churn_Prediction/blob/main/4.png)
![alt text](https://github.com/Hayoung-Zoe-Kim/ECommerce_Customer_Churn_Prediction/blob/main/5.png)
![alt text](https://github.com/Hayoung-Zoe-Kim/ECommerce_Customer_Churn_Prediction/blob/main/6.png)
![alt text](https://github.com/Hayoung-Zoe-Kim/ECommerce_Customer_Churn_Prediction/blob/main/7.png)

## Model performance
The Random Forest model far outperformed the other approaches on the test and validation sets. 

* **Logistic Regression** : OOS Accuracy 83% / Recall 78%
* **Decision Tree Classifier** : OOS Accuracy 97% / Recall 56%
* **Random Forest Classifier** : OOS Accuracy 95% / Recall 74%
* **Gradient Boosting** : OOS Accuracy 91% / Recall 63%
* **KNN Classifier** : OOS Accuracy 93% / Recall 68%


## Conclusion
* Tenure, Warehouse to Home distance, Complain and cashback amount are the key variables that impact customer churn
* Random forest was the best way to predict churn rate
* Recommendation: Increase customer tenure and cashback amount to for stronger customer loyalty and lock-in effect and decrease customers complaints 



