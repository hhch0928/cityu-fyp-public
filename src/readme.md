# Stock Price Prediction Using Social Media Posts in FinTech

This is a repository developed for CityU Computer Science Final Year Project.  
It served as a POC for using social media post to train a prediction model for stock market price.  
Moreover, it use LLAMA LLM Model by Meta to get the stock ticker and an emotional value.

## Data Source
The Tweets Data is retrieved from Kaggle [Company Ticker Tweets 2018-2023 NLP](https://www.kaggle.com/datasets/h4t3h4k3rs/ticker-tweets-2018-2023) By Vsevolod Ovchinnikov

## Before Run
You need to apply for Cloudflare Account to acquire your own account ID and Token  
Notice that you need to pay if u run whole project.  
Then you need to put it in the .env  
> CLOUDFLARE_ACC_ID = "Your_Account_ID_Here"  
> CLOUDFLARE_TOKEN  = "Your_TOKEN_Here"

## Running Step
1. Ensure ./data/tweets/original/tweets.csv Exist
2. CleanPostData
3. SocialMediaScore
4. GetStockData
5. GroupPostData
6. MergeData
7. TrainModelWithScore
8. GetPrediction