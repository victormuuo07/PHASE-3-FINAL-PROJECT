# **SyriaTel Customer Churn Prediction**

## **Overview**

This project focuses on analyzing customer churn for SyriaTel, a telecommunications company, to identify key factors that contribute to customer attrition and develop predictive models to help the company retain its customers. The analysis aims to provide actionable insights and recommendations that SyriaTel can implement to improve customer retention and overall profitability.

## **Business and Data Understanding**  

### **Stakeholder Audience**  

The primary stakeholders for this project include:

1. Customer Retention Team: Interested in understanding the factors leading to customer churn in order to develop effective strategies to retain customers.   
2. Upper Management: Focused on reducing churn rates to improve profitability and customer satisfaction, which are critical to the long-term success of the company.  

### **Dataset Choice**  

We used a telecommunications dataset that includes customer demographics, service usage, and billing information. This dataset is ideal for modeling churn because it captures relevant customer behaviors and service interactions that are indicative of churn risk.   

### **Key Features in the Dataset:**  

* Account Length  
* Area Code  
* Number Vmail Messages  
* Total Day Minutes  
* Total Eve Minutes  
* Total Night Minutes  
* Customer Service Calls  
* International Plan  
* Voice Mail Plan  

## **Modelling**  

We explored several models to predict customer churn:  

* **Logistic Regression:** Established as the baseline model due to its simplicity and interpretability.  
* **Decision Tree Classifier:** Captured non-linear relationships and provided insights into the most important features.  
* **Random Forest Classifier:** Improved accuracy by reducing overfitting compared to the decision tree.  
* **Stacking Ensemble Model:** Combined the strengths of multiple models to achieve the best performance.  

## **Feature Importance**  

We analyzed feature importance across models to identify key drivers of churn. The most influential features included customer service calls, total day minutes, and whether a customer had an international plan.  

## **Evaluation**  

### **Metrics**  
The models were evaluated using the following metrics:  

* Accuracy: The percentage of correct predictions.  
* Precision and Recall: To balance the trade-off between false positives and false negatives.  
* ROC-AUC Score: To assess the overall performance of the models in distinguishing between churn and non-churn customers.  

Best Model: The Stacking Ensemble Model achieved the highest performance with an ROC-AUC score of 0.92, making it the recommended model for deployment.  

## **Conclusion**  
### **Findings**  

**Key Determinants of Churn:** The analysis revealed that customer service calls and international plan were the most significant factors influencing churn. Frequent calls to customer service indicated dissatisfaction, while having an international plan correlated with lower churn rates.  
**Model Performance:** The stacking ensemble model outperformed individual models, demonstrating the value of combining multiple algorithms for better prediction accuracy.   


