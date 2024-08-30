# Data Science Phase_3_project
Project Overview
SyriaTel, a leading telecommunications company in Syria, is facing significant financial losses due to customer churn. To address this issue, SyriaTel is shifting from descriptive and inferential analysis to a predictive approach, aiming to identify at-risk customers using a machine learning model. The goal is to develop a predictive model using the SyriaTel Customer Churn dataset to accurately identify customers likely to churn and implement targeted retention strategies to reduce churn rates and improve profitability.

Key Questions Addressed
Best Model for Predicting Churn:

The analysis compared Decision Tree, K-Nearest Neighbors (KNN), and Random Forest models. The Random Forest model was identified as the best overall performer, with the highest accuracy, precision, recall, and ROC-AUC scores.
Accuracy of Churn Predictions:

The Random Forest model demonstrated high accuracy (93%), correctly identifying both churn and non-churn customers with minimal errors, making it a reliable tool for predicting customer churn.
Influential Features for Predicting Churn:

Using SHAP analysis, key features influencing churn predictions were identified, including the presence of an international plan, frequency of customer service calls, and total day minutes. These insights help SyriaTel target specific areas to improve retention.
Methodology
The project followed a structured approach:

Data Understanding and Cleaning:

Explored and prepared the dataset by handling missing values, errors, and irrelevant features.
Exploratory Data Analysis (EDA):
Visualized data distributions and relationships between features and the target variable.
Data Preprocessing:

Encoded categorical variables, scaled numerical features, and ensured consistent feature alignment between training and test datasets.
Modeling:
Trained and evaluated various models, including Logistic Regression, Decision Tree, Random Forest, and KNN, using cross-validation and hyperparameter tuning to optimize performance.
Feature Importance Analysis:
Used SHAP analysis to interpret the Random Forest model, highlighting the most influential features affecting churn predictions.

Model Evaluation

Random Forest:

Achieved the highest performance among all models with an accuracy of 93%, an F1-Score of 0.75, and a ROC-AUC Score of 0.85.
Best suited for predicting customer churn at SyriaTel due to its strong performance across all evaluation metrics.

Recommendations

Deploy the Random Forest Model:

Integrate the Random Forest model into SyriaTel’s CRM system for real-time churn prediction and continuously update the model with new data.

Enhance Customer Service:

Implement proactive strategies to reduce churn among customers frequently contacting support.
Tailor Retention Strategies:

Develop specialized plans for high-usage customers and offer incentives for segments identified as high-risk by the model.
Feature Selection Using SHAP:

Utilize SHAP analysis to streamline the model by focusing on the most impactful features, enhancing model generalization and performance.

Conclusion

By leveraging the Random Forest model and implementing targeted retention strategies, SyriaTel can effectively reduce customer churn, improve customer satisfaction, and achieve better financial outcomes. This proactive approach enables SyriaTel to maintain a competitive edge in the telecommunications industry.
