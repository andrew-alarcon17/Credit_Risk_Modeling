# Credit_Risk_Modeling

## About the Data

This data contains information about consumer loans in 2015 by a company called Lending Club. Features in this data include credit scores, number of finance inquiries, address including zip codes, and state, and many others. The file is a matrix of about 421 thousand observations and 74 variables.

## Project Summary

For this project, I will be exploring a dataset of debtors (borrowers) in order to try to compute three main components:

### A) Probability of Default
This estimates the likelihood that a borrower will be unable to meet its debt obligations. In the Monitoring notebook, the data is cleaned and preprocessed in order to create the PD Model.

### B) Loss Given Default
If a borrower defaults, LGD calculates the amount of money that is lost given by the creditor as a percentage of total exposure at the time of default.

### C) Exposure at Default
This is the total value a bank is exposed to when a loan defaults.

These models were created in order to predict their respective purposes for given borrowers in the year of 2015. These values were saved and then used in order to calculuate the total Expected Loss for the creditor.

## Conclusion

<img src="https://github.com/andrew-alarcon17/Credit_Risk_Modeling/blob/master/Visualizations/Expected%20Loss.png" width="700">

<img src="https://github.com/andrew-alarcon17/Credit_Risk_Modeling/blob/master/Visualizations/Total%20Values.png" width="700">
