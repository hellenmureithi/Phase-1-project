# Airbnb listing analysis project.
## Project Overview
Airbnb has become one of the leading platforms in the short term rental market, connecting millions of hosts and guests from different  parts of the country and also internationally. It has also proved to be a worthy competitor to hotel business chain since individuals now prefer Airbnbs due to their customer customization. With the larger amounts of data generated from listings, pricing, reviews, and availability, it provides an opportunity to analyze patterns and gain helpful insights to both the hosts and the customers.
This project strives to explore the key factors influencing pricing, availability, customer preferences, and neighborhood trends. Additionally, the findings can provide the Airbnb business with a deeper understanding of market dynamics to enhance overall performance.

## Business Problem
Airbnb’s short-term rental market is highly competitive, with pricing, location, and guest experience driving success. Hosts often struggle with setting competitive prices and attracting guests, while travelers face inconsistent pricing, availability, and host reliability. Solving these challenges can boost host revenue, improve guest satisfaction, and strengthen overall platform performance.

## Objectives.
1. To identify the most popular neighborhoods, room types, and hosts.
2. To analyze the relationship between prices and key factors.
3. To examine seasonal and booking trends.

## Data understanding
The data used in this project is a csv file named New York City Open Data from  kaggle website https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data.
It contains 20 columns and 48879 rows after data cleaning and feature engineering which include variables such as:
+ Id
+ host name
+ neighborhood group
+ pricing
+ number of reviews
+ availability

## Data Analysis
I was able to clean the data set by checking for missing values and duplicate values in the data set. I went a step further to feature engineer more columns in my dataset to help with further analysis and visualized various KPIs in Tableau https://prod-in-a.online.tableau.com/t/hellenmureithi-4caab9f9ed/authoring/Cleanedphase1project/Airbnblistingsperformance#2 to find the attached visualizations.

## Conclusions.
Airbnb demand is geographically concentrated in key neighborhoods, with Entire homes/apartments being the most popular room type.
Affordability drives guest engagement, as lower-priced listings attract more reviews, though price by itself has limited predictive power for availability or booking activity.
Seasonality plays a critical role, with demand and pricing peaking in December, August, and September, and weakening in May–July, particularly in June.

## Recommendations
### Neighborhood Strategy:
Hosts in high-demand neighborhoods (e.g., Williamsburg, Harlem, East Village) should emphasize location advantages and maintain competitive pricing.Hosts in less popular neighborhoods could stand out by offering discounts, better amenities, or unique experiences.

### Room Type Focus:
Continue prioritizing Entire home/apartment listings, but for shared/private rooms, emphasize affordability and unique experiences to attract budget-conscious guests.

### Dynamic Pricing & Seasonality:
Increase prices during peak months (December, August, September) to maximize revenue.Offer discounts or flexible booking options in low-demand months (June, May, July) to improve occupancy.

### Beyond Price:
Since price has weak correlations with reviews and availability, hosts should also invest in high-quality photos, amenities, guest experience, and customer service to boost engagement.
