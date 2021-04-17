# SoilClassification-Demo
An introduction to image classification and model interpretation in Tensorflow

### Background:
Classification of soils can be an extremely important skill in many different fields including geotechnical engineering, agricultural science, construction, and even the at-home gardening. While many classification schemes exist, a popular and intuitive way of classifying soils is based on soil grain size, such as gravel, silt, sand, etc. This is a rather simple way of looking at soil since there are firm cutoffs between each classification. For example, gravel is any grain over 2 mm in diameter, sand is between 1/16 mm to 2 mm, and silt/clay is smaller than 1/16 mm.  

### Objective
In this exercise, you will use computer vision to make a simple classification nodel of soils based on photos of gravel, sand, and silt. A convolutional neural network framework is provided below and will be used to complete the objective of the exercise. Your objective is to run several models, by changing key parameters such as the number of convolutional layers and the number of nodes in each convolutional layer within the CNN. Then, you will use the Tensorflow callback Tensorboard to determine which model preformed best.
