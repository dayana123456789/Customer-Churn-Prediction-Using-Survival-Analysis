# Customer-Churn-Prediction-Using-Survival-Analysis
This project focuses on analyzing customer churn using survival analysis techniques. Customer churn is a critical concern for businesses, and understanding when and why customers leave a service is essential for retention and growth.

# Key Concepts
* Survival Time: The time period during which customers are observed to determine whether they churn or not.
* Censorship: Observations that are stopped before the event of interest occurs, such as customers still using a service at the end of the observation period.
* Hazard Ratio: A measure of how different variables affect the likelihood of churn.
* 
# Dataset
The analysis is performed on a dataset from Kaggle https://www.kaggle.com/datasets/blastchar/telco-customer-churn containing customer information, including variables such as "Partner," "OnlineSecurity," "OnlineBackup," "TechSupport," "StreamingTV," "StreamingMovies," "Contract_One year," "Contract_Two year," "PaymentMethod_Electronic check," and "PaymentMethod_Mailed check." These variables are explored to understand their impact on customer churn.

# Analysis Highlights
* **Hazard Ratios**: The analysis reveals hazard ratios for various predictor variables. A hazard ratio greater than 1 indicates an increased risk of churn, while less than 1 suggests a decreased risk.
* **Statistical Significance**: Variables with statistically significant p-values (p < 0.05) are considered important in predicting churn.
* **Concordance Index**: The model's concordance index of 0.93 indicates a good fit, reflecting its ability to predict survival times effectively.
* **Survival Curve**: The survival curve shows that most customers remain with the service for a specific period, but churn rates increase over time.

# Insights and Future Steps
The analysis highlights variables that significantly impact customer churn. Businesses can use this information to develop strategies for customer retention. Further investigation can focus on understanding the reasons behind churn, such as price increases or service quality issues, and implementing measures to address them.

# Conclusion
This project provides a comprehensive analysis of customer churn using survival analysis techniques. It helps businesses with insights to improve customer retention and make data-driven decisions.

Feel free to explore the provided analysis for detailed insights and reach out with any questions or feedback.

# **Happy Analysis**
