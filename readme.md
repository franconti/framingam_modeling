# Introduction 
This is my second post using Framingham's cardiovascular study. In this post I will use this data set to introduce feature engineering and ensemble modeling. Firstly, I will display some feature analyses then ill focus on the feature engineering. Last part concerns modeling and predicting the 10-year risk of coronary heart disease.

The attributes are classified into several categories:

Demographic: Sex: male or female (Nominal) Age: Age of the patient (Continuous, though recorded in whole numbers)

Behavioral: Current Smoker: Indicates if the patient is currently a smoker (Nominal) Cigs Per Day: Average number of cigarettes smoked per day (Continuous, as it can take any numerical value)

Medical history: BP Meds: Indicates if the patient was using blood pressure medication (Nominal) Prevalent Stroke: Indicates if the patient had previously experienced a stroke (Nominal) Prevalent Hyp: Indicates if the patient was hypertensive (Nominal) Diabetes: Indicates if the patient had diabetes (Nominal)

Medical: Tot Chol: Total cholesterol level (Continuous) Sys BP: Systolic blood pressure (Continuous) Dia BP: Diastolic blood pressure (Continuous) BMI: Body Mass Index (Continuous) Heart Rate: Heart rate (Continuous) Glucose: Glucose level (Continuous)

Predicted Variable: 10-year risk of coronary heart disease CHD (binary: “1” signifies “Yes”, “0” signifies “No”)

This script follows three main parts:

-Feature analysis 

- Feature engineering

- Modeling

# References
https://www.kaggle.com/code/leaphys/titanic-top-4-with-ensemble-modeling

https://github.com/vahadruya/Capstone_Classification_Cardiovascular_Risk_Prediction/blob/main/Trial%20Notebooks/Classification_ML_Capstone_CVD_Risk_Prediction_KNNImputer.ipynb
