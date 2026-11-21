\# Practical 05: Probability and Hypothesis Testing



\## Objective

To calculate probabilities using a teachers' rating dataset and perform a two-tailed hypothesis test using the normal distribution.



\## Dataset

\- \*\*File:\*\* `teaching\_ratings\_20.csv`

\- \*\*Source:\*\* Dataset used in Practical 02

\- \*\*Total observations:\*\* 20

\- \*\*Main variable:\*\* `eval` (Teaching Evaluation Score)



\## Libraries Used

\- Pandas

\- NumPy

\- Matplotlib

\- SciPy (`scipy.stats.norm`)



\## Questions and Analysis



\### Question 1: Probability of Receiving an Evaluation Score Greater Than 4.5



Calculated the probability of receiving a teaching evaluation score greater than 4.5 using the `eval` column.



\*\*Results:\*\*

\- Total observations: 20

\- Evaluations greater than 4.5: 0

\- Probability: 0.0

\- Percentage: 0%



\### Question 2: Probability of Receiving an Evaluation Score Between 3.5 and 4.2



Calculated the probability of receiving an evaluation score greater than 3.5 and less than 4.2.



\*\*Results:\*\*

\- Total observations: 20

\- Evaluations in the specified range: 10

\- Probability: 0.5

\- Percentage: 50%



\### Question 3: Two-Tailed Hypothesis Test Using Normal Distribution



A professional basketball team wants to compare its average performance with the historical performance of professional players.



\*\*Given Data:\*\*



| Parameter | Value |

|---|---:|

| Historical Mean (μ) | 12 |

| Standard Deviation (σ) | 5.5 |

| Sample Size (n) | 36 |

| Sample Mean (x̄) | 10.7 |

| Significance Level (α) | 0.05 |



\*\*Hypotheses:\*\*



\- \*\*Null Hypothesis (H₀):\*\* The mean points scored by regional players is equal to the historical mean.

\- \*\*Alternative Hypothesis (H₁):\*\* The mean points scored by regional players is different from the historical mean.



\*\*Results:\*\*

\- Z-score: -1.4182

\- P-value: 0.1561

\- Significance level: 0.05

\- Decision: Fail to reject the null hypothesis.



\*\*Conclusion:\*\* Since the p-value (0.1561) is greater than the significance level (0.05), there is insufficient statistical evidence to conclude that the regional players' average points per game differs from the historical professional mean.



\## Concepts Covered

\- Probability calculation

\- Conditional filtering in Pandas

\- Counting observations

\- Calculating probability and percentage

\- Normal distribution

\- Z-score calculation

\- Two-tailed hypothesis testing

\- Null and alternative hypotheses

\- P-value interpretation

\- Significance level and statistical decisions



\## Conclusion

This practical demonstrates how Python can be used to calculate probabilities from a dataset and perform hypothesis testing using the normal distribution. Pandas is used for data filtering and analysis, NumPy for numerical calculations, and SciPy for normal distribution probability calculations.

