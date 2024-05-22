# PHASE-3-PROJECT
CUSTOMER CHURN ANALYSIS
Business Understanding
In the current modern world and competitive landscape, understanding and effectively managing customer churn is paramount for businesses aiming to sustain growth, customer retention, and profitability. A churn predictive model serves as a valuable tool in the endeavour by providing insights into customer behaviour and predicting which customers are likely to discontinue their relationship with the company. Some of the key variable features that will be used to create a business churn predictive model include factors that contribute to customer churn, allocation of resources, intervention needed, and lifetime of a customer in the business.

 Problem Statement
Customer churn remains a challenge for most businesses in different sectors that contribute not only to a decline in customer base but also to revenue loss. Therefore, to enable businesses to mitigate and take control of their customers, it is crucial to create a predictive churn model that gives businesses a heads-up and allows them to intervene before losing a customer. The objective of this project is to give insights for strategizing and forecasting for growth of business through retention and acquisition of customers.

Modelling
Some of the models employed during this exercise include Logistic Regression, Decision Tree Classifier, Gradient Boosting Classifier, Gaussian NB, and Support Vector Classifier.

Generally, the Gradient Boosting classifier has the best performance and seems a better choice among all models because of the high metrics for both training and testing. It shows a good generalizing ability, robustness and reliability. The other model that shows good performance is the SVC.

Model Metrics:
Recall Score:0.7908496732026143
Precision Score:0.852112676056338
Accuracy Score:0.947
F1 Score:0.8203389830508475
ROC AUC Score:0.883028142386431

![image](https://github.com/FMwenda2023/PHASE-3-PROJECT/assets/151983283/b83c4ada-6e6f-4b0c-aac1-3f1f779d3f07)


Model Performance: From the ROC Curve, we can conclusively say that the model has a strong distinguishing power between positive and negative classes. The model performs very well on the training data; it correctly identifies all instances and correctly predicts all instances. However, on the testing data, the model metrics are still strong but lower than those of the training data.

Model Limitation: The model is easily overfitting to training data even after tuning the model. This is due to lack of enough data to enable the data to generalize well and more accurately

Recommendations
Collection of more data to reduce the overfitting by enabling the model to perform better

Investigate and understand the ability of customer care staff to handle customer complaints. This will enable the business to establish its contribution to customer churn and be able to mitigate the same through education and training of staff.

Include more data from competitors to help the business improve internal processes and marketing strategies.

Study on competitors' charge rate, customer incentives, products and services offered to enable the business to get a competitive edge.

Investigate signals and ability to communicate effectively in areas where there is high customer churn

This was created by Faith Kagwiria Mwenda
