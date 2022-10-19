# Exploration of WeRateDogs Data set¶

## Data Set

WeRateDogs is a Twitter account that rates several people's dogs with humourous comment(s) about their dog. I want to create interesting and trustworthy analyses and visualizations. The Twitter archive provided only contains very basic tweet information. Additional gathering, then assessing and cleaning will be done for a worthy analyses and visualizations.

## Insights

1. Which dog stage has the highest favorite counts compared to other dogs stages?
2. Is there a correlation between favorite count and retweet count?
3. What is the top 5 Favorite Dog breed?

## Requirements

- Python 3+
- Jupyter notebook
  (Installing Anaconda is an easier route to downloading these packages)

## Libraries

- Numpy
- Pandas
- Matplotlib
- Seaborn
- requests
- BeautifulSoup
- lxml
- os
- io
- tweepy
- twython
- json
- timeit
- re

## Steps

1. Data Gathering

Three pieces of data were gathered by:

- Downloading the provided file, 'twitter_archive_enhanced.csv' manually. Once it is downloaded, I will upload it and read the data into a pandas DataFrame.

- Download programmatically the 'image-predictions.tsv' using the Requests library and the following URL: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv

- Gather each tweet's retweet count and favorite ("like") count using the tweet IDs in the WeRateDogs Twitter archive, query the Twitter API for each tweet's JSON data using Python's Tweepy library and store each tweet's entire set of JSON data in a file called tweet_json.txt file.
  Each tweet's JSON data should be written to its own line. Then read this .txt file line by line into a pandas DataFrame, tweet ID, retweet count, and favorite count.

Note: - There is no need to gather the tweets beyond August 1st, 2017 because you won't be able to gather the image predictions for these tweets since you don't have access to the algorithm used.

2. Assessing the data : Visually and Programmatically

3. Data Cleaning : Quality and Tidiness issues

4. Store the data

5. Analyze and Visualize the data set

## Summary of Findings

The findings from this investigation showed generally that :

- Doggo and Pupper dog stage have the highest favorite counts of about 98000
- There is a positive correlation between Favorite count and Retweet count
- The top 5 favorite dog breeds according to counts are golden_retriver, labrador_retriever, chihuahua, pembroke and pug.

```python

```
