# <p align="center">Twitter Sentimental Analysis using Python</p> 

My Summer Project

### Introduction
This python code will help us understand the sentiment of people correspondong to any issue or incident, by analyzing their comments on social media websites. 
- Here, to connect with social media, we are using Twitter as the source of data. 
- To pull data from twitter, a developer account is created and its API keys are generated, which are hidden in the source code

### Project Description 
- The API keys are hidden using environmental variables, so you need to generate your own API key to run this code in your machine
- This python code uses TextBlob library, which will identify the polarity level of each word in the tweet and gives a score between 0 to 1 for each tweet. 
- The tweet which has a polarity score closer to **0** is considered a negative response and closer to **1** is considered a positive response
- This project requires two inputs from the user for analyzation
      1.  The keyword for which the analysis needs to be performed
      2.  The number of tweets that this analysis requires to extract from Twitter
- For example if the user give **Bitcoins** as a keyword and **300** as the tweet count, then the result will be generated in a pie chart as mentioned in the screen shot below. 
- Here we will be getting three results on the chart along with the percentage of each response
      1.  Positive response
      2.  Negative resopnse
      3.  Neutral  response

<p align="center"><img src="Twitter Sentimental Result.png"></p>
