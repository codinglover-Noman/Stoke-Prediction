# Stoke-Prediction using Machine Learning 
According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.
## Objective: 
Create a predictive model that evaluates the probability of a patient experiencing a stroke, incorporating demographic information, health conditions, lifestyle factors, residence details, and health metrics.

## Datasets 
This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. 
Each row in the data provides relavant information about the patient.
The datasets: 
https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

## Attribute Information

1) id: unique identifier
2) gender: "Male", "Female" or "Other"
3) age: age of the patient
4) hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
5) heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
6) ever_married: "No" or "Yes"
7) work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
8) Residence_type: "Rural" or "Urban"
9) avg_glucose_level: average glucose level in blood
10) bmi: body mass index
11) smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
12) stroke: 1 if the patient had a stroke or 0 if not
*Note: "Unknown" in smoking_status means that the information is unavailable for this patient

## Acknowledgements
(Confidential Source) - Use only for educational purposes
If you use this dataset in your research, please credit the author.

## Machine Learning Problem Solving Workflow:

   ✅ Problem Understanding:
        Understand the nature of the problem.
        Have knowledge about the attributes of the data.

   ✅ Data Inspection:
        Determine the size of the dataset.
        Examine the data to understand the tasks it is currently performing.

   ✅Data Types and Quality Check:
        Verify the correctness of data types.
        Check for any missing values in the dataset.
        Identify and handle duplicate entries.

   ✅Exploratory Data Analysis (EDA):
        Inspect data to ensure the correctness of types and distributions.
        Examine occurrence frequencies for each column.

   ✅Correlation Analysis:
        Evaluate the correlation between input features and the output variable.
        Explore correlations among input variables.

   ✅Outlier Detection:
        Identify and handle outliers in the dataset.

   ✅ Feature Engineering:
        Identify and drop unnecessary columns based on domain knowledge or techniques.
        Encode categorical columns using techniques like Label Encoding, Ordinal Encoding, or One-Hot Encoding.

   ✅ Normalization (if necessary):
        Normalize the data if required by the chosen machine learning model.

   ✅ Model Selection:
        Implement various machine learning models to evaluate performance.
        Select the model that best fits the problem and dataset.



