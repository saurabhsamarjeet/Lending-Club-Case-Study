# Lending Club Case Study
Lending Club, a consumer finance marketplace focused on providing various loans to urban customers, faces a significant challenge in managing its loan approval process. The company needs to make informed decisions to reduce financial losses, particularly from loans granted to "risky" applicants.

These financial losses, known as credit losses, occur when borrowers default on their loans or fail to repay them. In other words, borrowers classified as "charged-off" contribute to the most substantial losses for the company.

The primary goal of this exercise is to help Lending Club minimize credit losses, which stem from two key scenarios:

1. Identifying applicants who are likely to repay their loans is essential for generating profits through interest payments. Failing to approve loans for these applicants could result in lost business opportunities.
   
2. Conversely, approving loans for applicants who are unlikely to repay and are at risk of defaulting can result in significant financial losses for the company.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The goal is to identify applicants who are at risk of defaulting on loans, thereby helping to reduce credit losses. This case study seeks to achieve this through exploratory data analysis (EDA) using the given dataset.

The company aims to understand the key factors that drive loan defaults, identifying the variables that strongly indicate a likelihood of default. This insight can be used to enhance the company's portfolio and risk assessment strategies.

The main objective of this exercise is to help Lending Club minimize credit losses. This challenge involves two critical scenarios:

1. Identifying applicants likely to repay their loans is essential because they generate profits for the company through interest payments. Failing to approve loans for such applicants could result in lost business opportunities.
   
2. Conversely, approving loans for applicants who are at risk of defaulting can lead to significant financial losses for the company.

## Conclusions
- Most of the borrowers taken loan amounts between 5500 - 15000, 99-95 percentile of loan amounts are below 30000
- Most of the Funded amount is in between 5500 - 15000, 99-95 percentile of Funded amounts is below 30000
- As loan rate increasing from 14.5 number of applications are decreasing.
- Most of the borrowers intrest rates are between 9.25 to 14.59
- Fully paid cutomers intrest rates are low with compare to defaulters.
- If intrest rate is high then there is probabilty of default loan
- Less salary borrowers are becoming defaulters and avg salary of charged off boorowes is less than fully paid borrowers




## Technologies Used

- [Python](https://www.python.org/) - version 3.11.7
- [Matplotlib](https://matplotlib.org/) - version 3.7
- [Numpy](https://numpy.org/) - version 1.24
- [Pandas](https://pandas.pydata.org/) - version 1.5
- [Seaborn](https://seaborn.pydata.org/) - version 0.12


## Acknowledgements
- This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.
- UpGrad tutorials on Exploratory Data Analysis (EDA) on the learning platform


## Contact
Created by  [@saurabhsamarjeet](https://github.com/saurabhsamarjeet) [@santhoshtalluri](https://github.com/santhoshtalluri)


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
