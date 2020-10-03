# Predicting Heart disease using Linear Support vector Machine

## Introduction 

Your heart is one of your body's most important organs. Essentially a pump, the heart is a muscle made up of four chambers separated by valves and divided into two halves. Each half contains one chamber called an atrium and one called a ventricle. The atria (plural for atrium) collect blood, and the ventricles contract to push blood out of the heart. The right half of the heart pumps oxygen-poor blood (blood that has a low amount of oxygen) to the lungs where blood cells can obtain more oxygen. Then, the newly oxygenated blood travels from the lungs into the left atrium and the left ventricle. The left ventricle pumps the newly oxygen-rich blood to the organs and tissues of the body. This oxygen provides your body with energy and is essential to keep your body healthy.

There are many factors that can increase your risk of getting heart disease. Some of these factors are out of your control, but many of them can be avoided by choosing to live a healthy lifestyle. Some of the risk factors you cannot control are: 
Age
Gender
High Cholesterol 
Life Style etc. 
##  Data
Here we have used  dataset from this link https://www.kaggle.com/ronitf/heart-disease-uci

This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them. In particular, the Cleveland database is the only one that has been used by ML researchers to
this date. The "goal" field refers to the presence of heart disease in the patient. It is integer valued from 0 (no presence) to 4.

1. Age: Displays the age of the individual.
2. Sex: Displays the gender of the individual using the following format : 1 = male 0 = female.
3. Chest-pain type: Displays the type of chest-pain experienced by the individual.
4. Resting Blood Pressure: Displays the resting blood pressure value of an individual in mmHg (unit).
5. Cholestrol: Displays the serum cholestrol in mg/dl (unit).
6. Fasting Blood Sugar: Compares the fasting blood sugar value of an individual with 120mg/dl. If fasting blood sugar > 120mg/dl then : 1 (true) else : 0 (false).
7. Resting ECG: 0 = normal 1 = having ST-T wave abnormality 2 = left ventricular hyperthrophy.
8. Max heart rate: Displays the max heart rate achieved by an individual.
9. Exercise induced angina: 1 = Yes 0 = No.
10. Oldpeak: ST depression induced by exercise relative to rest. Displays the value which is integer or float.
11. Slope: The slope of the peak exercise ST segment.
12. Number of major vessels colored by flourosopy.
13. Thal: Displays the thalassemia.
14. Diagnosis of heart disease: Displays whether the individual is suffering from heart disease or not.

## Model Training and Prediction:
We trained our prediction model through supervised learning as we already have the target variable. We have used Support Vector Machine to train the model and get prediction.

## Model Evaluation:
The confusion matrix is used here to evaluate our model. We got an accuracy of 86% using the SVM.
