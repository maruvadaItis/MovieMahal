# MovieMahal

This is the third development stage. Where we wish to develop textual descriptions out of a image using image recognition features.


The code was made to run on google colab as it is easy to use and code tracing is convenient.

Step1:-

1. We first pip install tensorflow


2.Then load all the images from cocodataset and also the image captions d=from the file.This dataset has almost 4 lakh captions . Each movie having 5 possible captions.


3.We read the individual files and then store the caption and images as vectors.


4.We can choose the number of captions to train from.If the dataset will be large then results will be better.


5.I select 40000 captions and train them


6.We load images and get unique images


7.We also capture unique vocabulary and select first 5000 words unique ones from captions.

Step2:

1.We split the dataset in 80-20 fashion.


2.We can tune the hyperparameters according to the system configuration. I first chose size of 64 and then dropped it to 32 for experimental results purpose.


3.We implement attention features to predict and therby implement bahdanau attention.


4.Then we use CNN encoders and RNN decoders .


5.We run the code for 20 epoch and plot the loss graph against epoch.


6.Then we try to feed in image url and then model predicts the captions.


Results:

The model seem to work better for batch size = 32 as the loss is less and we get good prediction results.


We can get higher accuracies if we increase the number of training captions and select optimum batch size.






MovieMahal
