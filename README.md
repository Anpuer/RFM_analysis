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
  - At Risk (19.92%) -> Negative
  - New Customers (15.13%) -> Negative
  - Potential Loyalist (12.61%) -> Positive
  - Hibernating customers (11.38%) -> Negative
  This is an early warning for businesses when up to 3/4 of customer groups show negative signs
- The two most important customer segments that are predicted to bring the largest revenue and profit are **Champions** and **Loyal Customers**, but they only account for a small portion of customers.
- 





