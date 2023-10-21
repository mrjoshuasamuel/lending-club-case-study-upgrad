# Loan Approval Analysis - UpGrad IIIT-B Assignment

## Introduction
This assignment focuses on analyzing loan data to determine significant factors that influence loan approval. Various visualizations and statistical methods were employed to gain insights into the data.

## Data Description

### Source
Data was obtained from the Lending Club. It contains multiple columns that describe different aspects of the loan and borrower.

### Key Columns
- Loan Amount (`loan_amnt`)
- Annual Income (`annual_inc`)
- Debt-to-Income Ratio (`dti`)
- Accounts Opened (`open_acc`)
- Public Records (`pub_rec`)
- Revolving Balance (`revol_bal`)
- Total Payment (`total_pymnt`)

## Visual Analysis

1. A series of histograms were created to visually examine the distribution of various columns in the dataset. These histograms revealed trends and distributions in the data.
2. A correlation matrix was generated to understand the interrelation between different columns. The heatmap visualization helped in identifying variables that are closely related to each other.

## Key Insights

From the analyzed data, the following key insights were derived:

1. The average loan amount issued is about $11,219.
2. Borrowers have an average annual income of approximately $68,968.93.
3. The average debt-to-income ratio is 13.32.
4. Borrowers have an average of 9.29 open accounts.
5. The average revolving balance is $13,382.53, with most borrowers having balances of $8,850 or less.
6. Most borrowers have no public records.

## Business Implications

1. There's a noticeable relationship between a borrower's income and loan amount, which can influence loan approval.
2. A higher number of open accounts could indicate that a borrower is credit active, but it could also signal potential over-leverage.
3. Debt-to-Income ratio is an essential metric as it gives an idea of a borrower's capacity to manage more debt.
4. Public records can be considered red flags; however, most borrowers in the dataset don't have any.
5. The correlation between `total_pymnt` and `loan_amnt` implies that larger loans generally have larger total payments.

## Python Implementation

To visually represent the correlation between columns, a heatmap using the Seaborn library was generated. This heatmap allowed for an easier interpretation of how different variables relate to each other in the context of loan approval.

## Conclusion

The analysis provided insights into the key factors that influence loan approval. This understanding will enable businesses to make informed decisions when assessing the creditworthiness of borrowers.# lending-club-case-study-upgrad
