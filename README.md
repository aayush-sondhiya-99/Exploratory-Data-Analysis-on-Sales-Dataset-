## **Objectives of Analysis**

The aim of this project is to analyze the sales dataset and obtain key insights that can help business make informed decisions improving its sales performance, customer satisfaction, and profitability . I will also create an interactive dashboard using PowerBI that will help stakeholders to explore the data visually .

## **Dataset Description**

This dataset, sourced from [Kaggle](https://www.kaggle.com/), contains comprehensive sales data, organized across five interrelated tables: customers, date, markets, products, and transactions. With over 1,50,000+ transactions, this dataset is well-suited for exploring sales performance, customer behaviors, and market trends across various regions and product categories. 

The dataset comprises the following five tables :

- **Customers:** Information on individual customers, including demographic details and customer identifiers.
    
    **Key Columns:** `customer_code`, `customer_name`, `customer_type`
    
- **Date:** A calendar dimension table that allows for time-based analysis of transactions.
    
    **Key Columns:** `DateID`, `Date`, `DayOfWeek`, `Month`, `Year`, `Quarter`
    
- **Markets:** Details on different sales regions or markets where the products are sold.
    
    **Key Columns:** `MarketID`, `MarketName`, `Region`
    
- **Products:** A catalog of products available for sale, including their categories and prices.
    
    **Key Columns:** `ProductID`, `ProductName`, `Category`, `Price`
    
- **Transactions:** The core sales transaction table, recording each individual sale made to customers.
    
    **Key Columns:** `TransactionID`, `CustomerID`, `ProductID`, `MarketID`, `DateID`, `Quantity`, `TotalAmount`
