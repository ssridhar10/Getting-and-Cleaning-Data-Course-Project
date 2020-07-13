Source data:
A full description is available at the site where the data was obtained:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
Here is the data for the project:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Purpose of R script
Create one R script called run_analysis.R that does the following.
1.	Merges the training and the test sets to create one data set.
2.	Extracts only the measurements on the mean and standard deviation for each measurement.
3.	Uses descriptive activity names to name the activities in the data set
4.	Appropriately labels the data set with descriptive variable names.
5.	From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject
Code Book:

Variables
.	x_test, y_test, subject_test, x_train, y_train, subject_train, data_features, activity_labels contains the data from the downloaded files.
.	train_combine, test_combine are merged data sets
.	data_features contains the names of all features.

Functions
.	Tidy data contains 180 observations of 480 variables of specifically mean and standard deviations.

