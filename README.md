
**Analysis of Framingham Heart Study

**Domain :

Healthcare

**Table of Contents:

Information
Loading Dataset
Data Cleansing & EDA
Conclusion
Source (Download On Request) : https://www.nhlbi.nih.gov/science/framingham-heart-study-fhs

![coronary-heart-disease-chd-n](https://user-images.githubusercontent.com/85118624/127723313-de5f65a3-b149-4a21-bc8b-cc02fd205b58.jpg)


**Details : 

The Framingham Heart Study has been an ongoing study, since 1948, attempting to identify common risk factors that contribute to cardiovascular disease. The study began with 5,209 men and women between the ages of 30-62 from the town of Framingham, Massachusetts. The study participants return every 2 years for detailed physical examinations, medical history, and lab tests.

The second generation of participants, the off-spring of the original participants, were enrolled in 1971. There were 5,124 of those. The “Omni Cohort” was enrolled in the Framingham Heart Study in 1994 after identifying the need to increase the diversity of the population. Framingham 3 began in 2002 with the enrollment of the grandchildren of the original participants, the third generation. The 2nd generation of the Omni Cohort was added in 2003. The majority of participants are caucasian.

The Framingham Heart Study has resulted in approximately 1,200 articles in different medical journals. Over the years, different diagnostic technologies have been added. Echocardiography, carotid artery ultrasound, cardiac MRI, and CT scans of the hart and coronary arteries are examples of some of the diagnostic technologies. Evaluations of the genetic profiles of all participants are also being evaluated.

**The Framingham Risk Score

The Framingham Risk Score is a 10-year calculation of risk for cardiovascular disease was formulated from the Framingham Heart Study. The Framingham Risk Score Calculator uses several factors in order to calculate the patient’s risk of developing cardiovascular disease within 10 years. Low intermediate, and high risk is based on the percent risk over 10 years.

Low Risk: <10% risk in the next 10 years
Intermediate Risk: 10-20% risk in the next 10 years
High Risk: >20% risk in the next 10 years

The components of the risk calculator are:
Sex : the gender of the observations. The variable is a binary named “male” in the dataset. 
age : Age at the time of medical examination in years. 
education : A categorical variable of the participants education, with the levels: Some high school (1), high school/GED (2), some college/vocational school (3), college (4) 
currentSmoker: Current cigarette smoking at the time of examinations 
cigsPerDay: Number of cigarettes smoked each day 
BPmeds: Use of Anti-hypertensive medication at exam 
prevalentStroke: Prevalent Stroke (0 = free of disease) 
prevalentHyp: Prevalent Hypertensive. Subject was defined as hypertensive if treated diabetes: Diabetic according to criteria of first exam treated 
totChol: Total cholesterol (mg/dL) 
sysBP: Systolic Blood Pressure (mmHg) 
diaBP: Diastolic blood pressure (mmHg) 
BMI: Body Mass Index, weight (kg)/height (m)^2 
heartRate: Heart rate (beats/minute) 
glucose: Blood glucose level (mg/dL) 
And finally the response variable : + TenYearCHD : The 10 year risk of coronary heart disease(CHD).

**Questions:

1. What is the spread of each attribute in the given data set ?
2. What are the lifestyle changes seen in people with heart disease?
3. Can we get the count of CHD based on gender?
4. Which characteristics are most prevalent in people have heart disease?
5. Can we group people of certain age together and figure out how Sys. BP and Dia. BP affects by Age group ?
6. How is our variables distributed? Are they imbalanced?
7. What are the weakness of this dataset?


**Objective :

we will look at prevalence of different risk factors, and see which ones are common with development of heart disease.

**Dataset Weakness:

The Framingham Risk Score (FRS) has driven cardiovascular disease risk screening for many years. In general, there are 2 main problems with current dataset. First, this screening happened based on known risk factors and not the actual presence of disease. Second, it is based on epidemiology.
Epidemiologic data can be tricky because it tells us about issues in a given population. However, it does NOT necessarily indicate risk for a specific person.
>>>>>>> aedcb661887a552e5335746579e69e6e79234254

**Domain :

Healthcare

**Table of Contents:

Information
Loading Dataset
Data Cleansing & EDA
Conclusion
Source (Download On Request) : https://www.nhlbi.nih.gov/science/framingham-heart-study-fhs

**Details : 

The Framingham Heart Study has been an ongoing study, since 1948, attempting to identify common risk factors that contribute to cardiovascular disease. The study began with 5,209 men and women between the ages of 30-62 from the town of Framingham, Massachusetts. The study participants return every 2 years for detailed physical examinations, medical history, and lab tests.

The second generation of participants, the off-spring of the original participants, were enrolled in 1971. There were 5,124 of those. The “Omni Cohort” was enrolled in the Framingham Heart Study in 1994 after identifying the need to increase the diversity of the population. Framingham 3 began in 2002 with the enrollment of the grandchildren of the original participants, the third generation. The 2nd generation of the Omni Cohort was added in 2003. The majority of participants are caucasian.

The Framingham Heart Study has resulted in approximately 1,200 articles in different medical journals. Over the years, different diagnostic technologies have been added. Echocardiography, carotid artery ultrasound, cardiac MRI, and CT scans of the hart and coronary arteries are examples of some of the diagnostic technologies. Evaluations of the genetic profiles of all participants are also being evaluated.

**The Framingham Risk Score

The Framingham Risk Score is a 10-year calculation of risk for cardiovascular disease was formulated from the Framingham Heart Study. The Framingham Risk Score Calculator uses several factors in order to calculate the patient’s risk of developing cardiovascular disease within 10 years. Low intermediate, and high risk is based on the percent risk over 10 years.

Low Risk: <10% risk in the next 10 years
Intermediate Risk: 10-20% risk in the next 10 years
High Risk: >20% risk in the next 10 years

The components of the risk calculator are:
Sex : the gender of the observations. The variable is a binary named “male” in the dataset. 
age : Age at the time of medical examination in years. 
education : A categorical variable of the participants education, with the levels: Some high school (1), high school/GED (2), some college/vocational school (3), college (4) 
currentSmoker: Current cigarette smoking at the time of examinations 
cigsPerDay: Number of cigarettes smoked each day 
BPmeds: Use of Anti-hypertensive medication at exam 
prevalentStroke: Prevalent Stroke (0 = free of disease) 
prevalentHyp: Prevalent Hypertensive. Subject was defined as hypertensive if treated diabetes: Diabetic according to criteria of first exam treated 
totChol: Total cholesterol (mg/dL) 
sysBP: Systolic Blood Pressure (mmHg) 
diaBP: Diastolic blood pressure (mmHg) 
BMI: Body Mass Index, weight (kg)/height (m)^2 
heartRate: Heart rate (beats/minute) 
glucose: Blood glucose level (mg/dL) 
And finally the response variable : + TenYearCHD : The 10 year risk of coronary heart disease(CHD).

**Questions:

1. What is the spread of each attribute in the given data set ?
2. What are the lifestyle changes seen in people with heart disease?
3. Can we get the count of CHD based on gender?
4. Which characteristics are most prevalent in people have heart disease?
5. Can we group people of certain age together and figure out how Sys. BP and Dia. BP affects by Age group ?
6. How is our variables distributed? Are they imbalanced?
7. What are the weakness of this dataset?


**Objective :

we will look at prevalence of different risk factors, and see which ones are common with development of heart disease.

**Dataset Weakness:

The Framingham Risk Score (FRS) has driven cardiovascular disease risk screening for many years. In general, there are 2 main problems with current dataset. First, this screening happened based on known risk factors and not the actual presence of disease. Second, it is based on epidemiology.
Epidemiologic data can be tricky because it tells us about issues in a given population. However, it does NOT necessarily indicate risk for a specific person.
