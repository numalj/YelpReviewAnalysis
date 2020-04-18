# YelpReviewAnalysis

This project scrapes the Yelp website to extract customer reviews of restaurants and builds a data set. The data set was used to train a **Naive Bayes classifier** that uses **Sentiment Analysis** to predict whether a review is positive (more than 3 stars) or negative (less than 3 stars).

**Things learnt:**
- Using the Yelp API to find the business ids of restaurants in the area
- Inspecting the Yelp webpage to find REST endpoints that can be queried to request review data
- Scraping and parsing reviews off of the Yelp website using xpath. Beautiful soup is another viable option for this
- Measures were taken to try and keep an equal number of positive and negative reviews, in order to avoid imbalance of the dataset
- Performing basic sentiment analysis on the extracted data
- Training a Naive Bayes Classifier
- Using the validation set to measure the model's performance

