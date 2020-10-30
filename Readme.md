Project Description

The package essentially works towards classifying audio files. It has varied applications majorly useful but not restricted to classification and prediction of the genre of songs by inputting a repository/library of music as source data and the testing file. The package develops an ANN model using the source data and predicts the class of the test data.

Authors: Chinmay Joshi, Nihal Todankar, Saumya Nauni, Harshit Bhavnani, Timothy Thampy, Anup Mishra

Function Description

1.  load\_features(data\_path):

This function is essentially responsible for taking the path of the source data as an input and processing the features (mfcc) of the data that can be used in the development of a model.

1.  load\_filename(data\_path):

This function creates an array of the filenames and the inclusions of the input dataset.

1.  predict\_categorical(x,y,epochs,x\_test,y\_test):

An integral function that develops a sequential ANN model of 5 layers - 4 Relu and 1 Softmax and compiled categorically. For the purpose of fitting, a batch size of 128 is hard-coded. The function returns a prediction of the class of the audio file.
