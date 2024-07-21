# ZOMATO-PERFORMANCE-ANALYSIS----CASE-STUDY
1.	Summary

This case study analyzes the performance of Zomato, a leading online food delivery and restaurant discovery platform. Using data from their internal dashboard, we examine key metrics including sales, user demographics, geographic distribution, and customer retention. The study reveals Zomato's strengths in certain markets and food categories, while also highlighting areas for improvement, particularly in customer retention and market expansion.
Key findings include a total sales figure of 987M across 2M transactions, strong performance in cities like Tirupati and GTB Nagar Delhi, and a dominant market share for non-vegetarian food items. However, the company faces challenges with a high customer churn rate and a significant sales decline in 2020, likely due to external factors such as the COVID-19 pandemic.
This case study provides insights and recommendations to help Zomato optimize its operations, improve customer retention, and drive sustainable growth in a competitive market landscape.

2.	Introduction

Company Background

Zomato, founded in 2008, has grown from a restaurant discovery platform to a comprehensive food tech company offering delivery services, restaurant reservations, and more. Operating in numerous countries, Zomato has become a key player in the global food delivery market.

Industry Context

The online food delivery industry has experienced rapid growth in recent years, driven by changing consumer preferences, urbanization, and technological advancements. However, the industry also faces challenges such as intense competition, regulatory pressures, and the need for continuous innovation.

3.	Problem Statement:
   
The dataset comprises essential parameters related to Zomato's operations, including sales figures, order counts, user demographics, food categories, ratings, and geographic performance. We aim to analyse this data to identify patterns, trends, and key performance indicators (KPIs) that can inform Zomato about market preferences, customer demographics, sales strategies, and operational effectiveness. The goal is to provide evidence-based strategies to optimize Zomato's offerings, enhance customer satisfaction, and improve overall business performance.

5.	About Dataset:

This dataset contains information on Zomato's performance across various metrics from the year 2017 to 2020. It includes data on overall sales, number of orders, user demographics, food category performance, year-over-year trends, and geographic distribution of sales and ratings. The dataset encompasses a mix of categorical and numeric values, with insights into customer behaviour, sales performance, and regional variations.

7.	Description of columns in the dataset:

There are multiple data sets they are users(users name, ID, gander, age, marital status), orders( number of orders from different restaurants), restaurant(restaurants with their location and the ratings for the same), menu( the menu of the restaurant), food( name of the dish and its type e.g. veg or non-veg), order type( the order ID and its type). 

8.	Benefits of the analysis:

By conducting these analyses, Zomato can gain insights into market preferences and customer demographics, optimize sales strategies and tailor food offerings, enhance customer satisfaction and retention, improve operational efficiency, and make data-driven decisions for expansion and growth. Through these benefits, this analysis contributes to making Zomato more responsive to customers' needs and preferences while improving its business performance.

9.	Data Analysis Approach:

We employed a mixed-method approach, combining quantitative analysis of sales and user data with qualitative assessment of market trends and user behaviour. Key performance indicators (KPIs) were calculated to benchmark Zomato's performance.

10.	Recommended Analysis:
    - Calculate the total sales amount and total number of orders.
    - Analyse the performance of different food categories (Non-Veg, Veg, Other) in terms of sales and ratings.
    - Examine the year-over-year sales trends to identify growth patterns and potential issues.
    - Investigate user demographics, particularly age distribution and gender split of gained and lost customers.
    - Evaluate geographic performance by analysing sales, ratings, and active users across different cities.
    - Identify the top-performing cities in terms of sales and user engagement.
    - Examine the average order value and its variation across different parameters (e.g., cities, food categories).
    - Investigate the relationship between active users and sales performance in different cities.

9.	Data Analysis and Visualizations:
1. Overall Performance Metrics
This section provides an overview of Zomato's key performance indicators
 
Visualization: The dashboard displays the following key metrics:
•	Amount: 987M
•	Sales: 2M
•	Rating: 148K
•	Orders: 150K
2. Food Category Performance
This analysis breaks down Zomato's active users and ratings across different food categories, highlighting customer preferences and potential areas for menu expansion. 
 
