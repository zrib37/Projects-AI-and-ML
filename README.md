# Projects-AI-and-ML

Emotion Recognition project by Zaira Rib

DESCRIPTION
Future customizations, such as understanding human emotions, could lead to a range of advancements, such as determining whether a person likes a specific statement, item or product, food, or how they are feeling in a particular circumstance, and so on. 
 
Objective:
To build a model using a convolutional neural network that can classify a person's emotion
 
Dataset description:
The dataset contains two folders named Train and Test. These folders have approximately 35,000 images of seven different human emotions, such as anger, disgust, fear, happiness, neutral, sadness, and surprise.
 
•	Train folder: This folder has images for training the model, which is divided into subfolders having the same name as the class. 
•	Test folder: This folder has images for testing the model, which is divided into subfolders having the same name as the class.
 
The following operations should be performed using KERAS or PyTorch or Torch vision:   
1.	Import the necessary libraries
2.	Plot sample images for all the classes 
3.	Plot the bar graph for the number of images in each class for both training and testing data
4.	Build a data augmentation for train data to create new data with translation, rescale and flip, and rotation transformations. Rescale the image at 48x48
5.	Build a data augmentation for test data to create new data and rescale the image at 48x48
6.	Read images directly from the train folder and test folder using the appropriate function
