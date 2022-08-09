# Project Name
> Lending Club Case Study


## Table of Contents
* [Problem Statement](#problem-statement)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Recommendations](#recommendations)
* [Acknowledgements](#acknowledgements)
* [Contacts](#contacts)


## Problem Statement
- Identification of risky loan applicants using EDA is the aim of this case study


## Technologies Used
- Language - Python 3
- library - Numpy
- library - Pandas
- library - matplotlib (version: '3.4.0')
- library - seaborn
- library - math


## Conclusions

- DTI:
Lower the DTI value, lower the chance of defaulting, Higher the value of DTI higher the chances of defaulting

- Loan Terms: 
Lower the loan terms lower the chances of loan amount being charged off
Higher the loan terms higher the chances of loan amount being charged off

5 years is a bigger term in comparison to 3 years, lot of factors change in these extra 2 years. Recession might come in, loss of job, annual income might come down, relocating to a higher cost of living city, increase in home rents, inflation, change in government, new regulations  are all possible reasons for increase in number of loan defaulter with higher loan terms

- Verification Status: 
The above chart clearly shows the members with verified sources are more likely to default in comparison to non-verified sources, which is really strange as the purpose of verification is to reduce the number of defaulters

- Interest Rates: 
The Lenders here are doing the correct thing by increasing the interest rates of risky loan requests in order to mitigate the risk of loan defaulting
Average interest rates for small business is around 13% and it has appeared loans for small business are at higher risks of defaulting

- Public Bankruptcies: 
People with 0 bankruptcies are lesser prone to loan defaulting than people with bankruptcies files.
This variable clearly indicates that in previous occasions the loan requestors have failed to pay back the entire money and filed bankruptcy to reduce or eliminate the prior debts
So, clearly they have failed before and are likely to fail again based on the prior history of loan payment

- Purpose: 
Smaller business seems to be having a higher risk of getting charged off in comparison to loans taken for personal purposes like wedding and car

Business related loans are always at higher risks as loan payments are often related to the profit made

- State Code, Zip Code & Cost of Living:
The first chart “ address state vs Charged off/Fully Paid ratio chart” has no trends as such

But, If we further drill down to Zip Codes, we can see the below trend
From the first chart let us consider Florida which is at higher risk of getting charged off
Then let us plot a ratio chart for all the zip codes in Florida.
Below is the observation:
322XX is Jacksonville FL, which is at a lower risk of defaulting
where as
331XX is Miami FL, which is at higher risk of defaulting
The cost of living in Miami, FL is 20.5% higher than in Jacksonville, FL Employers in Miami, FL typically pay 2.7% more than employers in Jacksonville, FL for the same type of job

HIGHER COST OF LIVING PLACES ARE MORE LIKELY TO BE DEFAULTERS

- Grades & Sub-Grades:
As we move from lower grade A to higher grade G, chances of defaulting increases
Similar trend is seen among sub grades within grades. Within a Grade, even if we move from 1 to 5 sub grade, the possibility of defaulting a loan is higher (in maximum case)

- Annual Income: 
Lower the Annual Income range, higher the chance of defaulting, Higher the Annual Income range, lower the chances of defaulting
Negative correlation detected

- Loan Amount:
Higher the fund amount higher is the risk of defaulting

## Acknowledgements
- This project is part of a case study from Upgrad for identification of risky loan applicants using EDA


## Contacts
- Created by [@debimahapatra]
- Created by [@saswatdash]
