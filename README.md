# Analyzing Patient Admissions & Clinical Characteristics in the Cardiology Unit
## Background
This study analyses hospital admissions, readmissions, and expiries over two at Hero DMC Heart Institute, Ludhiana, a tertiary care cardiology centre. The dataset has recorded 15758 observations i.e., admissions. It captures patient demographics, admission type, comorbidities (like DM, HTN, CAD, heart failure), and lab parameters. The outcomes (discharge or expiry) were analysed to uncover trends across age groups, gender, region, and medical conditions, helping identify critical risk factors and patterns for improved patient care and hospital resource planning.
## Business Objectives 
The questions asked from all the hospital admissions, readmissions, and expiries data are, 
-	What is the outcome of the admissions?
-	How is the admissions distribution among different age groups?
-	Does ICU stay differ among the Emergency and ordinary type of admissions?
-	Is there a pattern in admissions throughout the year?
-	What medical conditions have strong influence on patients?
-	What is the readmissions rate and is there any trend throughout the year for readmissions?
-	What is the outcome of the readmissions ?
-	What is the mortality rate and distribution of expired patients among gender, region and admissions type?
-	Which age group has more expiries?
-	What the most influential medical conditions for expiry outcome?
## Data Source
Source- Kaggle<br>
Format- CSV<br>
Records- 15757<br>
Columns- 56
## Data Structure
![Data Structure 1](https://github.com/meretimounika/Patient-Admissions-in-Cardiology-Unit/blob/main/Data%20Structure/DS%20Admissions-Expiry.png)
---
![Data Structure 2](https://github.com/meretimounika/Patient-Admissions-in-Cardiology-Unit/blob/main/Data%20Structure/DS%20Readmissions.png)
## Executive Summary
This study analyses 15,757 cardiology admissions over two years at Hero DMC Heart Institute, Ludhiana, focusing on admissions, readmissions, and expiries. Most patients were discharged (87%), with a mortality rate of 7.01%. Elderly patients, especially those admitted through emergency services, had the highest admission and expiry rates. Readmissions stood at 22.10%, peaking in later months. Heart failure, CAD, and ACS were the most influential conditions in expiries. The findings highlight the need for improved emergency care, geriatric support, post-discharge monitoring, and preventive care for chronic conditions.
## Insights
### Admissions-
- Most hospital admissions resulted in discharge (13,756), indicating successful treatment. Mortality (expiry) cases were 1,105, while 896 patients left against medical advice (DAMA), which may suggest financial, personal, or dissatisfaction-related reasons.
- Most of the hospital admissions were among elderly patients (more than 60) with 8,616, followed by middle-aged(41-60) individuals and Young adults(18-40). Age below 18 have least no of cases with 56. 
-	Emergency type has average of longest stay (7) and longest ICU (5) compared to the ordinary type admissions.
-	Hospital admissions showed fluctuations throughout the year. April had the lowest admissions, followed by a steady increase, peaking in November (1,497). The trend indicates higher admissions in the latter months, possibly due to seasonal health factors.
-	Most of the patients (76%) were from urban areas, while 23% were from rural areas, showing that rural residents required more hospital care. 63% of admissions are from male patients while female are of 36%. 69% of admissions were emergency, while 30% were outpatient admissions, telling us the criticality of patients.
-	CAD is the most dominant condition with 66% of them having among the patients whereas Hypertension, Diabetes and ACS have significant influence. Heart Failure and Raised Cardiac Enzymes are least influential conditions among all patients.
![Admissions Medical Conditions](https://github.com/meretimounika/Patient-Admissions-in-Cardiology-Unit/blob/main/Screenshots%20Dashboards/Admissions%20Medical%20Conditons.png)
### Readmissions- 
-	The overall readmission rate stands at 22.10%, indicating that out of 100 patients, at least 22 have been readmitted.
-	There are fluctuating readmissions early in the year, with a drop in April and a steady rise afterward. Readmissions peak in November, possibly due to seasonal illnesses, then slightly decline in December. 
-	Most of them have been discharged with few of them expired. 176 patients left the hospital against medical advice (DAMA - Discharge Against Medical Advice), this could indicate dissatisfaction with treatment, financial constraints, or personal decisions.<br>
### Expiry-
-	There is a expiry count of 1,105 with mortality rate of 7.01% indicates that approximately 7 out of every 100 patients did not survive.
-	Among the deceased patients, 63% were male, while 36% were female. This makes us understand that male population have gone through more critical medical conditions.
-	Most of the expiry happened in the urban region with emergency admissions followed by rural emergencies. Ordinary admissions had very low number in both regions.
-	Most expiries occurred among the elderly, with 731 cases, followed middle-aged adults. Young adults and children had the lowest cases. This suggests that older age groups are at a higher risk of mortality compared to younger individuals.
-	The most dominant influence among all the medical conditions is heart failure with nearly 60% of cases expiry caused due to it. Diabetes and Raised Cardiac Enzymes have least influence with rest of them having significant influence.
![Expiry Medical Conditions](https://github.com/meretimounika/Patient-Admissions-in-Cardiology-Unit/blob/main/Screenshots%20Dashboards/Expiry%20Medical%20Conditions.png)
## Dashboards
![Admissions](https://github.com/meretimounika/Patient-Admissions-in-Cardiology-Unit/blob/main/Screenshots%20Dashboards/Admissions%20Dashboard.png)
---
![Readmissions](https://github.com/meretimounika/Patient-Admissions-in-Cardiology-Unit/blob/main/Screenshots%20Dashboards/Readmissions%20Dashboard.png)
---
![Expiry](https://github.com/meretimounika/Patient-Admissions-in-Cardiology-Unit/blob/main/Screenshots%20Dashboards/Expiry%20Dashboard.png)
## Recommendations
-	Enhance Emergency and Critical Care Services like Strengthen emergency departments with more ICU beds, dedicated cardiac ICUs, and rapid response protocols to reduce mortality in high-risk admissions.
-	Improve Elderly Care Infrastructure, allocate more resources to geriatric care, including specialized wards and chronic condition management, as the elderly show the highest expiry rates.
	Implement Robust Post-Discharge Follow-up, introduce telehealth check-ins, remote monitoring, and medication adherence programs to prevent avoidable readmissions.
-	Providing financial aid schemes for patients who opt for DAMA despite requiring critical medical attention, ensuring they can focus on recovery without financial burden.
-	Focus on Preventive Healthcare for Chronic Conditions, prioritize early detection and management of hypertension, diabetes, and heart disease to reduce overall hospitalizations and expiry rates.
## Tools and Technologies
Excel - for data cleaning  and filtering<br> 
SQL- for querying of readmissions data, age group sorting and expiry data extraction<br> 
Power query- for data transforming and cleaning<br>
DAX- Measurements created for analysis<br> 
Power BI- for dashboards and charts creation 


