# Twitter Bot Retweet
## Overview
This Python script twitterbot_retweet.py is designed to automate retweeting, liking tweets, and following users on Twitter based on specified configurations.

## Functionality
The script utilizes Tweepy, a Twitter API library, to perform the following actions:
.Retweet tweets based on a defined query.
.Like tweets (optional, based on configuration).
.Follow users who tweeted (optional, based on configuration).

## Usage
1. Ensure you have installed the required libraries by running the following commands:
pip install tweepy
git clone https://github.com/tweepy/tweepy.git
cd tweepy
pip install .
2. Set up your Twitter API credentials:

3. Create a file named credentials.py and include your Twitter API keys (consumer_key, consumer_secret, access_token, access_token_secret) in the format specified in the sample credentials.py.
Modify the configurations in config.py:
QUERY: Define the search query for tweets.
FOLLOW: Set to True if you want the bot to follow users.
LIKE: Set to True if you want the bot to like tweets.
SLEEP_TIME: Adjust the sleep time between actions if needed.

4. Run the script:
python twitterbot_retweet.py
Configuration
Adjust the bot's behavior by modifying the variables in config.py:

QUERY: Search query for tweets.
FOLLOW: Set to True to enable following users.
LIKE: Set to True to enable liking tweets.
SLEEP_TIME: Time interval between actions (in seconds).

## Requirements
Python 3.x
Tweepy library: Install using pip install tweepy


## Disclaimer
Please use this script responsibly and in compliance with Twitter's terms of service. Excessive automation or misuse may lead to account suspension.
