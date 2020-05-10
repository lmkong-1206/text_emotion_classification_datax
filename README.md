# text_emotion_classification_datax
Modified based on https://github.com/mankutimma/text-emotion-classification.

We mainly use packages numpy, pandas and tensorflow that we discussed in data-x lecture.

In the code, we first import packages and load the dataset 'data/text_emotion_train_val_set.csv' in the data folder. Then we clean the dataset by removing the data not in the sentiment label 'happy', 'sad', 'surprise', 'hate' and love and tokenizing the text message. Then we split the dataset into training set and test set. We train a classification model using Neural Network approach with text message as feature and sentiment labels as response. After we get the classifier, we obtain the accuracy on training ste and test set respectively. Finally, we build a predict function that predict the sentiment of a sentence based on our model.

Running the file 'text_emotion_classification_notebook.ipynb' step by step can get the result that we present.
