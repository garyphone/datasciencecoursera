# Peer-graded Assignment: Getting and Cleaning Data Course Project

## Introduction

One of the most exciting areas in all of data science right now is wearable computing - see for example this [article](http://www.insideactivitytracking.com/data-science-activity-tracking-and-the-battle-for-the-worlds-top-sports-brand/).
Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. 
The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone.
A full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

## Dataset

Here are the data for the project:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

## Files

* `run_analysis.R` performs the data preparation and then followed by the 5 steps 
required as described in the course project’s definition:

	* Merges the training and the test sets to create one data set.
	
	* Extracts only the measurements on the mean and standard deviation for each measurement.
	
	* Uses descriptive activity names to name the activities in the data set.
	
	* Appropriately labels the data set with descriptive variable names.
	
	* From the data set in step 4, creates a second, independent tidy data set with the average of 
	each variable for each activity and each subject.

* `CodeBook.md` is a code book that introduces the variables, the data, and any transformations or works to
clean up the data.

* `tidy_data.txt` is the obtained data after using the R script.




























