# Consultant Business Report:
This report presents the findings of the project 'Customer segmentation and marketing analysis' for a UK-based online gift store.
The analysis focuses on customer history, product prefferences and products associations.   


1. Customer Segments:
Custumers are grouped into 3 clusters based on "recency,frequency, monetary" :

• Champions: Recent, frequent, high-spending customers.
• Loyal Customers: Regular buyers with consistent purchases.  
• At Risk: Previously active but declining, not frequent..  

2. Purchasing Patterns: 
Products purchasing lead to suggest the consequents products, to be viewed and purchased by the customer. 
Top 10 products are commonly bought together, having stongest association rules :


	frozenset({REGENCY TEA PLATE PINK}),	frozenset({REGENCY TEA PLATE GREEN })
	frozenset({REGENCY TEA PLATE GREEN }),	frozenset({REGENCY TEA PLATE PINK})
	frozenset({POPPY'S PLAYHOUSE KITCHEN, POPPY'S...,	frozenset({POPPY'S PLAYHOUSE LIVINGROOM })
	frozenset({POPPY'S PLAYHOUSE LIVINGROOM }),	frozenset({POPPY'S PLAYHOUSE KITCHEN, POPPY'S ...
	frozenset({REGENCY MILK JUG PINK }),	frozenset({REGENCY SUGAR BOWL GREEN})
	frozenset({REGENCY SUGAR BOWL GREEN}),	frozenset({REGENCY MILK JUG PINK })
	frozenset({POPPY'S PLAYHOUSE BEDROOM }),	frozenset({POPPY'S PLAYHOUSE LIVINGROOM , POPP...
	frozenset({POPPY'S PLAYHOUSE LIVINGROOM, POPP...,	frozenset({POPPY'S PLAYHOUSE BEDROOM })
	frozenset({REGENCY TEA PLATE ROSES }),	frozenset({REGENCY TEA PLATE PINK})
	frozenset({REGENCY TEA PLATE PINK}),	frozenset({REGENCY TEA PLATE ROSES })



3. Recommendations:  

Based on these associations, and after the customer purchased a product that being as antecedents, the system recommend a product from the consequents list. 

4. Business Actions:

The goal is to increase sales, improve customer's experience and enhance customer history such as:  
retain champions and reward it.  
motivate loyal customer to level up.  
encourage at-risk customer to return frequently.  


Marketing campaigns: marketing should target each segment of customers, by marketing stategies, advertising,, leveraging different seasons to re-engage inactive customers. offering packages or baskets based on association rules.

Customer retention strategies: 
- retain chapions by rewarding them, and with early access to new products, or with premuim sercives.  
- motivate loyal customers to level-up frequency and moneraty scores, by  making discounts with each purchased transactions, gaining points while reaching a specific threshold. 
- encourage at-risk customer to return more frequently by offering discounts based last purchased products , and on duration between trasctions, advertising that targets and simulates the personal needs of the customers based on their previous purchases to remind them. 
if he buy product A, after month we offer discount or points on the same product.

Product bundles:  
Based on association rules we can identify products frequnetly upurchased together, create  bundels, baskets or packeges with special prices or discounts. Or improve associated products together placement to be displayed, viewed and purchased together. 

Personalized offers:  
Based on the behavior of each customer, send messages or notifications to enhance the interaction and encourage them to return, sush as : send limited discounts and offers, send personalized basket offers based on frequent transactions or seasnal transactions of the customer.


So, by studying customer's behavior and  products' associations, we can improve customer retention, increase purchases and repeat it, develop marketing compains to target each customer.
