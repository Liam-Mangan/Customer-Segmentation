# Customer-Segmentation
This project applies clustering techniques to segment customers based on their purchasing behavior. The goal is to identify actionable customer groups and recommend marketing strategies. 

Source: https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis?resource=download
Size: 2240 x 29
Data set contains personal details about customers and their purchasing habits.

From the data I have found 3 groups of customers. 

Cluster 1: Older, moderate income, potentially grown kids. These shoppers look for deals when they spend.
 - Average age: 60.4
 - Average income: $57,310
 - Coupon behavior: Frequent coupon users
 - Household: Married - 0.3 kid(s)
 - Spending highlights:
   • MntWines: 455.1
   • MntMeatProducts: 129.3

Cluster 2: Middle aged, higher income, no kids. These are the big spenders.
 - Average age: 56.2
 - Average income: $75,436
 - Coupon behavior: Occasional coupon users
 - Household: Married - no kids
 - Spending highlights:
   • MntWines: 601.9
   • MntMeatProducts: 451.2

Cluster 3: Middle aged, lower income, has kids. These people haven't been doing a lot of shopping in our store.
 - Average age: 53.4
 - Average income: $34,828
 - Coupon behavior: Occasional coupon users
 - Household: Married - 0.8 kid(s)
 - Spending highlights:
   • MntWines: 39.2
   • MntMeatProducts: 21.7

How to capitalize  on each segment.
Cluster 1: Send coupons and alerts about deals (alerts should be targeted based on that individual spending habits. 

Cluster 2: Since these are our top spenders, we should do a deeper dive into their purchases. From this we could stock more premium brands and versions of products they like to buy. Another action could be to stock rare products they are likely to buy and alert them that they will be sold at the store while supplies last or limited promotion.

Cluster 3: This group is not doing a lot of shopping in our store. We may need to increase discounts on bulk items or add a low cost alternatives to current products, because they are lower income and have families they are likely looking for items in larger quantities, but are very price conscious.

------
Some things I would liked to have known about this data are details like geographical location, area demographics, store type (Large grocery, small grocery, artisan store). What I would propose as the next steps would be to do more targeted data collection on each segment to implement strategies.
