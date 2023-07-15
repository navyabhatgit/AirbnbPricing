This project aims to analyze the New York city airbnb dataset to identify critical factors affecting the pricing of Airbnb listings. Understanding the key factors that influence pricing, such as amenities, reviews, room type, and local demand and supply, will enable the hosts to develop a more strategic and effective pricing strategy. By leveraging this knowledge, hosts can optimize their pricing decisions to attract more bookings and maximize their revenue potential. The dataset contains information on the listing demographics, cancellation rules, and reviews.I used a combination of exploratory data analysis, feature engineering, and machine learning models
to identify critical drivers of the pricing strategy.My analysis revealed that the most important factors affecting the price are the location of the listing,
construction year, reviews, and its availability around the year.


Introduction and Motivation:

The hospitality sector undeniably contributes to the country’s GDP and vice versa. Airbnb
(founded in 2008) currently penetrates this market with a share of approximately 20% with over
6.1 million listings as of September 2022. What expedited them to conquer such market placement
is their pricing strategy to beat the competitors like booking.com, HomeAway, and many other
private Hotel/Holiday apartment-style accommodations.
To help the new as Ill as existing hosts set a smart pricing strategy, Airbnb’s new
SmartPricing software focuses on parameters like the local demand and supply, amenities, booking
frequency, ratings, room type, calendar availability, and similar listing searches in its algorithm.
The following project tries to dig deeper into how the above parameters help Airbnb in striking
the right prices for its listings in a Metropolitan like New York. In future, the scope of the project
can be further extended to understand the impact of seasonality on pricing with relevant data.

Modelling:

In my analysis, I have considered the linear regression model to predict the price, which is my
target variable. Linear regression is a widely-used and widely-understood model for predicting
continuous numerical values, making it a suitable choice for this dataset. The linear regression
model assumes that there is a linear relationship betIen the input features (predictors) and the
target variable(price). It estimates the coefficients of the predictors to create a linear equation that
can predict the target variable based on the given input. This model is interpretable and provides
insights into the impact of each predictor on the target variable.
HoIver, after evaluating the results, which shoId a low R-squared value of 0.0086, a high mean
squared error of 109331.7836, and a mean absolute error of 285.4882, I concluded that the linear
regression model did not provide satisfactory predictive performance. As the model did not have
Given these limitations, I explored other models, such as decision trees and K-Means Clustering
(KMeans), which might better capture the complex relationships in the data.
These models can potentially provide more accurate predictions and improve our understanding of the important
features affecting the price.
