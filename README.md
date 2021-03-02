# Natural Language Processing

This code is just about basics of sentiment analysis which consists of training a machine to understand some text and predict a certain outcome for these texts.
So in this case study here these text are reviews of a restaurant and we'll have to train a machine to understand if each review is positive or negative.
This is a very simple and classic way to be introduced to NLP.
We can try diverse machine learning models to tackle this problem. Indeed the essential part of our implementation will be to build the bag of words model but then once
it is built we can try several classification models. Why classification models? That's because we'll have to predict a binary outcome 1 or 0. 1 meaning the review is positive
and 0 meaning the review is negative. So we have actually the flexibility to try several machine learning models.
The dataset is .tsv(tab seperated values) file instead of .csv.  
the dataset contains only two columns. The first one containing all the reviews. We have in total 1000 reviews.
We're going to train a machine learning model to actually understand text and predict if it is positive or negative.
And then the second column shows if the review is positive or negative.
So one means that it is positive meaning the customer liked it and zero means that the review is negative.
And of course we have the real outcomes in order to train our machine learning model to understand if each of these text is positive or negative.

