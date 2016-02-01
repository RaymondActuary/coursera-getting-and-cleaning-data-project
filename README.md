# coursera-getting-and-cleaning-data-project

This is the course project for the Getting and Cleaning Data Coursera course. The R script, run_analysis.R, does the following:
1. Set working directory to folder with datasets
2. Read in the data from files
3. Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation
4. Loads the activity and subject data for each dataset, and merges those columns with the dataset
5. Merges the two datasets
6. Converts the activity and subject columns into factors
7. Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.

The end result is shown in the file tidyData.txt.
