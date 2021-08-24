# ASL alphabet classification
## Project disctiption
Project is the part of the AI course project dedicated to ASL alphabet classification using CNN.

## Goal of the project
Application of the CNN and ResNet models to the sign language pictures classification. To develop computer vision system that translate sign language to spoken language in streaming video. As first step, towards understanding how to build a translation system, we can reduce the size of the problem by translating individual letters, instead of sentences.

## Project tasks
1. Data preparation
2. Applying CNN model 
3. Applying ResNet model
3. Models comparison

 ## Set Up 
<code>notebook.ipynb</code>: Python code 
 
 ## Data 
The data set is a collection of images of alphabets from the American Sign Language, separated in 29 folders which represent the various classes. The training data
set contains 87,000 images which are 200x200 pixels. There are 29 classes, of which 26 are for the letters A-Z and 3 classes for <code>SPACE</code>, <code>DELETE</code>and <code>NOTHING</code>. Link to the [Kaggle Dataset](https://www.kaggle.com/grassknoted/asl-alphabet).

## Data preparation
Creating smaller train and test data frames 2900 images for train. Training set for the model: 64x64 colour images. Lebel map: From 0 to 28 for each
letter and special signs.

## Models Comparison
Train: 100 examples from each of the 29 classes => 2900 examples
Test: same as above, but different images 100 epochs, batch_size = 64
