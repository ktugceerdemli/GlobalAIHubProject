# GlobalAIHubProject

# Medical Appointment

Data from Kaggle [Link](https://www.kaggle.com/datasets/joniarroba/noshowappointments/data)

## Aim of this dataset

It's a medical appointment dataset which contains 110.527 data with 14 variables. The aim of this data set is try to understand patient why not showing up their appointment.

# Dataset Variables

- PatientId : The number of patient is 62299.

- AppointmentID : Unique number for each appointment.

- Gender : Male or Female

- ScheduledDay : The day patient get scheduled for appointment

- AppointmentDay: The day patient visit doctor

- Age: Age of the patient

- Neighbourhood: Where the appointment takes place

- Scholarship: Financial Aid

- Hipertension, Diabetes, Alcoholism: Illneess

- Handcap: Allowance

- SMS_received: Send sms to patient

- No-show: No or Yes to show up appointment (Target)

# Project Overview

This project explores both supervised and unsupervised machine learning methods, applying them to a real-world dataset to gain insights and build predictive models. The project utilizes CatBoost for supervised learning tasks and K-Means for unsupervised clustering, along with various feature engineering techniques to enhance the dataset.

Supervised Learning - CatBoost
For the supervised learning section, CatBoost, a gradient boosting algorithm, was implemented due to its efficient handling of categorical features and its ability to deliver high accuracy. To optimize the performance of the CatBoost model, Optuna, a hyperparameter optimization framework, was employed. Optuna efficiently searched through the hyperparameter space to identify the best configuration, resulting in improved model performance.

Unsupervised Learning - K-Means Clustering
In the unsupervised learning section, K-Means Clustering was applied to identify patterns and group similar data points. To determine the optimal number of clusters, two evaluation methods were used:

Elbow Method: The elbow curve helped in visualizing the point where adding more clusters provided diminishing returns.
Silhouette Score: This score was used to measure how similar each point is to its own cluster compared to other clusters, aiding in selecting the best number of clusters.


Key Libraries Used
CatBoost: For supervised learning tasks.
Optuna: For hyperparameter optimization.
K-Means: For clustering analysis.
PCA: For visualization of clustering
Scikit-learn: For evaluation metrics such as Silhouette Score and Elbow Method.
This project showcases how machine learning models can be effectively used for both predictive tasks and clustering, with proper attention given to hyperparameter tuning and feature engineering.

[Kaggle Link](https://www.kaggle.com/code/tugceerdemlial/medicalappointment-supervised-unsupervised/)
