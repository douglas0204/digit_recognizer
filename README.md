This is a Kaggle competition project. you can refer to link for this Kaggle competition https://www.kaggle.com/c/digit-recognizer/overview (Training & test dataset can also be downloaded from the link)

Project object:
This digigt recognizer project is to build machine learning model to visually recognize hand-written digits. 

Dataset:
hand written digit image with 28*28 pixel. I use 42000 examples for training data, 28000 examples for testing data.

Machine Learning Model:
Neural Network model by using TensorFlow library. You can check the model structure below. 
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 dense (Dense)               (None, 256)               200960    
                                                                 
 batch_normalization (BatchN  (None, 256)              1024      
 ormalization)                                                   
                                                                 
 dropout (Dropout)           (None, 256)               0         
                                                                 
 dense_1 (Dense)             (None, 64)                16448     
                                                                 
 batch_normalization_1 (Batc  (None, 64)               256       
 hNormalization)                                                 
                                                                 
 dropout_1 (Dropout)         (None, 64)                0         
                                                                 
 dense_2 (Dense)             (None, 10)                650       
                                                                 
=================================================================
Total params: 219,338
Trainable params: 218,698
Non-trainable params: 640
_________________________________________________________________

Test Result: 99% accuracy
