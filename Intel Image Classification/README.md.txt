# **Project title: MultiClass Image Classification using CNN**

**Objective:**
The main objective of this project is to develop a Deep Learning CNN model capable of 
appropriately classifying images according to their respective labels. The problem statement of the 
project is to identify which kind of scene can the image be categorized into accurately.

**Approach:**
The steps to be followed in this project are as below:
1) Downloading the dataset (Intel Image Classification from Kaggle).
Link: https://www.kaggle.com/puneet6060/intel-image-classification/download
2) Loading the data (both train as well as test).
3) Exploring and visualizing the image data present in the dataset i.e. Performing Exploratory Data 
Analysis (EDA)
4) Data pre-processing using the ImageDataGenerator library from Keras.
5) Defining and building the CNN model’s architecture with the help of different layers such as 
convolutional, maxpooling, flatten, dense layers.
6) Compiling the model and summarizing it out
7) Training the model to appropriately classify the images according to their labels.
8) Evaluating the model’s performance such as accuracy and loss and plotting them.
9) Saving the model and then loading it to test the model.
10) Predicting the image and visualizing it.
11) Perform transfer learning, i.e with a pre-trained model, extracting the already learned features, 
evaluating the model’s performance and predicting the images in order to test whether the model 
has performed well or not i.e to improve the model’s performance.

**Assumptions:**
It is assumed that the after training the model, it would achieve atleast 80% training accuracy and 
might perform even better after transfer learning where the learned features get transferred to the 
model and then trained for the better performance of the model. It is assumed that if the model is 
trained properly with correct CNN architecture the chances of overfitting and underfitting are less.

**Exceptions:**
The only exception I agree to is that due to a larger dataset, it might be possible that the model 
which will be trained from scratch might not reach a threshold accuracy level required for the 
model to work completely fine in classifying the images and because of that it is possible that my 
model would overfit. Also there are chances that the pre-trained models might also not be trained 
to a level of accuracy as compared to their performance with the classes they contain in their 
dataset as I might bring in some changes in some of its layers according to my defined dataset.

**Enhancement Scope:**
The model can perform even more better when transfer learning is applied to it. The project can be
further enhanced by integrating the model in the Android platform i.e apply the image classification 
concept in mobile devices. It can also be used for the physically disabled people to identify different 
images.
*************************************************Please note :*****************************************************
Before starting the procedures please install the libraries informed below in a virtual environment:
1.os
2.tqdm
3.OpenCV
4.Numpy
5.Pandas
6.Matplotlib
7.PILLOW
8.Tensorflow
9.Keras
10.IPython
11.Random
12.Pathlib
13.Glob
14.Datetime
15.Pydotplus

***********************************************STEPS TO START THE APP**********************************
1.Open the zip file.
2.Extract it to the directory which has all the python files and libraries.
3.Open the Anaconda Prompt(Anaconda3).
4.Activate the virtual environment which includes all the libraries required to run the file.
for example <base> C:\Users\(username)\activate (virtual environment name)
5.Then change the directory to Intel Image Classification.
for example <(virtual environment name)> C:\Users\(username)\cd Intel Image Classification
6.Then type the following command: python app.py runserver
for example <(virtual environment name)> C:\Users\(username)\cd Intel Image Classification\python app.py runserver
7.Then the server IP Address will be displayed on the Anaconda prompt screen. The server IP Address is 127.0.0.1:5000 or you can run it on any default server
8.Open this IP Address on any of the Web browser(Chrome usually preferrable for better output) and you will be able to view the Web Application.And the app is ready to use!
9.Now you have to just click on the buttons given and select the images.

The link to the working of Web Application is provided below:
https://drive.google.com/file/d/105jXGhSjaz0_6HGZd6Q7gaeIN5IU1-af/view?usp=sharing