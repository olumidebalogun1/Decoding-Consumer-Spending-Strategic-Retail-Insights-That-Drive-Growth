# Decoding Consumer Spending: Strategic Retail Insights That Drive Growth

<br>

## Project Background
In today’s fast-evolving and hyper-competitive retail environment, visibility into customer behavior, product performance, and revenue trends is no longer optional, it’s mission-critical for growth, agility, and market leadership.

This **Sales Analytics Project** was initiated in response to a real-world business challenge faced by Chris & Kris, a leading U.S. e-commerce company seeking to transform its sales data into smarter **marketing strategies and inventory decisions**. The objective? To go beyond hindsight reporting and deliver **forward-looking intelligence** that accelerates decision-making and drives profitability.

To meet this need, the project applied **end-to-end, data-driven analytics** to monthly sales transactions from **January to December 2024**, leveraging **Exploratory Data Analysis (EDA)** alongside **advanced machine learning techniques** like **Prophet for time-series forecasting, Market Basket Analysis**, and **KMeans clustering** to uncover patterns, predict trends, and drive smarter business decisions.

This hybrid approach not only provided a historical lens into business performance but also unlocked **predictive and prescriptive insights**, explaining why performance shifts occur and what to do next.

From identifying peak purchase hours and high-performing product categories to forecasting future demand surges and crafting bundled selling strategies, this project transformed raw data into an intelligent, action-ready analytics framework.

The result? A scalable, insight-powered roadmap that enables Chris & Kris to:

-	**Forecast with confidence**

-	**Market smarter**

-	**Align inventory with real demand**

-	**Maximize customer lifetime value**

-	**Drive sustainable revenue growth with precision**

This isn’t just analytics, it’s **decision intelligence** in action. Powered by**Python**. Guided by **insight**. Built for **impact**.

### 🔗 **Read the complete report – [Decoding Consumer Spending: Retail Insights That Drive Growth](https://github.com/olumidebalogun1/Decoding-Consumer-Spending-Strategic-Retail-Insights-That-Drive-Growth/tree/main/5.%20Final_Report)**

<br>
 
## Goal of this Project
The primary objective of this project is to **transform raw sales data** into actionable **business insights** that **fuel strategic, data-driven decision-making**. In an environment shaped by rising market complexities and evolving consumer expectations, it is no longer sufficient for businesses to merely understand historical performance, they must anticipate future trends and proactively prescribe optimal actions.

**This project aims to**:
- Uncover hidden sales patterns and identify untapped growth opportunities.
  
- Identify top-performing products and high-revenue cities driving business success.
  
- Analyze customer purchasing behavior to optimize the timing and targeting of marketing efforts.
  
- Forecast future sales trends to inform inventory management, budgeting, and strategic planning.
  
- Recommend targeted business strategies using customer segmentation and association rule insights.

**In simple terms**: this project empowers stakeholders with the intelligence they need to make faster, smarter, and more strategic decisions, ultimately improving sales performance, streamlining operations, enhancing customer engagement, and driving profitability in a competitive landscape.

<br>

## Business Challenge
Chris & Kris faces several operational and strategic challenges that hinder its ability to optimize performance:

-	**Limited visibility into which products or markets truly drive revenue**

-	**Lack of clarity on sales performance trends** at monthly or weekly levels

-	**Inability to leverage customer purchasing behaviors and timing** to plan effective marketing campaigns

-	**Reactive sales forecasting**, leading to missed opportunities and inefficient planning

-	**Underutilization of bundling and targeted promotions** to increase average transaction value

Without resolving these issues, the company risks:

-	Inefficient marketing spend

-	Inventory imbalances (overstock or stockouts)

-	Missed opportunities for growth and profit optimization

This project is designed to directly address these gaps and turn them into competitive advantages.

<br>

## **Key Business Questions**
This project aims to answer the following key questions:

1. Which month achieved the highest total sales, and what was the total sales figure recorded during that period?

2. What is the percentage growth in total monthly sales over time, and how does it vary across different months?

3. Which city achieved the highest total sales, and what was the total sales amount for that city?

4. Which product had the highest sales, and what factors do you believe contributed to its success? 

5. How do product sales vary across different days of the week, and what insights can be drawn from the distribution of order volumes by product and day?

6. On which day of the week do customers make the most purchases?

7. What is the optimal timing for advertisements and promotions to maximize customer purchases, based on historical purchase behavior?

8. What will our monthly sales look like over the next two years based on historical purchasing patterns?

9. What products are frequently bought together?

10. How can we group cities based on sales performance to uncover patterns for better sales strategy?

