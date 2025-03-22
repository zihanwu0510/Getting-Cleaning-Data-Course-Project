# Codebook

## Introduction
The original dataset has been processed based on the following five steps:
* Merges the training and the test sets to create one data set.
* Extracts only the measurements on the mean and standard deviation for each measurement. 
* Uses descriptive activity names to name the activities in the data set
* Appropriately labels the data set with descriptive variable names. 
* From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Dataset
[UCI HAR Dataset](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)

## Variables
* The original **code** column has been replaced by specific activity names.
* The **Acc** in column names has been replaced by "Accelerometer".
* The **Gyro** in column names has been replaced by "Gyroscope".
* The **Mag** in column names has been replaced by "Magnitude".
* The redundant **BodyBody** in column names has been replaced by "Body".
* **t**, **f**, **mean**, **std** has been replaced by "Time", "Frequency", "Mean", and "StandardDeviation".

** TIDY_DATA
The final tidy data set has 10299 rows and 88 columns.
The final average data set (which shows the average of each variable for each activity and each subject) has 180 rows and 88 columns.
