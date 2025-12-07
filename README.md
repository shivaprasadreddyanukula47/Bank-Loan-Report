# Bank Loan Analysis Report (Power BI + SQL)
# Project Objective
The objective of this Bank Loan Report Dashboard is to analyze loan applications, funded amounts,repayments,and borrower risk by leveraging SQL for data preparation and Power BI for interactive visualization.The dashboard helps financial teams monitor good vs. bad loan distribution, track month-to-month performance,understand borrower profiles,and identify key factors influencing loan outcomes.This enables data-driven decision-making to improve loan approval strategies,reduce defaults,and enhance portfolio performance.
## Data used
 <a href ="https://github.com/shivaprasadreddyanukula47/Bank-Loan-Report/blob/main/bank%20loan%20data.csv">Loan data</a>

# Queries Dataset
<a href="https://github.com/shivaprasadreddyanukula47/Bank-Loan-Report/blob/main/bank%20loan%20sql.pdf">queries</a>
## Questions (KPIs / Insights)
How many total loan applications were received?

What is the total funded amount and total amount received?

What percentage of loans are good vs. bad?

How do loan applications and funded amounts trend month-to-month?

Which loan purposes contribute the highest volumes and amounts?

How does loan performance differ by employee length, grade, and home ownership?

Which states show higher risk or higher loan activity?

What is the average interest rate and average DTI across borrowers?

What is the distribution of loans by term (36 vs 60 months)?

Which loan statuses (Fully Paid, Charged Off, Current) dominate the portfolio?
# SQL SUMMARY INSIGHTS
<img width="828" height="687" alt="Screenshot 2025-12-07 095801" src="https://github.com/user-attachments/assets/1e325fd6-4c3b-48ea-a001-96671611de9b" />
<img width="903" height="596" alt="Screenshot 2025-12-07 095823" src="https://github.com/user-attachments/assets/4d6caf11-85a7-4f88-b141-409e24cb3eb4" />
<img width="963" height="644" alt="Screenshot 2025-12-07 095850" src="https://github.com/user-attachments/assets/23f95a02-527e-498b-9f23-8625a15d740e" />
<img width="647" height="622" alt="Screenshot 2025-12-07 100517" src="https://github.com/user-attachments/assets/11aa3ed0-2501-481a-9d45-428ef4f15a74" />
<img width="813" height="788" alt="Screenshot 2025-12-07 100550" src="https://github.com/user-attachments/assets/6e965bf2-6abd-4792-a664-78307f0640ca" />
<img width="817" height="717" alt="Screenshot 2025-12-07 100606" src="https://github.com/user-attachments/assets/75cfcc7c-5dd9-43dc-8b42-e45906ecd091" />
<img width="813" height="397" alt="Screenshot 2025-12-07 100623" src="https://github.com/user-attachments/assets/102ab2de-827d-4d8e-8143-f77894f01de6" />

# POWER BI SUMMARY  DASHBOARD
<img width="1433" height="805" alt="Dashboard 1" src="https://github.com/user-attachments/assets/f26515ed-c4aa-4906-ad96-0bd177364a1e" />

# SQL OVERVIEW INSIGHTS
<img width="842" height="576" alt="Screenshot 2025-12-07 101118" src="https://github.com/user-attachments/assets/daa6e615-bb03-4990-853f-e745ef5169aa" />
<img width="461" height="207" alt="Screenshot 2025-12-07 101132" src="https://github.com/user-attachments/assets/b1cad711-1f47-49c6-97a4-9ac9e4adaa51" />
<img width="712" height="676" alt="Screenshot 2025-12-07 101149" src="https://github.com/user-attachments/assets/b5619e4b-d3c4-45dd-8710-e7089a1316ee" />
<img width="773" height="322" alt="Screenshot 2025-12-07 101201" src="https://github.com/user-attachments/assets/bf30bad8-48cf-4ddc-96ca-dddcc7ae8659" />
<img width="806" height="518" alt="Screenshot 2025-12-07 101220" src="https://github.com/user-attachments/assets/0c632336-5342-43bc-88b2-c12953fff4f9" />
<img width="678" height="539" alt="Screenshot 2025-12-07 101234" src="https://github.com/user-attachments/assets/19d8ca13-9605-497a-93cc-6e101e794595" />

# POWER BI OVERVIEW DASHBORAD
<img width="1432" height="803" alt="Dashboard 2" src="https://github.com/user-attachments/assets/7d65c7e5-e4fd-49ed-91ea-3fc4e6fff7b9" />

# POWER BI DETAILS
<img width="1430" height="807" alt="Dashboard 3" src="https://github.com/user-attachments/assets/7bab56f2-2bd8-406a-b331-3fbd9d3295db" />

<img width="1430" height="807" alt="Dashboard 3" src="https://github.com/user-attachments/assets/4891e537-cdc5-4a44-b7b4-9adcf569f4c2" />

# Process
1. Data Extraction(SQL)

Collected raw loan data from SQL database tables.
Queried loan applications,funded amounts,repayments,terms,and borrower details.
Performed initial cleaning using SQL(removing nulls,standardizing formats,filtering invalid records).

2. Data Cleaning & Transformation
Cleaned categorical fields (purpose,home ownership,loan grade).
Converted date fields (issue_date) into Year,Month,and MTD/MOM metrics.
Created calculated fields for:

Good vs Bad Loan

Loan Status

Total Funded & Received Amounts

Interest Rate & DTI categories

Data Modeling

3.Imported SQL tables into Power BI.
Built relationships between loan,customer,and status data.
Defined DAX measures for KPIs:

Total Loan Applications

Total Funded Amount

Total Received Amount

MTD & MOM calculations

Average Interest Rate & DTI

4.Dashboard Design

Built three pages: Summary,Overview,Details.

Applied consistent color themes and layout.

Ensured drill-down filters and interactive visuals.

Optimized for readability and decision-making.

5.Insight Generation

Identified trends in applications,funding,risk levels,and borrower demographics.

Highlighted high-risk categories(term, grade, loan purpose).

Summarized key findings for business decisions.
# FINAL SUMMARY
This project delivers a clear analysis of loan applications,funding,repayments,and borrower risk using SQL and Power BI.The dashboard highlights key KPIs,trends,and loan performance insights,helping identify good vs bad loans and supporting better financial decision-making.
## 👨‍💻 Developed By
### **Shiva Prasad Reddy Anukula**

















