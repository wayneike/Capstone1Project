# Capstone Project #1
Object Detection, classification and data analysis

## Part 1 - Object Detection and classification
Develop an AI model using a deep learning framework that predicts the type of vehicle present in an image as well as localizes the
vehicle by rectangular bounding box.

1. Create a parent folder for custom model training and child folders to store data
1. Prepare the dataset for model training and keep the following points in mind while
preparing it
    - This dataset contains many images, and depending on the compute power of the VM, it
might take a very long time to unzip this huge amount of data.
1. Create an CNN architecture for object detection of your choice to train an object detection
model. Please note that algorithm or architecture selection is a very important aspect of ML
model training, and you must pick the one that works the best for your dataset.
1. Evaluate the model and check the test results
1. Run inferences on sample images and see if vehicles are detected accurately

Jupyter Notebook can also be found here:

https://colab.research.google.com/drive/1KUza684s1diMVJGh7_mBHEk8JqF28y5P?usp=sharing

## Part 2 - Data Analysis
Analyze the usage of autopilot and its effect on road safety.

1. Preliminary data inspection and cleaning
a. Perform preliminary data inspection, checking for data types, missing values, and duplicates
b. Remove any columns that might not be relevant for the analysis
1. Exploratory Data Analysis
* Perform an in-depth exploratory data analysis on the number of events by date, per year, and
per day for each state and country
* Analyze the different aspects of the death events. For example:
    - What is the number of victims (deaths) in each accident?
    - How many times did tesla drivers die?
    - What is the proportion of events in which one or more occupants died?
    - What is the distribution of events in which the vehicle hit a cyclist or a pedestrian?
    - How many times did the accident involve the death of an occupant or driver of a Tesla
along with a cyclist or pedestrian?
    - What is the frequency of Tesla colliding with other vehicles?
* Study the event distribution across models
d.Check the distribution of verified Tesla autopilot deaths