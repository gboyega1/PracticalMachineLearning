# PracticalMachineLearning
Coursera Machine Learning Project Documentation

## PROJECT SUMMARY

Devices such as Jawbone Up, Nike FuelBand, and Fitbit now make it possible to collect a large amount of data about personal activity relatively inexpensively.
People regularly quantify how much of a particular activity they do, but rarely quantify how well they do it.
We shall utilize data from accelerometers on the belt, forearm, arm, and dumbell of 6 male participants aged between 20 and 28 years who were asked to perform barbell lifts correctly and incorrectly in 5 different ways.
The goal of this project is to predict the manner in which the participants did the exercise. The manner is categorized as follows

1. (Class A), Performing the exercise exactly according to the specification

2. (Class B), throwing the elbows to the front

3. (Class C), lifting the dumbbell only halfway

4. (Class D), lowering the dumbbell only halfway

5. (Class E) and throwing the hips to the front

## DATASETS

The links to the training and testing sets used for this project are given below

Training: http://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv
Testing: http://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv


## METHODOLOGY

1 As stated in the project summary, we are trying to predict the manner in which the test subjects performed the exercises. This is represented by the "classe" variable which has 5 distinct values; letters A to E. That makes this a classification problem. We shall build our prediction model using Random Forest.

2. Using Cross Validation, we shall further split the provided training set into a training and test set in the ratio 75:25 so that the testing set provided will be used to validate our model

3. Model Building: this is a classification problem and we shall build our prediction algorithm using either random forest or decision trees and this will be heavily dependent on the number of predictors.

3. The out of sample error should be 1 less the accuracy of the prediction model when applied to the test set
