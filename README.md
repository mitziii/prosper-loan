# prosper-loan
Udacity project Data communication

## Project Table of Contents :

  * Introduction of the topic and dataset
  
  * Dataset Investigation and preliminary wrangling
  
  * Univariate Exploration
  
  * Bivariate Exploration
  
  * Multivariate Exploration 
    
## Why this project?

* Data visualization is an important skill that is used in many parts of the data analysis process. 

* Exploratory data visualization generally occurs during and after the data wrangling process, and is the main method that you will use to understand the patterns and relationships present in your data. This understanding will help you approach any statistical analyses and will help you build conclusions and findings. This process might also illuminate additional data cleaning tasks to be performed. 

* Explanatory data visualization techniques are used after generating your findings, and are used to help communicate your results to others. Understanding design considerations will make sure that your message is clear and effective. In addition to being a good producer of visualizations, going through this project will also help you be a good consumer of visualizations that are presented to you by others.

## What will I learn?

* Supplement statistics with visualizations to build understanding of data.
  
* Choose appropriate plots, limits, transformations, and aesthetics to explore a dataset, allowing you to understand distributions of variables and relationships between features.
  
* Use design principles to create effective visualizations for communicating findings to an audience.

## Dataset

Loan Data from Prosper with Prosper Data Dictionary to Explain Dataset's Variables

The Dataset is taken from Prosper data, which originally contains 113,917 entries. For each entry, the data represent the infomation about borrower's Annual Percentage Rate (APR) for the loan, status, the amount, rate. Moreover, the data also allows us to know about prosper rating and score of the borrowers, as well as their occupation, ownership of a house, income range, etc.

## Questions

> The most popular characteristics of borrowers

> The characteristics of loans

> How to get a loan at lower rate, at first attempts, with a higher amount

> How loans are prefered by lenders
 
## Findings

> Several characteristics of borrowers which are most frequent are:

    Employment status: The employed are more likely to have the loan than the unemployed.

    Income: Higher income tends to facilitate the funding of borrowers.

    Home Ownership: Owning a house or having a mortgage can help a borrower to get the fund.

    Good Prosper score and Prosper rating: a good rated borrower is more likely to be funded.


> The characteristics of loans:

    Reasons for funding: Debt consolidation, Home improvement, Business, Auto.

    Most of the estimated return fall between 7.5% to 11.5%. There are many popular estimated return rates. There are also negative estimated returns (from -18% to below 0%). The reason may be these loans have estimated yield lower than the estimated principal loss on charge-offs.

    Many frequent loan amounts. There are very few loans with the amount from 20000USD to 35000USD, and the most of the loans are from 0 to 15000.

    The most popular borrower APR are 0.35797% with 43% of the loans and 0.35643% with 19%.


> How to get a loan at lower rate, at first attempts, with a higher amount

- For the borrowers with higher income and higher prosper score, the amount of loan tends to be higher. The borrowers with lower income tend to have lower Prosper score and lower amount of loan. It can be explained that the borrowers with higher income tend to have higher financial stability and the ability to pay back the loan, hence they receive higher trust and credit rating from the lenders. Hence, they can get the larger amount of loan. If Prosper score is high and the income range is high, the borrowers tend to gain the funding from his first attempt. 

- However, if the income is high but the prosper score is low, the borrowers still have to attempt many times to get the loan. In other words, the prosper score has higher impacts than income range of the borrowers in terms of whether the borrowers can get the funding. Ffor borrowers with higher credit score, the borrower APR is lower. Similarly, for borrowers with better Prosper Score, the APR is lower. It confirms the point that credit score and prosper score are negatively correlated to Borrower APR. It can be explained that the borrowers with higher income tend to have higher financial stability and the ability to pay back the loan, hence they receive higher trust and credit rating from the lenders. Hence, they can have higher score and get the loans at lower APR. 

> How loans are prefered by lenders

- For the loans with better prosper score, the lenders receive lower estimated return. The loans with better prosper score are more reliable and credit worthy, thus the lenders have lower levels of risk, and low risk is associated with low return. On the other hand, the loans with lower score are riskier, and the lenders receive higher return to trade off for the risks they have to bear. Therefore, the lenders may prefer low score loans since it can bring back more returns. 

- However, those loans with low score are associated with too many fluctuation of estimated return. Although lower prosper score loans can bring back to lenders higher estimated return, they also have the most tremendous variability and instability. For instance, for the loan with prosper score of 1, the estimated return varies from -20% to 20%, a very large volatility. This volatility is smaller when the prosper score goes up. For the loans with score of 11, the fluctuation is very small and the range of estimated return is very small and always positive. It infers that the lenders have to bear very low risk of not getting return. Thus, the lenders need to analyse carefully to find out the balance between risk and return.


