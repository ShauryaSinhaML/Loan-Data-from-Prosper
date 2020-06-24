# Loan Data from Prosper
## by Shaurya


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.
> - This data dictionary explains the variables in the data set.
> - You are not expected to explore all of the variables in the dataset! Focus your exploration on about 10-15 of them.

## Imports

- numpy
- pandas
- matplotlib
- seaborn

## Summary of Findings

# Observations:
> - Forr all the loans in genral Most of the people have completed their payment fo the loan however a significant proportion still is defaulted or is past due by 1-120 days
> - However in the case of Elite Loans(loans>10000) the completion rate is very low as compared to all the loans in genral
> - we see that most of the loans given out were to cover off other debts i.e. Debt Consolidation in both the cases Normal loans in. genal and Elite Loans(loan>10000)
> - Least loans were given to boats , green Loans and RV in case of genral Loans
> - While in case of Elite Loans the least no of loans were given to Student Use , Rv and Cosmetic Procedure
> - On an Average most no of Loans were taken by Computer Programmers followed by Executive and then teacher 
> - While in the case of Elite Loans (loans >10000) most loans were taken by Executive Followed by computer programmer and then analyst
> - On an Average least no of Loans were taken by Police Officer , civil Servise ,  Engineer mechanical
> - While in the case of Elite Loans (loans >10000) least loans were taken by truck driver , sales-retail , Engineer-Electrical
> - in case of all the loans taken into acount people with credit grade of **C , D , B** were gven more preference while people with credit grade of **NC** were less
> - while in case of Elite loans(loans>10000) loans people with credit grade of **B , AA , A** were gven more preference while people with credit grade of **HR** were less
> - People who were **employed** were given more preference both in normal and Elite loans(loans>10000) while they also are the once to ask for loans the most
> - most of the loans issued was between 1000-7000 range
> - We see that most of the people considering all the loans have their Prosper Score between 4-9
> - while those who recieved Elite Loans(loan>10000) has their Prosper Score between 6-9
> - BorrowerAPR BorrowerRate are linearly related
> - In the case of normal ie all the loans in genral 36 monts term has usally the highest borrow rate 
> - While in the case of elite loans(loan>10000) 60 months term had usually the highest borrow rate
> - with the increase of term usually the borrow rate can be expected to rise
> - with the increse in prosper score loan amount also increased drastially
> - having **credit score >729.5 and grade  AA , A , B, D , C** will ensure higher chances to get an Elite Loan(loan>10000)
> - people with higher credit score usually have lower borrowAPR and vice versa
> - people with Lower Prosper Rating usually have Higher borrowAPR and vice versa
> - Lender Yield is directly proportional to borrowAPR , Borrow Rate and Estimated Effective Yield
> - Similarly many other findings are seen from the above scatter matrix
> - Borrow rates for all the loan statuses were lower for elite loans(loan>10000) compared to the average of all the loans
> - elite loans tend to have terms 36 or 60 while on an average most loans have terms between 12-36
> - similarly for Prosper Ratings elite loans have prosper ratings > 4
> - elite loans have no cancellations and less delayed on an average
> - on an average the Loan amount for debt consolidation was th highest and lowest for student use


## Key Insights for Presentation

> - Having **credit score >729.5 , grade  AA , A , B, D , C and Prosper Score in between (6-9)** and having a job of **Executive Followed by computer programmer** demanding a loan for **Debt Consolidation** will ensure higher chances to get an Elite Loan(loan>10000).
> - Lender Yield is directly proportional to borrowAPR , Borrow Rate and Estimated Effective Yield
