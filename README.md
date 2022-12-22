# Survival_Analysis

This project focuses on the analysis of survival patients with Aids. The length of the probe is approximately 5 years, and data contains variables such as date of diagnosis, date of death, sex, age, and status.

Firstly I needed to clean the data so that further analysis could be made. With the use of classical functions and anonymous functions, I cleaned it and deleted empty columns. Additionally, I divided the data into 2 datasets, one with 5 years and the second with 2 to check differences between survival analysis between those years.

Finally using the Python library Lifelines I presented the Kaplan-Meier plot with differences between sexes in 2-year analysis, and used the log-rank test to check if both sexes had the same survival curves.

Furthermore, I checked the differences for 2-year data for both sexes in the Weibull distribution with the extraction of the lambda and rho value from that model and predicting the survival for females.

Afterward, I committed 3 plots with an examination of qqplots from 3 kinds of distributions (Weibull, Exponential and LogNormal), additionally, I counted the estimator AIC for each of those distributions.

Finally, I checked the Cox proportional hazards model and observed which of the variables had the biggest influence on the status of the patient.
