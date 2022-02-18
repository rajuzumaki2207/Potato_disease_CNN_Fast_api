# Potato_disease_CNN_Fast_api

The objective is to classify potato disease using images belonging to 3 different classes ['Potato___Early_blight', 'Potato___Late_blight', 'Potato___healthy'].
I have used CNN for training the images along with **tensorflow.data api** pipelines for effective usage of cpu and gpu

**Model Parameters**

 |Layer (type)                |Output Shape            | Param #   
 |----------------------------|-----------------------|-------
 |sequential (Sequential)  |  |(32, 256, 256, 3)      | 0         
 |                            |                       |          
 |sequential_1 (Sequential) | |(32, 256, 256, 3)      | | 0         
 |                            |                       |          
 |conv2d_30 (Conv2D)          |(32, 256, 256, 32)     ||  896       
 |                            |                       |          
 |max_pooling2d_30 (MaxPoolin |(32, 128, 128, 32)     | 0         
 |g2D)                        |                       |           
 |                            |                       |           
 |conv2d_31 (Conv2D)          |32, 126, 126, 64)      | 18496     
 |                            |                       |           
 |max_pooling2d_31 (MaxPoolin |(32, 63, 63, 64)       | 0         
 |g2D)                        |                       |           
 |                            |                       |           
 |conv2d_32 (Conv2D)          |32, 61, 61, 64)        | 36928     
 |                            |                       |           
 |max_pooling2d_32 (MaxPoolin |(32, 30, 30, 64)       | 0         
 |g2D)                        |                       |           
 |                            |                       |           
 |conv2d_33 (Conv2D)          |32, 28, 28, 64)        | 36928 
 -------------------------------------------------------------


Total params: 183,747
Trainable params: 183,747
Non-trainable params: 0



![alt text](https://github.com/rajuzumaki2207/Potato_disease_CNN_Fast_api/blob/main/Capture.JPG)
















![alt text](https://github.com/rajuzumaki2207/Potato_disease_CNN_Fast_api/blob/main/logo-teal.png)
