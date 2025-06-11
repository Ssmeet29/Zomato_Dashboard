# Zomato_Dashboard
Power BI
🍽️ Zomato Restaurant Insights Dashboard
Built with Power BI | Dataset from Kaggle

Project Summary
This Power BI project analyzes restaurant data from Zomato to uncover business insights around customer ratings, pricing, cuisine popularity, and delivery availability. It also highlights the best-rated restaurants per city using interactive toggles and filters.

Dataset
Source: Zomato Restaurants Dataset – Kaggle
Columns include:
Restaurant Name, City, Country
Aggregate Rating, Rating Text
Average Cost for Two, Price Range
Online Delivery, Table Booking
Cuisine Type, Votes

--------------------------------------------------------------------------------------------------------------------------------------
Step 1: Data Cleaning (Power Query Editor)
Removed nulls and duplicates
Renamed columns for clarity
Standardized Cuisines, City, and Rating Text values
Removed rows with error in Country Code

--------------------------------------------------------------------------------------------------------------------------------------
Step 2: Dashboard Visualizations
Each visual was designed to answer a key business question:

1. KPI Cards
Average Cost for Two
Max Aggregate Rating
Max Price Range
Total Votes

2. Pie Chart: Cuisine Distribution
Insight: “What cuisines are most common?”
Legend: Cuisines
Values: Count of Restaurant Name

3. Line Chart: Price Range vs Average Rating
Insight: “Are expensive restaurants always better rated?”
X-axis: Price Range
Y-axis: Avg. Aggregate Rating

4. Stacked Bar Chart: City vs Online Delivery
Insight: “Which cities support online delivery more?”
Axis: City, Count of Restaurant Name
Legend: Has Online Delivery

5. Column Chart: Table Booking Availability by Cuisine
Insight: “Which cuisines are usually available for dine-in?”
Axis: Cuisines, Count of Restaurant Name
Legend: Has Table Booking
-------------------------------------------------------------------------------------------------------------------------------------

Step 3: Group By + Merge for Highest Rated Restaurants
Goal: Find the highest rated restaurant in every city.

-------------------------------------------------------------------------------------------------------------------------------------
Step 4: Toggle Button Navigation
Implemented a bookmark-based toggle between:
Dashboard View
Best Rated Restaurants View

-------------------------------------------------------------------------------------------------------------------------------------
Used:
Buttons for navigation
Bookmarks for switching views
Images and logo for dashboard branding

Project Outcome
Designed for business decision-makers to explore where to expand next, what cuisines work best, and how pricing relates to quality.
Clean layout, KPI summaries, and interactive filters provide fast, intuitive insights.


