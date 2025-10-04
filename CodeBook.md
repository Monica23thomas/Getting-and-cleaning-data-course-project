# CodeBook

This code book describes the variables, the data, and transformations performed to clean up the data.

## Data Source
Human Activity Recognition Using Smartphones Dataset  
Version 1.0  
URL: https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones  

## Description
The experiments have been carried out with 30 volunteers. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) while wearing a smartphone.

The dataset includes sensor signals (accelerometer and gyroscope) pre-processed to obtain mean and standard deviation measurements.

## Variables

- **subject**: ID of the volunteer (1–30)
- **activity**: Activity performed
- **Other variables**: Mean and standard deviation of accelerometer and gyroscope measurements.  
  For example:
  - TimeBodyAccelerometerMeanX
  - TimeBodyAccelerometerMeanY
  - TimeBodyAccelerometerSTDX
  - FrequencyBodyGyroscopeMeanZ  
  (and so on)

## Transformations
1. Merged the training and test sets.
2. Extracted only mean and standard deviation features.
3. Replaced activity codes with descriptive names.
4. Labeled data with descriptive variable names.
5. Created a tidy dataset with the average of each variable for each subject and activity.

## Output
The final output is a tidy dataset: `tidy_data.txt`
