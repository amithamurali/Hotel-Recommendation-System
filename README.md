Hotel Recommendation System

Problem statement

Expedia has provided us logs of customer behavior. These include what customers searched for, how they interacted with search results (click/book), whether or not the search result was a travel package. The data is a random selection from Expedia and is not representative of the overall statistics.
We are interested in predicting which hotel group a user is going to book. Expedia has in-house algorithms to form hotel clusters, where similar hotels for a search (based on historical price, customer star ratings, geographical locations relative to city center, etc) are grouped together. These hotel clusters serve as good identifiers to which types of hotels people are going to book, while avoiding outliers such as new hotels that don't have historical data.
Our goal is to predict the booking outcome (hotel cluster) for a user event, based on their search and other attributes associated with that user event.
Recommending hotels to users based on hotel properties and user behavior. Sentiment Analysis of the reviews given by the user.
The train and test datasets are split based on time: training data from 2013 and 2014, while test data are from 2015. Training data includes all the users in the logs, including both click events and booking events. We only use training dataset.
destinations.csv data consists of features extracted from hotel reviews text.


1.Web Application Code

https://github.com/dsrivastava29/HotelRecommendation
Code is present on above repository. You can clone and use it or open it directly to your Visual Studio.


3.Web Application url

Link --- > http://hoteladvisorsystem.azurewebsites.net/
Credentials ---- >

Admin User: 
username - divyansh@hotel.com
password - divyansh

Customer User:
username - guest@hotel.com
password - guest



