Getting and Cleaning Data Week 4 Project

This repository includes the essential components for the Week 4 peer-graded assignment, focusing on obtaining and cleaning data using R.

Files:

CodeBook.md
This document provides comprehensive guidance on utilizing the contents of this repository. It details the variables, the dataset, and outlines any transformations or procedures executed to enhance the cleanliness of the data.

run_analysis.R
Contained within this script is the R code that facilitates the analysis. It follows a structured approach, comprising five steps:

Merging the training and test sets to construct a unified dataset.
Extracting only the measurements pertaining to the mean and standard deviation for each measurement.
Employing descriptive activity names to label the activities in the dataset.
Appropriately labeling the dataset with descriptive variable names.
Generating a second, independent tidy dataset from the dataset in step 4. This dataset includes the average of each variable for each activity and each subject.
FinalTidyData.txt
This text file represents the output of the final step in the analysis. It contains the cleaned and organized data with averages for each variable across activities and subjects.
