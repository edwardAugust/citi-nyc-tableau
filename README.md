# City Bike analysis

# Approach

I first attempted to upload multiple csv documents, and my computer wasn't happy with that
However the map still loaded and I able to explore that data and see the hotspots.
Definitely seemed like stations in midtown were very popular.

# Methods

I worked with two CSV files, one from March 2019 and May 2020.
From here I parred down the file using pandas. Also to reduce run time from using
two large files I narrowed my scope to the top 20 start stations for each.
I then split the dataframe into three, linked by duration time.
One for latitudinal and longitudinal data,
another for time data,
and the last for demographics.


# Conclusion

There was a definite marked difference between the two years. Although ridership may have dropped, new patterns emerged,
a nascent class of users (50-59) merit further investigation
In the future I would like to spend more time cleaning the data with pandas, and familiarizing myself with more tableau features.