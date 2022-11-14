# we_rate_dog_tweets_analysis

The twitter_archive_enhanced.csv and image_predictions.tsv files of the WeRateDogs tweets
were gathered from udacity servers using the requests package. However, some information 
needed for analysis such as favorite_count and retweet_count was not available in the dataset
and needed to be queried from twitter. The tweepy package was used for querying tweet_ids
present in the twitter_archive_enhanced.csv and the result was stored a tweet_json.txt.

Analysis of the datasets were carried out to generate insights such as;
  1. The popular dog breeds
  2. Dog distribution among the four stages
  3. The common dog names
  4. Relationship between likes and retweets
  5. what is the most popular source of tweets for our dataset?
