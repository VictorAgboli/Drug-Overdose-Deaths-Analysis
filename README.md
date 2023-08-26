# Drug-Overdose-Deaths-Analysis using Bayesian Inference

**Introduction:**
This project analyzes drug overdose deaths in the United States from 2017 to 2020 using Markov Chain Monte Carlo methods. The goal is to determine if there's a significant increase or decrease between successive years and validate claims made by the CDC Director, Dr. Rochelle P. Walensky. The dataset contains drug overdose deaths in 50 states plus the District of Columbia due to opioids, psychostimulants, and more.

**Methods:**
Histograms of overdose deaths are examined for common characteristics. Likelihood functions are developed based on log-transformed overdose deaths data, with prior distributions for parameters. Posterior distributions are generated using the Metropolis-Hastings Markov Chain. Key questions addressed are:
1. Difference in mean overdose deaths between 2017 and 2018.
2. Difference in mean overdose deaths between 2019 and 2020.

**Procedure:**
1. Define parameters for prior and likelihood distributions.
2. Generate posterior function by combining prior and likelihood distributions.
3. Run Markov Chain iterations using the Metropolis-Hastings rule.
4. Reach conclusions based on analysis.

**Results:**
For the analysis of 2017-2018 data, the probability that overdose deaths in 2017 are less than those in 2018 is approximately 0.32. For the analysis of 2019-2020 data, the probability that overdose deaths in 2019 are less than those in 2020 is approximately 0.84.

**Conclusion:**
The results support Dr. Walensky's claim of rising overdose deaths in the USA. Overdose deaths were likely higher in 2017 compared to 2018 and lower in 2019 compared to 2020. The findings are consistent with CDC reports, and as more data accumulates, the claim can be reevaluated.

