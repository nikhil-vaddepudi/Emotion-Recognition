# Emotion-Recognition
Emotion Recognition using SVM, Decision Tree etc.

## AIM
Train a multi-class classifiers to recognize facial expressions (emotions).

## Data Set used:
#### FER 2013 data set is used in this project.
The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centred and occupies about the same amount of space in each image.

   The task is to categorize each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Neutral, 5=Sad, 6=Surprise). 
   
   ##### Link: https://www.kaggle.com/datasets/msambare/fer2013
   
## Preprocessing:
    1. Downlaod FER 2013 data set by above link.
    
    2.unzip the data set
    
    3. Find <mark>HOG features</mark> of images and store HOG features and labels in data list.
    
    4. store data list in a pickle file for easy computation.

