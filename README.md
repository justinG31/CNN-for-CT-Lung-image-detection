# CNN-for-CT-Lung-image-detection
Justin Gomez, Avery Merlo

Description
----

This project examines a multi-class dataset of chest ct-scans prediction capability with the use of a VGG19-CNN model. We first collect the dataset from kaggle provided below splitting the data into training and validation sets. Following similar work done in the field of differentiating chest ct-scans for different lung diseases, COVID and Pneumonia with the most prevelance, we also have classes for normal images and lung-opacity images creating a total of 4 classes. Utilizing packages in tensorflow and keras, we implement a VGG19-CNN model and conduct transfer learning, pre-training the model with 'imagenet' and then using to top layers plus activation layers on our data. 

In the notebook we provide two examples of the VGG19 model differentiating by the optimizer. First we start by running the model with the optimizer 'adam' following previous work, then we hypothesize that we will achieve similar validation accuracy if not better utilizing stochastic gradient descent (sgd). 


Input and Output
----
Download the dataset from kaggle: https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database
The output will be the evaluation of the model and plots of the model loss and model accuracy.


How to Run
----

### 1: Clone Git Repository

Clone the repository using 'git clone https://github.com/justinG31/CNN-for-CT-Lung-image-detection.git'

### 2: Transfer the jupyter notebook to google drive 

Either clone the repository directy to google drive or just move the file over to utilize a gpu on the model. 

### 3: Confirm directory file paths

When mounting to google drive, confirm the file paths for the directory will work and all the images are downloaded

### 4: Run the notebook

(Command/CTRL + F9) or Run all 

