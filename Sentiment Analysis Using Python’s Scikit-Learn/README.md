# A Complete Sentiment Analysis Project Using Python’s Scikit-Learn

Comparing two different vectorizers and three machine learning models for a sentiment-analysis project in Python
Sentiment analysis is one of the most important parts of Natural Language Processing. It is different than machine learning with numeric data because text data cannot be processed by an algorithm directly. It needs to be transformed into a numeric form. So, text data are vectorized before they get fed into the machine learning model. There are different methods of vectorization. This project will demonstrate sentiment analysis using two types of vectorizers and three machine learning models.

Data Preprocessing:

1. The dataset has about 183,500 rows of data. There are 1147 null values. I simply will get rid of those null values.
2. As the dataset is pretty big, it takes a lot of time to run some machine learning algorithm. So, I used 30% of the data for this project which is still 54,000 data. The sample was representative.
3. If the rating is 1 and 2 that will be considered a bad review or negative review. And if the review is 3, 4, and 5, the review will be considered as a good review or positive review. So, I added a new column named ‘sentiments’ to the dataset that will use 1 for the positive reviews and 0 for the negative reviews.

The Final result is shown in the Jupyter file