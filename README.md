# Project1: Sales Insight Analytics
Cleansing and presenting basic transactional data to produce sales insights using MySQL &amp; Tableau

## Resources Used
MySQL Version: 8.0.22 build 107609 CE (64 bits)  
Tableau Desktop Version: 2020.3.2 (20203.20.1018.2303) 64-bit

## Data Cleaning

Replaced markets_name with UK city names   
Created exchange_rates table, USD & INR to GBP rates   
Created new_transactions with GBP currency and converted sales_amount   
Added missing product_code from new_transactions to products_complete   
Added margin field, with margin values between -0.02 and 0.5 to report profit trends



## Insights Highlights
- Sales volume and profit trending down in all regions, following 2018 peak

![](Images/Sales%20Insights%20Dashboard.png)
![](Images/Bottom%20Markets%20Table.png)
![](Images/Profit%20by%20C%20Type.png)
![](Images/Region%20Trends.png)

## Potential Next Steps
- Source customer data from CRM system to carry out segmentation and develop sales strategy
- Investigate the viability of markets in the South, particularly Southampton & Bristol