<br>

## Data Structure Overview 
The dataset utilized for this project is a comprehensive **monthly sales dataset spanning January 2024 to December 2024**. The original dataset consists of **172,531 transaction records** across **six well-structured columns**, capturing key sales metrics.

Following the **ETL (Extract, Transform, Load)** process, the data was **cleaned, enriched, and transformed** to enhance analytical depth and usability. The resulting transformed dataset comprises **171,780 refined records** across **thirteen structured columns**, integrating additional features such as time-based attributes, derived KPIs, and categorical groupings to support deeper insights and machine learning applications.

![Screenshot 2025-05-21 132048](https://github.com/user-attachments/assets/7ffc585d-ab60-485e-8f45-e5dfa5c9dd3f)

### 🔗 **Access the dataset [here](https://github.com/olumidebalogun1/Decoding-Consumer-Spending-Strategic-Retail-Insights-That-Drive-Growth/tree/main/1.%20Montly_Sales%20%20Data)**

<br>

## **Tools & Technologies Used**
For my deep dive into the company's sales outlook, I utilized the following tools and technologies:

#### 1. Python: 
The foundation of my analysis, enabling efficient data manipulation and insight extraction. Key libraries included:
   
-	**Pandas** for data cleaning and analysis
  
-	**Matplotlib** for basic data visualizations

-	**Seaborn** for enhanced and detailed plotting

#### 2. Machine Learning: 
To uncover patterns and make predictive insights, I incorporated:

-	**scikit-learn** for model development and evaluation

-	**XGBoost** for high-performance gradient boosting

-	**Prophet** for time series forecasting

#### 3. Jupyter Notebooks: 
Provided an interactive coding environment, allowing for seamless integration of code, analysis, and documentation.

#### 4.  Git & GitHub: 
Used for version control, code management, and collaboration, ensuring transparency and reproducibility throughout the project.

<br>

## **Methodology**
#### **Phase I: EDA – Descriptive & Diagnostic Analysis**

- **Data Cleaning & Preprocessing**: Removing duplicates, handling missing values, creating more columns, and formatting variables

- **Monthly Sales Analysis**: Identified the highest-grossing months and overall trends.

- **City-Level Analysis**: Mapped sales performance geographically.

- **Product & Weekly Trends**: Uncovered product demand patterns by weekday.

- **Insights Visualization**: Created clear visuals (bar charts, heatmaps) for storytelling.

#### **Phase II: Machine Learning – Predictive & Prescriptive Models**

- **Time Series Analysis**: Determined optimal times for promotions and customer engagement.

- **Sales Forecasting**: Used Prophet models to predict future sales.

- **Market Basket Analysis**: Revealed frequent product pairings using Apriori algorithm or any other analysis.

- **Clustering**: Applied KMeans to segment cities for targeted sales strategies.

This phased approach ensures a solid foundation of insight (what and why) followed by predictive and strategic guidance (what’s next and how to act).

<br> 

## **Performed ETL (Extract, Transform, and Load)**
This section outlines the ETL process used to prepare the data for analysis. It involves:

-  **Extracting** raw datasets from monthly sales dataset spanning January 2024 to December 2024

- **Transforming** the data by merging sources, correcting data types, handling missing values, removing duplicates to ensure consistency and accuracy, changing the data type to optimize memory usage, expanding the dataset with supplementary columns, organizing oata by Order date chronologically and reindexing, and formating float datatype to ensure consistency and accuracy. 

-  And finally, **Loading** the cleaned and structured data into the analysis environment for further **exploration and modelling**.

### **🔗 [Explore the full ETL script](https://github.com/olumidebalogun1/Decoding-Consumer-Spending-Strategic-Retail-Insights-That-Drive-Growth/blob/main/ETL_Process.ipynb)**

<br><br>

# The Analysis

This end-to-end, Python-powered analytics project harnesses the full potential of data science to solve real-world retail challenges faced by Chris & Kris, a U.S. e-commerce brand. It blends **Exploratory Data Analysis (EDA), Time Series Forecasting, Market Basket Analysis**, and **Clustering** to uncover what’s happening, why it’s happening, and how the business can act on it.

Every technique, be it **Prophet** for forecasting or **KMeans** for segmentation, was carefully chosen to do more than just crunch numbers. It was about converting complexity into clarity, surfacing hidden patterns, and engineering intelligent, scalable strategies that unlock growth, enhance efficiency, and future-proof business decisions.

This is more than just analytics, **it’s analytics with purpose, precision, and measurable business impact**. It’s a blueprint for smarter decisions, operational efficiency, and sustainable growth.

---
## Executive Summary – Overview of Findings
#### 1. Sales & Performance Trends
-	**December** delivered peak revenue of **$6.41M**, while **February** saw a dramatic **73.39% drop**, revealing demand seasonality and planning gaps.

-	Sales volatility is evident throughout the year, with a**+226.47% growth spike in November**, driven by seasonal campaigns.

#### 2. Product & Consumer Behavior
-	**AAA Batteries, Charging Cables, and Galaxy Buds** are top sellers—proving that **accessories drive volume**, not high-ticket electronics.

-	**Tuesday is the busiest shopping day**, with customer activity peaking between **11 AM–1 PM** and **6 PM–8 PM**.

-	Customers frequently buy in bundles, e.g., Google Phone and USB-C Charging Cable (**473 times**), highlighting **strong cross-sell opportunities**.

#### 3. Regional & Market Insights
   -	**San Francisco, LA, and NYC** dominate sales; San Francisco alone contributes **$9.4M**.

-	Underperforming cities like **Portland (ME)** and **Austin** offer potential with localized strategies and pricing adjustments.

-	**Cluster analysis** revealed 3 market tiers, helping tailor region-specific strategies.

#### 4. Forecasting & Predictive Insights
-	**Prophet model** forecasts continued upward trends in Q4, but **volatility is expected in early 2025**.

-	Even conservative forecasts project **baseline monthly sales > $1M**, supporting stable budgeting.

-	**Time-based marketing** aligned with peak behavior hours can significantly boost campaign ROI.
<br>

### Key Strategic Takeaways & Recommendations
**What Should the Business Do Next?**

1. **Scale Q4 Playbook**: Replicate high-performance strategies from Nov–Dec across other months to normalize growth.

2. **Create Bundles & Cross-Sell**: Leverage top product pairings to increase Average Order Value (AOV) and improve purchase experience.

3. **Boost Inventory Agility**: Align stock planning with forecast peaks and regional patterns to minimize overstock and stockouts.

4. **Target High-Impact Hours**: Concentrate ad spend between **11 AM–1 PM** and **6 PM–8 PM**, and launch promotions on Tuesdays.

5. **Optimize Low-Tier Markets**: Use clustering insights to drive tailored campaigns and reassess investment in low-performing cities.

6. **Diversify Beyond Top Markets**: Reduce over-reliance on San Francisco & LA by nurturing growth in underutilized regions.
<br>

### Business Impact (Expected Outcomes)
1. **Revenue Growth**: Uplift of **15–20%** by optimizing seasonality, product mix, and bundling strategy.

2. **Profitability**: **8–12% boost in profit margins** through better pricing and cost control strategies.

3. **Operational Efficiency**: **25–30% increase in forecast accuracy**, leading to smarter inventory and resource planning.

4. **Market Expansion**: **10–14% increase in regional penetration** through localized promotions in underperforming clusters.

5. **Sales Optimization**: **12–15% lift in cross-sell/upsell conversions** using insights from market basket analysis.
---
## 📁 More Resources - Codes & Other Resources

- **🔗 [ETL Code](https://github.com/olumidebalogun1/Decoding-Consumer-Spending-Strategic-Retail-Insights-That-Drive-Growth/blob/main/ETL_Process.ipynb)** - Extract, transform, and load operations for raw data.
  
- **🔗 [Monthly Sales Performance Trends](https://github.com/olumidebalogun1/Decoding-Consumer-Spending-Strategic-Retail-Insights-That-Drive-Growth/blob/main/1.%20Monthly%20Sales%20Performance%20Trends.ipynb)** - Monthly Sales Performance 

- **🔗 [Monthly Sales Growth Analysis](https://github.com/olumidebalogun1/Decoding-Consumer-Spending-Strategic-Retail-Insights-That-Drive-Growth/blob/main/2.%20Monthly%20Sales%20Growth%20Analysis.ipynb)** - Unveiling the Momentum

- **🔗 [Geographic Sales Performance Analysis](https://github.com/olumidebalogun1/Decoding-Consumer-Spending-Strategic-Retail-Insights-That-Drive-Growth/blob/main/3.%20Geographic%20Sales%20Performance%20Analysis.ipynb)** - Understanding the Sales Landscape

- **🔗 [Product Sales Analysis](https://github.com/olumidebalogun1/Decoding-Consumer-Spending-Strategic-Retail-Insights-That-Drive-Growth/blob/main/4.%20Product%20Sales%20Analysis.ipynb)** - Spotlight on Performance

- **🔗 [Product Sales Performance Analysis](https://github.com/olumidebalogun1/Decoding-Consumer-Spending-Strategic-Retail-Insights-That-Drive-Growth/blob/main/5.%20Product%20Sales%20Performance%20Analysis.ipynb)** - Who's Winning the Market?

- **🔗 [Weekly Purchase Trends Analysis](https://github.com/olumidebalogun1/Decoding-Consumer-Spending-Strategic-Retail-Insights-That-Drive-Growth/blob/main/6.%20Weekly%20Purchase%20Trends%20Analysis.ipynb)** - How Buying Behavior Changes Across Days

- **🔗 [Time Series Analysis]( https://github.com/olumidebalogun1/Decoding-Consumer-Spending-Strategic-Retail-Insights-That-Drive-Growth/blob/main/7.%20Time%20Series%20Analysis%20(Customer%20Behavior%20Timing).ipynb)** - Uncovering Customer Purchase Patterns Over Time

- **🔗 [Sales Forecasting](https://github.com/olumidebalogun1/Decoding-Consumer-Spending-Strategic-Retail-Insights-That-Drive-Growth/blob/main/8.%20Sales%20Forecasting%20with%20the%20Prophet%20Model.ipynb)** - Using Prophet forecasting model to predict monthly sales trends

- **🔗 [Customer Purchase Insights](https://github.com/olumidebalogun1/Decoding-Consumer-Spending-Strategic-Retail-Insights-That-Drive-Growth/blob/main/9.%20Market%20Basket%20Analysis%20(Customer%20Purchase%20Behavior).ipynb)** - To uncover product combinations that are frequently purchased together

- **🔗 [City Segmentation](https://github.com/olumidebalogun1/Decoding-Consumer-Spending-Strategic-Retail-Insights-That-Drive-Growth/blob/main/10.%20Clustering%20Cities%20Using%20the%20KMeans%20Model.ipynb)** - Clustering Cities by Sales Performance Using KMeans

<br><br>

# **1. Monthly Sales Performance Trends**

## Business Question
Which month achieved the highest total sales, and what was the total sales figure recorded during that period?
<br>

![1  Monthly Sales Performance Trends](https://github.com/user-attachments/assets/5b02f097-fb34-4115-85ba-23e7474ae986)
<br>

## Key Trends & Insights
-	**December leads in revenue** with **$6.41M**, making it the most profitable month of the year.

-	**November follows closely** at **$5.75M**, confirming a strong year-end sales surge driven by seasonal demand.

-	**February underperforms significantly**, with the lowest sales at **$1.24M**, suggesting a critical drop post-holiday.

-	**Sales begin rising from June**, pointing to a gradual buildup toward the end-of-year peak.
<br>

## Strategic Recommendations
-	**Double down on Q4 momentum**: Scale up **marketing, promotions, and inventory** for **November–December**, leveraging seasonal high demand.

-	**Start early with Q3 campaigns** (July–September): Launch pre-holiday promotions to **build anticipation and drive early conversions**.

-	**Diagnose February’s slump**: Investigate root causes, like **post-holiday fatigue or reduced consumer spending**, and introduce **targeted deals or loyalty perks**.

-	**Forecast with seasonality in mind**: Align **production, staffing, and budgets** to mirror sales cycles, maximizing efficiency and profitability.

<br><br>

# **2. Monthly Sales Growth Analysis**

## Business Question
What is the percentage growth in total monthly sales over time, and how does it vary across different months?
<br>

![2  Monthly Sales Growth Analysis](https://github.com/user-attachments/assets/668364cf-2ea6-4da2-901e-09b45f66e417)
<br>

## Key Trends & Insights
-	**Sales Volatility Noted Throughout the Year**: Monthly growth swings ranged from steep drops like **-73.39% (Feb)** and **-25.77% (Oct)** to explosive increases like **+226.47% (Nov)** and **+91.01% (Mar)**.

-	**November and December Dominated Sales**: November posted the **highest growth rate (+226.47%)**, while **December hit the revenue peak at $6.41M**.

-	**Strong Year-End Momentum**: Despite mid-year slumps, **Nov–Dec sales rebounded strongly**, surpassing all prior months in both **growth and absolute revenue**.

-	**Early-Year Dip Raises Concern**: February’s drastic **-73.39% drop** from January signals potential disruptions worth deeper investigation.
<br>

##  Strategic Recommendations
-	**Diagnose Decline Periods**: Deep-dive into **February, September, and October** to identify root causes of sales dips and mitigate future risks.

-	**Maximize High-Performance Months**: Leverage **November and December's +226.47% and $6.41M sales** by expanding festive offers and targeted promotions.

-	**Revive Mid-Year Sales**: Implement **May–September engagement strategies** like loyalty programs, product updates, or localized ads to stabilize growth.

-	**Plan Proactively with Forecasting**: Develop **predictive models** using past trends to anticipate low months and align **inventory, staffing, and marketing** accordingly.

<br><br>

# **3. Geographic Sales Performance Analysis**

## Business Question
Which city achieved the highest total sales, and what was the total sales amount for that city?
<br>

![3  Geographic Sales Analysis](https://github.com/user-attachments/assets/a1e5c69e-2499-4b4d-bc85-abc8fb5b6afa)
<br>

## Key Trends & Insights
-	**San Francisco dominates** with **$9.40M** in total sales, over **17x higher than Portland (ME)**, the lowest at **$543K**.

-	**Los Angeles ($6.35M)** and **New York City ($5.21M)** solidify California and New York as top revenue hubs.

-	A **clear performance gap exists** between leading cities and mid-tier markets like Austin, Portland (OR), and Seattle, highlighting untapped growth potential.
<br>

 ## Strategic Recommendations
-	**Prioritize top performers**: Amplify marketing and promotional efforts in **San Francisco, LA, and NYC** to drive even higher ROI.

-	**Boost low-tier city performance**: Roll out **localized campaigns and pricing strategies** in underperforming markets like **Portland (ME) and Austin (TX)**.

-	**Leverage regional insights**: Use **monthly sales trends and customer segmentation** to tailor offers by city and forecast demand more precisely.

<br><br>

# **4. Product Sales Analysis: Spotlight on Performance**

## Business Question
Which product had the highest sales, and what factors do you believe contributed to its success? 
<br>

![4  Product Sales Analysis](https://github.com/user-attachments/assets/e6d76321-5bd5-4ccf-b116-3ae33f09287c)
<br>

## Key Trends & Insights
-	**AAA Batteries (4-pack)** top the chart with **23,993 units sold**, outperforming high-value items like the **iPhone (4x less)** and **MacBook Pro (5.5x less)**.
  
-	**Top 5 products** are all **low-cost, high-demand accessories**,  no phones or laptops made the list.

-	**Galaxy Buds lead headphone sales**, outselling Apple AirPods and Bose SoundSport, showing **strong brand preference or better price-value**.

-	**Large appliances underperform**, with **Amana dryers and washers at the bottom**, suggesting **price resistance or low purchase frequency**.
<br>

## Strategic Recommendations
-	**Boost top-selling accessories**: Expand visibility and bundling opportunities for **batteries, cables, and headphones** to drive volume and upsell.

-	**Cross-sell with high-volume items**: Leverage top sellers like **AAA/AA batteries** to suggest **complementary products** at checkout.

-	**Push mid-tier audio gear**: Promote **Galaxy Buds and AirPods** more aggressively with **discounts or bundles**, while nudging premium brands like Bose with financing options.

-	**Revamp appliance and high-ticket marketing**: Audit **sales channels, pricing strategies, and promotional visibility** for underperforming items like **phones, laptops, and appliances**.

<br><br>

# **5. Product Sales Performance Analysis: Who's Winning the Market?**

## Business Question
How do product sales vary across different days of the week, and what insights can be drawn from the distribution of order volumes by product and day?
<br>

![5  Product Sales Performance Analysis](https://github.com/user-attachments/assets/9149a0ca-6f84-4b3f-984e-f26e88ae46e9)
<br>

## Key Trends & Insights
-	**Everyday essentials stay strong all week**: Products like **AAA/AA Batteries, Charging Cables, and Galaxy Buds** maintain **high, consistent daily sales**, making them reliable revenue drivers.

-	**Weekend spikes for audio and entertainment**: **Headphones and Flatscreen TVs** see a **notable weekend lift** (e.g., Dell Monitor sales jump from **604 to 898** on Sunday).

-	**Laptops and monitors peak early-week**: Sales of **Alienware and LG UltraGear** are strongest on **Mondays and Tuesdays**, likely reflecting **work-related purchases**.

-	**Appliances underperform but show Monday bumps**: Though low in volume, **Amana dryers and washers** gain slight traction on **Mondays**.
<br>

## Strategic Recommendations
-	**Stabilize stock for top movers**: Keep **charging cables, batteries, and Galaxy Buds** consistently stocked all week; set up **automated reordering** to avoid out-of-stock issues.

-	**Time promotions by consumer behavior**: Run **headphone and gadget ads on weekends**, and offer **Monday deals for laptops and monitors** to tap into productivity-driven buyers.

-	**Revamp strategy for low-performing appliances**: Introduce **bundles or flexible financing**, especially with **Monday visibility**, to improve conversion.

-	**Sync marketing with purchase peaks**: Target **weekend email blasts** toward **entertainment and audio gear**, and focus **midweek promotions** on accessories and productivity tech.

<br><br>

# **6. Weekly Purchase Trends Analysis**

## Business Question
On which day of the week do customers make the most purchases?
<br>

![6  Weekly Purchase Trends Analysis](https://github.com/user-attachments/assets/c7394788-972e-4059-b137-31b24b00bb0d)
<br>

## Key Insights
-	**Tuesday** is the peak day for customer purchases, bringing in the highest total sales of **$5.75M**.

-	**Friday** and **Sunday** closely follow as strong performers, with sales of **$5.70M** and **$5.66M**, respectively.

-	**Thursday** records the **lowest sales** of the week at **$5.41M**, suggesting it’s the least active day for purchases.

-	Overall, **weekday performance** is fairly balanced, with a slight edge on early and late-week days (Tue & Fri).

-	**Weekends** (Sat & Sun) remain strong, especially Sunday with **$5.66M**, which may reflect increased leisure-time shopping behavior
<br>

## Strategic Recommendations
-	**Leverage Tuesday as a peak opportunity day**: Launch new products, promotions, or campaigns on Tuesdays to capitalize on high customer engagement.

-	**Boost Thursday performance**: Introduce limited-time deals or loyalty incentives to draw traffic and increase conversions on this underperforming day.

-	**Optimize operations on high-volume days**: Ensure sufficient staffing, stock availability, and support coverage on Tuesday, Friday, and Sunday.

-	**Consider a midweek marketing strategy**: Use Wednesday and Thursday to engage inactive customers with personalized offers to smooth weekly revenue peaks.

-	**Data-Driven Scheduling**: Use this trend insight to inform marketing schedules, delivery logistics, and customer support planning.

<br><br>

# **7. Time Series Analysis: Uncovering Customer Purchase Patterns Over Time**
## Business Question
What is the optimal timing for advertisements and promotions to maximize customer purchases, based on historical purchase behavior?
<br>

![7  Time Series Analysis](https://github.com/user-attachments/assets/c08963be-d8d0-4520-af15-058a9d771df4)
<br>

## Key Insights
-	Customer activity follows a clear daily rhythm, **starting low** in the early morning, **building momentum** mid-morning, **peaking**in the afternoon and early evening, and tapering off gradually at night.

-	Consistently high customer activity is observed between **11:00 AM and 8:00 PM**, with the most significant spikes from:
  
- **11:00 AM to 1:00 PM** (Peak hours: 11 AM – 11,393; 12 PM – 11,594; 1 PM – 11,207)

- **6:00 PM to 8:00 PM** (Evening peak: 6 PM – 11,146; 7 PM – 11,757; 8 PM – 11,507)

-	**Low engagement** periods are between **2:00 AM and 5:00 AM**, where customer activity is minimal.
<br>

## Strategic Recommendations
To maximize conversions and get the most out of your ad spend:

#### Targeted Promotions Strategy
-	Run high-budget, high-impact campaigns between 11:00 AM and 1:00 PM, when purchase intent is at its peak.

-	Complement with reminder or follow-up ads in the evening (6:00 PM – 8:00 PM) when users have more downtime.

-	Use lighter awareness-based campaigns in the morning (9:00 AM – 11:00 AM) to set the stage for peak time conversions.

#### Scheduling Tactics
-	Segment marketing messages by hour: Informational in the morning, persuasive in the afternoon, urgency-based in the evening.

<br><br>

# **8. Sales Forecasting with the Prophet Model**

## Business Question
What will our monthly sales look like over the next two years based on historical purchasing patterns?
<br>

![8  Sales Forecasting with the Prophet Model](https://github.com/user-attachments/assets/c3a6327a-7a8f-4ff5-9961-7c17e175b673)
<br>

## Key Trends & Insights
-	**Sales Momentum is Strong**: Forecasts reveal a steady upward sales trend with approximately **$50K average monthly growth**, signaling healthy business expansion.

-	**Peak Season Alert**: Significant sales surges are projected around **November–December**, likely driven by holiday demand and promotional campaigns.

-	**Volatility in Early 2025**: Wider confidence intervals in **Feb–Apr 2025** suggest short-term uncertainty, an early signal to stay agile.

-	**Reliable Safety Net**: Even in conservative scenarios, **monthly sales stay above $1M**, offering a solid baseline for budgeting and inventory planning.

-	**Prophet Captures Seasonality**: The model successfully factors in recurring trends, aiding smarter demand forecasting and campaign timing.
<br>

## Strategic Recommendations
-	**Scale to Match Growth**: Anticipate increased demand by expanding operations, staffing, and logistics in sync with the projected monthly uptick.

-	**Stock Smart for Q4**: Optimize inventory levels to match high-demand windows like **November–December**, reducing missed sales and excess stock.

-	**Target Promotions by Risk Window**: Leverage high-variance months for aggressive marketing while preparing for potential dips using confidence intervals.

-	**Forecast-Driven Planning**: Use predicted figures to shape budgets, set achievable KPIs, and guide executive decisions with confidence.

-	**Build Resilience Plans**: Prepare financial and operational buffers for low-end forecast scenarios—especially during volatile periods.

<br><br>

# **9. Market Basket Analysis for Customer Purchase Insights**

## Business Question
What products are frequently bought together?
<br>

![9  Market Basket Analysis for Customer Purchase Insights](https://github.com/user-attachments/assets/d0529601-2276-43a1-9fae-a3c29711c515)
<br>

## Key Trends & Insights
#### High Accessory Attachment Rate:
- Google Phone is frequently bought with the USB-C Charging Cable (473 times), and Samsung Galaxy Phone with the same cable (172 times), confirming a strong dependency on accessories. A similar pattern was observed with the iPhone, frequently purchased alongside the Lightning Charging Cable (465 times) and Apple AirPods (157 times).

#### Bundling is the Norm, Not the Exception:
- Customers often grab devices and multiple accessories in one go, Google Phone + USB-C Cable + Bose SoundSport Headphones being a standout trio.

#### Cross-Brand Headphone Popularity:
- Galaxy Buds are co-purchased with iPhones, Google Phones, and Samsung phones, showing buyers care more about value and style than brand loyalty.

#### Pattern Repetition Confirms Behavior:
- Consistent two-way product combinations (e.g., iPhone + Cable and Cable + iPhone) reinforce predictable buying habits, goldmine for recommender systems.

#### Accessory-First Mindset:
- Charging cables and headphones frequently drive purchases. They're not impulse buys—they're part of the main event.
<br>

## Strategic Recommendations
#### Launch Pre-Built Bundles:
- Create discounted bundles like iPhone + Lightning Cable + AirPods to increase AOV (Average Order Value) and streamline decision-making.

#### Enhance "Frequently Bought Together" Logic:
- Use top co-purchase patterns to power AI-driven suggestions—especially for 2- and 3-item combos at checkout.

#### Optimize Physical Store Layout:
- Place high-affinity products (e.g., USB-C Cables next to Google Phones) for frictionless add-on purchases.

#### Run Smart Cross-Selling Campaigns:
- Offer promotions like “Buy a Google Phone, get 20% off Galaxy Buds” to capitalize on multi-brand buyers.

#### Forecast Inventory in Pairs:
- Predict accessory demand in tandem with device sales to reduce stockouts and enhance fulfillment planning.

<br><br>

# **10. Clustering Cities by Sales Performance Using KMeans**

## Business Question
How can we group cities based on sales performance to uncover patterns for better sales strategy?
<br>

![10  City Segment - Clustering Cities Using the KMeans Model png](https://github.com/user-attachments/assets/fcf61672-53f9-4c3d-afff-29ca37521eba)
<br>

## Key Insights and Strategic Recommendations
### Cluster 1 – High Sales & High Volume City
**Interpretation**:

-	San Francisco (CA), the only city in this cluster, demonstrates strong performance in both revenue and unit sales.

-	Indicates high demand, strong customer base, and effective local execution.

**Strategic Recommendations**:

-	Double down on success: Increase inventory levels, staffing, and marketing budget.

-	Introduce loyalty programs to retain high-value customers.

-	Launch premium products or upsell/cross-sell strategies, this city is more likely to adopt.

-	Consider using this city as benchmarks or pilots for new product launches.

### Cluster 2 – Moderate Sales & Moderate Volume Cities
**Interpretation**:

-	These cities perform reasonably well but have room for growth.

-	Represents stable markets with the potential to be moved into the high-performing cluster.

**Strategic Recommendations**:

-	Localized promotions to drive awareness and increase repeat purchases.

-	Sales training or incentive programs to boost performance.

-	Monitor customer behavior and competitor activity.

### Cluster 0 – Low Sales & Low Volume Cities
**Interpretation**:

-	Underperforming regions with low revenue and low units sold.

-	Maybe an indication of market saturation, low demand, or ineffective sales presence.

**Strategic Recommendations**:

-	Cost-efficiency measures: Evaluate whether continued investment is justified.

-	Reassess market potential: Are these markets viable with a different strategy?

<br><br>

## Key Expected Result and Estimated Business Impact
#### 1. Business Growth Optimization
- Achieve 20–25% revenue uplift by capitalizing on Q4 seasonal demand peaks (e.g., Nov–Dec) and replicating top-performing strategies year-round.

- Boost average order value by 10–15% through bundling high-affinity product combos (e.g., iPhone + Cable + AirPods).

- Enhance product portfolio profitability by 12–18% by prioritizing top-selling accessories and phasing out underperforming high-ticket items.

- Improve profit consistency by 8–12% using sales forecasting insights to align inventory, marketing, and staffing with demand cycles.

#### 2. Operational Efficiency & Smarter Decision-Making
- Increase sales forecast accuracy by 25–30% via Prophet model-based time series forecasting.

- Reduce stockouts and overstock by 15–20% using predictive inventory planning aligned with demand patterns and peak purchase times.

- Improve campaign ROI by 18–22% through time-targeted ads (11AM–2PM and 6PM–9PM) and weekday optimization (e.g., Tuesday launch campaigns).

- Cut decision turnaround time by 30% through actionable insights from EDA, clustering, and Market Basket Analysis.

#### 3. Market Expansion & Channel Optimization
- Drive 10–14% growth in underperforming cities by implementing targeted local campaigns and price optimization in low-volume zones.

- Increase customer engagement by 15–20% through tailored promotions aligned with day-of-week and time-of-day purchase behaviors.

- Improve omnichannel cross-selling by 12–16% using frequently bought together patterns to enhance online and in-store recommendations.

- Expand market share by 8–10% by investing in high-performance clusters (e.g., San Francisco, LA, NYC) and turning them into innovation hubs.
<br>

## **What I Learned**
Throughout this project, I significantly deepened my understanding of **Retail Sales Analysis** and strengthened my technical expertise in **Python-based data analytics and machine learning**. Here are some of the most valuable skills and insights I gained:

-	**Advanced Python Skills**: I enhanced my ability to manipulate and analyze data using libraries such as **Pandas**, while leveraging Matplotlib and Seaborn for effective visual storytelling.

-	**Machine Learning Application**: I applied models using **Scikit-learn, XGBoost**, and **Prophet** to identify patterns and generate predictive insights, moving beyond descriptive analytics to deliver strategic foresight.

-	**Data Cleaning & Preparation**: I reinforced the importance of meticulous data cleaning and formatting as the foundation for accurate, reliable analysis and model performance.

-	**Strategic Insight Generation**: By combining EDA with machine learning techniques, I learned how to generate business-critical insights that inform strategy, optimize marketing efforts, and support forward-looking decision-making.
<br>

## **Challenges & Growth**
This project came with its share of challenges, each providing valuable opportunities for growth:

-	**Handling Data Inconsistencies**: Navigating missing, duplicated, or inconsistent entries sharpened my data preprocessing techniques and taught me how vital data integrity is to meaningful analysis.

-	**Complex Visualizations**: Translating dense, multi-dimensional data into intuitive and impactful visualizations required creativity and precision—skills I significantly improved through iteration.

-	**Balancing Detail and Scope**: Striking the right balance between diving deep into specific analyses and maintaining a broad strategic overview was a continuous learning process, enhancing my ability to manage project scope effectively.
<br>

## **Conclusion**
This Retail Insights That Drive Strategy project showcases how combining Exploratory Data Analysis with Machine Learning can turn raw sales data into clear, actionable strategies. By uncovering sales patterns across time, geography, and customer behavior, the project addresses critical business questions, such as top-performing months, cities, and products, while revealing opportunities in product bundling, promotion timing, and customer segmentation.
Advanced techniques like **Prophet forecasting, market basket analysis**, and **KMeans clustering** provided predictive power and strategic guidance, enabling smarter decisions in inventory, marketing, and planning.
In short, this project equips decision-makers with the insights needed to optimize performance, enhance customer engagement, and drive sustained growth in a competitive retail environment.
<br>

**Feel free to explore, share, and connect! Let's transform data into decisions that drive measurable impact**.

## **Connect with Me**
- **📞 +234-8065060691**
- **📧 Email: Olumide Balogun**
- **🔗 LinkedIn**: [Connect with me on LinkedIn](https://www.linkedin.com/in/olumide-balogun1/)
- **🔗 Medium**: [Explore my Data Storytelling articles](https://medium.com/@Olumide-Balogun)

