# Project Overview: ChurnGuard
Objective: To identify why customers are leaving an E-commerce platform and build a high-accuracy Machine Learning model to predict future churn.

1. Data Preparation & Cleaning
Dataset Size: Analyzed a dataset containing over 5,600 customer records with 20 different attributes.

Handling Missing Values: Identified "holes" in columns like Tenure and DaySinceLastOrder. Used Median Imputation to fill these gaps, ensuring no data was lost while maintaining statistical accuracy.

Feature Encoding: Converted categorical text data (like Gender and Category) into numerical format using Label Encoding so the AI could process the information.

2. Exploratory Data Analysis (EDA)
Churn Distribution: Discovered that approximately 17% of customers had churned (left the platform).

The Tenure Factor: Visualized that customers are most likely to leave within their first month (Tenure 0-1). Loyalty increases significantly after the first year.

Category Risk: Identified that the Mobile Phone category has a disproportionately higher churn rate compared to Laptop and Electronics categories.

3. Machine Learning Model
Algorithm: Implemented the Random Forest Classifier, a powerful ensemble learning method.

Performance: Achieved an impressive 97.1% Accuracy Score.

Precision: Attained a 1.00 Precision for churners, meaning when the model predicts a customer will leave, it is almost always correct.

4. Key Business Insights (The "Why")
The model identified the top 3 drivers of customer loss:

Tenure: New customers lack engagement and leave early.

Cashback Amount: Customers are highly sensitive to financial incentives and rewards.

Warehouse to Home Distance: Long delivery distances correlate with higher dissatisfaction.

Conclusion & Recommendation
To reduce churn, the company should focus on improving the onboarding experience for new users and optimizing cashback rewards for the Mobile Phone category. This data-driven approach allows the business to save revenue by targeting "at-risk" customers before they leave.
