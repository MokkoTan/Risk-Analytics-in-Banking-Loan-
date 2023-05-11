# Risk Analytics in Banking
 _To Ensure The Consumers Capable of Repaying The Loan are Not Rejected_

![Data Banner](https://imgur.com/S49wEcv.jpg)

##### Data source from _Kaggle.com_ 
.

>
>Kaggle is an online community platform for data scientists and machine learning enthusiasts. Kaggle allows users to collaborate with other users, find and publish datasets, use GPU integrated notebooks, and compete with other data scientists to solve data science challenges.

.
#### Data Origin
Source Name:		Risk Analytics in Banking
Format:		‘CSV’
File Name:	 application_data.csv | previous_application.csv
Records:	 456255
.


[![N|Solid](https://imgur.com/i7f3esp.png)](https://www.kaggle.com/datasets/stephenpolozoff/top-beer-information?select=beer_data_set.csv)  

## Context
### Business Understanding
The loan providing companies find it hard to give loans to the people due to their insufficient or non-existent credit history. Because of that, some consumers use it as their advantage by becoming a defaulter. 

When the company receives a loan application, the company has to decide for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.


## My Role and Objectives 

As a consumer finance company which specialises in lending various types of loans to urban customers. I have to use EDA to analyse the patterns present in the data. This will ensure that the applicants are capable of repaying the loans are not rejected.

#### Use data analysis skill to find out :
 - Total number of Transactor vs Defaulter
-  Analyse Defaulter data patterns
-  How does Previous Application affect Current Application
-  Suggest methods to improve/ reduce the number of Defaulter

## Techniques used in this study

- Import Data
- Remove Column
- Alter Column Name
- Alter Column Data Type
- Create Table
- Merge Table

### Overview
![Dashboard Design](https://imgur.com/lWF2tub.jpg)
### Loan Application
![Dashboard Design](https://imgur.com/PHNiIo8.jpg)
### Transactor
![Dashboard Design](https://imgur.com/cQZ28rD.jpg)
### Defaulter
![Dashboard Design](https://imgur.com/Racesk0.jpg)
### Realty Information
![Dashboard Design](https://imgur.com/cwP5ecx.jpg)
### Insights
![Dashboard Design](https://imgur.com/AIOEKKu.jpg)


- Age is the main factor to look into
- Occupation of the Applicant & their total income
- Number of family member
- Realty Ownership / Car Ownership
- Methods to prevent company from loosing money


.

[![N|Solid](data:image/png;base64,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)](https://www.linkedin.com/in/mokko-tan-3222b91b4/)  
