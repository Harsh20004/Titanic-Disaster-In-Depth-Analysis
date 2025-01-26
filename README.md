# Titanic-Disaster-In-Depth-Analysis

## Project Overview
### This project focuses on performing an Exploratory Data Analysis (EDA) on the Titanic dataset to uncover key insights and trends. The main objectives include:

 - Understanding the data structure and key features.
 - Visualizing the distribution of numerical and categorical variables.
 - Analyzing passenger demographics and their impact on survival rates.
 - Identifying outliers and skewness.


## Titanic Dataset Column Descriptions

### Survived
- Indicates if the passenger survived:
  0: Did not survive
  1: Survived
  
### Pclass
- Passenger's travel class:
  1: 1st Class
  2: 2nd Class
  3: 3rd Class
  
### Name
- The full name of the passenger.
  
### Sex
- The gender of the passenger:
  male
  female

### Age
- Age of the passenger in years. Some entries may have missing values.

### SibSp
- Number of siblings or spouses aboard the Titanic.

### Parch
- Number of parents or children aboard the Titanic.

### Ticket
- The ticket number assigned to the passenger.

### Fare
- The amount paid for the ticket (in British Pounds).

### Cabin
- The cabin number of the passenger, if available.

### Embarked
- The port where the passenger boarded the Titanic:
  C: Cherbourg
  Q: Queenstown
  S: Southampton


## EDA on Titanic Dataset

### Tools & Libraries
- Pandas: Data manipulation and analysis
- Seaborn & Matplotlib: Data visualization

### Key Insights
- Survival Rates: Passengers in 1st class had a significantly higher survival rate compared to those in 2nd and 3rd class.
 Females had a much higher chance of survival compared to males, emphasizing the "women and children first" policy.

- Age Distribution: Younger passengers, especially children, had better survival rates.
Outliers in Age (e.g., passengers above 65) were identified but didn't significantly impact survival trends.

- Fare Trends: Passengers who paid higher fares were generally in 1st class and had a better survival rate.
The Fare distribution showed significant skewness.

- Embarkation Points: Most passengers embarked from Southampton (S), but passengers from Cherbourg (C) had a slightly higher survival rate.

- Family Influence: Passengers with small family sizes (based on Parch and SibSp) had a better survival chance than those traveling alone or in large families.

## Future Work

- Model Training: Train machine learning models (e.g., Logistic Regression, Random Forest) to predict passenger survival based on the dataset.
Evaluate model performance using metrics like accuracy and F1-score.

- Deployment: Build a web application or dashboard where users can input passenger details to predict survival probability.

