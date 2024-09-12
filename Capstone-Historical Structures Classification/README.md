
# Capstone Project: Historical Structures Classification


## Project statement:

This project is part of Capstone project for Post Graduate programm in AI/ML.

There are hundreds of years-old historical structures that preserve a country's and 
community's history for future generations and promote tourism opportunities. 
To help the travel and tourism industries, it has been decided to use advanced machine 
learning techniques to monitor the condition of these historical structures and report to 
government agencies if any of them need maintenance. 
Also, understanding customers (tourists) and their expectations is critical for effective 
marketing. A recommendation engine is an excellent way to supplement existing 
marketing outreach to prospects. 

## Task at Hand:
The problem objective consists of two parts Part1 and Part2:

### Part1:

XYZ Pvt. Ltd., a leading industry consulting firm, has been hired to help the cause by 
developing an intelligent and automated AI model using TensorFlow that can predict the 
category of a structure in an image in Indonesia.

### Part2:

The second objective of this project requires you to perform exploratory data analysis 
and develop a recommendation engine that will help tourists visit their places of interest.

## Approach to the problem:

Part1:

I performed the following steps as part of building a AI model using tensorflow to predict the structure of the image.

1) Used the OpenCV library to plot the sample images for each category for better understanding.

2) Used base model as MobileNetV2 for transfer learning to build a CNN model on top of that.

3) Added appropriate number of dense layers with activation function and dropouts for regularization in the CNN model.

4) Defined callbacks to stop the training once the validation accuracy reaches an optimum value.

5) Trained the model with and without data augmentatio techniques to compare the validation accuracy.

Part2:

Build a recommender system based on Collaborative filtering technique to recommend tourists other places of interest based on current place name.



## Tech Stack

Python, Pandas, Numpy, Matplotlib, Seaborn, Sklearn, Tensorflows,Keras, Surprise, Open CV, Jupyter Notebook.

