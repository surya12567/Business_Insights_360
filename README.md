## Business_Insights_360


## Project Overview

AtliQ Hardware is growing rapidly in the recent years, and they have decided to implement the data analytics using PowerBi in their company for the first time to surpass their competitors in the market and to make data driven decisions. This project is hoped to give answers to the questions of stakeholder in terms all the aspects like finance, sales, marketing and supply chain.

## Problem Statement
AtliQ Hardware is a consumer goods electronics company that operates in various countries and has experienced significant growth. However, despite their growth, the company still relies on using Excel files for data analytics. Excel files are not effective in generating insights and are hard to consume, making it challenging for the company to identify trends and opportunities in their data

Senior executives of this company have decided to invest in a data analytics project and have assigned a team for this work.

## Tool Used

• SQL

• POWER BI

• EXCEL

• DAX Language

• DAX Studio

## Business related terms

• Gross price

• Pre-invoice deductions

• Post-Invoice deductions

• Net Invoice sale

• Gross Margin

• Net sales

• Net profit

• COGC - cost of goods sold

• YTD - Year to Date

• YTG - Year to Go

• Direct

• Retailer

• Distributors

• Consumer


## Dataset Understanding

Understanding what data is available will be more helpful while doing analysis. before 

jumping on to the analysis get good understanding of what are data available.

Dimension table : It will have the static data like details of customer and products

Fact table : It will have the data about the transactions

gdb041:

•  dim_customer

    •  27 distinct markets (ex India, USA, spain)
    
    •  75 distinct customers thorough out the market
  
    •  2 types of platforms
   
         •Brick & Motors - Physical/offline store
         
         •E-commerce - Online Store (Amazon, flipkart)
         
    •  Three channels
         • Retailer
         
         • Direct
         
         • Distributors
         
• dim_market

        • 27 distinct markets (ex India, USA, spain)
        
        • 7 sub-zones
        
        • 4 regions
        
            • APAC
            
            • EU
            
            • nan
            
            • LATAM
• dim_product

        • Divisions
        
        • P & A(Pheripherals & Accessories)
        
        • PC
        
          • Notebook
          
          • Desktop
          
        • N & S
        
          • Networking
          
          • Storage
          
        • There are 14 different categories, Like Internal HDD, keyboard
        
        • There are different variants available for the same product
        
   • fact_forecast_monthly
   
         • This table is used to forecast the customer’s need in advance, which can help in
         
            • Higher customer satisfaction
            
            • Reduced cost in warehouses for storage purpose
            
         • The table is denormalized by data engineering team, as it is a data warehouse which is aimed
         
         to be used for analytical work.
         
         • All the date of the month will be replaced by the start date of the month
         
        • It will have all the column names and in the end it will have the forecast quantity 
        
        need of the customer
        
   • fact_sales_monthly
   
        • This table is more or less is same as fact_forecase_monthly table, but the last column 
        
        has the value of sold quantity instead of forecast value.
        
• gdb056

    • freight_cost
    
        • This table has details of travel cost and other cost for each market with fiscal year
        
    • gross_price
    
        • Has the details of gross prices with product code
        
    • manufacturing_cost
    
        • Has the details of manufacturing cost with product code with year
        
    • Pre_invoice_dedutions
    
        • Has the details of pre invoice deductions percentage for each cutomer with year
        
    • Post_invoice_deductions

        • Post invoice deductions and other deductions details



