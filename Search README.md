# MovieMahal
This is the first development first and we wish to develop a search feature, where given a query shows all the matching results taking into account the tf-idf and cosine similarity scores.

The code was made to run on google colab as it is easy and code tracing is convenient.

We take two csv files tmdb_5000_movies and tmdb_5000_credits.

Step1:

1.First we need to create a index for our dataset.



2.The inverted index contains mappings from term to the movie names that those terms appear in .



3. We take into consideration the concepted of weigted votes and rank the movies based on their popularity.



4.We filter the title removing all the stop words.



5. Now we develop tfidf features for our movie over view and remove all the duplicate titles and matching with the indices of respective movies



Step2:

1. After developing the tfidf features and calculating the scores we aim to develop features where in we can filter our movies based on exta features apart from name and plot.




2.We create a soup joining all the keywords,production_house name,directors name,genre. So that when we search for a movie we can get all the query matching results and also the results that is common to all features.This simply makes search engine more efficient.


MovieMahal
