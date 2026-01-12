# Term Deposit Telephonic Marketing Campaign Analysis

![Marketing_dashboard](https://github.com/user-attachments/assets/69345d05-3ac8-4f1a-86b0-36a41bc13df4)

## Project Background
Term deposits are a major source of income for banks, offering customers fixed-term investments with guaranteed returns. To promote term deposits, banks employ multiple outreach strategies, including email, advertising, digital marketing, and telephonic campaigns. While telephonic marketing remains one of the most effective channels, it is also costly due to the need for large call centers. This project focuses on analyzing **three years of telephonic marketing data (50,000 records)** to identify customer segments most likely to convert, enabling more targeted and cost-effective campaigns.

---

## Data Structure & Initial Checks
The dataset contains customer demographics, banking profile, campaign interaction details, and conversion outcomes across three years. Key fields include age, job, marital status, education, account balance, loan status, contact channel, contact timing, call duration, contact frequency, previous campaign history, and subscription outcome. Initial checks involved cleaning missing values, standardizing categorical variables, validating numeric ranges, and ensuring consistency across all records.

---

## Executive Summary
Analysis of telephonic marketing campaigns reveals clear patterns in term deposit conversions. Customers aged **25–34**, with **€0–5,000 account balances**, working in **management roles**, **married**, and with **secondary education** are the most likely to subscribe. Conversions are highest among **newly contacted clients** or those contacted fewer than **21 times**, while customers who previously declined rarely convert upon recontact. Clients without other banking products (car or housing loans) show stronger uptake. **May** records the highest number of successful deposits, while **March** achieves the highest conversion rate. **Cellular calls** consistently outperform other contact methods.

---

## Insights Deep Dive
- **Demographics:** Younger working professionals (25–34) dominate successful conversions.  
- **Contact Frequency:** Increased contact volume shows diminishing returns and lower conversion rates.  
- **Customer History:** Prior non-conversion is a strong indicator of future non-conversion.  
- **Product Portfolio:** Customers without existing loan products are more receptive to term deposits.  
- **Seasonality:** Campaign effectiveness varies by month, with notable peaks in March and May.  
- **Channel Performance:** Cellular outreach is the most effective communication channel.

---

## Recommendations
- Prioritize **new leads and lightly contacted clients** for telephonic campaigns.  
- Focus targeting on **high-conversion demographics** to maximize ROI.  
- Limit repeated calls to previously non-converting customers to reduce costs.  
- Emphasize **cellular contact** as the primary outreach method.  
- Align major campaigns with **high-performing months** such as March and May.

---

## Assumptions & Caveats
- Analysis assumes data accuracy and consistent campaign execution across the three-year period.  
- Results are based on historical behavior and may not fully reflect future market or economic changes.  
- External factors (interest rates, economic conditions, competing products) were not included in the analysis.  
- Findings are most applicable to telephonic marketing and may not generalize to other channels.
