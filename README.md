# Real-Estate-Agency-Analysis

## 📌 Overview
This project contains a set of **interactive Power BI dashboards** designed to provide actionable insights into **property listings, client interactions, and sales performance** across major cities.  
The dashboards enable stakeholders to track **KPIs**, identify **top-performing locations**, understand **buyer behaviors**, and optimize **marketing and pricing strategies**.

## 🛠️ Tools & Technologies
- **Power BI** – Data modeling, visualization, and dashboard design.
- **DAX (Data Analysis Expressions)** – Custom measures, cloumns, tables and KPIs.
- **Excel / CSV** – Data storage and transformation.
- **Data Cleaning** – Power Query for preprocessing.

## 📝 Project Steps

### 1. **Data Exploration**
- Loaded property and sales data into Power BI.
- Reviewed dataset columns, values, and relationships.
- Checked for missing values, outliers, and inconsistent formats.

### 2. **Data Handling & Cleaning**
- Removed null and duplicate records.
- Changed data types (dates, numbers, text).
- Merged columns for better readability (e.g., first name & second name to full name).
- Applied filtering to remove irrelevant or incorrect entries.

### 3. **Data Modeling**
- Created relationships between property, sales, and client tables.
- Ensured referential integrity between all tables.

### 4. **Calculated Columns**
- Added calculated columns such as:
  - Purchase Status
    

### 5. **Measures & KPIs**
- Built DAX measures including:
  - Total Sales Count
  - Total Sales Value
  - Average Sale Price
  - Total Visits
  - Total Clients
  - Total Buyers
  - First Time Buyers
  - Repeat Buyers
  - Average Sale Price
  - visit to sale Conversion Rate
  - Client Based Conversion Rate
  - Most Common Property Type
  - Time On Market (Days)
  - Total Properties listed
  - Types of Property
  - Average price per sqm
  - Average Visit per sale

### 6. **Calculated Tables**
- Created summary tables for:
  - Client Journy Table As helper table
    

## 📊 Dashboards or Reports Included
**Page 1: Executive Overview**

**Key Insights**

1. Overall Market Performance
   -Total Listed Properties: 1,000
   
   -Total Visits: 5,000
   
   -Total Sales: 2,000
   
   -Conversion Rate: 40% (below target of 50%).
   
   -Average Sale Price: 769K.

3. City-Level Sales Value & Volume

   -Top by Sales Value: Miami (329.6M) and New York (335.2M).

   -Highest Property Count: New York (431), closely followed by Miami (423).

   -Smallest Market: Houston (374 properties), yet with a competitive sales value of 294.5M.

5. Yearly Sales Trend (Line Chart)

   -2023: 474M sales value.

   -2024: Sharp increase to 793M (peak year).

   -2025 YTD: Significant drop to 271M — possibly due to incomplete year data or a slowdown in market activity.

7. Conversion Rate Performance (Gauge Visual)

   -Current conversion rate is 0.40, 10 percentage points below the target (0.50).

   -Indicates room for improvement in turning visits into sales.

**Recommendations**

1. Boost Conversion Rates

   -Analyze lead-to-sale process by city to identify bottlenecks.

   -Increase follow-up efficiency with potential buyers through targeted campaigns.

2. Capitalize on High-Value Markets

   -Prioritize marketing in New York and Miami, which show both high property counts and high sales values.

   -In Houston, despite fewer properties, sales value per property is strong — explore expansion.

3. Investigate 2025 Drop

   -Determine if 2025 drop is due to seasonality, incomplete data, or reduced demand.

   -If slowdown is confirmed, adjust pricing or marketing strategies early.

4. Improve Visit Quality

   -Work on attracting more qualified leads rather than just increasing visits.

   -Focus ad spend on demographics with higher conversion likelihood.

**Screenshot**

<img width="873" height="490" alt="Report page 1 - Executive Overview" src="https://github.com/user-attachments/assets/678d26c1-e9be-4ac4-a785-b93cf4f3c8e2" />



**Page 2: Sales Analysis**

**Key Insights**

1. Overall Sales Performance

   -Total Sales Count: 2,000.

   -Total Sales Value: 2B.

   -Average Sale Price: 769K.

   -Conversion Rate: 40%.

   -Average Time on Market: 147 days — almost 5 months from first visit to sale, indicating a relatively long sales cycle.

3. Average Sale Price by Property Type

   -Highest: Warehouse (800.1K), followed by Office (777.72K).

   -Lowest: Apartment (750.74K).

   -Price variation across property types is not huge (~6% difference), suggesting market pricing is fairly stable.

5. Sales Value by Location & Property Type

   -New York: Strong performance in Apartments (81M) and Offices (79M).

   -Miami: Villas dominate with 95M sales, plus strong Apartment sales (89M).

   -Los Angeles: Balanced performance across all types, with Apartments (76M) and Warehouses (60M) leading.

   -Houston: Warehouses lead (70M) despite a smaller market size.

   -Chicago: Apartments lead (70M) with strong Retail (59M) and Villas (58M).

7. Sales Trends Over Time

   -Similar trend to Executive Overview: 2024 was the peak year.

   -Notable dips in some months — possibly tied to seasonal demand or economic conditions.

9. Agent Performance 

   -Certain agents significantly outperform others in both sales count and value.

   -High conversion rate agents could serve as benchmarks for training.

**Recommendations**

1. Reduce Time on Market

   -Investigate delays in property sales cycles — focus on process efficiency and faster closing strategies.

   -Consider adjusting pricing or offering limited-time incentives for properties sitting on the market longer than 120 days.

