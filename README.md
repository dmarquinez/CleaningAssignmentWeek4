Getting and Cleaning Data Course Project
================

## Purpose

The purpose of this project is to demonstrate the ability to collect,
work with, and clean a data set. The goal is to prepare tidy data that
can be used for later analysis.

## Data set / input

The data set is collected from the accelerometers from the Samsung
Galaxy S smartphone. You can download it in the following link but it’s
unnecesary because the script will do it for you.  
[Zip to download the data
set](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)  
[Full
description](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

## Files of the data set

The dataset includes the following files:  
\* `features_info.txt`: Shows information about the variables used on
the feature vector.  
\* `features.txt`: List of all features.  
\* `activity_labels.txt`: Links the class labels with their activity
name.  
\* `train/X_train.txt`: Training set.  
\* `train/y_train.txt`: Training labels.  
\* `test/X_test.txt`: Test set.  
\* `test/y_test.txt`: Test labels.  
The following files are available for the train and test data. Their
descriptions are equivalent.  
\* `train/subject_train.txt`: Each row identifies the subject who
performed the activity for each window sample. Its range is from 1 to
30.  
\* `train/Inertial Signals/` : This directory is irrelevant to our
project.

## Analysis

I followed the next steps:

1.  Merged the training and the test sets to create one data set.
2.  Extracted only the measurements on the mean and standard deviation
    for each measurement.
3.  Changed the names of the activities in the data set.
4.  Changed the labels with descriptive variable names.
5.  Generated a data set with the average of each variable for each
    activity and each subject.

## Output

The new data set is in
[`averages.txt`](https://github.com/dmarquinez/CleaningAssignmentWeek4/blob/master/averages.txt)
with the averages of the mean and the standard deviation of each subject
and activity. The details of each variable are in the
[`CodeBook.md`](https://github.com/dmarquinez/CleaningAssignmentWeek4/blob/master/CodeBook.md)
file.

## Other files in this repository

In this repository you can find:  
\*
[`README.md`](https://github.com/dmarquinez/CleaningAssignmentWeek4/blob/master/README.md)
: This file that you are reading.  
\*
[`README.Rmd`](https://github.com/dmarquinez/CleaningAssignmentWeek4/blob/master/README.Rmd)
: RMarkdown file to generate
[`README.md`](https://github.com/dmarquinez/CleaningAssignmentWeek4/blob/master/README.md).  
\*
[`CodeBook.md`](https://github.com/dmarquinez/CleaningAssignmentWeek4/blob/master/CodeBook.md)
: Info about the variables along with units, values, etc.  
\*
[`CodeBook.Rmd`](https://github.com/dmarquinez/CleaningAssignmentWeek4/blob/master/CodeBook.Rmd)
: RMarkdown file to generate
[`CodeBook.md`](https://github.com/dmarquinez/CleaningAssignmentWeek4/blob/master/CodeBook.md).  
\*
[`run_analysis.R`](https://github.com/dmarquinez/CleaningAssignmentWeek4/blob/master/run_analysis.R):
**The script.**

## Sources

  - [Getting and Cleaning the Assignment. Blog by David
    Hood](https://thoughtfulbloke.wordpress.com/2015/09/09/getting-and-cleaning-the-assignment/)
  - Coursera forum
  - [Stackoverflow](https://stackoverflow.com/) and google, obviously.
  - [RMarkdown](https://rstudio.com/wp-content/uploads/2015/03/rmarkdown-spanish.pdf)
