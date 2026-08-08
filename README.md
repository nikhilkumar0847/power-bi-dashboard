📊 Blinkit Power BI Dashboard

Project Overview

The Blinkit Power BI Dashboard is an interactive business intelligence dashboard designed to analyze Blinkit's marketing performance and customer/order analytics.

The dashboard provides a visual overview of campaign performance, advertising metrics, customer engagement, order activity, customer feedback, and geographic distribution.

The report contains three pages:

-> Introduction
-> Marketing Analytics
-> Customer Analytics

---------------------------------

📑 Dashboard Pages

1. Introduction about the Project

The Introduction page provides an overview of the dashboard and navigation to the different analytical sections.

--------------

2. Marketing Analytics

The Marketing Analytics page focuses on understanding the performance of marketing campaigns and advertising channels.

Key Metrics

-> Clicks
-> Impressions
-> Conversions
-> Return on Ad Spend (ROAS)
-> Number of Campaigns

 Visualizations Used

-> Clustered Column Chart  

  Used to compare campaign-wise spend and revenue generated.

-> Donut Chart  
  
  Used to analyze **spending across different marketing channels**.

-> KPI Cards

  - Clicks
  - Impressions
  - Conversions
  - Return on Ad Spend
  - Number of Campaigns

-> Slicers / Filters

  - Date of Order
  - Date of Campaign
  - Order Total
  - Campaign Spend
  - Order Location
  - Campaign Channel
  - Campaign Name

These interactive filters allow users to analyze marketing performance based on different campaigns, dates, channels, locations, and spending ranges.

-----------------------------------

3. Customer Analytics

The Customer Analytics page focuses on customer orders, engagement, feedback, responses, and geographic distribution.

Key Metric

-> Total Number of Orders

Visualizations Used

-> Donut Chart

  Used to analyze Customer Engagement.

-> Bar Chart  
  
  Used to analyze Customer Responses.

-> Map Visualization
    
  Used to visualize the **geographic distribution of customers/orders.

-> Word Cloud  
  
  Used to represent customer feedback and identify frequently occurring terms.

-> KPI Card
  
  - Total Number of Orders

-> Slicers / Filters

  - Order Location
  - Date of Order
  - Order Total
  - Payment Method
  - Categories

These filters allow users to explore customer and order information interactively.

-----------

🗂️ Data Tables and their values

The dashboard is built using 7 data tables from the source dataset.

1. BLINKIT_BRAND_DETAILS

Contains product and brand-related information such as:

- Product ID
- Product Name
- Category
- Brand
- Price
- MRP
- Margin Percentage
- Shelf Life
- Minimum Stock Level
- Maximum Stock Level

2. BLINKIT_DELIVERY_STATUS

Contains order delivery and transaction information including:

- Order ID
- Customer ID
- Order Date
- Promised Delivery Time
- Actual Delivery Time
- Delivery Status
- Order Total
- Payment Method
- Delivery Partner ID
- Store ID

3. BLINKIT_QUANTITY_DETAILS

Contains order-level product quantity information:

- Order ID
- Product ID
- Quantity
- Unit Price

4. `BLINKIT_FESTIVE_OFFER

Contains marketing campaign and advertising performance information:

- Campaign ID
- Campaign Name
- Date
- Target Audience
- Channel
- Impressions
- Clicks
- Conversions
- Spend
- Revenue Generated
- ROAS

5. BLINKIT_ORDER_DETAILS

Contains customer feedback and review information:

- Feedback ID
- Order ID
- Customer ID
- Rating
- Feedback Text
- Feedback Category
- Sentiment
- Feedback Date

6. BLINKIT_CUSTOMER_DATA

Contains customer-related information including:

- Customer ID
- Customer Name
- Email
- Phone
- Address
- Area
- Pincode
- Registration Date
- Customer Segment
- Total Orders
- Average Order Value

7. BLINKIT_DATE_DATA

Contains inventory-related date information:

- Product ID
- Date
- Stock Received
- Damaged Stock

-----------------------------

📈 Dashboard Summary

| Dashboard Page | Main Focus | Major Visualizations |

|-----------------|-----------|----------------------|

| Introduction | Dashboard overview | Navigation / introductory elements |

| Marketing Analytics | Campaign & advertising performance | Column Chart, Donut Chart, KPI Cards, Slicers |

| Customer Analytics | Orders & customer engagement | Donut Chart, Bar Chart, Map, Word Cloud, KPI Card, Slicers |

----------------------------------

🛠️ Tools Used

-> Microsoft Power BI
-> Power Query
-> DAX
-> Microsoft Excel

-----------------------------------

📊 Project Highlights

About the project

* Interactive marketing performance analysis
* Campaign-level spend and revenue comparison
* Advertising channel analysis
* Click, impression and conversion tracking
* ROAS analysis
* Customer engagement analysis
* Customer feedback analysis
* Geographic customer analysis
* Interactive filtering using slicers
* Customer feedback visualization using Word Cloud
