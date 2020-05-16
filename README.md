# Airbnb_Seattle 

This repository designated for a project that analyzes a dataset which contains Seattle Airbnb data. This dataset is available and downloadable from Kaggle https://www.kaggle.com/airbnb/seattle. 

In this project, several business questions were proposed and answered through data exploration. A detailed write-up for this project is available on Medium. https://medium.com/@p3akash/planning-a-trip-to-seattle-let-me-help-you-with-some-data-4b5ab04c0853


## Project motivation
Airbnb is a leading marketplace where members list the properties, which can be booked by users for stay. It published dataset related to its property listings in Seattle and Boston from 2016.

Considering the availability of detailed attributes related to property listings along with the pricing over the year 2016 and reviews, it provides a great opportunity to understand the market dynamics of Airbnb property listings of Seattle and Boston over the year. The analysis of such dataset can reveal how various attributes related to the property like location, amenities, size etc. as well as time period of the year and day of the week might be influencing the booking price of each property on Airbnb.

## Install

The code is written in Python 3 with Jupyter Notebook. A set of libraries used in this analysis include 
numpy, 
pandas, 
matplotlib, 
seaborn and
NLTK. 
Execute the following code in a Notebook cell to install NLTK:
nltk.download()`

## Data Description
Data used in this project are included in the \data folder.
It includes three data files 'calendar.csv', 'listings.csv', and 'reviews.csv'. A detailed description on these files can be found at the Kaggle link provided in the first paragraph of this readme file.<br>
Data is available in the Zip file.

## Business Questions

What are top 5 neighborhoods with most no of listings? <br>
What are average listing price for each neighborhood? <br>
Which is the busiest season of the year and how prices changed during peak season? <br>
What factors of the listing correlate best for predicting the price ? <br>

## Summary of the results
# 1. The top 5 neighborhoods with most no of listings are:
      Other neighborhood: 800 listings
      Capitol Hill: 560 listings
      Downtown: 520 listings
      Central Area: 360 listings
      Queen Anne: 290 listings

# 2. What are average listing price for each neighborhood?
     Average price for eachneighborhood are represented through a point graph in the jupyter notebook
     Mangolia has the heighest average price.

# 3. Which is the busiest season of the year and how prices changed during peak season?
     Average listing price reached to the peak on July and August. These are the most busienst months of the year.
    
# 4. What factors influence the booking price of property?
      booking price is highly correlated with attributes like number of people that property can accommodate, number of bedrooms, beds         and size in square feet. 
      
## Acknowledgement
This project wouldn't have been possible in the case of inavailability of datasets provided by Airbnb team. Thanks to Kaggle for hosting the dataset and making it easily accessible to large data science community. Thanks to Udacity reviewers team for providing valueable feedback on improving this project. Special thanks to open source contributors for creating and maintaining wonderful libraries like Pandas, Numpy, Matplotlib, Scikit Learn, Seaborn and Jupyter Notebook other dependencies of these libraries.




