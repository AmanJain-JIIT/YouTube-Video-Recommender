# YouTube-Video-Recommender
ML Project on YouTube videos recommendation using cosine similarity

It's a machine learning project on youtube video recommendation.

Dataset : youtube.csv Recommender : recommender.py

Libraries Used :

NumPy : Linear Algebra library 
pandas : for data reading and data pre-processing 
difflib : for finding closest match to the input taken from user in case of any spelling mistakes 
sklearn.featue_extraction : TfidfVectorizer -> to convert textual dataset into numeric features 
sklearn.metrics.pairwise : cosine_similarity -> to find similarity among rows in the dataset 
Tkinter : UI library of python

The dataset consists of 3600 videos along with columns like index, title, link, category, channel, etc.....

The dataset has been first pre-processed and concerned features are extracted from the dataset 
Features extracted from daatset : a. Title b. Link c. Channel d. Category

Then those selected features are converted to numeric data using TfidfVectorizer

Then the similarity is calculated using cosine_similarity function

Then the recommender function is implemented, so as to find 10 similar videos to the video given by the user as his last watched video

UI of the application is designed using Tkinter library of python
