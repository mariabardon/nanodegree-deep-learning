## Project Overview

The end product of this work is an application that, given an image of a dog, it estimates the dog's breed. If given an image of a human instead, the application will detect so, and will identify the resemblance of that person with a dog breed. The application uses different models, first detect if there is a human in the image, a second model to detect if there is a dog in the image, and a third model to classify the dog breed of the image.  

The first model (used to detect if there is a human face in the image), is an already implemented face-detector provided by OpenCV and located at haarcascades/haarcascade_frontalface_alt.xml. For the second model (used to detect a dog in an image) we use a pretrained vgg classification model. For the third model we create and train a CNN model from scratch and compare it with a CNN model that uses transfer learning from resnet. 

## Other useful notes

The network architecture, training and testing is done in the notebook dog_app.ipynb. 

The file workspace_util is used to keep the cnn training in a remote gpu while there is no activity in my computer. 

The files model_scratch.pt and model_transfer.pt keep the parameter results of the most accurate epoch. 

The folder haarcascades contains an program that detects human faces in images. This has been provided by OpenCV, and the XML files are on github:
https://github.com/opencv/opencv/tree/master/data/haarcascades

The folder 'data' contains the sets of human and dog breeds used for training and testing our application. 

The folder 'images' contains images used in the explanations of dog_app.ipynb notbook.


If you want to use parts of this project, please do not forget to follow the **Udacity Honor Code** and reference the used material. 
