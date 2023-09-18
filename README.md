# [PYTHON] RFM_analysis
## I. Introduction
### 1. RFM analysis

**What is RFM analysis**

- RFM stands for recency, frequency, and monetary value, three key indicators used to analyze customer behavior and identify groups of customers that share similar characteristics.
- Understanding RFM analysis can help you get a pulse on your current customer engagement levels (recency), identify loyal and regular customers (frequency), and highlight high-value customers (monetary value). 

**Why RFM**

- With RFM, you can segment customers based on their purchasing patterns to help you predict future behavior, target your marketing efforts effectively, find your best customers, and increase customer retention. Customer loyalty is a critical factor that can make or break your business.
  - **Recency** provides insights into current customer engagement levels by measuring how much time has passed since their last purchase.
  - **Frequency** lets you see which customers are loyal and engage with your brand or company regularly by measuring how often customers interact with you within a specific period of time.
  - **Monetary value** helps to highlight which customers are most valuable and generate the most revenue for your business. This number represents the total amount of money a specific person has spent on your company as a customer.
- Understanding recency, frequency, and monetary value will help you make informed decisions about how to optimize your marketing strategies, increase retention, identify your best customers, and ultimately drive business success.

**Reference**

[How to Calculate RFM Score: The Key to Unlocking Customer Loyalty and Growth](https://patchretention.com/blog/how-to-calculate-rfm-score)

### 2. Business case

- This is data set of a global retail company so there are many customers. On the occasion of Chirstmas and New Year even, the Mareting Department wants to run marketing campaigns to thank customers who have supported the company over the past time. As well as exploiting customres who have the potential to become loyal customers.
- However, the Marketing Department have not yet been able to classify the segments of each customer to deploy each marketing program suitable for each customer group because the data set is too lagre.
- The Marketing Director proposed using the RFM model and because the amount of data is too large so we have to build a flow to deploy Segmentation evaluation through Python programming.

## II. Data Visualization 
![Count of Customer by segment](https://github.com/Anpuer/RFM_analysis/assets/144112015/b42376ad-41d6-4b6e-b093-98571920e6ac)
![Treemap](https://github.com/Anpuer/RFM_analysis/assets/144112015/e983aead-8562-41a6-8514-0b86520da2cb)
![avg date](https://github.com/Anpuer/RFM_analysis/assets/144112015/14f103fc-28ae-4662-b3e8-7005670b4a72)
![avg freque](https://github.com/Anpuer/RFM_analysis/assets/144112015/aebf7130-2ab9-454d-aaab-3ea235914e11)
![avg sales](https://github.com/Anpuer/RFM_analysis/assets/144112015/7348a897-2a2a-421f-b8a7-f7429825dc42)


## III. Insight
- Most of customers are in these groups:
  - Potential Loyalist (14.88%) -> Positive
  - At Risk (13.24%) -> Negative
  - Hibernating customers (12.48%) -> Negative
  - Champions (10.09%) -> Positive
- The two most important customer segments that are predicted to bring the largest revenue and profit are **Champions** and **Loyal**, meanwhile **Loyal** segment only account for a small portion of customers (7.94%).
- **Loyal** has a high frequency of purchases (only after **Champion**) but the most recent purchases are much farther than many segments (**Champion, Need Attention, New Customers, Potential Loyalist, Promising**).
- The segments that spend the most money are: **Champions, Loyal, Potential Loyalist, At risk**. The **At risk** segment used to buy regularly but have not done so for a long time.
- **New customers** have purchased products quite recently but have a low purchasing frequency and the profits this customer segment brings are not high.
- With the retail store, the main task is always to grow in customers, market share, and revenue received from orders. **R** will be the index that businesses need to pay the most attention to because Superstore currently has a % of customers intending to abandon (recently at a high level). The higher this index is, the higher the customer's tendency to leave is found. It is a warning for businesses to change products to meet customer needs or change policies to improve service quality.

## IV. Recommendations
- The company needs to change product policies and offer more promotions to make them more diverse and attractive to each customer group. Here are a few recommendations across a few segments that I think businesses need to pay attention to
  - **Champion**: Must retain these customers at all cost -> Propose customer equipment programs with different and highly personalized values, increase Customer Lifetime Value by recomending higher value items, product combos based on predictions from order history.
  - **Loyal**: Find out why this customer segment often made purchases in the past but has not made purchases recently -> After classifying the customer file, you can send a survey email to find out with an accompanying reward of vouchers or promotional offers on future purchases.
  - **At Risk**: This customer segment brings quite high profits, but only because the proportion is quite large, not because they buy a lot -> find out why they are not satisfied and do not return to buy.
  - **Potential Loyalist**: accounts for the highest proportion, but doesn't spend too much -> find ways for them to increase the value of their shopping cart each time they make a purchase -> For example, give free gifts for transactions that exceed average order value threshold.
- For new and promising customers, pay attention to initially create a closer relationship -> Send a thank you note, ask for a review from the order, attach a voucher,...
- The cost of attracting new customers is much greater than the cost of retaining old customers -> This group of customers cannot be ignored. For customers in the remaining groups -> What makes them unhappy -> MKT deparment needs to do in-depth research on Customer churn Analysis, conjecturing the causes can come from many sides.




