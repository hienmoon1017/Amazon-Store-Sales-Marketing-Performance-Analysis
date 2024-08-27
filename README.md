# Monthly Amazon Store's Sales & Marketing Performance Analysis
Here is the summary of requirement to analyze the Amazon Store's Sales &amp; Marketing Performance

|      | Monthly Amazon Store's Sales & Marketing Performance Analysis                         |
|---------------|--------------------------------------|
| Industry | E-commerce | 
| Product type | Gift products | 
| Department | Sale & Marketing | 
| Problem statement | Deep dive into key data analytics concepts to uncover useful insights for planning in the next month | 
| What are you solving for? | - Q1: What was the sales performance by product type and SKU in this month? <br> - Q2: How to optimize Sales & Advertising Marketing Performance? What improvements can be made? | 
| Goals/metrics | Analyze sales and marketing performance in this month to gain key takeaways for planning in the next month | 
| Deliverables | Charts outlining findings and recommendations | 
| Data period | 1 Dec 2023 - 31 Dec 2023 | 
| Are datasets available? | Yes | 
| Dataset list | The dataset can be downloaded from the link [HERE]() |
| Metrics explanation | - SKU: Stock Keeping Unit <br> - COGS: Cost Of Goods Sold <br> - P&L: Profit and Loss |

👍 Tools: Advanced Excel (Power Query, Power Pivot), DAX (Data Analysis Expressions)

# Dataset Diagram
![Dataset Diagram](https://github.com/user-attachments/assets/a7e1627b-4885-4ab9-9442-7488837d1618)

# Exploratory Data Analysis (EDA)
+ Data formatting is correct. No missing or invalid data was found. 
+ Number of SKU: 50
+ Number of Campaign Name: 259
+ Average Revenue by SKU: $5,817
+ _Extra infomation:_

| Product Type     | Number of SKU | Average Revenue | Number of SKU with Revenue Higher than the Average Revenue ($5,817)
|---------------|--------------------------------------:|--------------------------------------:|--------------------------------------:|
| Apron |3|$1,830|0| 
| Can Cooler |16|$8,143|6|
| Jar Candle |7|$675|0|
| Night Light |6|$474|0|
| Tumbler |18|$8,195|13|

# Q1: What was the sales performance by product type and SKU in this month?
![Q1-sale performance analysis-revenue](https://github.com/user-attachments/assets/de8e9248-ce78-4a64-94e5-38de11e5ab49)

👉 **Key Takeaways**:
+ The **Tumbler** product had the **highest** revenue in this month, totaling **$147,508**, which contributed to **51%** of the total revenue for that month.
+ The **Can Cooler** came in **second** with a revenue of **$130,286**, accounting for **45%** of the total revenue in this month.
+ **Jar Candle** and **Night Light** had the **lowest** performance, with revenues of **$675** and **$474**, respectively.
+ To **boost sales in the next month**, consider focusing on the **top 10 SKUs with the highest revenue**.

![Q1-sale performance analysis-PL](https://github.com/user-attachments/assets/ee8ffe97-07b2-4fb3-b5d8-fb7aa215903f)

👉 **Key Takeaways**:
+ The **Tumbler** and **Can Cooler** had good profits, with a P&L of **$17,890** and **$16,361**, respectively. Their P&L margins were **12%** and **13%**, meaning the profit was 12% and 13% of their total revenue.
+ In contrast, the **Night Light**, **Jar Candle**, and **Apron** experienced losses. Their P&L figures were **-$1,109, -$730**, and **-$368**, with P&L margins of **-39%**, **-15%**, and **-7%**, indicating that their losses were 39%, 15%, and 7% of their total revenue.

# Why Night Light, Jar Candle, and Apron lost
![Revenue Source](https://github.com/user-attachments/assets/30ee61a3-5413-4b4a-97cc-54a116cbabfc)

👉 **Reason**:
+ The **Night Light**, **Apron**, and **Jar Candle** products **heavily relied on advertising** for their revenue, with **85%**, **77%**, and **60%** of their revenue coming from ads, respectively.

💡 _**Recommendations:**_
+ **Optimize advertising campaign performance** by closely monitoring and adjusting key metrics like ROAS (Return on Ad Spend) and CPO (Cost Per Order) to ensure cost efficiency and profitability.
+ **Research user interest** in gift products on the Amazon store to increase revenue from organic (non-ads) sources, thereby reducing dependency on advertising.

# Q2: How to optimize Sale & Advertising Marketing Performance? What improvements can be made?

![top 10 highest ROAS by SKU](https://github.com/user-attachments/assets/d8999490-b8ea-4b6b-97cf-96a36885b14c)

👉 **Key Takeaways**:
+ Prioritize the top 10 SKUs with the highest ROAS in Jan,2024

![how to solve with 3 lost product](https://github.com/user-attachments/assets/ebdafa33-5a70-42a9-a075-c49bbeda31b8)

👉 **Key Takeaways**:
+ For the **03 products with losses** (Night Light, Jar Candle, and Apron), turn off campaigns where sales = $0 or where ROAS < 5 and Sales < $100 (_Note:_ ROAS = Sales / Ad Expense)

💡 _**Recommendations:**_
+ Name campaign name logically for easier management

**_Additional charts for optimization ads campaign_**
![heatmap_ad campaign performance by campaign name](https://github.com/user-attachments/assets/6d3a44a6-3269-486b-a289-cedfa172584c)

_and_

![heatmap_ad campaign performance by SKU](https://github.com/user-attachments/assets/4e53660f-c6f9-4016-83f2-4a333e1553fe)


Thank you for stopping by, and I'm pleased to connect with you, my new friend!

**Please do not forget to FOLLOW and star ⭐ the repository if you find it valuable.**

Wish you a day filled with happiness and energy!

Warm regards,

Hien Moon | [Visit My Blog](https://hienmoon.com/?utm_source=github&utm_medium=readme)
