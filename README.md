# Australian-Rental-Market-Analysis (2026)

Project Overview
This project analyses Australian rental listings for 2026 to understand rental pricing patterns, affordability differences between suburbs, and the concentration of premium rental markets across Australian states.
Using Power BI and DAX, interactive dashboards were built to explore rental distribution, identify expensive and affordable suburbs, and evaluate rental efficiency based on property size.
The project aims to demonstrate how data modelling, analytical metrics, and visual storytelling can transform raw rental listing data into meaningful insights about housing markets.

Project Objective
The goal of this project is to demonstrate how data analytics and business intelligence tools can be used to explore real-world housing market dynamics and support data-driven decision making.

Dataset
Dataset used: Australian Rental Market Listings (2026)

Tools Used
Power BI – Dashboard creation and data visualisation
DAX (Data Analysis Expressions) – Custom analytical metrics
Data Modelling – Rental market indicators and affordability metrics

Dashboards Developed
1. Australian Rental Market Overview
   -This dashboard explores rental market dynamics across Australian states.
Key insights include:
  -Median rent levels by state
  -Distribution of rental listings across price segments
  -Premium rental market concentration
  -Rental price spread (IQR)

2. Suburb Rental Affordability Analysis
  -This dashboard focuses on suburb-level insights including:
Key insights include:
  -Most expensive suburbs
  -Most affordable suburbs
  -Rent distribution by bedroom size
  -Rent efficiency based on property size

Analytical Metrics Developed
Several custom analytical metrics were created using DAX to better understand rental pricing patterns.
  -Median Weekly Rent : Represents the middle value of rental prices when listings are ordered from lowest to highest.(Median rent is preferred over average rent because extremely expensive properties can skew average values, making median a more reliable indicator of typical rental prices.)
  -Average Weekly Rent : Calculates the average rental price across all listings. (Used mainly for comparison with the median to identify potential price skew caused by high-value listings.)
  -Rent Percentiles (P25 & P75) : These metrics divide rental listings into distribution segments.
    -P25 (25th percentile) identifies lower-priced rental listings
    -P75 (75th percentile) identifies higher-priced rental listings
   These percentiles help classify the rental market into budget, mid-range, and premium segments.
  -Rent Interquartile Range (IQR) : The IQR measures price spread between P25 and P75.
    IQR = P75 − P25
    This metric helps understand how widely rental prices vary within a market.
  -Premium Listings Share : Measures the proportion of rental listings that fall within the top 25% of rental prices.
    This indicator helps identify markets with strong premium rental demand.
  -Rent per Bedroom : Calculates rental price relative to property size:
    Rent per Bedroom = Rent / Number of Bedrooms
    This metric helps evaluate cost efficiency of larger properties and shared housing.
  -Affordability Ranking (Suburb) : Ranks suburbs based on median weekly rent from lowest to highest.
    Lower-ranked suburbs represent more affordable rental markets.
  -Rent Index : Compares the median rent of a specific location relative to the overall market median.
    This metric helps understand how expensive or affordable a location is relative to the national market.

Key Insights from the Analysis
  -Rental prices vary significantly across Australian states and suburbs.
  -Premium rental listings are concentrated in certain markets, indicating stronger rental demand.
  -Larger properties tend to have lower rent per bedroom, suggesting shared housing may improve cost efficiency.
  -Median rent provides a more accurate representation of the rental market compared to average rent.

Future Improvements
  -Future extensions of this project could include:
  -Rental yield analysis (rent vs property price)
  -Vacancy rate analysis
  -Time-series rental trend analysis
  -Property investment analytics



