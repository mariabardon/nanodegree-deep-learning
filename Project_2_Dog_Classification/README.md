## Project Overview

The end product of this work is an application that, given an image of a dog, it estimates the dog's breed. If given an image of a human, the application will identify the resembling dog breed. It uses different models to, first, classify the image as either dog or human image, and then to either look for the breed or the resemblance. 




## Project Instructions

The network architecture, training and testing is done in the notebook dog_app.ipynb. 

The file workspace_util is used to keep the cnn training in a remote gpu while there is no activity in my computer. 

The files model_scratch.pt and model_transfer.pt keep the parameter results of the most accurate epoch. 

The folder haarcascades contains an program that detects human faces in images. This has been provided by OpenCV, and the XML files are on github:
https://github.com/opencv/opencv/tree/master/data/haarcascades

The folder data contains the sets of human and dog breeds used for training and testing our application. 

The folder images contains images used in the explanations of dog_app.ipynb notbook.




