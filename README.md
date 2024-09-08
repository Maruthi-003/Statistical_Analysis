# Statistical_Analysis

## Overview
This project analyzes a dataset containing various factors such as age, sex, BMI (Body Mass Index), number of children, smoking status, and medical charges. The main goal is to explore the statistical relationships between these variables, with a particular focus on understanding how BMI affects medical costs.

The project utilizes Python libraries like **NumPy**, **Pandas**, **Matplotlib**, **SciPy**, and **StatsModels** to perform the analysis. Key statistical concepts such as descriptive statistics, hypothesis testing (t-tests), confidence intervals, and linear regression are employed to derive insights from the data.

## Dataset
The dataset used for this analysis contains the following columns:
- **age**: Age of the individual
- **sex**: Gender (1 for male, 0 for female)
- **bmi**: Body Mass Index, a measure of body fat based on height and weight
- **children**: Number of children covered by the health insurance
- **smoker**: Whether the individual smokes (1 for yes, 0 for no)
- **charges**: Medical charges billed to the individual

The data is loaded from a CSV file called `medical_cost.csv`.

## Statistical Concepts Used

### 1. Descriptive Statistics
Descriptive statistics provide insights into the distribution of the data. We compute the following for each variable:
- **Mean**: Average value
- **Median**: Middle value when sorted
- **Mode**: Most frequent value
- **Standard Deviation**: Measure of data spread
- **Variance**: The square of standard deviation
- **Skewness**: Measure of data asymmetry
- **Kurtosis**: Measure of the 'tailedness' of data

### 2. Hypothesis Testing (One-Sample t-test)
A **one-sample t-test** was conducted to test if the mean BMI significantly differs from a population mean (0.05). The t-statistic and p-value are computed to assess statistical significance.

### 3. Confidence Interval
We calculate a 95% confidence interval for BMI to understand the range within which the true mean is expected to lie.

### 4. Linear Regression
A **linear regression** is performed to investigate the relationship between BMI (independent variable) and medical charges (dependent variable). This helps us quantify the impact of BMI on medical costs.

#### Key Regression Output:
- **R-squared**: Proportion of the variance in medical charges explained by BMI.
- **Coefficient**: The estimated change in medical charges for a unit increase in BMI.
- **P-value**: The statistical significance of the relationship.

## Results Summary
- **Descriptive Statistics**: The average BMI is approximately 30.66, and the average medical charges are 13,270.42.
- **T-Test**: The p-value for the t-test was 0, leading us to reject the null hypothesis and conclude that BMI is significantly different from the population mean.
- **Confidence Interval**: The 95% confidence interval for BMI is between 30.34 and 30.99.
- **Linear Regression**: The results show a statistically significant positive relationship between BMI and medical charges. A unit increase in BMI is associated with an increase of approximately 393.87 in medical charges.

## Conclusion
The analysis demonstrates that BMI is a significant predictor of medical costs. However, the low R-squared value suggests that other factors also influence medical charges. The dataset provides valuable insights into healthcare costs, particularly in relation to BMI, but further analysis incorporating additional variables may be necessary to fully understand the drivers of medical costs.

## Requirements
To run the analysis, you'll need the following Python libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `scipy`
- `statsmodels`

You can install these using pip:
```bash
pip install numpy pandas matplotlib scipy statsmodels
```
name :B Maruthi Kumar
email: maruthikumarbandaru@gmail.com
linkedin: linkedin.com/in/maruthi-kumar-328537258/
