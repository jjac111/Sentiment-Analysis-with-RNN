# Sentiment-Analysis-with-RNN
Small python project that trains an RNN to identify the sentiment of a comment ot text. The program takes a string of text as an input and returns a predicted boolean value determining the positiveness of the text. This project is developed and explained thoroughly in a Jupyter Notebook file. 

## Data
The data used to train the model is extracted from the IMDB dataset for movie reviews. The reviews are tokenized and set to a maximum standard length, while the vocabulary is set to a maximum of 5000 words.

## Model 
The designed AI model is a mix of an Embedding layer + Recurrent layer (LSTM) + Dense layer.

## Training
The model is then trained with a training set of the data for 5 epochs. With this little training time the model is able to reach 85% accuracy.

The key difference in this project with most sentiment analysis is that we are not just using a Bag of Words for the inputs, but we also take the sequence into account.
