# JHU_Course3_Project
## Getting and Cleaning Data Course Project Submission

The run_analysis.R file does the following:
* lines 1 - 15 read in all of the train, test, features, and activity label datasets
* lines 16 - 32 rename the columns for the various datasets read in
* lines 35 merges all the train and test data into one dataframe
* lines 38 - 40 subset only the columns with mean and standard deviations of various measurements
* lines 44 merges the subsetted data with the proper activity name
* lines 47 - 50 calculate the average of the measurements by subject and activity and writes the resulting table to a text file
