# Sentiment-analysis

Hii, People 
I know i have not add dataset but you don't know that I imported these data from twitter and help of twitter API.
for the data(tweet) i had to create Twitter Developers Account.

Let me tell you all the steps for Import tweets from the Twitter:

1).Go on https://developer.twitter.com/en

2).Create a new account or sign in with existing twitter account

3).And fill all the details they asking for like why do you want api and tweets.

4).Agree to all conditions (Read all condition carefully it will help you)

5).In the Next page you have to name your twitter app.

6).After that you get your API Keys

7).There are three types of Account 

    A).Essential
    
    B).Elevatad
    
    C).Academic Research
    
These all are free account but it will take 2-4 business days to allow access.

8).You get open API and secret API Keys to use in code.

9).Install 

pip install Tweepy

For authentication

#authenticate
auth = tw.OAuthHandler(consumer_key, consumer_secret)
auth.set_access_token(access_token, access_token_secret)
api = tw.API(auth, wait_on_rate_limit = True)

And you are ready to analysis on tweets.
