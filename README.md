# End-to-End-Employee-Churn-Prediction-with-Azure-Databricks

## Introduction

This project addresses the critical issue of employee churn, which can lead to substantial costs and disruptions for organizations. By leveraging Azure Databricks, Spark, Scikit-Learn, MLflow, and Hugging Face Spaces, I developed a robust and scalable machine learning solution to predict employee churn and help organizations retain top talent.

![ezgif com-animated-gif-maker (6)](https://github.com/Abhi0323/End-to-End-Employee-Churn-Prediction-with-Azure-Databricks/assets/112967999/1c15638e-0719-44f9-9c6d-bfbe74842bde)

## Project Overview

The project consists of the following key stages:

## 1. Data Ingestion and Preparation:

* Loaded and processed employee churn data using Azure Databricks
* Leveraged Spark's powerful data processing capabilities to handle large datasets efficiently.

## 2. Initial Data Exploration with Spark SQL:

* Created a temporary view of the data and ran SQL queries.
* Gained insights into key metrics like average satisfaction level and total churn count.

## 3. Data Preprocessing with PySpark:

* Handled missing values, encoded categorical variables using StringIndexer and OneHotEncoder.
* Assembled feature vectors with VectorAssembler to prepare the data for machine learning.

<img width="1468" alt="Screenshot 2024-05-19 at 6 38 06 PM" src="https://github.com/Abhi0323/End-to-End-Employee-Churn-Prediction-with-Azure-Databricks/assets/112967999/47b49e82-3511-4aca-8cf2-d977fcaf1419">

## 4. Machine Learning Model Building with Scikit-Learn:

* Converted the processed Spark DataFrame to a Pandas DataFrame for model building.
* Experimented with various models including Logistic Regression, Decision Trees, Random Forests, and Gradient Boosting.
* Performed hyperparameter tuning with GridSearchCV for the best model performance.
* Evaluated models using accuracy, ROC-AUC score, and confusion matrix, with the Random Forest model showing the best results.

## 5. Model Management with MLflow:

* Integrated MLflow to track experiments, log metrics, and manage model versions.
* Registered the best model in the MLflow Model Registry for version control and easy deployment.

<img width="1464" alt="Screenshot 2024-05-19 at 5 50 00 PM" src="https://github.com/Abhi0323/End-to-End-Employee-Churn-Prediction-with-Azure-Databricks/assets/112967999/aa5ee966-9a1c-4992-82ae-cd4f60d05ccc">

<img width="1459" alt="Screenshot 2024-05-19 at 6 44 14 PM" src="https://github.com/Abhi0323/End-to-End-Employee-Churn-Prediction-with-Azure-Databricks/assets/112967999/439f1a06-8e4e-43b5-9755-14c69adb8de1">
  
## 6. Model Serving with Azure Databricks:

* Seamlessly deployed the model using Azure Databricks' model serving capabilities.
* Provided a real-time inference endpoint to integrate with HR systems for real-time churn predictions.

<img width="1470" alt="Screenshot 2024-05-19 at 5 52 34 PM" src="https://github.com/Abhi0323/End-to-End-Employee-Churn-Prediction-with-Azure-Databricks/assets/112967999/22dd33d8-137b-498d-804c-3fb1aeaa503f">

## 7. Application Deployment on Hugging Face Spaces:

* Developed an interactive application using Streamlit, deployed on Hugging Face Spaces.
* Allowed users to input employee data and receive churn predictions in real-time.
* Demonstrated the model's scalability and low latency.

<img width="591" alt="Screenshot 2024-05-19 at 6 32 31 PM" src="https://github.com/Abhi0323/End-to-End-Employee-Churn-Prediction-with-Azure-Databricks/assets/112967999/7c53dbfd-7f0c-4c84-ad98-a294776327d1">

## 8. Performance Monitoring and Scalability Testing:

* Monitored the model's performance using Azure Databricks' comprehensive monitoring tools.
* Ensured the model could handle high traffic and deliver efficient predictions.

<img width="1464" alt="Screenshot 2024-05-19 at 6 34 50 PM" src="https://github.com/Abhi0323/End-to-End-Employee-Churn-Prediction-with-Azure-Databricks/assets/112967999/91e8eca2-6e1e-4e1f-be33-8182e321901d">

## 9. MLOps for Seamless Model Management and Deployment:

* Employed robust MLOps practices with Azure Databricks and MLflow.
* Streamlined the deployment process, eliminating the need for extensive operational infrastructure.
* Enabled continuous model management, monitoring, and updating to maintain high performance.
  
## Conclusion

This project demonstrates a comprehensive and efficient approach to predicting employee churn, highlighting the integration of advanced data analytics and machine learning tools. The final application provides valuable insights for organizations to retain their best-performing employees, showcasing the potential of MLOps in streamlining model deployment and management.
