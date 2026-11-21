\# Practical 02 – Descriptive Statistics and Data Analysis



\## Overview



This practical focuses on analyzing a professor ratings dataset from top universities in the USA using Python libraries such as Pandas, NumPy and Matplotlib.



It covers descriptive statistics, data distribution, gender-wise comparison of beauty scores, and tenure status analysis.



\## Aim



To perform descriptive statistical analysis on professor rating data and understand differences in beauty scores and tenure status across genders.



\## Objectives



\- Understand the difference between time-series and cross-sectional data.

\- Calculate the mean, median, minimum and maximum values of the number of students.

\- Generate a descriptive statistics table.

\- Visualize beauty scores using a histogram.

\- Compare average beauty scores and standard deviations by gender.

\- Calculate tenure percentages for male and female professors.



\## Dataset



\*\*File:\*\* `teaching\_ratings\_20.csv`



The dataset contains 20 records and 12 columns.



Important variables include:



\- `minority`

\- `age`

\- `gender`

\- `credits`

\- `beauty`

\- `eval`

\- `division`

\- `native`

\- `tenure`

\- `students`

\- `allstudents`

\- `prof`



\## Libraries Used



\- Pandas

\- NumPy

\- Matplotlib



Install the libraries using:



```bash

pip install pandas numpy matplotlib

```



\## Questions and Implementation



\### Q1. Identify the type of data



Determine whether the professor rating dataset represents time-series or cross-sectional data.



\### Q2. Calculate student statistics



Calculate the following values for the `students` column:



\- Mean

\- Median

\- Minimum

\- Maximum



\### Q3. Descriptive Statistics Table



Use Pandas `describe()` to generate descriptive statistics for numerical columns.



The table includes count, mean, standard deviation, minimum, quartiles and maximum.



\### Q4. Histogram of Beauty Scores



Create a histogram of the `beauty` variable using Matplotlib.



Use the histogram to examine the distribution and frequency of beauty scores.



\### Q5. Beauty Scores by Gender



Group the dataset by gender and calculate:



\- Mean beauty score

\- Standard deviation of beauty score



Compare the results for male and female instructors.



\### Q6. Tenure Percentage by Gender



Use a cross-tabulation to calculate the number and percentage of tenured and non-tenured professors in each gender group.



Use row-wise normalization to calculate percentages.



\## Key Results



\### Q2 – Student Statistics



| Measure | Result |

|---|---:|

| Mean | 35.5 |

| Median | 26 |

| Minimum | 16 |

| Maximum | 200 |



\### Q5 – Beauty Score Comparison



| Gender | Mean | Standard Deviation |

|---|---:|---:|

| Female | 0.438889 | 0.396430 |

| Male | 0.161364 | 0.543366 |



\### Q6 – Tenure Percentage



| Gender | Not Tenured | Tenured |

|---|---:|---:|

| Female

