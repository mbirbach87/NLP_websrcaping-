Project 3: Web APIs & Classification
Content
This repository contains a few Jupyter Notebook containing code that shows how I  imported data by web scraping Reddit’s API. The main summary notebook shows how I took my gathered data (CSV files) in order to perform EDA and ultimately build a model predicting which subreddit a given post would land in.

Description of the data set
The dataset consists of data that was scrapped from Reddit’s API through Python'. I scraped  JSON files and used NLP to clean up the data. I used CountVectorizer and TfidVectorizer to create features from the thread title and descriptions. The two subreddit’s used for gathering data were stocks and weather. 2,000 posts were collected with 1,000 coming from each subreddit.

Models utilized
RandomForestClassifier
LogisticRegression
