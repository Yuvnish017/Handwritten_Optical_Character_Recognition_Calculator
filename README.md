# Handwritten Optical Character Recognition Calculator
The project aims at creating pipelines for training CNN model for recognising digits and some basic arithmetic operators and for using the trained model to solve
mathematical equations from images containing handwritten characters.

## Prerequisites
* Python==3.8.5
* imutils==0.5.3
* numpy==1.19.5
* seaborn==0.11.1
* opencv_python_headless==4.5.1.48
* pandas==1.1.5
* matplotlib==3.3.0
* tensorflow_cpu==2.4.1
* scikit_learn==1.0.1
* tensorflow==2.7.0

## Description of Files and Folders
* data folder - contains dataset and test images
* Handwritten_Optical_Character_Recognition_Calculator.ipynb - python notebook containing codes for loading the dataset, preprocessing, data visualization, training the model,
visualization of results and testing pipelines for equation solving.
* maths_symbols_and_digits_recognition.h5 - trained model
* requiremnents.txt - contains the prerequisites mentioned above

## Dataset
The dataset was taken from https://www.kaggle.com/sagyamthapa/handwritten-math-symbols.
The dataset contains images of handwitten digits as well as four basic arithmetic operators namely - Add, Subtract, Multiply, and Divide.
