
**DASHBOARD SCREENSHOT**  
<img width="500" height="382" alt="image" src="https://github.com/user-attachments/assets/7f72b0d0-d2e3-4304-a5b9-a8db934929ee" />

**EXCEL FILE LINK:** shopping_behavior_Analysis_Excel_Dashboard.xlsx 

**OVERVIEW**:
An Excelbased analysis of shopping behavior and sales performance across U.S. regions in 2024, combining an at-a-glance executive dashboard with a deeper insights summary. The project segments revenue by category, region, payment method, season, customer demographics, and subscription status to identify what's driving and what isn't driving; order value and category performance.

**BUSINESS** **QUESTIONS**
- How do discounts, payment methods, seasonality, and customer demographics influence order value and category performance across U.S. regions?
- where should marketing and inventory focus be prioritized?

**KEY** **MATRICS**

| Metric | Value |
|---|---|
| Total Revenue | $233,081 |
| Transactions | 3,900 |
| Average Order Value | $59.76 |
| Average Customer Rating | 3.73 / 5 |
| Discounted Revenue | $99,411 (42.7% of total) |
| Undiscounted Revenue | $133,670 (57.3% of total) |
| Subscriber Revenue Share | 27% |
| Non-Subscriber Revenue Share | 73% |

**KEY** **INSIGHTS**
- **Category** **Performance:** Clothing generates the most revenue, followed by Accessories, Footwear and Outerwear; Generating respectively:$104,264 - $74,200 - $36,093 - $18,524.
- **Payment** **Behaviour:** PayPal and Credit Card are the leading payment methods; Bank Transfer sees the least use; generating a transaction count of respectively: 677 - 671 - 612. 
- **Seasonality:** Revenue is broadly balanced across the year, with Fall the strongest season and Summer noticeably softer
- **Subscription:** Non-subscribers generate nearly 3x the revenue of subscribers (73% vs. 27%),suggesting the business is still acquisition-heavy; Converting more repeat non-subscribers into subscribers looks like a meaningful level for recurring revenue growth.  
- **Gender:** Meles customers drive the large majority of revenue(68% vs 32% for female costumers). To Highlight that most of revenue is concentrated in the category males between age 18 until 67.

**What's** **Included:** This Project Presents two complementary Views of the same Dataset.
- **Executive** **Summary:** a KPI-card layout of regional map, category, payment methods, seasonality, age/gender, subscription status.
- **Insight** **Summary:** A denser analysis view pairing the same KPIs with written findings, category, payment, season, gender and breakdown tables.
  
**Data:** 
Source data - [shopping_behavior_raw.csv](shopping_behavior_raw.csv) - contains customer-level transaction records, including: Customer ID, Age, Gender, Item Purchased, Category, Purchase Amount, Location, Size, Color, Season, Review Rating, Subscription Status, Discount Applied, Promo Code Used, Previous Purchases, Payment Method, and Frequency of Purchases.
**Originally sourced from:** https://www.kaggle.com/datasets/iamsouravbanerjee/customer-shopping-trends-dataset

**Methodology**
- Cleaned and validated the raw dataset (duplicates, missing values, category/location standardization)
- Built summary tables segmenting revenue by category, payment method, season, age band, gender, and subscription status
- Calculated headline KPIs — total revenue, transactions, AOV, average rating, and discount split
- Designed two dashboard views: a visual KPI overview and a narrative insights summary; using (pivot tables and formulas)

**Tools Used:**  MICROSOFT EXCEL 



