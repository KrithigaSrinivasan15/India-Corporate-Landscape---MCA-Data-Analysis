## India Corporate Landscape — MCA Data Analysis

> Analyzing 1.99 Million company records from India's Ministry of Corporate Affairs (MCA)



## What This Project Is About

This project explores India's complete company registration database to answer real business questions:

- Which states have the most registered companies?
- What % of companies are still active today?
- Which industries dominate India's business landscape?
- How has company registration grown since 1857?
- How much capital is authorized vs actually paid up?

---

## Tools Used


- Python (Pandas) - Cleaned raw data — handled nulls, fixed dates, standardized columns 
- PostgreSQL - Stored data, created 6 views to segment 1.99M rows by category 
- Power BI - Built 8-page interactive dashboard with DAX measures and slicers 

---

## Data Pipeline

Raw MCA Data (1.99 Million rows) → Python Cleaning → PostgreSQL 6 Views → Power BI 8 Page Dashboard

---

## Dashboard — 8 Pages

- Corporate India — Overview - 1.99M total companies, 60.99% active, Maharashtra as top state 
- Active vs Inactive — Company Status - 60.99% Active, 37.88% Inactive, 1.13% Unknown 
- State-Wise Company Registration - Maharashtra 395K, Delhi 348K, West Bengal 207K — Top 10 bar + all states treemap 
- Authorized vs Paidup Capital - Capital comparison by state — Maharashtra leads at 21.92T authorized cap 
- Business Scale Breakdown - 54.68% Small Scale, 31.72% Medium, 11.12% Large, rest Micro and Enterprise 
- Private vs Public vs OPC - Private Limited 18.19L, Public Limited 1.39L, OPC 30K, Foreign 2.1K 
- Sector-Wise Business Activity - Real Estate 6.79L (#1), Manufacturing 4.10L (#2), Wholesale 2.27L (#3) 
- Company Registration Trend - Growth from 1857 to 2020 — peak registrations in 2019 at 1.28 Lakh companies 

---

## Real Numbers from the Dashboard


- Total Companies Analyzed - 1.99 Million
- Active Companies - 60.99% 
- Inactive Companies - 37.88% 
- Top #1 State - Maharashtra (3.95 Lakh) 
- Top #2 State - Delhi (3.48 Lakh) 
- TOP #1 Business Sector - Real Estate (6.79 Lakh companies) 
- TOP #2 Business Sector - Manufacturing (4.10 Lakh companies) 
- Largest Company Class - Private Limited (18.19 Lakh) 
- Peak Registration Year - 2019 (1.28 Lakh companies) 
- Data Range - 1857 to 2020 
- Majority by Capital - Small Scale ₹1L–10L (54.68%) 

---

## PostgreSQL Views Created

- Company_status_vw - Companies grouped by Active, Inactive, Unknown 
- Company_state_wise_vw - Company count and totals per state 
- Industry_sector_vw - Company count per business sector 
- Capital_size_vw - Companies bucketed as Micro, Small, Medium, Large, Enterprise 
- Company_class_vw - Private, Public, OPC, Foreign, LLP breakdown 
- Registration_by_year_vw - Company count registered per year (1857–2020) 

---

## DAX Measures Written

- Active Rate % - % of companies currently active — 60.99% 
- Top State - State with highest registered companies — Maharashtra 
- Total Active Companies - Count of active companies only 

---

## Key Business Findings

- Maharashtra and Delhi together hold 37% of all registered companies in India
- Real Estate is #1 sector with 6.79 lakh companies — nearly double Manufacturing
- 54.68% of companies are Small Scale (₹1L–10L capital) — confirms India's MSME-dominated economy
- Nearly 38% of companies are inactive — 1 in 3 registered companies is no longer operating
- Company registrations grew 163x in 70 years — from around 780 in 1950 to 1.28 lakh in 2019
- Private Limited dominates at 91% of all company classes

---

## Corporate India Overview:

## <img width="950" height="543" alt="Corporate India Overview" src="https://github.com/user-attachments/assets/84433e7f-7a5f-46c6-a3cb-68e44c0c0529" />


## Company Status Analysis:

 ## <img width="947" height="543" alt="Company Status Analysis" src="https://github.com/user-attachments/assets/599d1ee7-cf5e-41cf-95bf-ae635631c059" />

## State Wise Company Registration:

 ## <img width="952" height="542" alt="State Wise Company Registration" src="https://github.com/user-attachments/assets/78c86691-6c3e-4023-a0d7-912e77433b79" />

## Capital Contibution Analysis: 

 ## <img width="952" height="541" alt="Capital Contribution Analysis" src="https://github.com/user-attachments/assets/5b9c6601-6a9d-45ba-a2b6-4382953c3350" />

## Business Scale Breakdown: 

 ## <img width="950" height="543" alt="Business Scale Breakdown" src="https://github.com/user-attachments/assets/7e9f1aa4-e620-478b-8ebc-31bae06c5263" />

## Company Class Distribution: 

 ## <img width="947" height="537" alt="Company Class Distribution" src="https://github.com/user-attachments/assets/01b37d75-8b00-4ea7-9c18-77e2214fd01c" />

## Sector Wise Business Activity:

 ## <img width="953" height="540" alt="Sector Wise Business Activity" src="https://github.com/user-attachments/assets/d5891185-999f-417e-a09e-864436fbf232" />

## Company Registration Trend: 
 
 ## <img width="954" height="542" alt="Company Registration Trend" src="https://github.com/user-attachments/assets/6a1d87a7-86a5-4484-8a61-c9dd39033787" />


## [MCA PROJECT.ipynb](https://github.com/user-attachments/files/28192599/MCA.PROJECT.ipynb)

## [MCA PROJECT.sql](https://github.com/user-attachments/files/28196111/MCA.PROJECT.sql)



 
## About Me

I come from a Business Advisory background and am moving into Data Analytics.
This project shows I can handle real-world data end to end — clean it, store it, segment it, and find insights that actually mean something to a business.



- LinkedIn: [www.linkedin.com/in/krithiga-srinivasan-716401347]
- Email: [krithigasrinivasan@yahoo.com]
  

---
