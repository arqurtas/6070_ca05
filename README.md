# kNN Movie Recommender Engine
This is a kNN-based movie recommender engine implemented in Python. The engine uses the IMDB rating, and genre information (Biography, Drama, Thriller, Comedy, Crime, Mystery, and History) to recommend similar movies. The dataset used for training the model is available in the movies_recommendation_data.csv file.

The dataset is available in the movies_recommendation_data.csv file. You can access it using the following URL: https://github.com/ArinB/MSBA-CA-Data/raw/main/CA05/movies_recommendation_data.csv

- Building a Recommender System

Imagine you are creating your own movie suggestion website and incorporating this back-end recommendation engine. Consider a person visiting your website and finding the movie "The Post" there. Although the user is undecided about whether they want to watch it, the categories it belongs to pique their interest. The back-end algorithmic gears start turning as soon as the user scrolls down to the "More Like This" section to see what suggestions your recommendation website will make.

Your website asks its back end to return the top 5 films that are most like "The Post." A suggestion dataset identical to ours is present in the back end. A feature vector for "The Post" is first created, after which a program like the one below is used to look for the five films that are most like "The Post," and lastly the results are sent back to the user at your website.

The genre information for the movie "The Post" is as follows:

IMDB Rating = 7.2, Biography = Yes, Drama = Yes, Thriller = No, Comedy = No, Crime = No, Mystery = No, History = Yes

- Libraries Required:

Pandas library (pip install pandas)
Scikit-learn library (pip install scikit-learn)
