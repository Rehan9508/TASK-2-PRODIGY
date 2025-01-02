Name: Rehan Majid

Company: Prodigy InfoTech

CIN: PIT/JUN24/03902

Domain: DATA SCIENCE

Duration: 1st December2024 to 31st January2025

Project Overview: Titanic Dataset Analysis Project Objective: The primary goal of this project is to perform data cleaning and exploratory data analysis (EDA) on the Titanic dataset. This dataset contains information about the passengers of the Titanic, including demographic details, ticket class, fare, and survival status. The analysis aims to uncover patterns and trends that influence survival rates, explore relationships between variables, and prepare the data for further modeling , predictive analysis.

Dataset Description: The Titanic dataset includes the following files:

gender_submission.csv: Provides a basic prediction on survival based on gender. train.csv: Contains training data with features and survival outcomes. test.csv: Contains test data with passenger details but without survival outcomes. Key columns include:

PassengerId: Unique identifier for each passenger. Survived: Survival status (0 = Not Survived, 1 = Survived). Pclass: Passenger class (1 = First, 2 = Second, 3 = Third). Sex: Gender of the passenger. Age: Age of the passenger. SibSp: Number of siblings/spouses aboard. Parch: Number of parents/children aboard. Fare: Ticket fare. Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton). Steps Followed in the Analysis: Importing and Loading Data:

Loaded data from CSV files using Pandas. Displayed basic information about the datasets (e.g., columns, data types, missing values). Data Cleaning:

Handling Missing Values: Filled missing Age values with the median age. Replaced missing Embarked values with the most frequent port. Dropped the Cabin column due to excessive missing data. Filled missing Fare values with the median fare. Duplicate Removal: Checked and removed duplicate rows (if any). Exploratory Data Analysis (EDA):

Univariate Analysis: Examined the distribution of numerical features like Age and Fare using histograms. Analyzed categorical variables (Survived, Pclass, Sex, Embarked) using count plots. Bivariate Analysis: Explored the relationship between Survived and key features (Sex, Pclass, Age). Created pie charts, scatter plots, and bar plots to identify patterns. Correlation Analysis: Computed correlations between numerical features to identify dependencies. Visualized correlations using a heatmap. Insights Derived:

Survival Patterns: Higher survival rates for females compared to males. Passengers in first class had a significantly higher chance of survival. Age and Survival: Younger passengers tended to have better survival rates. Non-survivors were older on average compared to survivors. Fare and Survival: Higher ticket fares were associated with higher survival probabilities. Embarkation Port: Passengers embarking from Cherbourg (C) had higher survival rates than those from Southampton (S) or Queenstown (Q). Descriptive Statistics:

Provided detailed statistics for numerical features (mean, median, standard deviation, etc.). Highlighted variations between survivors and non-survivors in terms of age, fare, and class. Data Visualization:

Used Seaborn and Matplotlib for creating intuitive and aesthetically pleasing plots. Plotted pairwise relationships to explore multidimensional interactions. Key Outcomes and Learnings: EDA revealed significant relationships between survival and features like gender, class, and fare. Missing value handling and feature engineering prepared the dataset for predictive modeling. Data visualization aided in understanding the dataset's underlying structure and trends. Future Steps: Use the cleaned and analyzed data to build predictive models (e.g., logistic regression, decision trees) to predict survival. Perform feature selection and engineering to improve model accuracy. Explore advanced visualizations for deeper insights into passenger demographics and survival factors. This project demonstrates foundational data analysis skills and highlights the importance of structured EDA in understanding and preparing datasets for further analysis.

![image](https://github.com/user-attachments/assets/7553a8d9-fb4a-4c02-b112-0372242e184f)
![image](https://github.com/user-attachments/assets/12e86b37-c325-449f-8d34-ac5264263ee0)
![image](https://github.com/user-attachments/assets/3fd45425-7fdc-4925-aeb5-b70ced83c641)
![image](https://github.com/user-attachments/assets/45b66f2b-28f2-4955-a6dc-7f856ae1bea1)
![image](https://github.com/user-attachments/assets/967220e6-89d7-455c-88c2-ce3e89253eb1)
![image](https://github.com/user-attachments/assets/6a95cd35-08d8-411e-8ec2-009eef28746e)
![image](https://github.com/user-attachments/assets/17feccc8-59be-4947-8c47-028b2193635d)
![image](https://github.com/user-attachments/assets/2abf8ca0-44d4-48f6-b703-775e6fcd5fbc)
![image](https://github.com/user-attachments/assets/a646b543-c24a-4e9e-89d0-e4971f89e346)
![image](https://github.com/user-attachments/assets/394e1e17-f013-4279-896c-a8687f0ca7ee)
![image](https://github.com/user-attachments/assets/d1178207-877e-492f-84d1-023bbb45d9f8)
![image](https://github.com/user-attachments/assets/81fc0bf3-6966-480e-bd55-383fa5afb6da)
![image](https://github.com/user-attachments/assets/cccb5a3c-fc94-41c9-a619-b313c945c69a)
![image](https://github.com/user-attachments/assets/c0b73919-6b69-42f9-b2e2-d8679b745e06)
