# MovieMahal
Classifier Phase

In this phase our aim is to build a prediction model that can basically predict the genre of the movie given the plot.
The code is made to run on google colab for convienent and easy code tracing purpose.

Step1:

1.We load dataset movies.csv and our aim is to target genres of individual movie and basically split them as our dataset is not that refined


2.After splitting the genre now we check for the genre coverage throughout the data set and calculate the individual genre count.



3.We similarly caluculate number of distinct genre, the most number of genres featuring throughout and individual genre cumulative frequencies.

Step2:

1.Now we take into consider the movie plots of each movie . First we clean the plot by removing unnecessary punctuations,symbols and converting the text into lower case.


2.Now we vectorize our plot and calculate all the distinct words for each movie plot for all the movies and train them against the genre.



Step3:

1.We build our prediction model were we feed our training data.


2.The dataset were trained with multinomial naive bayes classifier and was compared with linearSVC classifier.


3.We get the accuracy readings for each genre given the plot.


Results:


1.linearSVC performed better across all the genres when compared to multinomial naive bayes classifier.


2.Some hyperparameter tuning were done and the minute changes in the results were recorded.


