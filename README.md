This is my solution to Coursera project for the Getting and Cleaning Data Course. 
The R script run_analysis.R, does the following steps:

1. Download the dataset if it does not already exist in the working directory
2. Load the activity and feature info
3. Load the training and test datasets, keeping only those columns which reflect a mean or standard deviation, loads the activity and subject data for each dataset, and merges those columns with the dataset
4. Merges the two datasets
5. Converts the activity and subject columns into factors
6. Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
7. The end result is shown in the file tidy.txt
