# Statistical_Analysis

## Introduction
This analysis focuses on the statistical evaluation of a dataset containing medical costs based on factors such as age, sex, BMI (Body Mass Index), number of children, smoking habits, and associated charges. The primary goal of this study is to explore key descriptive statistics such as mean, median, mode, and standard deviation of the variables, followed by hypothesis testing and regression analysis to understand the relationship between BMI and medical charges. This report will provide insights into how BMI influences medical costs and how various statistical methods can be applied to real-world healthcare data.

## Summary
The dataset was first explored using basic descriptive statistics to understand the central tendencies and dispersion of the variables. Key findings include:

The average age in the dataset is 39 years, with the median also at 39 years.
The BMI has a mean of 30.66, with a standard deviation of 6.1, indicating variability in the population's weight status.
The majority of the population (approximately 80%) are non-smokers, which significantly affects medical costs.
A one-sample t-test was conducted to test whether the average BMI significantly differs from a population mean of 0.05. The test produced a t-statistic of 183.63 and a p-value of 0, leading to the rejection of the null hypothesis. Additionally, a 95% confidence interval for the BMI was computed, ranging from 30.34 to 30.99.

Furthermore, a linear regression analysis was performed to determine the relationship between BMI and medical charges. The results showed a statistically significant positive relationship, with a p-value of less than 0.000, suggesting that higher BMI is associated with increased medical charges.

## Conclusion
This analysis highlights the use of statistical methods, such as descriptive statistics, hypothesis testing, and linear regression, to derive meaningful insights from healthcare data. The results confirm that BMI has a significant impact on medical costs, which aligns with existing medical literature that links obesity with higher healthcare expenses. The analysis underscores the importance of monitoring BMI to control healthcare costs, especially for conditions related to obesity.
