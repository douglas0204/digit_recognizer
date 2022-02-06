This is a Kaggle competition project. you can refer to link for this Kaggle competition https://www.kaggle.com/c/digit-recognizer/overview (Training & test dataset can also be downloaded from the link)

Project object:
This digigt recognizer project is to build machine learning model to visually recognize hand-written digits. 

Dataset:
hand written digit image with 28*28 pixel. I use 42000 examples for training data, 28000 examples for testing data.

Machine Learning Model:
Neural Network model by using TensorFlow library. Overview of the model structure is below. You can check the code for detail. 
____________________________
 Layer (type)               
============================
 dense (Dense)                                                                                
 batch_normalization (BatchNormalization)                                 
 dropout (Dropout)                        
 dense_1 (Dense)                                               
 batch_normalization_1 (BatchNormalization)                                                 
 dropout_1 (Dropout)                      
 dense_2 (Dense)                   

Test Result: 99% accuracy
