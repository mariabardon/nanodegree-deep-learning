## Project Overview

This is the second project that I did for the Udacity Deep Learning Nano degree.

In this project, I learned how to build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images.  Given an image of a dog, my algorithm got to identify an estimate of the canine’s breed.  If supplied an image of a human, the code will identify the resembling dog breed.  



## Project Instructions

The network architecture, training and testing is done in the notebook dog_app.ipynb. 

The file workspace_util is used to keep the cnn training in a remote gpu while there is no activity in my computer. 

The files model_scratch.pt and model_transfer.pt keep the parameter results of the most accurate epoch. 

The folder haarcascades contains an program that detects human faces in images. This has been provided by OpenCV, and the XML files are on github:
https://github.com/opencv/opencv/tree/master/data/haarcascades

The folder data contains the sets of human and dog breeds used for training and testing our application. 

The folder images contains images used in the explanations of dog_app.ipynb notbook.




