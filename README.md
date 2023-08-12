# RFM_Analysis
## **Introduction**

**1.1. Business question**

- SuperStore is a global retail company. The Marketing Department wants to run marketing campaigns during the Christmas and New Year holidays to thank customers for their past support of the company. In addition, potential customers can be exploited to become loyal customers.
- The Marketing Director also proposed a plan to use the RFM model in Python to segment customers, and then launch appropriate marketing campaigns. Analyze the current situation of the company and give suggestions to the Marketing team
- With the retail model of Superstore company, which indicator should be most focused in in the 3 indicators R, F, and M?

**1.2. Dataset**

Dataset includes 4 different related tables including: transaction information, products information, returned orders of customers purchasing products from 2014 to 2017 and RFM classification

1. Transaction information dataframe
    
2. Returned orders dataframe
    
    We have to filter orders that were not returned before RFM analysis
    
3. Products dataframe
    'Product ID' is not unique because some products have same Product ID but have different Product Name => drop 'Product Name' then remove duplicate records so that 'Product ID' will be unique
    
4. Segmentation dataframe
    We have to split each RFM score into single rows
    
**1.3. Method: RFM analysis**

- RFM is a method used for analyzing customer value. It is commonly used in database marketing and direct marketing and has received particular attention in retail and professional services industries
- RFM stands for the three dimensions:
    1. Recency – How recently did the customer purchase?
    2. Frequency – How often do they purchase?
    3. Monetary Value – How much do they spend?
- RFM analysis numerically ranks a customer in each of these three categories, generally on a scale of 1 to 5 (the higher the number, the better the result). The “best” customer would receive a top score in every category.

## Data Visualization
Please see coding file for more detailed visualizations

## Recommendations

***1. Recency, Frequency and Monetory value of Superstore:***
- With the retail model, the main task is always to grow in terms of customers, market share, and revenue received from orders. R will be the most important index that businesses need to pay attention to because Superstore currently has a % of customers intending to leave (last time was high). The higher this number, the higher the customer's tendency to leave. It is a warning for businesses to change products to meet customer tastes or change policies to improve service quality.

***2. 11 small segments of Superstore to 3 main segments:***
- The company needs to change the policy on products, offer more promotions so that they become diverse and attractive to each customer group.
    - VIP group: attractiveness from promotions and exclusive VIP programs -> increased spending, frequency
    - Medium group: product attractiveness, suitable purchasing power, encouraging increased spending from savings combos to get to VIP rank, enjoying VIP privileges -> MKT's problem is how to make them feel satisfied and continue to increase the cart value. For example: combo policy, upsell, research feedback, purchase experience, gift voucher discount... 
    - Low group: product attractiveness, price -> From there, increase the rate of return and purchase

- It is necessary to offer special benefits and special care programs for VIP customers for 2 main purposes:
    - Clearly define the boundaries between the VIP group and the rest.
    - Increase the spending level of this customer group and increase the frequency of purchases
- For the Low group:
The cost to attract new customers is much greater than the cost of retaining old customers -> This customer group cannot be ignored For customers in the Low group, they do not have time to purchase recently, however purchase frequency quite often -> What makes them unhappy -> MKT needs to do in-depth research on Customer churn Analysis. Guessing the cause can come from many sides: price, product quality, competitors, or customers themselves when a decrease in income means a decrease in spending.

