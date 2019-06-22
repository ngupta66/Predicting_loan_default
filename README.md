# predicting_loan_default

The Lending Club is the world's largest peer-to-peer lending platform. Lending Club enables borrowers to create unsecured personal loans between $1,000 and $40,000. The standard loan period is three years. Lending Club enables borrowers to create loan listings on its website by supplying details about themselves and the loans that they would like to request. On the basis of the borrower’s credit score, credit history, desired loan amount and the borrower’s debt-to-income ratio, Lending Club determines whether the borrower is credit worthy and assigns to its approved loans a credit grade that determines payable interest rate and fees. The standard loan period is three years; a five-year period is available at a higher interest rate and additional fees. The loans can be repaid at any time without penalty.
Investors make money from interest. Rates vary from 6.03% to 26.06%, depending on the credit grade assigned to the loan request. Lending Club makes money by charging borrowers an origination fee and investors a service fee. The size of the origination fee depends on the credit grade and ranges to be 1.1%-5.0% of the loan amount. The size of the service fee is 1% on all amounts the borrower pays.
Loan delinquency is a failure to make loan payments when they are due. Extended delinquency can result in loan default. A lender may take legal action to get the money back. Load default has several adverse effects.
To reduce loan default risk, Lending Club focuses on high-credit-worthy borrowers, declining the loan applications, assigning higher interest rates to riskier borrowers within its credit criteria. Only borrowers with FICO score of 660 or higher can be approved for loans. The statistics on Lending Club's website state that, as of December 31, 2016, 62.3 percent of borrowers report using their loans to refinance other loans or pay credit card debt.

### Data Set Used
The Dataset used in this project is The Lending Club dataset available from kaggel website. (https://www.kaggle.com/wordsforthewise/lending-club/home). It is a real world data set which contains 2004126 rows of loan listing and 150 columns (attributes) of the each loan listing from year 2007 to 2018 Q2. Out of 150 columns, some columns have missing data and some columns are not needed for the analysis.  After applying several data wrangling method, data set contains 2004095 rows and 83 columns. 4 columns are of data type category, 4 columns are of data type datetime64, 66 are of data type float64, and 9 are of data type object.

