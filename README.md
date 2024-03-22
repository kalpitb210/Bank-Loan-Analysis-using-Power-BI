# Bank-Loan-Data-Analysis
Bank loans are a crucial financial tool that enables individuals and businesses to achieve their goals and manage financial needs. However, it's essential for borrowers to understand the terms, costs, and responsibilities associated with loans to make informed financial decisions.

## Project Overview
- This project aims at analyzing the risk appetite of banks. When the bank receives a loan application, the bank must decide for loan approval based on the applicant’s profile, and nalyze the good loans, bad loans, bank amount funded, bank profit, bank loss, etc.
- Exploratory Data Analysis using Power BI was performed to draw insghts.

## Dataset Used
This project utilizes the dataset of U.S. bank loan data for the year 2021, with over 38500 loan applications data.

## Terminologies
- **Loan ID:** Loan ID is a unique identifier assigned to each loan application or loan account. It serves as a primary key for tracking and managing individual loans.
- **Address State:** Address State indicates the borrower's location.
- **Employee Length:** Employee Length provides insights into the borrower's employment stability. Longer employment durations may indicate greater job security.
- **Employee Title:** Employee Title specifies the borrower's occupation or job title. It helps lenders understand the source of the borrower's income.
- **Grade:** Grade represents a risk classification assigned to the loan based on creditworthiness. Higher grades signify lower risk.
- **Sub Grade:** Sub Grade refines the risk assessment within a grade, providing additional risk differentiation.
- **Home Ownership:** Home Ownership indicates the borrower's housing status.
- **Issue Date:** Issue Date marks the loan's origination date. It's crucial for loan tracking and maturity calculations.
- **Last Credit Pull Date:** Last Credit Pull Date records when the borrower's credit report was last accessed. It helps monitor creditworthiness.
- **Last Payment Date:** Last Payment Date marks the most recent loan payment received. It tracks the borrower's payment history.
- **Loan Status:** Loan Status indicates the current state of the loan (e.g., fully paid, current, default). It tracks loan performance.
- **Next Payment Date:** Next Payment Date estimates the date of the next loan payment. It assists in cash flow forecasting.
- **Purpose:** Purpose specifies the reason for the loan. It helps understand borrower intentions.
- **Term:** Term defines the duration of the loan in months.
- **Verification Status:** Verification Status indicates whether the borrower's financial information has been verified. It assesses data accuracy.
- **Annual Income:** Annual Income reflects the borrower's total yearly earnings. It assesses repayment capacity.
- **DTI (Debt-to-Income Ratio):** DTI measures the borrower's debt burden relative to income. It gauges the borrower's capacity to take on additional debt.
- **Instalment:** Instalment is the fixed monthly payment amount for loan repayment, including principal and interest.
- **Interest Rate:** Interest Rate represents the annual cost of borrowing expressed as a percentage.
- **Loan Amount:** Loan Amount is the total borrowed sum. It defines the principal amount.

## Explanation of Terms Used in the Report
- **MTD (Month-to-Date):** Refers to the cumulative total for the current month up to the current date.
- **MoM (Month-over-Month):** Represents the percentage or absolute change compared to the previous month.
- **Good Loan:** This category includes loans with a loan status of 'Fully Paid' and 'Current.
- **Bad Loan:** This category specifically includes loans with a loan status of 'Charged Off.

## Guide
In the ```summary``` dashboard, you can click on filters for Purpose, Grade, and State to explore bank loan data for the year 2021. This includes Total Loan Applications, Total Funded Amount, Total Amount Received, Average Interest Rate, Average Debt-to-Income Ratio (DTI), along with their monthly averages and monthly growth rates. Additionally, information on Good Loan Issued, Bad Loan Issued, and Loan Status is available.

![image](https://github.com/kalpitb210/bank-loan-data-analysis/assets/116106587/85130531-eda9-4458-ab3e-267312a7bba9)

--------------

In the ```overview``` dashboard, you can also click on filters for Purpose, Grade, and State to explore bank loan data for the year 2021. Additionally, you can explore a summary of monthly data, bank loan details for each state in the U.S., loan terms, borrower's years of employment, loan purposes, and the homeowner status of the borrower. When clicking on these diagrams, the data will interactively change across all diagrams and tables.

![image](https://github.com/kalpitb210/bank-loan-data-analysis/assets/116106587/42dfc0a3-085c-483f-abcb-0a1568cb309d)

------------------

In the ```details``` dashboard, you can also click on filters for Purpose, Grade, and State to explore bank loan data for the year 2021. In addition, you can click on the main table's headers to sort and filter, and you can scroll through the main table to view all the loan data records for the banks in 2021.

![image](https://github.com/kalpitb210/bank-loan-data-analysis/assets/116106587/e2a3877a-7508-4b47-8f55-ca94382fce94)
