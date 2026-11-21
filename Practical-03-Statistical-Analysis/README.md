\# Practical 03: Statistical Analysis and Data Visualization



\## Objective

To perform statistical analysis on a professors' rating dataset using Python libraries such as Pandas, NumPy, and Matplotlib.



\## Dataset

\- \*\*File:\*\* `Student\_Rating\_Dataset\_120\_Entries.xlsx`

\- \*\*Records:\*\* 120

\- \*\*Columns:\*\* 13



\## Libraries Used

\- Pandas

\- NumPy

\- Matplotlib

\- OpenPyXL



\## Questions and Analysis



\### Question 1: Tenure Percentage of Visible Minorities

Calculated the percentage of visible-minority professors who are tenured and compared their tenure status with non-visible-minority professors.



\*\*Results:\*\*

\- Total visible-minority professors: 30

\- Tenured visible-minority professors: 17

\- Percentage tenured: 56.67%



\### Question 2: Average Age by Tenure

Calculated the mean and standard deviation of age for tenured and untenured professors using `groupby()` and `agg()`.



| Tenure Status | Mean Age | Standard Deviation |

|---|---:|---:|

| No | 44.018868 | 7.865432 |

| Yes | 50.955224 | 10.517565 |



\### Question 3: Age Distribution

Created a histogram using `plt.hist()` to visualize the distribution of professors' ages.



\### Question 4: Gender Distribution

Studied the difference between `plt.bar()` and `plt.barh()` and plotted the gender distribution.



\*\*Results:\*\*

\- Male professors: 80

\- Female professors: 40



\### Question 5: Median Evaluation Score

Calculated the median evaluation score for tenured professors using the Pandas `median()` function.



\*\*Result:\*\* 4.0



\## Concepts Covered

\- Reading Excel files using Pandas

\- Filtering DataFrames

\- Grouping data using `groupby()`

\- Calculating mean, standard deviation, and median

\- Frequency distribution

\- Data visualization using Matplotlib

\- Vertical and horizontal bar charts



\## Conclusion

This practical helped in understanding statistical analysis and data visualization using Python. Pandas was used for data manipulation and statistical calculations, while Matplotlib was used to create graphical representations of the data.

