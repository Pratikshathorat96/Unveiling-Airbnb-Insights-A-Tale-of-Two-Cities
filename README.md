![image](https://github.com/Pratikshathorat96/Unveiling-Airbnb-Insights-A-Tale-of-Two-Cities/assets/120496034/0a275a1c-f5c4-4b6b-a57c-7bf9953d19a8)

# Unveiling Airbnb Insights: A Tale of Two Cities (Chicago &amp; New Orleans)

## Dashboard - https://drive.google.com/file/d/1jFpm9VpE4Fyu2lcGe8h_EZCtyhmuerrD/view?usp=sharing

Project By - Pratiksha Akshay Thorat.

Deliverables: 

Google doc link of Tableau project - https://drive.google.com/file/d/1AJyM889L4T5jLov7qpKocqsQz54UCcAP/view?usp=sharing

Video Presentation Link - https://youtu.be/iOakDYMtDCg

Google colab link for EDA - https://colab.research.google.com/drive/1iXMOwc74upMHc4OccSqpX9n2l3BLZt4e?usp=sharing 

Problem Statement:

In the context of Airbnb operations, how can the utilisation of Tableau facilitate a comprehensive comparative examination between Chicago and New Orleans, two diverse urban environments? 
This inquiry seeks to leverage Tableau's visual analytics capabilities to uncover and illustrate the shared attributes, disparities, and distinctive patterns inherent to Airbnb's presence in these cities, thus elevating the depth and insightfulness of the study.

Dataset Selection:

For this EDA project, we have chosen the "Airbnb Listings Data" dataset from 2 major cities: Chicago and New Orleans. This dataset provides a comprehensive snapshot of various attributes related to Airbnb listings, such as property type, neighbourhood, pricing, availability, and more. The dataset is ideal for conducting an in-depth exploration of the local Airbnb market and deriving actionable insights.

Why Airbnb:

Airbnb, a prominent online platform, enables individuals to reserve accommodations spanning a spectrum from beds and rooms to apartments and entire homes across global locales. This user-centric platform serves as a conduit for seamless property rentals, negating the need for intricate intermediaries or substantial capital outlays. Notably, users can secure lodgings at significantly competitive rates relative to traditional hotels. Distinctively, Airbnb extends its reach to regions where convectional hotel presence might be limited, offering an avenue for lodging acquisition in underserved locales. Moreover, the inclination towards immersive local experiences often steers individuals towards selecting accommodations embedded within native communities, fostering a distinctive preference for authenticity and cultural engagement.

Airbnb Statistics • Over 4 million listings worldwide • 150 million users in 191 countries • Worldwide value is $32 billion • Global growth rate since 2009 - 153%






Dataset Details:

- Dataset Name: Airbnb Listings Data
- Source: Link to dataset
- Cities: Chicago & New Orleans
- Description: The Airbnb Listings Data contains information about different properties available for rent on Airbnb in a specific city. Each record represents a unique listing and includes attributes such as property type, neighbourhood, number of bedrooms, pricing, availability, host information, and more.


Key Attributes:

1. id: Unique identifier for each listing.
2. name: The title or name of the listing.
3. host_id: Unique identifier for the host of the property.
4. host_name: Name of the host.
5. neighbourhood_group: The broader area or group that the neighbourhood belongs to.
6. neighbourhood: Specific neighbourhood where the property is located.
7. latitude: Latitude coordinate of the property.
8. longitude: Longitude coordinate of the property.
9. room_type: Type of room (e.g., Private room, Entire home/apt, Shared room).
10. price: Price of the listing per night.
11. minimum_nights: Minimum number of nights required for booking.
12. number_of_reviews: Total number of reviews received for the listing.
13. last_review: Date of the last review.
14. reviews_per_month: Average number of reviews per month.
15. availability_365: Number of days the listing is available for booking in a year.

Problem Areas to Explore:

1. Which are the popular neighbourhoods, their average prices and no. of listings?
2. What is the percent share of different property types and room types?
3. How the pricing is varying with location, property type, and reviews?
4. What are the different correlations between type of hosts and factors like- reviews & price?

Divide the visualisation findings into 4 categories:
Overview of Airbnb 
Property analysis 
Pricing analysis 
Host analysis






How to proceed with the dashboard:

Data Cleaning
Begin by addressing the disorder and inconsistency within the dataset. Utilise Jupyter Notebook and Tableau Prep to systematically cleanse the data, rectifying discrepancies, eliminating duplicates, and standardising formats.

Data Transformation
Generate supplementary columns by utilising pre-existing categorical data. These columns will be derived from extensive descriptive text, which, in its original form, proved arduous to comprehend and unsuitable for visualisation purposes. The extra columns that we created gave a much clear sense of how to approach and make an effective visualisation.

Tableau 
Employ Tableau Prep to leverage its distinctive "Group and Replace" feature. Under the column denoted as Neighbourhood there are instances where identical entities are variably represented due to disparities in letter casing, spelling variations, or phonetic similarity. The "Group and Replace" algorithm inherent to Tableau Prep proved instrumental in mitigating this issue. 


1: Introduction

Welcome everyone to the presentation on "Unveiling Airbnb Insights: A Tale of Two Cities".
Today, I'll explore how Tableau facilitates a comparative examination between Chicago and New Orleans, two diverse urban environments, leveraging Airbnb operations data.

2: Problem Statement

My inquiry aims to utilize Tableau's visual analytics capabilities to uncover and illustrate shared attributes, disparities, and distinctive patterns in Airbnb's presence between Chicago and New Orleans.

3: Dataset Selection

I have chosen the "Airbnb Listings Data" dataset from Chicago and New Orleans for my EDA project. This dataset provides a comprehensive snapshot of various attributes related to Airbnb listings.

4: Why Airbnb

Airbnb serves as a global platform for property rentals, offering unique lodging experiences at competitive rates.
Its presence extends to regions with limited traditional hotel options, emphasizing immersive local experiences.

5: Airbnb Statistics

Over 4 million listings worldwide
150 million users in 191 countries
Worldwide value of $32 billion
Global growth rate since 2009: 153%

6: Dataset Details

Detailed attributes of the Airbnb Listings Data including id, name, host information, neighbourhood, room type, pricing, and availability.

7: Problem Areas to Explore

Popular neighborhoods, average prices, and number of listings.
Share of different property types and room types.
Pricing variations with location, property type, and reviews.
Correlations between types of hosts and factors like reviews and price.

8: Data Cleaning

I began by addressing disorder and inconsistency within the dataset using Jupyter Notebook and Tableau Prep. This included data cleansing, rectifying discrepancies, eliminating duplicates, and standardizing formats.

9: Data Transformation

I generated supplementary columns from extensive descriptive text to provide clearer insights for visualization purposes.

10: Tableau Utilization

Utilizing Tableau Prep's "Group and Replace" feature helped mitigate issues like inconsistencies in representing identical entities within the Neighbourhood column.

11: Overview of Airbnb

Visualizations providing an overview of Airbnb operations in Chicago and New Orleans.

12: Property Analysis

Insights into popular neighborhoods, property types, and room types in both cities.

13: Pricing Analysis

Visualizations illustrating pricing trends, variations with location, property type, and reviews.

14: Host Analysis

Exploration of correlations between types of hosts and factors like reviews and price.

15: Conclusion

My Tableau dashboard offers comprehensive insights into Airbnb operations in Chicago and New Orleans, enabling informed decision-making and strategic actions.
