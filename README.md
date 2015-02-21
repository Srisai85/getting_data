Getting and Cleaning Data Course Project

A brief description of how the run_analysis.R script works.

It is assumed that tthe zip file is already downloaded from "https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip" and unzipped
inside the working directory.

Load or Source the "run_analysis.R" file in R.

The script merges the training and the test sets to create one data set into a file named "merged_data.txt"


The script then extracts only the measurements on the mean and standard deviation for each measurement, uses descriptive activity names to name the activities in the data set and appropriately label the data set with descriptive variable names. 

From this data set, a second, independent tidy data set with the average of each variable for each activity and each subject is created and named "means.txt"