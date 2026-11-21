# Unsupervised Learning Capstone Challenge:  

This project is an end-to-end Unsupervised Learning building solution for real transaction data.
The goal is to investigate the data, discover hidden patterns, and transform those discoveries into business decisions.

## Business Problem: 
The company has a hugeamount of data about customers and products during a year, but still doesn't know their custormers, preferences, behaviors, also doesn't know favorite products or association between product, so the main goals os to redefine customer and products, find relations and associations that lead the company to make best desicion on marketing compains and customers retetion, increase sales and level-up the work.  

## Objectives: 
Understanding a real-world business problem.
Exploring and cleaning raw data.
Creating meaningful features.
Applying unsupervised learning techniques.
Choosing appropriate algorithms.
Evaluating clustering results.
Discovering purchasing patterns.
Building recommendation logic.
Translating ML outputs into business recommendations.


# Dataset description
This dataset contains real transactions from a UK-based online gift store: UCI Online Retail Dataset
Period:
December 2010 → December 2011 (included)
Approximately:
541,000 transactions

- Available features : 
InvoiceNo:	Transaction ID
StockCode:	Product ID
Description:	Product name
Quantity:	Number of purchased items
InvoiceDate:	Purchase date and time
UnitPrice:	Product price
CustomerID:	Customer identifier
Country:	Customer country

# Techniques Used:  
- Data exploratation and cleaning :  
Handle missing values
Remove duplicate records
Create new feature: total price(unitprice*quantity)  
Apply 'StandardScaler' to feature data
convert data types  
visualize and compare purchasing based on some features.  

- customer segmemtation :  
create RFM table (recency, frequency, monatary) 
features scaling 
Apply K-Means clustering  
Use Elbow methode and Silouette method to evaluate and compare.  
Define customer personas, using "name" labels:  
    - Champions:	Recent, frequent, high-spending customers  
    - Loyal Customers:	Regular buyers with consistent purchases  
    - At-Risk Customers:	Previously active but declining.  

- PCA Visualization :
Apply PCA to reduce your customer features into 2 dimensions.  
Visualize customer segments. 


# Market Basket Analysis :
Create a basket 
Apply Apriori algorithm  
Generate association rules  
Evaluate usng support, confidence   
Display strongest associations(frequent products together).  

# Recommendation : 
Using assocaition rules, and customer history(antrcedents elements) recommend top 10 of suitable products.  

# Main findings :
We find 3 clusters(types) of customers :  
 customer personas, using "name" labels:  
    - Champions:	Recent, frequent, high-spending customers  
    - Loyal Customers:	Regular buyers with consistent purchases  
    - At-Risk Customers:	Previously active but declining.

we find products associated strongly together, preffered products.

# Business recommendations : 
Marketing campaigns: marketing should target each segment of customers, by marketing stategies, advertising,, leveraging different seasons to re-engage inactive customers. offering packages or baskets based on association rules.

Customer retention strategies: 
- retain chapions by rewarding them, and with early access to new products, or with premuim sercives.  
- motivate loyal customers to level-up frequency and moneraty scores, by  making discounts with each purchased transactions, gaining points while reaching a specific threshold. 
- encourage at-risk customer to return more frequently by offering discounts based last purchased products , and on duration between trasctions, advertising that targets and simulates the personal needs of the customers based on their previous purchases to remind them. 
if he buy product A, after month we offer discount or points on the same product.

Product bundles:  
Based on association rules we can identify products frequnetly upurchased together, create  bundels, baskets or packeges with special prices or discounts. Or improve associated products together placement to be displayed, viewed and purchased together. 


