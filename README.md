# Python_BankingSector_RiskAnalysis
This case study aims to identify patterns which indicate if a client has difficulty paying their installments which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. This will ensure that the consumers capable of repaying the loan are not rejected. Identification of such applicants using EDA is the aim of this case study.

Python Notebook Flow:
• Import required libraries such as pandas, numpy, matplotlib and seaborn
• Load application data and previous application data
• Verify application data columns for NULL values in columns
• If a column is having more than 40% null values, then drop that column
• For all other columns, updated NULL to Mode / Median of that column
• Plot various graphs for different columns
• Plot co-relation for different columns

Plot graphs for current application…
• % of defaulters Vs regular payer
• Age wise breakup of defaulters
• Loan type wise breakup in terms of defaulters and regular payer
• Gender wise breakup in terms of defaulters and regular payer
• Defaulters Vs regular payer having car and realty
• Employment /Occupation type wise breakup in terms of defaulters and regular payer
• Income wise breakup in terms of defaulters and regular payer
• Housing wise breakup in terms of defaulters and regular payer

Plot graphs for previous application…
• Loan type for previous loan applications
• Approval status for previous loan applications
• Rejection reason for previous loan applications
• Interest rate for previous loan applications
• Credit for previous loan applications
• Down payment for previous loan applications
• Number of days taken for decision for previous loan applications
• Payment type for previous loan applications
