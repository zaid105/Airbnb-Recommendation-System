# Airbnb-Recommendation-System
## Overview
Airbnb, a popular platform for sharing rooms, has made a big impact on where people stay when they travel. With over three million listings worldwide, Airbnb offers a wide variety of places to stay, each with its own style, amenities, and location. Guests have their own preferences, but some amenities always seem to make them happy, as shown by their positive reviews and ratings.

Both guests and hosts are important for Airbnb's success. Guests want a great experience, aiming for a five-star stay with amenities that make them happy. Hosts want to attract as many guests as possible, so they often focus on offering the top 10 amenities that guests look for.

For hosts to be successful on Airbnb, they need to consider many factors. New hosts may need advice on making their properties attractive, while existing hosts might wonder why they're not getting high ratings. Our goal as consultants is to help both new and experienced hosts understand how to get top ratings and become Superhosts.
<br><br>
![image](https://github.com/zaid105/Airbnb-Recommendation-System/assets/142628044/8c34cfab-dbc9-4a45-8f80-7eafbc2cc1df)

# Goals
* To analyze Airbnb data in Los Angeles, comparing superhosts and standard hosts.
* To develop a content-based recommendation system for Airbnbs in Los Angeles.
* Identify key amenities associated with superhost status.
* Determine the most impactful amenities for achieving and maintaining superhost status in the Los Angeles Airbnb market.

# Data
Data was obtained http://insideairbnb.com/get-the-data/. Data has two csv files listings which contains 45591 records and 75 features that give information about each listing in western cape and host information. The reviews file has 1528123 rows and 6 columns which provide guest information and their reviews of the airbnb they stayed at.

#  Recommender System

The recommender system was developed by calculating cosine similarity between listings using a Bigram TF-IDF vectorizer.

# Conclusion


It's possible to become a superhost within the first year of hosting, but most hosts reach this status after around 6 years.

The highest-rated listings often offer amenities like Wifi, long-term stay options, a kitchen with essentials, a hairdryer, dishwasher, washer, iron, fire extinguisher, private entrance, free parking, and a first aid kit.

There's a subtle difference between superhosts and regular hosts based on features like amenities and ratings. However, being a superhost gives an advantage as they get prioritized in search results, leading to more customers and income.

The recommender system is performing well, providing recommendations with relatively high similarity scores (cosine similarity of 0.1 and above) based on user inputs.
