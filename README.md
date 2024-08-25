# Problem statement
Loan providers often face challenges in granting loans to individuals with insufficient or non-existent credit histories. This lack of history can sometimes be exploited by consumers who default on their loans. For a consumer finance company, specializing in offering various types of loans to urban customers, we need to use exploratory data analysis (EDA) to identify patterns within the data that can help ensure that applicants who are capable of repaying their loans are not wrongly rejected.

When the company receives a loan application, it must make a decision based on the applicant’s profile. There are two key risks associated with this decision:

If the applicant is likely to repay the loan, rejecting the application results in a lost business opportunity for the company.
If the applicant is likely to default, approving the loan could lead to financial loss.
The dataset provided contains information about loan applications at the time of application. It reflects two scenarios:

Clients with payment difficulties: These clients had late payments of more than X days on at least one of the first Y installments in our sample.
Other cases: All other instances where payments were made on time.

When a client applies for a loan, four potential outcomes can occur:

**Approved:** The loan application is approved by the company.
**Cancelled:** The client cancels the application during the approval process, either due to a change of mind or unfavorable loan terms.
**Refused:** The company rejects the loan application because the client does not meet the required criteria.
**Unused Offer:** The client cancels the loan at various stages of the process.
In this case study, EDA will be used to understand how consumer and loan attributes influence the likelihood of default.

# Business Objectives
The primary goal of this case study is to identify patterns that signal a client's potential difficulty in repaying installments. These insights can be used to take actions such as denying the loan, reducing the loan amount, or offering loans to high-risk applicants at higher interest rates. This analysis will help ensure that only those capable of repaying the loan are approved.

The aim is to identify the key factors, i.e., driver variables, behind loan defaults. Understanding these variables will aid the company in portfolio and risk assessment.
