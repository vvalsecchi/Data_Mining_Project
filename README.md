# Data_Mining_Project

## Project
The idea is to carry out an analysis to understand which are the best European hotels.

### Objectives in terms of Cleaning and Data Preparation:
- [x] Extract a "positivity" score from the text of the reviews through sentiment analysis.
- [x] Extract the city and country of the hotel from latitude and longitude.
- [x] Management of null values.
- [x] Graphic visualization of the features in order to better observe the distribution.

### Main analysis objectives:
- [x] Investigate a possible correlation between the nationality of the reviewers and the positive degree of the reviews.
- [x] Investigate a possible correlation between the number of days from checkout and the degree of positive feedback.
- [x] Identify frequent subgroups of words for positive, negative reviews and tags.
- [x] Train a hotel rating model based on reviews.
- [x] Train a regression model to relate geographic location and time of year with the positive feedback.

## Required libraries:
* nltk
* sklearn 
* smart_open
* gensim
* mlxtend
* geopy
* IPython
* reverse_geocoder
* pandas
* seaborn
* numpy
* matplotlib
* plotly
* wordcloud

## Required datasets:
* Hotel_Reviews.csv from kaggle (https://www.kaggle.com/jiashenliu/515k-hotel-reviews-data-in-europe?select=Hotel_Reviews.csv)
