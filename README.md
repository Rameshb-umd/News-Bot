# News Bot 
(https://twitter.com/Rate_Tweets_Bot)


The AutoReply Bot( @Rate_Tweets_Bot ) created for this assignment responds with three tweets
whenever a user mentions the bot in their tweet. The bot looks for a specific format in the tweet
to perform four different function.

Twitter provides features for viewing hashtags that are trending, however, the features only
provides options to view the stream of tweets that contains the hashtags. When the stream of
tweets is viewed it does not provide a clear picture of the trending story or displays the tweets
from a credible account at the top. In order to overcome this problem the bot is created which
will find a credible tweet and present to the user to understand trending news. This bot looks for
the best tweet that summarizes the trending story by calculating the validity of the source, the
exposure and interaction score of each tweet and sends the top three tweets to the user so that
users can understand the trending story better by directly looking at the top three tweet’s content

  - ***Search a phrase/word from the public stream and summarize and reply back top three popular
tweets.***
  - ***Search a phrase/word from the list of user timelines and summarize and reply back top three
popular tweet.***
  - ***Find top 3 tweets among all the news accounts.***
  - ***Find top 3 tweets among all the news accounts and also include tweet account that interests
the user.***

**Search a phrase/word from the public stream and summarize and reply back top three popular tweets**  
**Input** : ‘@Rate_Tweets_Bot #Brussels Attack#’  
**Output**: Top 3 Tweets containing the Phrase ‘Brussels Attack’ and its rating and exposure
statistics.
**Method**: The bot collects tweets with given phrase from all the accounts till a set limit is
reached. The tweets are then rated based on tweet’s potential exposure or audience and also the
rate of interaction with the tweet and tweet owner’s account. It also takes in account tweet
owner’s verification status. After the tweets are rated, top three tweets with their statistics are
replied back to the user.
* * *
**Search a phrase/word from the list of user timelines and summarize and reply back top three
popular tweet**  
**Input** : ‘@Rate_Tweets_Bot @Cnn #Brussels Attack#’  
**Output**: Top 3 Tweets containing the Phrase ‘Brussels Attack’ and its rating and exposure
statistics.
**Method**: The bot collects tweets with given phrase list of accounts the bot follows and also the
account the user have mentioned in their tweet till a set limit is reached. The tweets are then
rated based on tweet’s potential exposure or audience and also the rate of interaction with the
tweet and the tweet owner’s account. It also takes in account tweet owner’s verification status.
After the tweets are rated, top three tweets with their statistics are replied back to the user.
* * *
**Find top 3 tweets among all the news accounts**  
**Input** : ‘@Rate_Tweets_Bot send me trending news tweets’.  
**Output**: Top 3 Tweets among the set of news tweets account and its rating and exposure
statistics.  
**Method**: The bot collects recent 50 tweets from all the news accounts that the bot follows. The
tweets are then rated based on tweet’s potential exposure or audience and also the rate of
interaction with the tweet and the tweet’s owner account. After the tweets are rated, top three
tweets with their statistics are replied back to the user.
* * *
**Find top 3 tweets among all the news accounts and also include tweet account that interests the user**  
**Input** : ‘@Rate_Tweets_Bot @cnn @fox send me trending news tweets’  
**Output**: Top 3 Tweets among the set of news tweets account and its rating and exposure
statistics.  
**Method**: The bot collects recent 50 tweets from all the news accounts that the bot follows and in
addition to the predefined list it also collects tweets from accounts that the user has mentioned in
their list. The tweets are then rated based on tweet’s potential exposure or audience and also the
rate of interaction with the tweet and the tweet’s owner account. After the tweets are rated, top
three tweets with their statistics are replied back to the user.
* * *

