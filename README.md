# Project Name
> Lending Club Case Study


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Background - 
  - A Consumer Finance Company specializes in lending various types of loan to urban customers. 
  - Company decides on loan approval based on customers profile 
  - __2 Major risks__ associated with approval decision:
    - *Loss of Business*: Loan approved when Customer is likely to repay loan. 
    - *Financial Loss*: Loan approved when Customer is not likely to repay loan i.e. likely to default 
  - __Loan Accepted__ - 3 Scenarios occur :
    - *Fully Paid*: Principal and Interest Repaid. 
    - *Current*: Ongoing Loan and Customer paying instalments. Loan Tenure not completed.
    - *Charged-off*: Instalments not paid in due time for a long time i.e. Customer Defaulted on Loan. 
  - __Loan Rejected__ - No transactional history present & hence, data not available with the Company/in the used dataset. This category has no impact on the assessment of bad loans because there is no transaction history present.
- __Business Problem__ - Identify & Understand the Driving Factors/Variables which are strong indicator of Loan Default to reduce the Bad Loans.
- __For Dataset__, we are using a CSV file stored in the root folder i.e. same folder as readme file.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Term –> Shorter loan tenures are at a higher risk of defaulting
- Grade –> Lending Club should provide more Grade A loans. G Grade loans are risk and have ~50% default rate.
- Purpose –> debt consolidation has the biggest charged_off rate
- Annual Income Classification –> Explains which income group consumer can have more loan default
- Loan Amount –> Explains that medium loan amount usually has a higher loan default rate.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - v3.9.0
- Seaborn - v0.12.2
- pandas - v2.0.1
- numpy - v1.24.3

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by *Lending Club Case Study* provided by UpGrad PG course for AI/ML
- This project was based on [Lending Club](https://www.lendingclub.com/).


## Contact
Created by [@sophophilic] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->