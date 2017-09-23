# Getting and Cleaning Data - Course Project

This is the course project for the Getting and Cleaning Data Coursera course.
The R script, `run_analysis.R`, does the following:

1. Download and unzip the dataset if it does not already exist in the working directory.
2. Merge the training and the test sets to create one data set.
3. Extract only the measurements on the mean and standard deviation for each measurement.
4. Use descriptive activity names to name the activities in the data set.
5. Create a second, independent tidy data set with the average of each variable for each activity and each subject.

The end result is shown in the file `secTidySet.txt`.