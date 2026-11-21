\# Practical 07: Regression Analysis



\## Objective

To perform regression analysis using the teachers' rating dataset and study the relationship between gender, age groups, beauty scores, and teaching evaluation scores.



\## Dataset

\- \*\*File:\*\* `teaching\_ratings\_20.csv`

\- \*\*Source:\*\* Dataset used in Practical 02

\- \*\*Total observations:\*\* 20



\## Libraries Used

\- Pandas

\- NumPy

\- Matplotlib

\- Statsmodels



\## Questions and Analysis



\### Question 1: Regression with T-Test — Gender and Teaching Evaluation



\*\*Question:\*\* Does gender affect teaching evaluation rates?



Converted the gender variable into a numerical regression variable:

\- Female = 1

\- Other gender category = 0



Applied Ordinary Least Squares (OLS) regression using `sm.OLS()` and displayed the regression summary using `model.summary()`.



\*\*Results:\*\*

\- Female coefficient: 0.2465

\- Standard error: 0.170

\- T-statistic: 1.451

\- P-value: 0.164

\- R-squared: 0.105



\*\*Decision:\*\* Fail to reject the null hypothesis.



\*\*Conclusion:\*\* Since the p-value is greater than 0.05, there is insufficient statistical evidence of a significant difference in teaching evaluation rates by gender in this dataset.



\### Question 2: Regression with ANOVA — Beauty Score Across Age Groups



\*\*Question:\*\* Does the beauty score of instructors differ by age?



Created three age groups using `pd.cut()`:



\- Below 40

\- 40–55

\- Above 55



Used the formula-based OLS model with `C(age\_group)` to treat age groups as categorical variables. Then performed ANOVA using `sm.stats.anova\_lm()`.



\*\*Results:\*\*

\- F-statistic: 0.072279

\- P-value: 0.930556

\- Degrees of freedom for age group: 2



\*\*Decision:\*\* Fail to reject the null hypothesis.



\*\*Conclusion:\*\* Since the p-value is greater than 0.05, there is insufficient statistical evidence of a significant difference in beauty scores across the three age groups.



\### Question 3: Regression — Beauty Score vs Teaching Evaluation



\*\*Question:\*\* Is the teaching evaluation score correlated with the beauty score?



Applied simple linear regression using beauty score as the independent variable and teaching evaluation score as the dependent variable.



Used `sm.OLS()` to fit the regression model and `model.summary()` to display the results.



\*\*Results:\*\*

\- Beauty coefficient: 0.0200

\- Standard error: 0.186

\- T-statistic: 0.107

\- P-value: 0.916

\- R-squared: 0.001



\*\*Decision:\*\* Fail to reject the null hypothesis.



\*\*Conclusion:\*\* The p-value is greater than 0.05, indicating insufficient statistical evidence of a significant linear relationship between beauty score and teaching evaluation score.



\## Concepts Covered

\- Regression Analysis

\- Ordinary Least Squares (OLS)

\- Independent and Dependent Variables

\- Dummy Variable Encoding

\- T-Test in Regression

\- ANOVA

\- Categorical Variables using `pd.cut()`

\- Regression Summary Interpretation

\- R-squared

\- Regression Coefficients

\- P-value and Significance Level



\## Conclusion

This practical demonstrates how Statsmodels can be used to perform regression analysis and ANOVA. It helps understand how independent variables relate to a dependent variable and how regression coefficients, R-squared values, and p-values are interpreted.



The results indicate that none of the three analyses provides sufficient evidence of a statistically significant relationship or difference at the 5% significance level.

