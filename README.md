# Zoom-Style-Subscription-Revenue-Dashboard

## Project Overview
This Power Bi Project simulates subscription revenue analysis for SAAS business model inspired by platform like Zoom. It focuses on Key financial KPIs such as Monthly Recurring Revenue(MRR), Churn, Lifetime Value(LTV) and Gross Margin- designed for Finance team.

## Objectives
 Analyze Monthly Recurring Revenue(MRR),
 Annual Recurring Revenue (ARR),
 Customer CHurn and LTV,
 Track active and cancelled subscriptions over time,
 Identify trends and revenue movements by plan type, country and customer type,
 Provide actionable insights for retention and revenue growth.

## Data Source
 Data for this project is organised as follows:

### csv files (Static Dimension data)
1. **Customers.csv**
   - Location    : './DATA/Customers_Finance.csv'
   - Description : Contains Customer master data.
   - Key Columns :
        - 'CustomerID' (primary Key)
        - 'JoinDate'
        - 'Region'
        - 'Gender'
        - 'AgeGroup'
2. **Plans.csv**
   - Location    : ''./DATA/Plans_Finance.csv'
   - Description : Contains subscription plan metadata.
   - Key Columns :
        - 'PlanID'
        - 'PlanName'
        - 'PricePerMonth'
        - 'CostPerMonth'

 ### SQL Server table (Trandactional Subscription data )
  3. **Subscriptions**
     - Server      : LAPTOP-4B9640PB\MSSQLSERVER02
     - Database    : Subscriptions_Analysis
     - Table       : 'finance.Subscriptions'
     - Description :  Contains all subscription records.
     - Row count   : ~60000
     - Key Columns :
         - 'Subscriptiom id'
         - 'CustomerID'
         - 'PlanID'
         - 'StartDate'
         - 'EndDate'
         - 'Status'
         - 'PaymentMethod'
         - 'Discount'
         - 'Currency'
         - 'InvoiceAmount'
    
     

