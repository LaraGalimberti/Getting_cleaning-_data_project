# Getting_cleaning-_data_project
Getting and Cleaning Data - Final Project


Final project for the Getting and Cleaning Data Coursera course.

You'll find R script: run_analysis.R, that do:

- Download the dataset from web if it does not already exist in the working directory.
- Read train and test datasets, merge them into x(measurements), y(activity) and subject
- Load the data(x's) feature, activity info and extract columns named 'mean'(-mean) and 'standard'(-std). 
- Modify column names to descriptive. (-mean to Mean, -std to Std, and remove symbols like -, (, ))
- Extract only selected columns, and merge x, y(activity) and subject data.
- Replace y(activity) columns to it's name by refering activity label 
- Generate 'Tidy Dataset' that consists of the average (mean) of each variable for each subject and each activity. The result is shown in the file tidy_dataset_fin.txt.
