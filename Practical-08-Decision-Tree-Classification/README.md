\# Practical 08: Decision Tree Classification



\## Aim

To build a Decision Tree Classifier using Python and Scikit-learn on the Pima Indians Diabetes dataset. The practical includes feature selection, dataset splitting, model training, evaluation, visualization, and analysis of Entropy, Information Gain, and Gini Index.



\## Dataset

\- \*\*Dataset:\*\* Pima Indians Diabetes

\- \*\*Records:\*\* 768

\- \*\*Features:\*\* 8 independent variables

\- \*\*Target:\*\* `Outcome`

\- \*\*Target classes:\*\*

&#x20; - `0` – No Diabetes

&#x20; - `1` – Diabetes



\## Technologies and Libraries

\- Python

\- Pandas

\- NumPy

\- Matplotlib

\- Scikit-learn



\## Practical Tasks



1\. Import the required Python libraries.

2\. Load and inspect the diabetes dataset.

3\. Separate independent variables (`X`) and the dependent variable (`y`).

4\. Split the dataset into training (80%) and testing (20%) sets.

5\. Build and train a Decision Tree Classifier using the Entropy criterion.

6\. Evaluate the model using accuracy, confusion matrix, and classification report.

7\. Visualize the trained Decision Tree.

8\. Identify the root feature and its splitting threshold.

9\. Calculate Entropy, Information Gain, and Gini Index.

10\. Compare candidate root splits using Information Gain.



\## Key Results



| Measurement | Result |

|---|---:|

| Dataset shape | 768 × 9 |

| Training records | 614 |

| Testing records | 154 |

| Model accuracy | 69.48% |

| Root feature | Glucose |

| Root threshold | 154.5 |

| Parent Entropy | 0.9328 |

| Weighted Child Entropy | 0.7891 |

| Information Gain | 0.1436 |

| Parent Gini Index | 0.4541 |

| Weighted Child Gini Index | 0.3619 |

| Gini Reduction | 0.0923 |



\## Model Evaluation



The Decision Tree achieved an accuracy of approximately \*\*69.48%\*\* on the testing dataset.



The confusion matrix was:



```text

\[\[92  8]

&#x20;\[39 15]]

```



The classification report showed:

\- No Diabetes: Precision 0.70, Recall 0.92, F1-score 0.80.

\- Diabetes: Precision 0.65, Recall 0.28, F1-score 0.39.



\## Conclusion



A Decision Tree Classifier was successfully implemented using the Pima Indians Diabetes dataset. The dataset was divided into training and testing sets, and the model was trained using the Entropy criterion.



The model selected \*\*Glucose\*\* as the root feature with a threshold of \*\*154.5\*\*. The comparison of candidate root splits also ranked Glucose first based on Information Gain.



The practical demonstrated feature selection, classification, model evaluation, tree visualization, and the use of Entropy, Information Gain, and Gini Index to understand decision tree splitting.



\## Folder Structure



```text

Practical-08-Decision-Tree-Classification/

├── README.md

├── Practical08.ipynb

└── DATA/

&#x20;   └── diabetes.csv

```



\## Author

Atul Sharma



B.Tech – Computer Science and Engineering (Data Science)

