\# Practical 06: Statistical Hypothesis Testing



\## Objective

To perform statistical hypothesis testing and correlation analysis using the teachers' rating dataset.



\## Dataset

\- \*\*File:\*\* `teaching\_ratings\_20.csv`

\- \*\*Source:\*\* Dataset used in Practical 02

\- \*\*Total observations:\*\* 20



\## Libraries Used

\- Pandas

\- NumPy

\- Matplotlib

\- SciPy (`scipy.stats`)



\## Questions and Analysis



\### Question 1: Independent T-Test — Gender and Teaching Evaluation



\*\*Question:\*\* Does gender affect teaching evaluation rates?



Separated male and female teaching evaluation scores and performed an independent T-test using `ttest\_ind()`.



\*\*Results:\*\*

\- T-statistic: -1.4508

\- P-value: 0.1640

\- Significance level (α): 0.05



\*\*Decision:\*\* Fail to reject the null hypothesis.



\*\*Conclusion:\*\* Since the p-value is greater than 0.05, there is insufficient statistical evidence of a significant difference in teaching evaluation rates between male and female instructors.



\### Question 2: ANOVA — Beauty Score Across Age Groups



\*\*Question:\*\* Does the beauty score of instructors differ by age?



Divided instructors into five age groups using `pd.cut()`:



\- Below 35

\- 35–45

\- 46–55

\- 56–65

\- Above 65



Applied the one-way ANOVA test using `f\_oneway()` to compare beauty scores across these groups.



\*\*Output shown in the practical:\*\*

\- F-statistic: NaN

\- P-value: NaN



\*\*Observation:\*\* The test could not produce valid results because one or more age groups had too few observations. The output also displayed a small-sample warning.



\### Question 3: Chi-Square Test — Association Between Tenure and Gender



\*\*Question:\*\* Is there an association between tenure status and gender?



Created a contingency table using `pd.crosstab()` and performed the Chi-Square test using `chi2\_contingency()`.



\*\*Contingency Table:\*\*



| Tenure | Female | Male |

|---|---:|---:|

| No | 2 | 3 |

| Yes | 7 | 8 |



\*\*Results shown in the practical:\*\*

\- Chi-square statistic: 0.0

\- P-value: 1.0

\- Degrees of freedom: 1



\*\*Hypotheses:\*\*

\- \*\*Null Hypothesis (H₀):\*\* There is no association between tenure status and gender.

\- \*\*Alternative Hypothesis (H₁):\*\* There is an association between tenure status and gender.



\*\*Decision:\*\* Fail to reject the null hypothesis.



\### Question 4: Pearson Correlation — Beauty and Teaching Evaluation



\*\*Question:\*\* Is the teaching evaluation score correlated with the beauty score?



Used the `pearsonr()` function to calculate the Pearson correlation coefficient and p-value. A scatter plot was also created using `plt.scatter()`.



\*\*Results:\*\*

\- Correlation coefficient: 0.0253

\- P-value: 0.9158



\*\*Decision:\*\* Fail to reject the null hypothesis.



\*\*Conclusion:\*\* The correlation coefficient is close to zero, indicating a very weak linear relationship between beauty score and teaching evaluation score. The p-value is greater than 0.05, so there is insufficient evidence of a statistically significant linear correlation.



\## Concepts Covered

\- Independent T-Test

\- One-Way ANOVA

\- Chi-Square Test of Independence

\- Pearson Correlation

\- Null and Alternative Hypotheses

\- P-value and Significance Level

\- Contingency Tables

\- Age Group Classification using `pd.cut()`

\- Data Visualization using Scatter Plots



\## Conclusion

This practical demonstrates the use of statistical tests to examine differences and relationships in a teachers' rating dataset. SciPy was used to perform hypothesis testing and correlation analysis, while Pandas was used for data manipulation and Matplotlib for visualization.



The results also demonstrate why sample size and data distribution are important when selecting and interpreting statistical tests.

