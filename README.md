# Distinguishing between Cats and Dogs using Tensorflow

## Goal of the Project: 
The goal of this project was to use TensorFlow to create a script that could distinguish between cats and dogs as well as create a resilient AI system that could be trained to increase the accuracy of distinguishing between cats and dogs.

## Tools Used:
Visual Studio Code
Images of cats and dogs database
Libraries(Keras, TensorFlow, cv2)

## Methodology:
In order to create this script many libraries had to be imported so that the system could be trained to distinguish between these two animals. As seen in the image to the right, the libraries that were downloaded were NumPy, pandas, cv2, matplotlib, TensorFlow, Keras, os, and zipfile. 
After importing all of these libraries the system is instructed to unzip the training and testing databases so that all of those pictures of cats and dogs need not be stored in the folder itself. After unzipping and extracting the files, the main and training directories were determined and the path that the system would take to access those files was given. Then the system was told that a cv2 library would be used to read these images in the database into an array. These images will be read as grayscale images and their size has been restricted to 80 by 80. Then this function is called and the pictures are reshaped and added to the array. After they are added to the array, a new sequential model is made so that the training process can begin. First, a  densely-connected layer with 64 units is added to the model and then another 64-unit layer is added. After this, the layers are flattened so that the training period wouldn’t take days. After that, it was compiled with some default optimizations in mind and it is trained. After it was trained a test run of whether or not it would properly identify the photos was programmed. The system would classify them all and then add them to a .csv file, which is a data record file. 

## Challenges Faced:
The main challenge that I faced was learning how to use Tensorflow. This is because the deep learning process is very complicated due to the convolutional neural network layers. Each layer has its own function and even if a small value is changed, the models will react differently and the accuracy of the training model will be altered significantly. Therefore, a lot of experimenting was done to see how each value would impact the results. 
