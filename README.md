# User-Events-Funnel-Analysis

SQL funnel analysis project using BigQuery and Excel visualizations

# 1. Background and Overview

This project analyzes user behavior throughout an e-commerce sales funnel using SQL in Google BigQuery and dashboard visualizations in Microsoft Excel.

The objective of this analysis was to better understand how users move through the customer journey, identify where users drop off in the funnel, evaluate marketing channel performance, and uncover opportunities to improve conversion and revenue performance.

Focuses
  Funnel conversion analysis
  Traffic source performance
  User journey timing
  Revenue analysis
  Business recommendations based on data insights
Tools Used
  Google BigQuery
  SQL
  Microsoft Excel
  GitHub

# 2. Data Structure Overview

The dataset consists of user-level event tracking data from an e-commerce platform.
Each row represents a user event generated during the customer journey.

Main Columns
  Column Name  	Description
  user_id	  Unique identifier for each user
  event_type  	Type of event performed by the user
  event_date  	Timestamp of the event
  traffic_source  	Marketing source that brought the user
  amount	Purchase   revenue associated with purchase events

Analysis Period
December 2025 – February 2026

# 3. Executive Summary

The analysis revealed that the checkout process is highly efficient, with strong conversion rates from checkout initiation to final purchase. This suggests that the payment and checkout experience is functioning effectively with minimal friction.
However, the largest drop-off occurs earlier in the funnel between product browsing and cart additions, indicating opportunities to improve product engagement and purchase intent.
Traffic source analysis showed that social media generated the highest traffic volume but delivered the weakest conversion efficiency, suggesting that current social campaigns are attracting low-intent visitors rather than qualified buyers.
Revenue analysis found that the Average Order Value (AOV) was approximately $115, creating a strong benchmark for evaluating Customer Acquisition Cost (CAC) efficiency across marketing channels.

# 4. Insights Deep Dive

Funnel Conversion Analysis
The funnel analysis measured how users progressed through each stage of the customer journey.

<img width="449" height="283" alt="image" src="https://github.com/user-attachments/assets/b149cfd9-86a5-4061-ab5c-d451e8895897" />

Key findings:

Strong checkout-to-purchase conversion rates (~80%+)
Significant drop-off between page views and add-to-cart activity
Users who reached checkout were highly likely to complete purchases

Traffic Source Performance
Traffic source analysis compared conversion efficiency across marketing channels.
Key findings:
Social media drove the largest share of website traffic
Social traffic had the lowest conversion rate
Higher-intent channels such as email and organic traffic converted more efficiently
This suggests that traffic quantity does not necessarily translate into revenue quality.

User Journey Timing
Customer journey timing analysis measured:
Time from page view to add-to-cart
Time from cart to purchase
Overall purchase journey duration
This analysis provided insight into user buying behavior and purchasing speed.

Revenue Analysis
Revenue metrics included:
Total revenue
Total buyers
Average Order Value
Revenue per visitor
Revenue per buyer
Key finding:
Average Order Value was approximately $115, providing a useful benchmark for marketing profitability analysis.

# 5. Recommendations

UX & Website Optimization
•	Don’t Touch the Checkout Flow: The conversion rates from Checkout Start to Purchase are excellent (~80%+). This indicates the technical payment flow is frictionless.
o	Action: Do not redesign the checkout page right now; you risk breaking something that is working perfectly.

Marketing Strategy
•	Stop Overinvesting in Social for Sales: social media is driving ~30% of our traffic (Volume), but has the lowest conversion rate (Efficiency). We are likely paying for “window shoppers.” 
o	Action: Shift budget away from “Traffic” objectives on social ads and focus on “Retargeting or “Lead Gen” to capture emails instead

Financial & Revenue
•	Audit Ad Spend against AOV: We found our Average Order Value is ~$115.
o	Action: Set a strict Customer Acquisition Cost (CAC) limit. If we are paying more than $30-$40 to acquire a customer via Social Media ads (which convert poorly), we are likely losing money on those specific transactions.

