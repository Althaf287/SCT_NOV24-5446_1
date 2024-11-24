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
