# brazil-reimbursement
Data Analysys of Brazil's House of Deputies Reimbursements

# Introduction
The purpose of this data analysys is to get an insight on the money that Brazilian politicians spend on various categories. They are entitled to refunds if they spend any of their money on an activity for the goverment or the people. The data of it are public but there are less analysis on it. There are a lot of very suspicious data regarding the deputies expending behavior.

## Code and Resources Used 
**Python Version:** 3.7  
**Packages:** pandas, numpy, sklearn, matplotlib, seaborn
**Dataset:** https://www.kaggle.com/epattaro/brazils-house-of-deputies-reimbursements?select=deputies_dataset.csv

## Detailed Project Walk-Through


## Data Cleaning
First, I need to clean up the data before doing EDA. I made the following changes and created the following variables:
* Extract the year from receipt_date which have a datetime format and year only format.
* Extract the year from refund_date which has two different datetime format and missing value. Replacing the missing value with the year from the rows above the data.
* Replacing the missing value in political_party with the rows above the data.
* Replacing the missing value in party_nmembers based on their political_party, the one which don't have the political_party are being replace with the median value of the party_nmembers


## EDA


## Result




