# Project-1-Sales-Insight-Analytics
Cleansing and presenting basic transactional data to produce sales insights using MySQL &amp; Tableau

## Code and Resources Used
MySQL Version: 8.0.22 build 107609 CE (64 bits)  
Tableau Desktop Version: 2020.3.2 (20203.20.1018.2303) 64-bit

## Data Cleansing and Transformation

Cleanse Product_type, some records were 'Own Brand\n' or 'Own Brand/r' for both Own Brand and Distribution product types
- e.g 'update products_complete    
set product_type = 'Own Brand'  
where product_type = 'Own Brand\n';

Add in Margin field in products table
- '

Added in a random margin between -0.02 & 0.05, for the sake of trending profitability
- 'update products_complete SET products_complete.margin 
= rand()*(0.5--0.02)+-0.02 where Margin IS Null'

## Insights Highlights
- Sales volume and profit trending down in all regions, following 2018 peak

![](Images/Sales%20Insights%20Dashboard.png)
![](Images/Bottom%20Markets%20Table.png)
![](Images/Profit%20by%20C%20Type.png)
![](Images/Region%20Trends.png)

## Potential Next Steps
- Source customer data from CRM system to carry out segmentation and develop sales strategy
- Investigate the viability of markets in the South, particularly Southampton & Bristol
