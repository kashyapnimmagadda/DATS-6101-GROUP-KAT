# DATS-6101-DATA-SCIENCE-TEAM-KAT
Repository for team KAT of DATS 6101 by Professor Farhana Faruqe, Spring 2023.

## Project Description
### Topic Proposal
World Health Organization has estimated 12 million deaths occur worldwide; every year due to heart diseases. Half the deaths in the United States and other developed countries are due to cardiovascular diseases. The early prognosis of cardiovascular diseases can aid in making decisions on lifestyle changes in high-risk patients and in turn reduce complications. This project covers manual exploratory data analysis using R in R-Studio. The dataset used in this project is the heart disease dataset from Kaggle, and both data and code for this project will be available on my GitHub repository.

Here are some SMART questions we are trying to answer:
1.	What are the key risk factors and their correlations with the occurrence of heart strokes? 
2.	Find out any patterns or trends in the distribution of these risk factors, in each dataset of patient medical records related to heart stroke cases, using exploratory data analysis. 
3.	Identify any potentially significant insights or areas of further investigation?

Our dataset combines an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD). The dataset provides the patients’ information. It includes over 4,240 records and 15 attributes.

The dependent or target variable is the "TenCHD" column (10-year risk of coronary heart disease), which is a binary variable indicating the presence or absence of heart disease in the patient. It is the variable that we want to predict based on the other variables in the dataset.

The independent variables or features in this dataset are the remaining 14 columns, including the patient's age, gender, smoking_status, cigaretes_per_day, bp_meds, stroke_history, hypertensive_ history, diabetes, cholesterol level, systolic blood pressure, diastolic blood pressure, body mass index, heart rate, glucose level.


Source of the data set:
https://www.kaggle.com/datasets/dileep070/heart-disease-prediction-using-logistic-regression

### Variables  
Each attribute is a potential risk factor. There are both demographic, behavioral and medical risk factors.

**Demographic:**
* Sex: male or female(Nominal)
* Age: Age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous)  

**Behavioral:**
* Current Smoker: whether or not the patient is a current smoker (Nominal)
* Cigs Per Day: the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can have any number of cigarettes, even half a cigarette.)  

**Medical(History):**
* BP Meds: whether or not the patient was on blood pressure medication (Nominal)
* Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)
* Prevalent Hyp: whether or not the patient was hypertensive (Nominal)
* Diabetes: whether or not the patient had diabetes (Nominal) 
 
**Medical(Current):**
* Tot Chol: total cholesterol level (Continuous)
* Sys BP: systolic blood pressure (Continuous)
* Dia BP: diastolic blood pressure (Continuous)
* BMI: Body Mass Index (Continuous)
* Heart Rate: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values.)
* Glucose: glucose level (Continuous)
Predict variable (desired target)
* 10 year risk of coronary heart disease CHD (binary: “1”, means “Yes”, “0” means “No”)
