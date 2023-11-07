# E-Commerce Customer Churn Prediction

## Project Overview
* Predicted Cutomer Churn for an E-Commerce platform based on customer attributes such as Tenure, Recency and Cashback Amount.
* Executed diverse models such as Random Forest, Gradient Boosting and KNN Classifier to identify key predictors.
* Optimized several models by employing respective techniques to fine-tune hyperparameters.
  For instance, optimized Logistic Regression by finding the optimal threshold that maximizes the true positive rate minus the false positive rate; used GridSearchCV for Decision Trees; and implemented a random grid and RandomizedSearchCV for Random Forests.
* dataset : https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction
  
## Highlights of Analysis
![alt text](https://github.com/Hayoung-Zoe-Kim/ECommerce_Customer_Churn_Prediction/blob/main/Churn by Tenure.png)
![alt text](https://github.com/Hayoung-Zoe-Kim/ECommerce_Customer_Churn_Prediction/blob/main/Churn by Day Since LastOrder.png)
![alt text](https://github.com/Hayoung-Zoe-Kim/ECommerce_Customer_Churn_Prediction/blob/main/6.png)
![alt text](https://github.com/Hayoung-Zoe-Kim/ECommerce_Customer_Churn_Prediction/blob/main/7..png)

[ Model performance ] 

The Random Forest model far outperformed the other approaches on the test and validation sets. 
* **Random Forest Classifier** : OOS Accuracy 95% / Recall 74%
* **Logistic Regression** : OOS Accuracy 83% / Recall 78%
* **Decision Tree Classifier** : OOS Accuracy 97% / Recall 56%
* **Gradient Boosting** : OOS Accuracy 91% / Recall 63%
* **KNN Classifier** : OOS Accuracy 93% / Recall 68%

## Conclusion
Through rigorous data analysis and model optimization, we have determined that variables such as tenure, warehouse-to-home distance, customer complaints, and cashback amount significantly impact customer churn. The Random Forest algorithm, with its robust performance metrics, stood out as the most effective predictive model for churn rate, offering actionable insights for strategic customer retention.

#### Key Findings:
* **Tenure:** Customers with longer relationships with the company are less likely to churn, underlining the importance of nurturing customer relationships over time.
* **Warehouse-to-Home Distance:** A proxy for delivery times or service promptness, the shorter distances correlate with higher retention, highlighting the value of logistics efficiency.
* **Customer Complaints:** Directly linked to customer satisfaction, a higher number of complaints increases churn risk, stressing the need for an exceptional customer service framework.
* **Cashback Amount:** As a tangible value-back incentive, higher cashback amounts are instrumental in reducing churn, indicating the effectiveness of reward programs.

#### Strategic Recommendations:
* **Foster Customer Tenure:** Implement loyalty programs that reward customers incrementally over time, thereby encouraging longer subscription periods and fostering a sense of brand loyalty.
* **Optimize Logistics:** Invest in logistical improvements to minimize warehouse-to-home delivery times, enhancing customer satisfaction and reducing the likelihood of churn due to service delays.
* **Enhance Customer Service:** Establish a robust customer feedback loop and resolution process to rapidly address and rectify complaints, which will, in turn, improve customer retention.
* **Amplify Cashback Incentives:** Leverage cashback incentives more strategically, perhaps tiered by customer value segments, to ensure that high-risk customers are given ample reason to continue their patronage.

## ⭐️ Applicable Business Use Cases for This Churn Prediction Analysis:
#### E-Commerce Platforms
* **Personalization of Offers:** Based on the churn probability, e-commerce companies can personalize promotions and offers for customers at risk of churning. They could provide targeted cashback rewards or discounts on the next purchase to improve retention.
* **Loyalty program:** Use churn predictions to segment customers and tailor loyalty programs more effectively, focusing on those with higher tenure and spend.

#### Subscription-Based Services:
* **Proactive Customer Support:** For services that rely on monthly or annual subscriptions, the model can help in identifying customers who might churn, enabling customer support to proactively reach out and address any potential issues.
* **Tiered Subscription Models:** Implementing tiered subscription models where higher cashback or discounts are provided as the customer's tenure increases, incentivizing long-term subscriptions.

#### Financial Services
* **Credit Card rewards:** Banks could use churn predictions to offer increased cashback rewards on credit card transactions or other banking products to retain high-value customers.
* **Insurance Renewals:** Insurance companies can tailor their renewal offers by giving discounts or added benefits to customers who have a higher likelihood of churning.






