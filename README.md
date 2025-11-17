# AirBnb
Python Data Analysis and Visualization
Airbnb Listings EDA: New York 2024
Project Overview

This project explores New York Airbnb listings to uncover patterns in pricing, availability, and host behavior. Using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn, we clean, visualize, and analyze the dataset to derive actionable insights.

Objectives

Examine room types, pricing, and availability across neighborhoods.

Understand host behavior and listing trends.

Identify price outliers and unusual listing patterns.

Provide recommendations for both guests and hosts based on findings.

Dataset

Size: 20,765 listings with 22 features

Key features include:

id, name, host_name

neighborhood_group, latitude, longitude

price, room_type, availability_365

reviews_per_month, beds, last_review

Workflow & Analysis
1. Data Cleaning

Handled missing values in price, neighborhood, and beds.

Converted last_review to datetime.

Capped extreme prices above $1,000 to reduce skewness.

2. Exploratory Data Analysis (EDA)

Room Types:

Counted listings by room_type using bar charts.

Entire homes/apartments were the most common type.

Neighborhood Insights:

Analyzed pricing trends across boroughs.

Manhattan had the highest average listing prices.

Availability & Reviews:

Heatmaps revealed correlations among price, availability_365, number_of_reviews, and beds.

Listings with higher availability often had lower prices but more reviews.

Price Distribution:

Histograms and boxplots showed most listings ranged from $50–$300 per night.

Extreme outliers ($10,000+) were identified and filtered.

Host Behavior:

Boxplots highlighted hosts with multiple listings, suggesting professional hosting patterns.

Relationship Analysis:

Pairplots demonstrated connections between price, availability_365, and number_of_reviews.

Visualizations Used

Bar Charts: Room types, neighborhood distributions

Histograms & Boxplots: Price distributions and outlier detection

Heatmaps: Correlation among numerical variables

Pairplots: Relationships between price, reviews, and availability

Key Insights

Pricing Trends: Manhattan listings are the most expensive; entire homes/apartments cost more than private/shared rooms.

Room Type Distribution: Private rooms provide budget options despite the prevalence of entire homes/apartments.

Outliers: Extremely high-priced listings exist but are rare.

Availability & Reviews: Listings with higher availability tend to attract more reviews and are priced lower.

Host Behavior: Some hosts manage multiple listings, indicating professional hosting activity.

✅ Takeaway: The analysis provides a clear understanding of New York Airbnb trends, helping guests make informed choices and hosts optimize pricing and availability.
