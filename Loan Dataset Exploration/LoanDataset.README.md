# Loan Dataset Exploration
## by Kingsley Ubani


## Dataset

> This document describes the Loan Data-Set from Prosper. It contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income and many others.

> The only issue I had with some columns were the data-types. So I eventually had to convert the data-types from objects to category to enable me understand the analysis on the distributions.

> Also,for the Loan Status I had to represent all Past Due entries( I mean all records containing Past Due periods) as just Past Due.



## Summary of Findings

> My major variable of interest is the Borrower's Rate. And from the visuals, it is clearly a multimodal distribution with the highest spike at 0.3177 interest rate. This means most borrowers prefer to borrow at 0.3177 interest rate, as it has the greatest number.

> Loan Status- Defaulted and Charged-off borrowers had higher interest. This is actually normal, as they have are defaulters.

> Employment Status- All borrowers within the employment status bucket are given reasonably higher interest rate, except for the borrowers whose employment status is Not-Available.

> Credit Grade- The borrowers with the higher interest rates in this category fall within D, E and HR Credit Grades.

> Verified borrowers were clearly given more loans and out of this number,majority of the loans were allocated to mostly borrowers with current and completed loan status.

> Employed borrowers were clearly given more loans and out of this number,majority of the loans were allocated to mostly borrowers with current and completed loan status.

> Borrowers willing to pay within 36 month term were give more loans and out of this number, majority of the loans were allocated to mostly borrowers with current and completed loan status.

> Borrowers that fall within the C credit-grade were give more loans and out of this number, majority of the loans were allocated to mostly borrowers with completed and charged-off loan status.

> Borrowers with income range between $25,000-74,999 were clearly given more loans and out of this number,majority of the loans were allocated to mostly borrowers with current and completed loan status.

> Borrowers that are home owners were clearly given more loans and out of this number,majority of the loans were allocated to mostly borrowers with current and completed loan status.

> 


## Key Insights for Presentation

> The following(not limited to this) factors determine the Loan outcome status of a borrower; CreditGrade, EmploymentStatus, Occupation, IsBorrowerHomeowner, IncomeRange, IncomeVerifiable, LoanOriginalAmount, Term, BorrowerRate.

> Also, the following(not limited to this) factors affect the interest rate of a borrower; CreditGrade, EmploymentStatus, Occupation, IsBorrowerHomeowner, IncomeRange, IncomeVerifiable, LoanOriginalAmount, Term, BorrowerRate.

> Finally, The loan original amount is way lesser for borrowers that don't own a house through out a term-period. This means there is a difference in loans depending on the loan original amount.