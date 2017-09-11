This project goal is to combine 2 datasets, countries and tweets, and to get meaningful results using Spark.
The first dataset contains such fields like country, country code. The second dataset contains field - tweet_text, it is a column of the database collection stored using MongoDB. This column was extracted to form a CSV file which stores only texts of all tweets.
A data frame was created from the first dataset by filtering data. The second dataset was cleaned to get rid of empty tweets and split into words. These words were counted based on the Map Reduce paradigm. A produced data frame contains words with numbers of their occurrences in tweets.
Both data frames are merged into one on countries names. After that data about all the countries can be analyzed.

This project is a final assignment for the Big Data integration and Processing course of the Big Data Specialisation (Coursera)
