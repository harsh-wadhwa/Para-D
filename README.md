# Para-D
Detecting Malaria using CV and Machine Learning

## What it is?
- ParaD is a model which will predict whether the image of a cell is infected by parasite or not.
- In most cases, personal examination through microscope is the only way to diagnose malaria. 
- Which requires skilled Laboratory Technician, which increases the cost and time of the diagnosis.
- Also since it is done manually the accuracy of diagnosis is low as compared to model.

## Process
- Data Preprocessing - Load the images from dataset and assign labels
- Splitting - The loaded dataset is split into training dataset and test dataset.
- Model - A CNN model is created using keras 
- Training - The model is trained using the training dataset

## Data
- The dataset has been taken from: https://ceb.nlm.nih.gov/repositories/malaria-datasets/
- The dataset contains 2 folders
- Parasitized
- Uninfected
- And a total of 27,558 images.

## Libraries Used
- Numpy
- Tensorflow/Keras
- Sklearn
- Matplotlib
- OpenCV (cv2)
