\# Practical 11: Sunspot Data Analysis using Gamma Distribution and MCMC



\## Aim

To analyze monthly mean sunspot numbers using the Gamma probability distribution and Markov Chain Monte Carlo (MCMC) methods.



\## Dataset

\- \*\*Dataset:\*\* Monthly Mean Total Sunspot Number

\- \*\*Source:\*\* SILSO — World Data Center for the Production, Preservation and Dissemination of the International Sunspot Number

\- \*\*File:\*\* `SN\_m\_tot\_V2.0.csv`

\- \*\*Period:\*\* January 1749 to November 2018

\- \*\*Observations:\*\* 3,239



\## Technologies and Libraries

\- Python

\- Pandas

\- NumPy

\- Matplotlib

\- SciPy



\## Practical Tasks



1\. Load and visualize monthly sunspot data over time.

2\. Model sunspot counts using the Gamma distribution across 12-year cycles.

3\. Plot a histogram of sunspot counts.

4\. Apply the Metropolis-Hastings MCMC algorithm using initial parameter values a = 4 and b = 10.

5\. Visualize the first 50, all, and last 50 MCMC samples.

6\. Remove burn-in samples and visualize parameter traces and histograms.

7\. Estimate distribution parameters and predict sunspot observations.



\## Concepts Covered

\- Exploratory Data Analysis

\- Time-Series Visualization

\- Gamma Probability Distribution

\- Shape and Scale Parameters

\- Metropolis-Hastings Algorithm

\- Markov Chain Monte Carlo

\- Burn-in Period

\- Parameter Estimation



\## MCMC Configuration

\- Initial shape parameter (a): 4

\- Initial scale parameter (b): 10

\- Total iterations: 5,000

\- Burn-in samples: 1,000



\## Conclusion

Monthly sunspot data was analyzed using Python visualization and statistical methods. The Gamma distribution was used to model sunspot counts, while the Metropolis-Hastings algorithm was applied for MCMC-based parameter estimation.



The practical demonstrates how probability distributions and Bayesian sampling techniques can be used to study and estimate parameters from observed data.



\## Folder Structure



```text

Practical-11-Sunspot-Analysis-MCMC/

├── README.md

├── Practical11.ipynb

└── DATA/

&#x20;   └── SN\_m\_tot\_V2.0.csv

```



\## Author

Atul Sharma



B.Tech – Computer Science and Engineering (Data Science)

