# KingCountyHouseSales

## Overview
This project presents a Tableau dashboard analyzing real estate transactions in King County, Washington. The dashboard provides interactive filtering, visual breakdowns of sales prices, and key insights into housing trends, conditions, and distributions across multiple dimensions.


## Project Objective
The objective of this project is to leverage Tableau for real estate analytics, enabling users to:
- Explore daily sales price trends.
- Identify housing characteristics that influence prices.
- Visualize geographic trends across King County.
- Support data-driven decision-making for buyers, sellers, and real estate professionals.


## Data Preparation
- Cleaned and formatted the raw housing dataset.
- Created calculated fields (e.g., daily average price, price bins, frequency counts).
- Applied filters for year built, square footage (living and lot), and calendar-based date selection.
- Built heatmaps to compare property condition against view quality.


## Tools Used
- Tableau (visualization, interactivity, dashboard design)
- Excel & Power Query (data cleaning and structuring)


## Dashboard Features
### 1. Filters
- **Calendar & Dropdown**: Select specific month and day for trend analysis.
- **Sliders**: Filter by year built, living square footage, and lot size.


### 2. Visualizations
- **Daily Average Sales Price (Line Chart)**: Tracks fluctuations in average house prices over time.
- **Distribution of House Prices (Histogram)**: Shows the frequency distribution of homes by price bins.
- **Distribution of Bedrooms & Bathrooms (Histograms)**: Highlights the most common house structures in terms of bedrooms and bathrooms.
- **Map View**: Geographic heatmap of sales prices and volume across King County neighborhoods.
- **View vs. Condition Heatmap**: Compares property view quality (e.g., no view, average, good, excellent) with condition ratings, highlighting how both factors affect sales values.


### 3. Interactivity
- Users can filter by build year, living area, and lot size.
- Calendar filter enables time-based analysis.
- Hover tooltips reveal detailed insights.


## Images
```
![Dashboard Overview](images/Dashboard.png)
![Calendar Filter](images/Calender.png)
![View vs. Condition Heatmap](images/ViewConditions.png)
![Distribution of Bathrooms](images/Bathrooms.png)
![Distribution of Bedrooms](images/Bedroom.png)
![Distribution of House Prices](images/HousePrices.png)
![Geographic Map](images/Map.png)
![Daily Sales Price Trend](images/LineChart.png)
```


## Key Insights
- **Price Distribution**: Majority of homes sold fall between $200K–$600K, with fewer high-end luxury homes above $1M.
- **Bedrooms & Bathrooms**: 3-bedroom and 2-bathroom homes dominate the market, aligning with typical family housing needs.
- **Geographic Trends**: Areas near Seattle and Bellevue show higher concentrations of sales and elevated prices compared to rural zones.
- **View & Condition Impact**: Homes with good to excellent views combined with strong condition ratings command significantly higher total sales.
- **Time Trends**: Daily sales prices exhibit fluctuations with noticeable peaks, suggesting seasonal or demand-driven spikes.
