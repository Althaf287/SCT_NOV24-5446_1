# SCT_NOV24-5446-TSK 1
# SCT_NOV24-5446-TSK 2

# SCT_NOV24-5446-TSK 1

# Population Data Visualization: SkillCraft Technology Internship Task 1
## Overview
This project visualizes the distribution of population data for various countries around the world, with a focus on the year 2010. The task involves creating bar charts to visualize the top 10 and bottom 10 countries by total population, as well as exploring gender-specific populations (male and female) in these countries.

## Task Description
Task: Create bar charts or histograms to visualize the distribution of a categorical or continuous variable such as the distribution of ages or gender in population.
Task Completed By: Althaf N.
## Project Structure
The project consists of the following:

Data Cleaning : Importing and cleaning population data.
Visualization:
Bar charts showing the top 10 and bottom 10 countries based on total population in 2010.
Gender-specific population analysis (for male and female populations in 2010).
Python Libraries Used:
pandas: For data manipulation and analysis.
matplotlib: For creating static, interactive, and animated visualizations.
seaborn: For statistical data visualization.
### Data Source
The data used for this project is from the World Bank population dataset, which includes population statistics for countries across various years.

## Steps Involved
### 1. Data Loading
The dataset is loaded using the pandas library from a CSV file, which contains information on population for different countries and years.

### 2. Data Cleaning
Unnecessary columns such as "Country Code" and "Indicator Name" are dropped.
Rows with missing values are removed for consistency.
### 3. Population Data Filtering
The population data for the year 2010 is extracted, and the countries are sorted by total population for that year.

### 4. Data Visualization
Top 10 countries by population: A bar chart is created to show the top 10 countries with the highest total population in 2010.
Bottom 10 countries by population: A separate bar chart visualizes the bottom 10 countries with the lowest total population in 2010.
Gender-Specific Population: Two additional bar charts visualize the top 10 countries by male and female populations in 2010.
### 5. Visualization Customization
Value labels are added to the bars in the charts to provide exact population values, and the layout is adjusted for clarity.

# SCT_NOV24-5446-TSK 2

# Titanic Dataset - Data Cleaning and Exploratory Data Analysis (EDA)
This repository contains an analysis of the Titanic dataset available on Kaggle. The goal of this project was to perform data cleaning and exploratory data analysis (EDA) to identify patterns and trends in the data that may help predict the survival of passengers aboard the Titanic. This was an internship task as part of SkillCraft Technology's Data Science program.

## Dataset Source
The dataset used in this project is from the Kaggle Titanic competition.

## Steps Taken
### Step 1: Load the Titanic Dataset
The Titanic dataset was loaded into a pandas DataFrame for analysis.

### Step 2: Data Cleaning
The following steps were performed to clean the data:

Missing Values: Missing values were handled by imputing the Age column with the median, filling missing Embarked values with the most frequent embarkation point, and dropping the Cabin column due to excessive missing values.
Data Types: Columns like Survived, Pclass, and Embarked were converted to categorical data types to improve analysis.
### Step 3: Exploratory Data Analysis (EDA)
EDA was conducted to understand the relationships between various features and survival rates:

Summary Statistics: A quick overview of numerical features was generated.
Visualizations: Distributions for key features like Age, Fare, and Survived were visualized. We also explored survival rates by Sex, Pclass, Age, and Embarked.
Correlation Analysis: A correlation matrix was created to identify relationships between numerical features.
### Step 4: Feature Engineering
New features were created to better capture information:

FamilySize: Combined the number of siblings/spouses (SibSp) and parents/children (Parch) to create a new feature.
IsAlone: A binary feature indicating whether a passenger was traveling alone (based on the FamilySize feature).
### Step 5: Feature Importance
A Random Forest Classifier was used to assess the importance of different features in predicting survival. The most important features were identified and ranked.

### Step 6: Conclusion
Based on the data analysis, we can draw several conclusions:

Women had a higher survival rate than men.
First-class passengers had a higher survival rate than those in lower classes.
Younger passengers had a higher chance of survival.
Passengers who embarked at Cherbourg (C) had a higher survival rate than those who embarked at Southampton (S) or Queenstown (Q).
