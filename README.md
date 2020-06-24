# CNN-Model-for-Image-Sentiment-Prediction-and-Confusion-Matrix-
CNN Model for Image Sentiment Prediction and Confusion Matrix 


*******************************************************************************************************
This is work is on CNN Model for Image Sentiment Prediction and Creating Confusion Matrix in Data Frame
*******************************************************************************************************

Package Version
python 3.6.8
numpy  1.16.1  
skimage 0.16.2
pandas 0.24.1
keras 2.2.4                  

The image sentiment prediction is carried out using CNN model. 
The images are read from the given folder and corresponding ground truth labels are read into a data frame.
From the input images a image set suitable for CNN model is prepared.

The cross validation is with stratified folds is performed and for each fold the performance of the CNN is evaluated on both train set and test set.
The true positive, false positive, true negative and false negative are collected for train and test set.
A data frame 'performanceTb' is created to store true positive, false positive, true negative and false negative values.

Please set the imPath to the folder consisting of images seperated by two backslash

For example: c:\\\images\\\

A sample of images are kept here, please see the below link for complete image set.
http://www.ee.columbia.edu/ln/dvmm/vso/download/twitter_dataset.html

Further Projects and Contact
www.researchreader.com

https://medium.com/@dr.siddhaling

Dr. Siddhaling Urolagin,
dr.siddhaling@gmail.com

