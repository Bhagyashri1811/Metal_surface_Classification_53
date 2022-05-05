# Metal_surface_Classification_53
One page brief of the project 

Definition,
The project is about the detection and classification of the defect on the strongly reflected surface. 
Need to classify the defect into 6 different classes. The classes are Crazing, inclusion, patches, pitted surface, rolled-in-scale, and scratches.

Data set details,
The data set is consisting of two folders one is for training and the other is for validation.
The training folder and validation folder consist of six folders of defects. In the training set, each folder is consisting of 240 grayscale images and in validation, each folder is consisting of 60 grayscale images. Therefore the total number of images is 1440 in the training set and 360 in the validation set. Total grayscale images are 1800.

Feature taken,
The features taken are the part and patterns of the image where the defect is been found. The images are read through imread function and is been converted to the array for the features extraction.

Algorithms used,
SVM (support vector Machine)
Random Forest 
KNN (K-nearest Neighbor)

Result (performance parameters all)
Confusion matrix
Accuracy Score
Classification report which consists of a precision, recall, f1-score, and support for each class.

Training and testing time along with machine hardware description,
Using Laptop: Training time = 20 minutes.
Hardware Intel core i5, RAM 8GB, ROM 1TB

Data set file/link
Link for dataset:
https://www.kaggle.com/datasets/kaustubhdikshit/neu-surface-defect-database

Code run in Personal laptop in google colab.

Name: Bhagyashri Khimsuriya
Roll no: 91900133053
