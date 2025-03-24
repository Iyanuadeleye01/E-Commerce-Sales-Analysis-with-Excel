# E-Commerce-Sales-Analysis-with-Excel
This analysis focuses on examining customer behavior insights in e-commerce sales using Excel  

##  Project Overview  
This project aims to **analyze customer behavior, sales trends, and business performance** of an e-commerce store using **Exploratory Data Analysis (EDA) in Excel**. By leveraging past sales data, I provided insights into **customer demographics, loyalty, pricing strategies, purchase patterns, marketing effectiveness, and return rates** to support data-driven decision-making.

##  Objectives  
The analysis seeks to answer key business questions, including:  
- **Customer Demographics and Spending:** Which age group (young vs. old) spends more? What product categories do they prefer?  
- **Customer Loyalty and Retention:** How often do customers return purchases? How does satisfaction affect brand loyalty?  
- **Pricing and Discounts:** Do discount-sensitive customers spend more? Does discount usage affect return rates? Are high-income customers interested in discounts?  
- **Purchase Behavior and Preferences:** How does product category impact shipping preference? What are the peak shopping hours and days?  
- **Marketing and Ad Engagement:** Does social media influence purchase amounts and product ratings?  
- **Return Rate and Product Quality:** Do lower-rated products have higher return rates? Which category has the highest returns? Are dissatisfied customers more likely to return products?  

##  Dataset  
The dataset consists of past sales records from the e-commerce store, containing:  
- **Customer Information:** Age, Income, Time To Decision, Customer ID, Gender, Age Group, Marital Status, Education Level, Occupation, Location, Payment Card, Device Used     for Shopping, Time Spent on Research, Purchase Channels, Frequency of Purchase.  
- **Purchase Details:** Purchase Category, Purchase Amount, Shipping Preference, Purchase Intent, Discount Used, Discount Sensitivity, Time of Purchase, Weekdays.  
- **Returns & Satisfaction:** Return Rate, Product Rating, Customer Satisfaction, Brand Loyalty, Customer Loyalty Member  etc.  
- **Marketing Engagement:** Social Media Influence, Engagement with ADs.  

##  Methodology  
The analysis was conducted using **Microsoft Excel** with the following steps:  
1. **Data Cleaning & Preparation:** Checking for duplicates, Checking for missing values and other data inconsistencies.  
2. **Feature Engineering:** Created new columns like **Age Group (Young/Old)**, **Weekdays**.  
3. **Exploratory Data Analysis (EDA):**  
   - Used **Pivot Tables, Charts, and Slicers** to explore trends.  
   - Conducted **Comparative Analysis** on spending behavior, loyalty, and returns.  
   - Examined **relationships** between variables like discount_used, discount sensitivity and return rates.  
4. **Dashboard Creation:** Developed an **interactive Excel dashboard** to visualize insights.  

##  Key Insights  
1. **Purchase Amount By Age Group:** Young customers spent slightly more on purchases, with a total purchase value of $138,000.87 compared to $136,000.20 for older customers. Young customers showed the highest preference for home appliances, while arts & crafts were the least purchased category. Older customers preferred jewelry & accessories and electronics, while they showed the least interest in hotel items, office supplies, and luxury goods
2. **Customer Loyalty and Retention:**  Customers enrolled in the loyalty program had a higher return rate of 96% than non-members, who had a 95% return rate
The relationship between brand loyalty and customer satisfaction was inconsistent, suggesting no significant dependency between the two variables.
3. **Pricing and Discount:** Discount-sensitive customers who used discounts recorded a higher total purchase value of $273,000.80 compared to those who were indifferent to discounts at $263,000.20. However, customers who did not use discounts still had a notable total purchase amount of $271,000.10, indicating that non-discounted purchases remain significant. Customers who used discounts had a higher return rate of 52% compared to 48% for those who did not use discounts. Further analysis and additional metrics are needed to fully understand the impact of discount usage on return rates. Customers with high income used discounts more than customers with middle income.
4. **Purchase behavior and Preference:** Customers who purchase office supplies prefer express shipping the most, while those buying sports and outdoor items show the highest indifference to shipping preferences. Customers who purchase home appliances use standard shipping the most. The busiest shopping day of the week is Tuesday, with an average of 159 customer transactions, the hours were accounted for in this analysis.
5. **Marketing and Ads Engagement:** Customers with high social media influence made more purchases, totaling approximately $284,000.30, compared to $262,000.80 for those with no social media influence. Interestingly, customers with high social media influence provided the lowest product ratings, whereas those with no, low, or medium social media influence gave higher ratings.
6. **Return rate and Product quality:** Customers who give higher product ratings tend to have higher return rates than those who give lower ratings. The travel and leisure (flight) category experiences the highest return rate, while the healthcare category has the lowest. Dissatisfied customers do not show a strong tendency to return products, while the most satisfied customers have the highest return rates. However, customer satisfaction does not follow a consistent pattern in relation to return rates.
##  Recommendations  
1. Since young customers purchase more home appliances and older customers prefer jewelry and electronics, marketing efforts should be tailored to highlight these preferences. Personalized promotions can help increase engagement and sales.
2. Customers sensitive to discounts tend to spend more, but higher return rates among discount users suggest possible dissatisfaction. It's essential to evaluate the impact of discounts on product quality perception and implement better ways to ensure customer satisfaction.
3. The loyalty program shows only a slight or no difference in return rates compared to non-members. To improve customer retention, the program should be reassessed to offer better incentives that encourage long-term loyalty and reduce return rates.
4. Optimizing shipping options based on product categories can improve the customer experience and reduce delivery-related complaints.
5. Customers influenced by social media purchase more but give lower ratings. This suggests that marketing should not just focus on driving purchases through social media but also on setting the right expectations to improve satisfaction and ratings.
6. The travel and leisure category has the highest return rates, which signals potential quality concerns. Product quality assessments and better customer education can help reduce return rates.


##  Next Steps  
- Further refine analysis with **advanced statistical methods**.  
- Implement **automated reporting** for continuous monitoring.  

## Tools Used  
- **Microsoft Excel (Online)**  
- **Pivot Tables & Pivot Charts**  
- **Excel Functions & Slicers**  
