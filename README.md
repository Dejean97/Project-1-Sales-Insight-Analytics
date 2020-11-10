# Project-1-Sales-Insight-Analytics
Cleansing and presenting basic transactional data to produce sales insights using MySQL &amp; Tableau

## Code and Resources Used
MySQL Version: 8.0.22 build 107609 CE (64 bits)  
Tableau Desktop Version: 2020.3.2 (20203.20.1018.2303) 64-bit

## Data Cleansing and Manipulation

 update products
SET products.Margin = rand()*(0.5--0.5)+-0.5
where Margin IS Null
