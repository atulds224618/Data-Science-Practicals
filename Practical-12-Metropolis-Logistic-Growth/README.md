\# Practical 12: Metropolis Algorithm and Deterministic Logistic Growth Model



\## Aim



To implement the Metropolis Algorithm for generating samples from a target probability distribution and simulate a deterministic logistic growth model using Euler's Method.



\## Part A: Metropolis Algorithm



\### Objective

To generate random samples from a standard normal distribution using the Metropolis Algorithm.



\### Concepts Covered

\- Probability Distribution

\- Standard Normal Distribution

\- Markov Chain Monte Carlo (MCMC)

\- Metropolis Algorithm

\- Proposal Distribution

\- Acceptance and Rejection

\- Acceptance Rate

\- Histogram Visualization



\### Configuration

\- Target Distribution: Standard Normal Distribution

\- Initial Value: 0

\- Proposal Standard Deviation: 1

\- Number of Samples: 10,000



\### Evaluation

\- Display the first 10 generated samples.

\- Calculate the acceptance rate.

\- Plot a histogram of generated samples.

\- Compare the histogram with the actual standard normal probability density function.



\## Part B: Deterministic Logistic Growth Model



\### Objective

To simulate population growth using the deterministic logistic growth model and Euler's Method.



\### Logistic Growth Equation



dP/dt = rP(1 - P/K)



Where:

\- P = Population size

\- r = Growth rate

\- K = Carrying capacity

\- t = Time



\### Model Parameters

\- Growth Rate (r): 0.2

\- Carrying Capacity (K): 1000

\- Initial Population (P0): 50

\- Time Range: 0 to 50

\- Number of Time Points: 200



\### Concepts Covered

\- Deterministic Models

\- Logistic Population Growth

\- Carrying Capacity

\- Euler's Numerical Method

\- Population Simulation

\- Data Visualization



\### Evaluation

\- Calculate population values using Euler's Method.

\- Display the first 10 population values.

\- Display the final population.

\- Plot population growth against time.



\## Technologies and Libraries

\- Python

\- NumPy

\- Matplotlib

\- SciPy



\## Conclusion



The Metropolis Algorithm was implemented to generate samples from a standard normal distribution. The generated samples were analyzed using an acceptance rate and histogram visualization.



A deterministic logistic growth model was also implemented using Euler's Method. The simulation demonstrates how population growth approaches the carrying capacity over time.



\## Folder Structure



```text

Practical-12-Metropolis-Logistic-Growth/

├── README.md

├── Practical12.ipynb

└── DATA/

```



\## Author



Atul Sharma



B.Tech – Computer Science and Engineering (Data Science)

