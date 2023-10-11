# LendingClub Case Study
> LendingClub is a financial services company headquartered in San Francisco, California. It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission, and to offer loan trading on a secondary market. so When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Research Flow](#research-flow)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Project Background
  - LendingClub is a financial services company headquartered in San Francisco, California. It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission, and to offer loan trading on a secondary market. so When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.    
- Business Problem
  - In this case study, we used EDA to understand how consumer attributes and loan attributes influence the tendency of default.
    - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
    - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.
- Dataset used
  - Firm's proprietary lending record ranging from 2007-2011

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Research Flow
- Data understanding and manipulation
  - Deletion of Null valued columns
  - Deletion of Single Valued columns
  - Appropriate feature selection after deeletion of unnecessary columns
  - Identification of missing values
  - Appropriate treatement of missing values
- Standardization of columns
- Outlier Identification and their treatment
- Analysis
  - Univariate Analysis
    - Univariate analysis of some categorical columns
    - Corelation finding between Numeric columns
    - Categorization of some Numeric columns (Binning method)
    - Deriving some required features from the given features
  - Multivariate Analysis

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Numpy - version 1.23.5
- Pandas - version 1.5.3
- Matplotlib - version 3.7.1
- Seaborn - version 0.12.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by UpGrad and IIIT Banglore


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
