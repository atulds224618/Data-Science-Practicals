\# Practical 09: K-Nearest Neighbors (KNN) Classification



\## Aim

To implement the K-Nearest Neighbors (KNN) classification algorithm using the Iris dataset and evaluate its performance using different K values.



\## Dataset

\- \*\*Dataset:\*\* Iris Dataset

\- \*\*Source:\*\* Scikit-learn (`sklearn.datasets.load\_iris`)

\- \*\*Total Records:\*\* 150

\- \*\*Features:\*\* 4

\- \*\*Target Classes:\*\* 3



\### Features

1\. Sepal Length

2\. Sepal Width

3\. Petal Length

4\. Petal Width



\### Target Classes

\- 0 – Setosa

\- 1 – Versicolor

\- 2 – Virginica



\## Technologies and Libraries

\- Python

\- Pandas

\- NumPy

\- Matplotlib

\- Scikit-learn



\## Practical Tasks



1\. Perform Exploratory Data Analysis using `head()`, `describe()`, and `groupby()`.

2\. Separate independent and dependent variables.

3\. Apply feature scaling using StandardScaler.

4\. Split the dataset into training and testing sets.

5\. Train a K-Nearest Neighbors classifier.

6\. Generate a confusion matrix and calculate accuracy.

7\. Generate a classification report.

8\. Compare error rates for different K values.

9\. Plot error rates against K values.

10\. Identify the best K value.

11\. Visualize actual and predicted test results.



\## Model Configuration

\- \*\*Algorithm:\*\* K-Nearest Neighbors

\- \*\*Initial K Value:\*\* 5

\- \*\*Train-Test Split:\*\* 80:20

\- \*\*Feature Scaling:\*\* StandardScaler

\- \*\*Distance:\*\* Euclidean (default Minkowski distance with p=2)



\## Model Evaluation



The trained model is evaluated using:

\- Confusion Matrix

\- Accuracy Score

\- Precision

\- Recall

\- F1-score

\- Error Rate



Different K values are tested to identify the value with the lowest testing error rate.



\## Conclusion



The K-Nearest Neighbors classification algorithm was implemented using the Iris dataset. Exploratory Data Analysis and feature scaling were performed before training the model.



The model was evaluated using a confusion matrix, accuracy score, and classification report. Different K values were compared using their error rates, and the best K value was selected based on the minimum observed testing error.



The practical demonstrates how KNN performs classification based on the distance between data points and how the choice of K affects model performance.



\## Folder Structure



```text

Practical-09-KNN-Classification/

├── README.md

├── Practical09.ipynb

└── DATA/

```



\## Author

Atul Sharma



B.Tech – Computer Science and Engineering (Data Science)

