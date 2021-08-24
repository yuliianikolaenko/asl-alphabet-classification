# ASL alphabet classification
## Project disctiption
Project is the part of the AI course project dedicated to ASL alphabet classification using CNN.

## Goal of the project
Application of the CNN and ResNet models to the sign language pictures classification. To develop computer vision system that translate sign language to spoken language in streaming video. As first step, towards understanding how to build a translation system, we tried reduce the size of the problem by translating individual letters, instead of sentences.

## Project tasks
* [Data preparation](#Data-preparation)
* [Applying CNN model](#CNN-model)
* [Applying ResNet model](#ResNet-model)
* [Models comparison](#Models-comparison)


 ## Set Up 
<code>notebook.ipynb</code>: Python code 
 
 ## Data 
The data set is a collection of images of alphabets from the American Sign Language, separated in 29 folders which represent the various classes. The training data
set contains 87,000 images which are 200x200 pixels. There are 29 classes, of which 26 are for the letters A-Z and 3 classes for <code>SPACE</code>, <code>DELETE</code>and <code>NOTHING</code>. Link to the [Kaggle Dataset](https://www.kaggle.com/grassknoted/asl-alphabet).

![alt text](https://github.com/yuliianikolaenko/asl-alphabet-classification/blob/main/asl.png)

## Data preparation
Creating smaller train and test data frames 2900 images for train. Training set for the model: 64x64 colour images. Lebel map: From 0 to 28 for each
letter and special signs.

## CNN model
![image](https://user-images.githubusercontent.com/51966068/130612844-c4368c64-6329-4321-a0b7-80be975aa84a.png)
## ResNet model
![image](https://user-images.githubusercontent.com/51966068/130612829-7bffe755-cbe6-4d67-aa9c-3e3bd08459e0.png)
## Models Comparison

