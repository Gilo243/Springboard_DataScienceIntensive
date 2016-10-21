# Capstone Project Proposal

Twitter data constitutes a rich source that can be used for capturing information about any topic imaginable. Users share thoughts, links and pictures, commenting on live events and with approximately 500 million tweets sent per day, there is a wealth of data to analyse and play with.

One such recent event that has been very well documented on Twitter is 'Brexit', an abbreviation that refers to the "British exit" of the European Union. I plan to take a deep dive exploration into Twitters take on Brexit and, in particular, look into tweet sentiment and whether it can be used to identify Brexit opinion. 

Data will be mined via the Twitter Search API, which is  part of Twitters REST API. To this purpose I will use Tweepy, a Python library for accessing the Twitter API, to extract two distinct datasets of Brexit related tweets (Pre & Post referendum). Preliminary filters will be applied on the tweets captured through the functionality of the API, for example restricting the location of tweets to the UK via the geocode parameter and filtering out all retweets.

Once the data has been collected and appropriate data cleaning techniques applied, EDA will identify interesting trends including trending hashtags, tweets with most retweets and users of importance. Then taking these learnings, I will look at contructing an algorithm that can be used as a valid indicator of Brexit political sentiment. Deliverables will be in the form of project code/report and a slide deck summary.