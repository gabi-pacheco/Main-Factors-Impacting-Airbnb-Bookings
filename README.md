# Airbnb Host Performance Report

You see the dashboard [here]()

## Project Overview
This project was part of a group mini-project developed during a Data Analytics Bootcamp with **Le Wagon**. The aim was to understand why some Airbnb hosts rent more than others by analyzing host behavior, listing properties, and seasonal trends. The focus was on visualizing the key factors affecting rental performance.

## Data Source
**Listings Table:** 500 rows, each representing a unique Airbnb listing.

**Calendar Table:** 72,101 rows, representing daily availability and booking information for each listing.

The two tables are connected via listing_id.

**Tools Used**

**BigQuery:** For data transformation and SQL queries. 

**Looker:** For creating visualizations and dashboards.

## Analysis Breakdown
The analysis was divided into three parts:

**1. Hosts**
Hosts' response time and review scores were key factors in rental frequency.
Hosts who responded within an hour had a significantly higher rental rate than those who took longer to respond.

**2. Properties**
Occupancy Segments were created to categorize listings based on the occupancy rate (calculated as rented days / available days).
Price Segments were also created to understand how pricing affected booking patterns.
Listings in the mid-range price segments (Cozy Retreats: €76–150) showed higher occupancy rates than both budget and high-end properties, suggesting a sweet spot in pricing.

**3. Seasonal Trends**
Occupancy rates varied seasonally, with September seeing a peak of 93%, dropping to 62% by January. The analysis revealed higher rental activity in early fall and lower activity in winter, pointing to predictable seasonality in Airbnb bookings.

## Conclusion & Actionable Insights

**Conclusion:**
The project concludes that hosts who are more responsive and price their properties within the mid-range segment tend to rent out their listings more frequently. Seasonal trends also play a significant role, with a clear dip in occupancy rates towards the end of the year.

**Actionable Insights for Business Teams:**

**Improve Host Responsiveness:** Encourage hosts to respond to inquiries within an hour to maximize booking opportunities.
Optimize Pricing: Properties priced in the mid-range (€76–150) segment tend to perform better in terms of occupancy. Hosts should adjust their pricing to fall within this range to maximize rentals.

**Seasonal Promotions:** Offer targeted promotions during the winter months to counteract the seasonal drop in bookings, as occupancy rates tend to decrease towards the end of the year.

## Team: 
- [Gabriella Pacheco](https://github.com/gabriellapacheco)
- [Núria M. Martí](https://github.com/nuriamarti)
- Danilo de Oliveira Pereira
