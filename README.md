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
   - Downlaod FER 2013 data set by above link.
    
   - unzip the data set
    
  - Find **HOG features** of images and store HOG features and labels in data list.
       - HOG, or Histogram of Oriented Gradients, is a feature descriptor that is often used to extract features from image data. 
          It is widely used in computer vision tasks for object detection.
    
   - store data list in a pickle file for easy computation.
## Multi class classifier:   

### 1) SVM(Support Vector Machine)

-Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

-The goal of the SVM algorithm is to create the best line or decision boundary that can segregate n-dimensional space into classes so that we can easily put the new data point in the correct category in the future. This best decision boundary is called a hyperplane.

 - we use **sklearn.SVC** to implement SVM

-SVM chooses the extreme points/vectors that help in creating the hyperplane. These extreme cases are called as support vectors, and hence algorithm is termed as Support Vector Machine. Consider the below diagram in which there are two different categories that are classified using a decision boundary or hyperplane:

### 2) Decision Tree
  - Decision Tree is a Supervised learning technique that can be used for both classification and Regression problems, but mostly it is preferred for solving Classification problems. It is a tree-structured classifier, where internal nodes represent the features of a dataset, branches represent the decision rules and each leaf node represents the outcome.
   
- In a Decision tree, there are two nodes, which are the Decision Node and Leaf Node. Decision nodes are used to make any decision and have multiple branches, whereas Leaf nodes are the output of those decisions and do not contain any further branches.

- The decisions or the test are performed on the basis of features of the given dataset.
- It is a graphical representation for getting all the possible solutions to a problem/decision based on given conditions.

- It is called a decision tree because, similar to a tree, it starts with the root node, which expands on further branches and constructs a tree-like structure.
- In order to build a tree, we use the CART algorithm, which stands for Classification and Regression Tree algorithm
