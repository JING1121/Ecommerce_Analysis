# YOUKE TECH- CustomerBehaviorsAnalysis

Tools: Python
Project Type: AnalysisData, Data Cleaning, EDA, Visualization
Select: Stakeholder

🔙[**Back to Homepage**](https://www.notion.so/About-Me-1697a7a1452b8054b4adfafec8c57cd8?pvs=21)

![未命名的设计.jpg](YOUKE%20TECH-%20CustomerBehaviorsAnalysis%2016b7a7a1452b80c5bc08e1473cfe0b47/7677f5c7-c779-49ac-8fe2-d7455d314568.png)

# YOUKE- CUSTOMER BEHAVIORS ANALYSIS

## **Project Background**

YOUKE Tech, an e-commerce company established in 2018, specializes in selling popular electronics, including Smartphone, Tablet, Laptop, Smartwatch, Headphones. I collaborate with the Operations team to analyze data and provide actionable recommendations aimed at enhancing the performance of the sales, product, and marketing team.

## **Executive Summary**

---

YOUKE Tech’s sales analysis of 108k records from 2019 to 2022 reveals annual revenue stabilizing at approximately $7 million, approaching pre-COVID levels. North America and EMEA regions account for 80% of total sales, with Monitors and AirPods contributing 60% of the revenue. However, declining customer retention is a key concern, as unique purchase rates and repeat purchase rates have dropped by 15% and 10%, respectively.

To address these challenges, YOUKE Tech could focus on expanding its top-performing product lines, optimizing bundling strategies, and enhancing loyalty programs to boost customer lifetime value. Additionally, targeted growth initiatives in APAC and LATAM, combined with improvements in digital channels such as the mobile app, are essential for strengthening market presence and driving long-term sustainable growth.

## **Data Structure Overview**

---

- Data Explication
    
    TheElectronic Sales Database contains both numeric and categorical data, capturing essential customer and transaction details.
    
    - Customer ID: Unique identifier for each customer.
    - Age: Age of the customer (numeric)
    - Gender: Gender of the customer (Male or Female)
    - Loyalty Member: (Yes/No)
    - Product Type: Type of electronic product sold (e.g., Smartphone, Laptop, Tablet)
    - SKU: a unique code for each product.
    - Rating: Customer rating of the product (1-5 stars)
    - Order Status: Status of the order (Completed, Cancelled)
    - Payment Method: Method used for payment (e.g., Cash, Credit Card, Paypal)
    - Total Price: Total price of the transaction (numeric)
    - Unit Price: Price per unit of the product (numeric)
    - Quantity: Number of units purchased (numeric)
    - Purchase Date: Date of the purchase (format: YYYY-MM-DD)
    - Shipping Type: Type of shipping chosen (e.g., Standard, Overnight, Express)
    - Add-ons Purchased: List of any additional items purchased (e.g., Accessories, Extended Warranty)
    - Add-on Total: Total price of add-ons purchased (numeric)

![                                                         YOUKE DATASET ERD](YOUKE%20TECH-%20CustomerBehaviorsAnalysis%2016b7a7a1452b80c5bc08e1473cfe0b47/image.png)

                                                         YOUKE DATASET ERD

## **Insights Deep-Dive**

---

### Sales Trends and Growth Rates

- Sales surged in 2020 but dropped 45% by 2022, returning slightly above pre-pandemic levels.
- Peak sales occur in **November and December**, while **February and October** see lower sales.
- North America and EMEA account for **80% of total sales**.
- The U.S. alone contributes **50% of total revenue**.

**Key Product Performance**.

---

[](https://images.spr.so/cdn-cgi/imagedelivery/j42No7y-dcokJuNgXeA0ig/d0a8c67d-8165-449f-a2ee-f47049af9a61/annual_sales/w=3840,quality=90,fit=scale-down)

[](https://images.spr.so/cdn-cgi/imagedelivery/j42No7y-dcokJuNgXeA0ig/def5bdcb-b7a4-490f-8bb9-936589d60f4c/monthly_metrics/w=3840,quality=90,fit=scale-down)

**Key Product Performance**

---

- During the pandemic, laptop sales soared, with MacBook orders increasing by 400% and ThinkPad by 220%. This trend has since reversed post-pandemic.
- Four products: monitors, AirPods, laptops, and Samsung Cable Pack, generate 96% of total revenue.
- AirPods account for 45% of all orders ($7.7M revenue).
- Monitors lead in revenue, contributing $9.8 million (35% of total sales) from 2019 to 2022.
- Samsung Cable Pack represents 20% of orders but only 2% of revenue, likely due to its low price or use in promotions.

[](https://images.spr.so/cdn-cgi/imagedelivery/j42No7y-dcokJuNgXeA0ig/91a8257f-f7eb-4656-909b-e34b1a11d6e9/product_performance/w=3840,quality=90,fit=scale-down)

### Customer Growth and Repeat Purchase Trends

---

- Steady growth from **2019 to 2021**, peaking at **30,000 unique customers** in 2021.
- Sharp decline by **40% in 2022**, indicating a loss of new customers.
- Consistent decrease in repeat purchase rates (≥2 orders), dropping from **20.22% in 2019** to **14.76% in 2022**, suggesting retention challenges.
- Despite the decline, a **stable core of loyal customers** continues to make multiple purchases annually.
- The decline in both unique and repeat customers in **2022** may reflect changing **market dynamics** or evolving **customer preferences**.

[](https://images.spr.so/cdn-cgi/imagedelivery/j42No7y-dcokJuNgXeA0ig/a1934ebd-122f-4568-907c-2bffb8bdad97/customer_retention/w=3840,quality=90,fit=scale-down)

### Loyalty Program Performance

---

- Loyalty members make their first purchase **20 days earlier** than non-loyalty members (**50 days vs. 70 days**), reducing time to first purchase by **30%**.
- Loyalty members generate **$500K more in revenue**, spend **$30 more per order**, and place **500K more orders** than non-loyalty members.
- Loyalty metrics surged after the pandemic but showed signs of **slowing in 2022**.
- The program performs strongly in **North America**, while **APAC and LATAM regions** remain **volatile**, indicating a need for **region-specific strategies**.
- Loyalty purchases have a **higher refund rate** compared to non-loyalty purchases.

[](https://images.spr.so/cdn-cgi/imagedelivery/j42No7y-dcokJuNgXeA0ig/9ca1fe55-294e-4faf-a22d-3ebc79d53b74/loyalty/w=3840,quality=90,fit=scale-down)

### Sales by Platforms & Channels

---

- Direct channels account for **83% of total sales** ($23M).
- Social media contributes **1%** of sales.
- Affiliate channels contribute **3%** ($878K) and have the **highest average order value (AOV)** at **$303**.
- Email campaigns have the **lowest AOV** at **$181**.
- The **website generates 97%** of sales ($27M) with an AOV of **$304**.
- The **mobile app lags**, generating only **$867K** in sales with an AOV of **$47**.

[](https://images.spr.so/cdn-cgi/imagedelivery/j42No7y-dcokJuNgXeA0ig/91528dec-f3d1-4a32-960a-aeab6f28d4d6/channel_platform/w=3840,quality=90,fit=scale-down)

![image.png](YOUKE%20TECH-%20CustomerBehaviorsAnalysis%2016b7a7a1452b80c5bc08e1473cfe0b47/image%201.png)

### Refund Rate Trends

---

- Refund rates for **high-ticket items** peaked early in the pandemic but have stabilized at **4-6%**.
- Refunds across all products **decreased in 2021** compared to the previous two years.
- Laptops had the **highest refund rates** in **2019 and 2020** (17%) but have since declined to **6-9%**, aligning with other categories.
- **Apple AirPods Headphones** have the **highest refund count** at **2.6K**, with a **5% refund rate**.
- Loyalty purchases exhibit a **higher refund rate** than non-loyalty purchases, potentially warranting **further investigation**.

[](https://images.spr.so/cdn-cgi/imagedelivery/j42No7y-dcokJuNgXeA0ig/521dcf08-947e-4669-bfc5-e31e4e9f35f6/loyalty_impact_refund/w=3840,quality=90,fit=scale-down)

## **Recommendations**

---

Maximizing Product Offerings

- **Expand High-Performing Categories**: Increase catalog variations in monitors, AirPods, and laptops to meet diverse customer needs with premium models, driving repeat purchases and solidifying market presence.
- **Optimize Samsung Cable Pack**: Reevaluate the Samsung Cable Pack's pricing strategy, bundle it with high-value items, or offer as a promotional gift to increase average order value (AOV) and revenue contribution.

Customer Growth and Retention

- **Boost Repeat Purchases**: Target single-purchase customers with personalized re-engagement campaigns and introduce tiered rewards within the loyalty program to incentivize frequent purchases and improve retention.
- **Revitalize Customer Acquisition**: Expand acquisition channels to include social media, influencer partnerships, and affiliate programs. Refine YOUKE's messaging to re-engage past customers and attract new ones.
- **Leverage Core Customer Insights**: Analyze behaviors and preferences of repeat customers to enhance loyalty campaigns. Introduce referral incentives to drive word-of-mouth growth and increase new customer acquisition from existing networks.

Loyalty Program Enhancements

- **Enhance Loyalty Onboarding**: Implement targeted onboarding campaigns with first-purchase discounts or early access offers. Tiered rewards will further incentivize frequent purchases and strengthen customer loyalty.
- **Data-Driven Program Refinement**: Continuously monitor loyalty metrics to refine program offerings based on data, ensuring sustained engagement and effectiveness.

Maintaining Low Refund Rates

- **Sustain Successful Practices**: Replicate effective strategies from 2021, including detailed product descriptions, stringent quality control, and robust post-purchase support, to maintain low refund rates and meet customer expectations.

Optimizing Channels and Platforms

- **Expand Affiliate Partnerships**: Increase affiliate partnerships or offer higher commissions to attract influential marketers, enhancing brand reach and boosting AOV.
- **Enhance Mobile App Experience**: Improve the mobile app's checkout and personalization features to capitalize on rising mobile usage and increase its contribution to total sales.

Regional Growth Strategies

- **Focus on High-Performing Regions**: Continue allocating resources to North America and EMEA with regionalized marketing and product availability strategies tailored to local preferences.
- **Target Growth in APAC and LATAM**: Leverage localized partnerships and culturally tailored promotions to capture growth potential in APAC and LATAM, stabilizing sales in these emerging markets.

[Back to Homepage](https://www.notion.so/About-Me-1697a7a1452b8054b4adfafec8c57cd8?pvs=21)