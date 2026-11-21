\# Practical 04: Data Cleaning and Visualization



\## Objective

To perform data cleaning, identify duplicate instructor records, calculate statistical measures, and visualize relationships between instructor age, teaching evaluation scores, gender, tenure, and course division.



\## Dataset

\- \*\*File:\*\* `teaching\_ratings\_20.csv`

\- \*\*Source:\*\* Dataset used in Practical 02

\- \*\*Total observations:\*\* 20

\- \*\*Unique instructors:\*\* 20



\## Libraries Used

\- Pandas

\- NumPy

\- Matplotlib



\## Questions and Analysis



\### Question 1: Duplicate Cases and Age Analysis



Identified duplicate cases using the `prof` column, which represents instructor IDs. Calculated the average age and standard deviation using all observations and repeated the analysis after retaining one observation per instructor.



\*\*Results using all observations:\*\*

\- Average age: 43.7

\- Standard deviation: 9.652379



\*\*Results after removing duplicate instructor records:\*\*

\- Number of observations: 20

\- Average age: 43.7

\- Standard deviation: 9.652379



\*\*Observation:\*\* The dataset contains 20 observations and 20 unique instructors. Therefore, removing duplicate instructor records does not change the statistical results.



\*\*Note:\*\* The practical instructions mention 94 instructors, but the supplied dataset and displayed output contain 20 unique instructors.



\### Question 2: Lower-Division Courses and Teaching Evaluations



Calculated average teaching evaluation scores for lower-division and upper-division courses using `groupby()` and created a bar chart using Matplotlib.



\*\*Results:\*\*

\- Lower division: 3.800000

\- Upper division: 3.926316



\*\*Observation:\*\* Upper-division courses have a slightly higher average teaching evaluation score in this dataset.



\### Question 3: Relationship Between Age and Teaching Evaluation Scores



Created a scatter plot using `plt.scatter()` to visualize the relationship between instructor age and teaching evaluation scores.



Each point represents an observation. The plot helps identify possible patterns between age and evaluation scores.



\### Question 4: Gender-Differentiated Scatter Plot



Created separate scatter plots for male and female instructors to compare the relationship between age and teaching evaluation scores.



Different labels and a legend were used to distinguish the two groups.



\### Question 5: Scatter Plot by Gender and Tenure



Created a scatter plot differentiating observations by both gender and tenure status.



The graph uses separate groups for:

\- Female - Tenured

\- Female - Not Tenured

\- Male - Tenured

\- Male - Not Tenured



This visualization helps compare age and teaching evaluation patterns across the four groups.



\## Concepts Covered

\- Identifying duplicate records using `duplicated()`

\- Removing duplicates using `drop\_duplicates()`

\- Calculating mean and standard deviation

\- Grouping data using `groupby()`

\- Creating bar charts

\- Creating scatter plots

\- Filtering DataFrames by conditions

\- Comparing data across gender and tenure categories



\## Conclusion

This practical demonstrates how Pandas can be used for data cleaning and statistical analysis, while Matplotlib helps visualize relationships between numerical and categorical variables. It also highlights the importance of checking dataset size and unique records before drawing conclusions.

