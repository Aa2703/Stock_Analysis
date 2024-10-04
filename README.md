##Stock Movement Analysis Based on Social Media Sentiment

#Project Overview
This project aims to analyze and predict stock price movements by leveraging sentiment analysis of social media data. By extracting relevant discussions from platforms such as Reddit, we aim to understand how public sentiment correlates with stock performance. The sentiment is derived from stock-related posts, and the goal is to explore how sentiment trends can potentially influence stock price changes.


#Key Features:
•	Data Collection: Scraping posts from subreddits like r/wallstreetbets and r/stocks.
•	Sentiment Analysis: Analyzing public sentiment using natural language processing techniques.
•	Stock Price Prediction: Investigating the relationship between sentiment and stock price movement using historical stock price data.
Project Objectives
•	Scrape Reddit posts using Python’s asyncpraw library and extract stock mentions for companies such as Apple, Tesla, AMD, Google, and Microsoft.
•	Perform sentiment analysis on scraped Reddit posts to categorize sentiment into positive, neutral, or negative classes.
•	Integrate historical stock price data to analyze the impact of sentiment on stock movements.
•	Build a predictive model that can anticipate stock price changes based on social media sentiment.




#Table of Contents
•	Installation
•	Data Sources
•	Data Collection
•	Sentiment Analysis
•	Stock Price Integration
•	Predictive Modeling
•	Results
•	Future Work
•	Contributing
•	License
Installation
To get started, clone this repository and install the required dependencies.
bash



#Copy code
git clone https://github.com/Aa2703/Stock_Analysis.git
cd Stock_Analysis
pip install -r requirements.txt





Dependencies:
•	Python 3.x
•	pandas, numpy - for data manipulation
•	asyncpraw - for scraping Reddit posts
•	yfinance - for fetching stock price data
•	scikit-learn - for sentiment analysis and modeling
•	matplotlib, seaborn - for data visualization
•	nltk, VADER - for sentiment scoring


#Data Sources
This project uses two primary sources of data:
->Reddit: Social media posts from subreddits like r/wallstreetbets and r/stocks are scraped using the asyncpraw library.


#Data Collection
Reddit data is collected by scraping relevant posts using the asyncpraw library. 
The following fields are extracted from each post:
->Title: Title of the post
->Text: Post content
->Score: Upvotes/downvotes of the post
->Subreddit: Subreddit from where the post was fetched
->Date: Timestamp of the post
->Stock Mentions: Whether specific stocks like AAPL, TSLA, or MSFT are mentioned in the post

