# Seattle Airbnb Open Data - Udacity Analysis

### Medium Article https://medium.com/@muellerch2293/thats-how-you-become-rich-and-famous-on-airbnb-9f33a35604e3

The following project was created for the Udacity Data Scientist Nanodegree.
It uses the data provided in https://www.kaggle.com/datasets/airbnb/seattle to answer the following questions:

1. What are the most important factors for a successful Airbnb listing?
2. How does location and time influence the price of my Airbnb?
3. Does the number of available listings influence the price?

To answer these questions  listings.csv and calendar.csv are used
While listings.csv contains a list of all Airbnb listings (with detailed information about every aspect of the listing) the calendar.csv files contains information about the availability and price of every listing for every day of 2016

### Results: 
Even though with a relatively low r-squared score of 29% on the test data we cannot reliably use the model to predict our success it still explains 29% of the variance in the data! Looking at the strongest coefficients yields a good idea of what has a positive influence on the success of a listing. 
Furthermore it was showed that the prices depend on the location of the airbnb as well as on the time. Airbnbs are pricier in summer and on weekends!
A strong correlation between the number of available listings and the price was not observed.

### Content:
* airbnb.ipynb: jupyter notebook
* data/listings.csv: files containing the listings of seattle in 2016
* data/calendar.csv: files containing the calendar of seattles airbnb listings



### used libraries:
* numpy
* pandas
* seaborn
* datetime
* sklearn
* json
* pathlib