3. Leverage High-Performing Property Types

   -Promote Warehouses in Houston and Villas in Miami — these categories show exceptional value in their respective markets.

   -Target marketing campaigns by property type and city to maximize ROI.

5. Boost Apartment Sales Value

   -Apartments consistently sell well in volume but have lower average sale prices.

   -Explore premium apartment offerings or value-add upgrades to raise prices.

7. Agent Training & Best Practices

   -Identify top-performing agents (high conversion rate and sales value).

   -Share their sales techniques across the team to raise overall performance.

9. Seasonality Planning

   -If sales dips are seasonal, plan promotions or open-house events in low-demand months to smooth revenue fluctuations.

**Screenshots**

<img width="873" height="489" alt="Report page 2 - Sales Analysis" src="https://github.com/user-attachments/assets/4e1c54dc-2990-4920-b26a-c2d793471c93" />



**Page 3: Client Interaction**

**Key Insights**

1. Client Conversion Funnel

   -Total Clients: 1,500.

   -Clients Who Visited: 1,456 (~97% visit rate, indicating strong initial engagement).

   -Clients Who Purchased: 1,096 (~73% conversion rate from total clients, very high compared to industry averages).
   
3. Purchase Behavior

   -First-Time Buyers: 526 (48% of buyers).

   -Repeat Buyers: 570 (52% of buyers).

   -Balanced split between first-time and repeat purchases — strong repeat buyer percentage suggests solid customer satisfaction and loyalty.

5. Visit Frequency

   -Average Visits per Sale: 5 visits per buyer — shows a relatively long decision-making journey.

   -Top clients by visits:
        William Brown: 14 visits
        Laura Allen: 13 visits
        Michel Anderson: 12 visits
        John Diaz: 11 visits
        Alyssa Mendoza: 10 visits

   -These high-visit clients may indicate higher-value purchases or indecision before buying.

4. High-Value Repeat Clients

   -The table visual (not shown here) allows identification of clients with high visit frequency and high total sales value — ideal for VIP programs.
   
   
**Recommendations**

1. Shorten Decision Cycle

   -For clients averaging 8+ visits, introduce tailored offers or decision aids (virtual tours, personalized financing options) to reduce time from visit to purchase.

2. Leverage Repeat Buyers

   -Maintain engagement with repeat buyers through loyalty programs, exclusive previews, and targeted upsell opportunities.

3. Engage First-Time Buyers Post-Sale

   -Since nearly half of buyers are first-timers, set up automated post-sale follow-up to encourage them to return for future purchases or referrals.

4. Segment Client Outreach

   -Use slicers (Year, Quarter, Month, Location, Property Type) to segment clients for personalized marketing — e.g., promoting high-demand property types in each city.

5. Analyze Top-Visit Clients for Insights

   -Review why high-visit clients took longer to purchase — was it budget concerns, property mismatch, or process delays?

   -we use these insights to refine sales process and reduce visit count for future similar clients.  

**Screenshots**

<img width="874" height="493" alt="Report page 3- Client Interaction" src="https://github.com/user-attachments/assets/e8117d12-d516-4a3c-aa63-27865954f17e" />


**Page 4: Property Listing Insights**

**Key Insights**

1. Portfolio Overview

   -Total Listed Properties: 1,000.

   -Property Types: 5 (Villa, Office, Apartment, Warehouse, Retail).

   -Most Common Type: Apartment (215 listings).

   -Average Price per Sqm: $1,950.

2. Listings by Property Type

   -Top Three Property Types by Volume

      :Apartment – 215 listings, $1,980/sqm.

      :Villa – 208 listings, $1,860/sqm.

      :Retail – 195 listings, $1,990/sqm.

   -Highest Avg Price per Sqm: Warehouse – $2,080/sqm despite having fewer listings (192).

3. Geographical Pricing Trends

   -Highest Avg Price per Sqm: Chicago ($2,036/sqm).

   -Lowest Avg Price per Sqm: Miami ($1,901/sqm).

   -Balanced Listing Volume Across Cities: All cities have ~190–206 properties listed, suggesting a fairly even market coverage.

4. High-Value Locations

   -Chicago and Warehouse properties stand out as top performers in terms of price per sqm — potential premium segments.

   -Los Angeles and Houston have nearly identical average prices per sqm (~$1,950) but maintain high listing counts (198 each), making them strong competitive markets.

**Recommendations*

1. Capitalize on Premium Segments

   -Focus marketing efforts on Warehouse properties in Chicago, as both location and property type command above-average pricing.

   -Position these as premium investment opportunities.

2. Price Optimization for Miami

   -With an average of $1,901/sqm — lower than other cities — investigate whether the lower price is due to property quality, demand, or market saturation.

   -Consider targeted campaigns or property upgrades to increase pricing power.

3. Balance Inventory Mix

   -Apartments are the most common listing type, but high-price-per-sqm categories like Warehouses and Retail should be given more visibility to maximize revenue per sale.

4. Location-Specific Targeting

   -For Los Angeles and Houston, where pricing is similar and competitive, emphasize differentiators such as neighborhood amenities, nearby infrastructure projects, and lifestyle appeal.

5. Dynamic Filtering for Deeper Insights

   -Use slicers (Year, Quarter, Month, Location, Property Type, Price Range) to analyze seasonal or regional shifts in property demand and adjust marketing strategies accordingly.

**Screenshots**

<img width="874" height="492" alt="Report page 4- Property Listing Insights" src="https://github.com/user-attachments/assets/94f85a18-1723-48eb-b868-37d7a6733063" />



   



   
