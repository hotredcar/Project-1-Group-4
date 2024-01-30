# Project-1-Group-4

Comprehensive Heart Health Data Analysis - Understanding Heart Disease Influencers

Overview:

This project aims to comprehensively analyse and visualize health-related data to gain insights into factors influencing heart disease (HD) outcomes. According to the CDC, heart disease is a leading cause of death for people of most races in the U.S. with some key indicators including diabetes status, obesity (high BMI), not getting enough physical activity, or drinking too much alcohol. Identifying and preventing the factors that have the greatest impact on heart disease is crucial in healthcare. In turn, developments in computing would allow to detect "patterns" in the data that can predict a patient's condition. Objective of this study is to find any insightful correlations between the risk factors included, and their potential patterns and relatedness to heart diseases. As such, it covers various aspects, including data cleaning, exploratory analysis, and visualization. 

Source:

The data is sourced from the CDC's Behavioural Risk Factor Surveillance System (BRFSS) and Kaggle. BRFSS conducts annual telephone surveys to collect data on the health status of U.S. residents. Established in 1984 with 15 states, BRFSS now collects data in all 50 states, the District of Columbia, and three U.S. territories. BRFSS completes more than 400,000 adult interviews each year, making it the largest continuously conducted health survey system in the world. The most recent dataset includes data from 2022, covering indicators related to heart disease, including some major presumed risk factors such as smoking, diabetes, obesity, physical inactivity, and excessive alcohol consumption. These factors directly or indirectly may influence heart disease, leading to the selection of the most relevant variables for analysis of their interdependencies. 

-	https://www.cdc.gov/brfss/annual_data/annual_2022.html
-	https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease

Variables in the Dataset:

1.	Race: Imputed race/ethnicity value. 
2.	Sex: Gender (Male/Female).
3.	Age: Fourteen-level age category.
4.	Health: General health perception.
5.	BMI: Body Mass Index.
6.	PA:  Engagement in physical activity or exercise in the past 30 days.
7.	Sleep: Hours of sleeping per day.
8.	Smoker: History of smoking (Yes/No).
9.	Alcohol: Heavy drinking status.
10.	Difficulty Walking: Difficulty walking or climbing stairs.
11.	Kidney Disease: History of kidney disease.
12.	Skin Cancer: History of skin cancer.
13.	Asthma: History of Asthma.
14.	COPD: History of Chronic obstructive pulmonary disease.
15.	Diabetes: History of diabetes.
16.	Stroke: History of stroke.
17.	HD: Respondents reporting coronary heart disease (CHD) or myocardial infarction (MI) or Angina.
    
Data analysis steps taken:

1.	 Data Cleaning
   
-	Utilized Pandas to clean and pre-process datasets.
-	Handled missing values, ensuring data consistency.
-	Re-organised data structure and formatting.
-	Selected indicators were only studied, reducing the size of the dataset by 58%.
2.	Exploratory Data Analysis (EDA)
-	Conducted exploratory data analysis to understand health indicators interdependencies and rate of influence on heart diseases.
-	Identified outliers and explored potential correlations.
3.	Correlation Analysis
-	Investigated correlations between different health indicators, demographical and lifestyle factors.
4.	Geospatial Analysis
-	Performed geospatial analysis to visualize prevalence of heart disease across different states.

Usage:

-	To explore the analysis process, findings, and gain insights into health indicators and their relationships with heart disease, refer to the “Main2.ipynb” Jupyter notebook available in this repository.
-	“output_data” folder includes all the data visualisation plots. 
-	CSV files used for the main dataset and geospatial analysis are included in the repository.

Collaborators:

- Gilbert Dichoso
- Deldata Musa
- Ali Yazdan
- Kah Jun Yong

Acknowledgments:

We acknowledge the CDC for providing the BRFSS dataset, which serves as the foundation for this analysis. The project's focus on both coding skills and statistical analysis makes it a valuable resource for individuals interested in gaining practical experience in data science.

