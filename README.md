# MTN Q1 2025 CUSTOMER SEGMENTATION AND CHURN REPORT
---
# Project Overview 
Customer churn is one of the biggest concerns for telecom companies, especially in competitive markets like Nigeria. This dataset simulates the behavior, preferences, and churn patterns of MTN Nigeria customers in Q1 2025. It provides rich insight into device usage, data plan preferences, age groups, tenure, churn drivers, and revenue patterns.

### Objective 
- Understand overall churn behavior in Q1 2025.
- Segment customers by tenure, plan type, purchase frequency, revenue, and device.
- Identify key churn drivers across satisfaction rate, customer reviews, and demographics.
- Support MTN business stakeholders with actionable retention strategies.

### Data Sources
- MTN Nigeria eShop [https://shop.mtn.ng/] 
- All device types, data plan names, and pricing were taken directly from the official MTN eShop in Q1 2025.
- All customer records and usage patterns were synthetically generated for educational and analytical purposes with the assistance of ChatGPT (OpenAI).

### Tools 
Power BI: Power Query for cleaning, DAX Formula, Dashboard Creation

### Dashboard Breakdown & Key Insights

#### Overview Page

KPIs Displayed:
- Total Revenue: ₦199M
- Average Revenue Per User (ARPU): ₦204.67K
- Average Data Usage: 99.30 GB
- Average Satisfaction Rate: 2.95/5
- Overall Churn Rate: 29.16%
- State with the Highest Revenue: Plateau (9M)
-  State with the Lowest Revenue: Lagos (3M)
-  State with the highest Churn Rate: Adamawa (61.11%)

#### Insight:
- The churn rate of 29.16% is moderately high. While not alarming, it indicates that nearly 3 in 10 customers discontinued service.
- The average satisfaction rate being below 2.95 (neutral) suggests overall customer experience needs improvement.
- Average revenue per user of over ₦200K reflects high spending behavior among retained users, valuable for loyalty programs.

#### Revenue by MTN Device
Insight:
- 5G Broadband Router customers contributed the highest revenue (₦101M), followed by Broadband MiFi (₦48M) and 4G Router (₦37M).
- Despite 5G Router having the highest churn (as seen later), Mobile SIM Card generated the least revenue (₦13M), indicating lower value and possibly more prepaid/temporary users.

#### Total Revenue by Customer Tenure Category
Insight:
- Legacy and Very Loyal customers contributed a combined ₦126M over 60% of total revenue.
- New and Recent customers together generated only ₦18M, proving that longer tenure customers are significantly more valuable.


#### Churn Rate % by Tenure Category
Insight:
- Highest churn occurred among:
- Legacy Customers: 32.5%
- Established Customers: 32%
- Very Loyal Customers: 31.12%

- Surprisingly, New Customers had a lower churn rate (22.73%) than expected.
-  This shows that retention weakens over time, and long term users still leave likely due to unmet evolving expectations.


#### Churn Rate % by Device Type
Insight:
- Mobile SIM Card users had the highest churn (31.23%).
- 4G Routers followed with 30.09%.
- Broadband MiFi and 5G Routers had lower churn at 27.95% and 26.75%.

- Light, temporary use devices see more churn, while premium devices retain users better.


#### Churn Rate % by Purchase Frequency
Insight:
- Customers with low purchase frequency had the highest churn (32.22%).
- Those with very high frequency churned less (27.39%).
-High engagement = low churn. More active users are more loyal.


####  Churn Rate % by State
Insight: 
- Adamawa had the highest churn rate with over 61.11% churn rate
- While Ekiti State had the second highest churn rate.
- This might be because Network coverage is bad

#### Churn Rate % by Age Classification
Insight:
- Millennials have the highest churn (35.36%), followed by Gen Z (27.81%).
- Gen X and Boomers had lower churn (26.44% and 26.76%).
- Younger users are more volatile and quick to switch, likely due to price sensitivity or alternative options.


#### Churn Rate % by Gender
Insight:
- Female churn rate is higher (30.30%) than male (27.97%).
- May indicate gender specific expectations or plan preferences.

#### Churn Rate % by Customer Review
Insight:
- Shockingly, customers who gave Excellent reviews had the highest churn rate (33.13%).
- Poor reviews had the lowest churn (24.75%).
- This contradiction suggests customers may rate high before leaving, or their expectations change after review submission. It’s a red flag excellent reviews don’t guarantee loyalty.

#### Churn Rate % by Satisfaction Rate
Insight:
- Churn is highest at 5 star satisfaction, again, showing that average to high satisfaction is not a perfect churn predictor.
- The lowest churn (24.75%) occurred at 2 stars, which seems counterintuitive and should be investigated.


#### Revenue by Purchase Frequency
- Very High Frequency customers had:
- Highest revenue per user (₦300.9K),
- These users are high value, loyal, and data-hungry. They are key targets for upselling or loyalty programs.

#### Distinct Count Customer ID by Churn Reasons
Top reasons for churn include:
- Better offers from competitors (29)
- High call tariffs (26)
- Costly data plans (20)
- Poor network & fast data consumption (20 + 18)
- Poor customer service (18)
- Relocation (15)

- These are actionable insights, pricing and data value are major concerns.


#### Total Revenue by Month (Q1)
 Insight:
   Highest revenue was generated in the month of Feb with over (87M)
   While March remained as the lowest with over (49M)


#### Recommendations
- Retain High Value Customers (Legacy & Very Loyal)
- Launch exclusive plans or rewards to retain your most profitable users.
- Revamp Mobile SIM Card Experience
- Focus on improving experience for low spend, high churn SIM users through bundles or loyalty incentives.
- Engage Millennials & Gen Z with Targeted Offers
- Develop flexible, youth focused bundles. Use influencers, data sharing plans, or social media bundles.
- Recheck Review Collection Process
- Investigate why churn is high among “Excellent” reviewers possibly timing or misleading feedback flow.
- Create Plan Recommendations Based on Usage
- Suggest optimal plans to users with high usage to prevent dissatisfaction and churn.
- Expand in Low-Churn Regions
- Invest more in customer support and marketing in states with higher retention.
- Pricing Review
- Review call tariffs and data plan pricing against competitors.
- Launch Re-Engagement Campaigns
- Target users in the 3–12 month tenure segment with retention offers.

