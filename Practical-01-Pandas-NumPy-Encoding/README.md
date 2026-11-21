\# Practical 01 – Pandas, NumPy and One-Hot Encoding



\## Overview

This practical explores basic data manipulation and numerical operations using Pandas and NumPy. It also demonstrates how categorical data can be converted into numerical format using One-Hot Encoding.



\## Aim

To understand data handling using Pandas, perform numerical operations using NumPy, and implement One-Hot Encoding on categorical data.



\## Objectives

\- Load and explore a student performance dataset using Pandas.

\- Understand DataFrame structure, shape and information.

\- Separate numerical and categorical columns.

\- Convert DataFrames into NumPy arrays.

\- Perform matrix operations using NumPy.

\- Apply One-Hot Encoding to categorical variables.



\## Dataset

The practical uses a student performance dataset containing 20 records and 12 columns.



The dataset includes information such as:

\- Student ID

\- Gender

\- Study hours

\- Attendance percentage

\- Sleep hours

\- Parental education

\- Internet access

\- Extracurricular activities

\- Part-time job

\- Previous grade

\- Final exam score

\- Final grade



\## Libraries Used

\- Pandas

\- NumPy



Install the required libraries:



```bash

pip install pandas numpy

```



\## Implementation



\### 1. Import Libraries

Import Pandas and NumPy for data manipulation and numerical computation.



\### 2. Load and Explore Data

Load the CSV dataset into a Pandas DataFrame and inspect it using:

\- `head()`

\- `info()`

\- `shape`



\### 3. Separate Data Columns

Separate numerical and categorical columns and check for missing values in numerical data.



\### 4. NumPy Array Operations

Convert the DataFrame into a NumPy array and explore:

\- Shape

\- Size

\- Number of dimensions



\### 5. Matrix Operations

Create matrices using array slicing and perform:

\- Addition

\- Subtraction

\- Element-wise multiplication

\- Matrix multiplication

\- Transpose

\- Determinant

\- Inverse



\### 6. One-Hot Encoding

Convert categorical variables into numerical representations using Pandas `get\_dummies()`.



\## Files

\- `Practical01.ipynb` – Jupyter Notebook containing the implementation.

\- `DATA/` – Dataset used in the practical.



\## Conclusion

This practical demonstrates how Pandas and NumPy can be used for data exploration, manipulation and numerical computation. It also introduces One-Hot Encoding, an important preprocessing technique used to convert categorical data into numerical form for machine learning.



\## How to Run

Open `Practical01.ipynb` using Jupyter Notebook or PyCharm and execute the cells sequentially.

