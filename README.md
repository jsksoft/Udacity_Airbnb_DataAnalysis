# Udacity_Airbnb_DataAnalysis
Analyzing Boston Airbnb data using the CRISP-DM Process<br>
Udacity Nanodegree: Date Science

## Objective
Within the Udacity Nanodegree: Data Science, I had the project to analyse Airbnb data from Boston, MA. For this analysis I used the CRISP-DM Process (Cross Industry Process for Data Mining). I worked on the following questions: 

- In which time in the year does Boston have the most bookings?
- What is the most extensive and cheapest area in Boston?
-  Does the mean price of the location influence the numer of bookings?
- Is there a general correlation between the number of rooms (e.g. bedrooms) and the price of an accommodation?

## Libraries
The following python libraries are used for the project:
- Pandas
- Numpy
- Matplotlib
- Seaborn

## Dataset
The dataset can be downloaded on Kaggle: https://www.kaggle.com/airbnb/boston
It contains the follwing files:
- lisings.csv
- calender.csv
- reviews.csv

## Results
- Besides the September months the number of bookings is pretty constant between around 45,000 and 63,000 bookings per month. 
- Nevertheless, December and January have a shlitly higher amount of bookings with values > 60,000.
- South Boston Waterfront is the most expensive location in Boston with a mean price of above $300 while Mattapan is the cheapest location in Boston with mean prices below $100.
 - It does not look like that there is a big correlation between the number of bookings and high-price or low-price locations. 
- In general, the higher the number beds, bedrooms or bathrooms, the higher will be the median price of an accommodation. 

My results are summarized on a blog post which can be found here:  
https://jklinder.medium.com/being-successful-at-airbnb-in-boston-7a15357c7037
