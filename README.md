# toxic_comment_classification
Our input features which will be our inputs to our DNN architecture will be the column consisting of the comments text.

As our input features are in the form of a text and not in the form of numbers and integers which is usually prefferd by the ML algorithms we will have to find a way to convert the raw text in the form of integers so that they can be fed to our model. (how to do this explained later)

Also the input texts are of different lengths. But our model expects the input sequences to have the same length. So we need to find a way to make all the lenght of input sequences equal.

Coming to our labels that we have to predict, we got in total six predictor classes. Depending on the input text we have to predict to which class our input text can be classified.

The values of our output labels are 0 and 1, corresponding to whether a particular statement can be classified in that class or not.
