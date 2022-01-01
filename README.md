# Proposal: New York Airbnb Case Study Using Regression Model

Tourism is getting a lot of attention recently in Saudi Arabia to follow the Saudi vision 2030 goals.  As a result of government’s efforts to revive and nourish tourism, many entertainment and tourism programs have been established. These programs have attracted millions of visitors from all across the globe. A lot of those visitors love to experience living with local people to live the whole experience of how local people are living their daily lives and to have more connections with locals. This experience can be provided by allowing local people to rent a property they own and prepared especially for tourists and have these properties listed in a globally known platform such as Airbnb. In this project my aim is to perform exploratory data analysis and build a predictive data model on New York city Airbnb data to answer below questions:

*	What are the factors affecting property prices?
*	Which listed properties are the busiest and why?
*	What are the lessons learned from New York city case study that can be applied on Riyadh city?


## Dataset Description

The dataset is taken from [Kaggle](https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data) website and it includes all information related to the host listings and property description of New York city in the year of 2019. It consists of 16 features and 48,895 observations. Detailed description of each feature is listed below:

*	id: listing ID
*	name: name of the listing
*	host_id: host ID
*	host_name: name of the host
*	neighbourhood_group: location
*	neighbourhood: area
*	latitude: latitude coordinates
*	longitude: longitude coordinates
*	room_type: listing space type
*	price: price in dollars
*	minimum_nights: amount of nights minimum
*	number_of_reviews: number of reviews
*	last_review: date of latest review
*	reviews_per_month: number of reviews per month
*	calculated_host_listings_count: amount of listing per host
*	availability_365: number of days when listing is available for booking

## Design

In this project I will be doing an exploratory data analysis to gain more insight into the data and to try to find out answers to some of the questions listed above. Also, I will develop a predictive regression model using polynomial regression and support vector regression to predict property prices and to discover the most effective features in deciding the price. R-squared and root mean squared error will be used to measure models’ performance and to find out which model is performing better.

## Tools

*	Google colaboratory notebook.
*	Python.
*	Sklearn.
*	Pandas.
*	Numpy.
*	Matplotlib.
