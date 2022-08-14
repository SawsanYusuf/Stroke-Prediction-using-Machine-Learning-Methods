# Stroke-Prediction-using-Machine-Learning-Methods

According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.

#### In this project, we need to Build a supervised model to predict whether a patient is likely to get a stroke. We used Stroke Prediction Dataset from Kaggle which contains 11 clinical features for predicting stroke events based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.

#### The healthcare-dataset-stroke-data.csv dataset includes the following fields:

1. id: unique identifier

2. gender: "Male", "Female" or "Other".

3. age: age of the patient.

4. hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension.

5. heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease.

6. ever_married: "No" or "Yes".

7. work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed".

8. Residence_type: "Rural" or "Urban".

9. avg_glucose_level: average glucose level in blood.

10. bmi: body mass index.

11. smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*.

12. stroke: 1 if the patient had a stroke or 0 if not.

*Note: "Unknown" in smoking_status means that the information is unavailable for this patient.

## The classification algorithms that we used in this project:

1. K Nearest Neighbor(KNN).

2. Decision Tree.

3. Support Vector Machine.

4. Logistic Regression.

## The methods we used to evaluate our models:

1. Jaccard Index.
2. F1-Score.
3. LogLoss.