Visualization: The dashboard shows three food categories with their respective sales and ratings:
1.	Non-Veg: 106M sales, 10K rating
2.	Veg: 731K sales, 12K rating
3.	Other: 932 sales, 927 rating
	This data illustrates the dominance of non-vegetarian options in terms of sales, while also showing strong ratings for vegetarian items.
3. Year-over-Year Sales Trends
This section examines Zomato's sales performance over the past few years, identifying growth patterns and potential external impacts on the business. 
 
Visualization: A line graph titled "Sale by Year" is provided, showing:
•	2017: Approximately 0.1bn
•	2018: Peak at about 0.41bn
•	2019: Slight decrease to around 0.38bn
•	2020: Sharp decline to about 0.14bn
	This graph clearly illustrates the company's growth, peak, and subsequent decline, likely influenced by external factors such as the COVID-19 pandemic.
4.	User Demographics and Behaviour
This analysis explores Zomato's user base, including age distribution, gender split, and customer acquisition and retention metrics. 
 
Visualization: The dashboard provides several relevant data points:
•	Active Users: 78K
•	A bar graph showing user distribution by age, with a peak in the 20-25 year range
 
•	Gain Customers: Male (5.9K) > Female (5.1K) 

 
•	Lost Customers: Male (18.8K) > Female (14.0K) 
	This data highlights Zomato's appeal to young adults and reveals challenges in customer retention.
5.	Geographic Performance
This section analyses Zomato's performance across different cities, considering factors such as sales, order counts, user base, and ratings. 
 
Visualization: The dashboard provides a table with city-wise performance metrics, including:
•	City names (e.g., GTB Nagar,Delhi, Kothrud,Chennai, Faridabad)
•	Sales figures
•	Order counts
•	User numbers
•	Gain Users
Additionally, there are bar charts showing:
•	Sales by City
•	Rating by City
•	Active users by City

 
 
 
There's a disparity between cities with highest sales and those with highest ratings, suggesting opportunities for growth in well-rated areas with lower sales volumes.


10.	Entity-Relationship Diagram (ERD)
  
•	"Zomato Data Model ERD"
•	Description: The provided image illustrates the relationships between key entities in Zomato's data structure. The model consists of six main entities: food, menu, Orders_type, orders, users, and restaurant.

11.	SWOT Analysis
Strengths
•	Strong presence in key urban markets
•	High average order value
•	Appeal to young adult demographic
Weaknesses
•	High customer churn rate
•	Overdependence on non-vegetarian food category
•	Declining sales trend (2019-2020)
Opportunities
•	Expansion in high-rated, lower-sales cities
•	Development of vegetarian and 'Other' food categories
•	Increased order frequency strategies
Threats
•	External disruptions (e.g., pandemic effects)
•	Intense competition in food delivery sector
12.	Recommendations
1.	Customer Retention Strategy 
o	Implement a tiered loyalty program
2.	Menu Diversification 
o	Promote high-quality vegetarian options
o	Explore and expand the 'Other' category
o	Collaborate with restaurants on exclusive menu items
3.	Geographic Expansion 
o	Focus resources on high-rated cities with growth potential
o	Develop city-specific marketing and partnership strategies
o	Replicate successful practices from top-performing cities
4.	User Engagement Enhancement 
o	Create targeted campaigns for the 20-30 age group
o	Implement a referral program leveraging the young user base
5.	Order Frequency Improvement 
o	Introduce time-based promotions and subscription models
o	Optimize push notifications and email marketing
o	Implement AI-driven personalized recommendations
6.	Pandemic Recovery Plan 
o	Develop strategies for contactless delivery and safety measures
o	Explore new revenue streams (e.g., grocery delivery, meal kits)
13.	Conclusion
Zomato demonstrates strong performance in key urban markets and maintains a loyal active user base. However, the company faces significant challenges, particularly in customer retention and adapting to market disruptions. By implementing the recommended strategies, Zomato can address these challenges, diversify its offerings, and position itself for sustainable growth in the competitive food delivery market.
The success of these initiatives will depend on Zomato's ability to execute effectively, continuously analyse performance data, and rapidly adapt to changing market conditions. Regular monitoring and analysis of key metrics will be crucial for long-term success and maintaining a competitive edge in the dynamic food tech industry.

Created and presented by
Govardhani.G

