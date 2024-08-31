# Life Expectancy Analysis

## Project Overview

In this project, we aim to investigate various factors affecting life expectancy across different countries and regions. The dataset used in this analysis contains information on life expectancy, economic indicators, health expenditures, educational status, and disease prevalence from multiple countries over several years. By examining these variables, we seek to understand how economic and social factors contribute to differences in life expectancy worldwide.

Our analysis involves data cleaning, preprocessing, and exploratory data analysis (EDA) to uncover meaningful patterns and trends. The ultimate goal is to provide insights that can inform policy decisions aimed at improving health outcomes globally.

## Research Questions

1. **How does life expectancy vary across different countries and regions?**
2. **What is the relationship between GDP and life expectancy?**
3. **How do health expenditures impact life expectancy?**
4. **What is the effect of education (schooling) on life expectancy?**
5. **How does the prevalence of diseases like HIV/AIDS correlate with life expectancy?**
6. **What trends can be observed in life expectancy over time?**

## Dataset Information

The dataset contains various indicators that may influence life expectancy, including economic, health, and demographic factors. Below is a brief explanation of the columns included in the dataset:

- **Country**: The name of the country.
- **Year**: The year the data was recorded.
- **Status**: The development status of the country (Developed or Developing).
- **Life expectancy**: The average life expectancy in years.
- **Adult Mortality**: The adult mortality rate, indicating the probability of dying between the ages of 15 and 60 years per 1,000 population.
- **infant deaths**: The number of infant deaths per 1,000 population.
- **Alcohol**: Alcohol consumption per capita (age 15+), measured in liters of pure alcohol.
- **percentage expenditure**: Health expenditure as a percentage of GDP per capita.
- **Hepatitis B**: Immunization coverage for Hepatitis B among 1-year-olds, given as a percentage.
- **Measles**: The number of reported measles cases per 1,000 population.
- **BMI**: The average Body Mass Index (BMI) of the entire population.
- **under-five deaths**: The number of deaths of children under five years old per 1,000 population.
- **Polio**: Immunization coverage for Polio among 1-year-olds, given as a percentage.
- **Total expenditure**: The general government expenditure on health as a percentage of total government expenditure.
- **Diphtheria**: Immunization coverage for Diphtheria, Tetanus toxoid, and Pertussis (DTP3) among 1-year-olds, given as a percentage.
- **HIV/AIDS**: The number of deaths due to HIV/AIDS per 1,000 live births (age 0-4 years).
- **GDP**: The Gross Domestic Product per capita, measured in USD.
- **Population**: The population of the country.
- **thinness 1-19 years**: The prevalence of thinness among adolescents aged 10 to 19 years, given as a percentage.
- **thinness 5-9 years**: The prevalence of thinness among children aged 5 to 9 years, given as a percentage.
- **Income composition of resources**: The Human Development Index in terms of income composition, ranging from 0 to 1.
- **Schooling**: The average number of years of schooling.

## Project Steps

### STEP 1: Importing Necessary Libraries
- Import all the necessary libraries such as `pandas`, `numpy`, `plotly`, etc.

### STEP 2: Reading/Loading Data Set
- Load the dataset into a DataFrame using `pandas`.

### STEP 3: Descriptive Analysis
- Perform basic descriptive analysis to understand the structure of the data.

### STEP 4: Initial Exploratory Data Analysis (EDA)
- **Univariate Analysis**: Analyze the distribution of individual variables.
- **Bivariate Analysis**: Explore relationships between two variables.
- **Multivariate Analysis**: Examine interactions between multiple variables.

### STEP 5: Imputing Missing Values
- Handle missing data using appropriate imputation techniques.

### STEP 6: Outlier Treatment
- Identify and treat outliers to ensure they do not skew the analysis.

### STEP 7: Feature Engineering
- Create new features or modify existing ones to enhance model performance.

### STEP 8: Feature Selection (Optional)
- Select the most relevant features for the analysis.

### STEP 9: Encoding of Data
- Convert categorical variables into numerical values using encoding techniques.

### STEP 10: Post-Split Exploratory Data Analysis (EDA)

## Addressing the Research Questions

### 1. How does life expectancy vary across different countries and regions?
- Use visualizations to compare life expectancy across countries and regions.
- Provide descriptive statistics for life expectancy by country and region.

**Findings:**
- Life expectancy varies significantly across different countries.
- Developed countries tend to have higher life expectancy compared to developing countries.

### 2. What is the relationship between GDP and life expectancy?
- Create a scatter plot to visualize the relationship between GDP and life expectancy.
- Calculate and display the correlation between GDP and life expectancy.

**Findings:**
- A positive correlation exists between GDP and life expectancy, indicating that wealthier countries tend to have longer life expectancy.

### 3. How do health expenditures impact life expectancy?
- Create a scatter plot to visualize the relationship between health expenditures and life expectancy.
- Calculate and display the correlation between health expenditures and life expectancy.

**Findings:**
- Higher health expenditures are correlated with higher life expectancy.
- Investing in health significantly impacts the overall life expectancy of a country.

### 4. What is the effect of education (schooling) on life expectancy?
- Create a scatter plot to visualize the relationship between schooling and life expectancy.
- Calculate and display the correlation between years of schooling and life expectancy.

**Findings:**
- There is a positive correlation between years of schooling and life expectancy.
- Education plays a crucial role in improving life expectancy.

### 5. How does the prevalence of diseases like HIV/AIDS correlate with life expectancy?
- Create a scatter plot to visualize the prevalence of HIV/AIDS and life expectancy.
- Calculate and display the correlation between HIV/AIDS prevalence and life expectancy.

**Findings:**
- There is a negative correlation between the prevalence of HIV/AIDS and life expectancy.
- Higher rates of HIV/AIDS prevalence are associated with lower life expectancy.

### 6. What trends can be observed in life expectancy over time?
- Create a line plot to visualize the trend of life expectancy over the years for the top 10 countries.
- Analyze significant changes or patterns over time.

**Findings:**
- The top 10 countries consistently exhibit higher life expectancy values throughout the years.
- Globally, there is an upward trend in life expectancy over the years, indicating significant advancements in healthcare systems.

## Conclusion

This project has provided valuable insights into the factors that influence life expectancy across different regions and countries. Understanding these factors can help guide policies and strategies to improve global health outcomes.


