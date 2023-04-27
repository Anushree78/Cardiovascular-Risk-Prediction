# Cardiovascular-Risk-Prediction

# Summary:

Cardiovascular diseases are the major cause of mortality worldwide. According to WHO, 17.9 million people died in 2019, accounting for 32% of all global fatalities. Though CHDs cannot be treated, predicting the risk of the disease and taking the necessary precautions and medications can help to avoid severe symptoms and, in some cases, even death. As a result, it is critical that we accurately predict the risk of heart disease in order to avert as many fatalities as possible.

Predicting coronary heart disease in advance helps raise awareness for the disease. Preventive measurements like changing diet plans and exercise can slow down the progression of CHD. Early prediction can result in early diagnosis. So, we can treat the disease at an early stage and avoid more invasive treatment.

The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD) based on their health statistics and information about their tobacco usage.

# Problem Statement
The dataset is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts.The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD). The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes. Variables Each attribute is a potential risk factor. There are both demographic, behavioral, and medical risk factors

# Data Set

The dataset is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The dataset provides the patient's information and health stats. It includes over 4,000 records and 15 attributes.

Data Description and Attributes:-

id: Patient identification number. Demographic:

Sex: male or female("M" or "F") Age: Age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous)

Behavioral

is_smoking: whether or not the patient is a current smoker ("YES" or "NO") Cigs Per Day: the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can have any number of cigarettes, even half a cigarette.)

Medical( history)

BP Meds: whether or not the patient was on blood pressure medication (Nominal) Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal) Prevalent Hyp: whether or not the patient was hypertensive (Nominal) Diabetes: whether or not the patient had diabetes (Nominal) Medical(current)

Tot Chol: total cholesterol level (Continuous) Sys BP: systolic blood pressure (Continuous) Dia BP: diastolic blood pressure (Continuous) BMI: Body Mass Index (Continuous) Heart Rate: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values.)

Glucose: glucose level (Continuous) Dependent variable (desired target)

*10-year risk of coronary heart disease CHD(binary: “1”, means “Yes”, “0” means “No”)
