# Loan Insights for EasyLoan  

## Project Overview  

EasyLoan is a financial services provider that offers a variety of loan products, including personal loans, car loans, and mortgages. Operating in Canada, the United Kingdom, and the United States, the company aims to gain insights into the performance of its loan services across different geographic regions. The analytics team seeks to identify areas of strength and weakness to better inform the business strategy team.  

## Objective  

The primary objective of this project is to ensure the reliability and accessibility of the loan data in the `lending` database to facilitate accurate reporting by the analytics team.  

## Database Schema  

The relevant data resides in a database named `lending`. The following components are critical for gathering insights:  

- **Loans Table**: Contains information on each loan issued, including types, amounts, and repayment statuses.  
- **Clients Table**: Stores details about the clients, including geographic location and demographic information.  
- **Payments Table**: Tracks payment history and any defaults associated with the loans.  
- **Interest Rates Table**: Provides current and historical interest rates for different loan types across various regions.  

### Example Schema Table Descriptions (Hypothetical)  

| Table Name         | Description                                                                        |  
|--------------------|------------------------------------------------------------------------------------|  
| `loans`            | Contains loan details including loan type, amount, duration, and status.          |  
| `clients`          | Holds client information such as name, address, country, and demographic details.  |  
| `payments`         | Records payment schedules, amounts paid, and overdue payments.                     |  
| `interest_rates`   | Displays interest rates applicable to different loan types and regions.           |  

## Methodology  

1. **Data Audit**: Conduct a thorough audit of the `lending` database to ensure data quality, integrity, and completeness.  
2. **Data Normalization**: Standardize data formats across different tables for consistency.  
3. **Accessibility Checks**: Ensure that the data is easily accessible for reporting purposes using appropriate SQL queries or business intelligence tools.  
4. **Data Documentation**: Create comprehensive documentation to guide the analytics team on how to use the data effectively.  
