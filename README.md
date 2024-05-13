# Project Name
> Lending Club case study to identify prediction parameters for defaulters of a loan.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A consumer finance company which specializes in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
I have used the data set provided by Lending Club module laon.csv

-
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
The following parameters that could enable bank to look to avoid the risk of having more deaulters
1. For higher loan amount the term is 36 months and loan amount <= 10000 the term is 60 months which is odd. Also employees with less emp_length have taken higher loan amount which they might end up In becoming a defaulter
2. Employees with Grade B & A are highest loan seekers and there are more outliers in Grade A 
3. People with Subgrades A4, B3 ,B4,  B5 have taken loans 
4. The main purpose is for paying Rent or Mortgage which could be cause for becoming defaulters
5. The major purpose for loan request is debt_consolidation - which means this loan is taken to repay another loan. This parameter should be considered by bank before providing loan 
6. More number of people from CA has taken followed by NY. This is a key parameter to analyse and who has not repayed 
7. For Source Not Verified the loan amount median is around 7000 and interest rate also seems to be less compared to other sources


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was done using EDA sample .
- References for data cleanup and visualization used google support...


## Contact
Created by [@githubusername] - @vimalasuchi


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
