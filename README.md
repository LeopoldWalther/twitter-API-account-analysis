# Wrangle and analyze data of WeRateDogs Twitter posts

This project is part of the Udacity Nanodegree Data Analyst. It is based on data
gathered via the downloaded twitter archive of the WeRateDogs account,
twitter-API queries and a file downloaded programmatically using the Requests
library.

## Quickstart
 _xxx_ :

```$ conda```



## Structure

1. Gather: Data is gathered from three different sources of data as described
   in steps below:
   - The WeRateDogs Twitter archive. File twitter_archive_enhanced.csv as comma separated file in local directory.
   - The tweet image predictions, i.e., what breed of dog (or other object, animal, etc.) is present in each tweet according to a neural network. This file (image_predictions.tsv) is hosted on Udacity's servers at URL.
   - Each tweet's retweet count and favorite ("like") count at minimum, and any additional data. Using the tweet IDs in the WeRateDogs Twitter archive, query the Twitter API for each tweet's JSON data using Python's Tweepy library and store each tweet's entire set of JSON data in a file called tweet_json.txt file. Each tweet's JSON data should be written to its own line. Then read this .txt file line by line into a pandas DataFrame with (at minimum) tweet ID, retweet count, and favorite count. Note: do not include your Twitter API keys, secrets, and tokens in your project submission

## Dependencies
The following python libraries are used in the project:
- pandas
- NumPy
- requests
- tweepy
- json

## Known Bugs
