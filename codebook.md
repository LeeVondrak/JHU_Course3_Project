# JHU_Course3_Project - Codebook
The variable descriptions in run_analysis.R are as follows:

* X_train: dataframe - 7352 obs. of 561 variables - training observations and values for the various measurements
* y_train: dataframe - 7352 obs. of 1 variables - the activity ID performed for each observation in X_train
* subject_train: dataframe - 7352 obs. of 1 variables - the subject for each ovservation in X_train
* X_test: dataframe - 2947 obs. of 561 variables - testing observations and values for the various measurements
* y_test: dataframe - 2947 obs. of 1 variables - the activity ID performed for each observation in y_train
* subject_test: dataframe - 2947 obs. of 1 variables - the subject for each ovservation in y_train
* features: dataframe - 561 obs. of 2 variables - the second column is the list of names to be used for column names for the X_ dataframes above
* activity_labels: dataframe - 6 obs. of 2 variables - the translation between activity ID and actual activity
* merged_data: dataframe - 10299 obs. of 563 variables - a table of the training and testing sets along with the subject
* meanStdColumns - vector - 1:81 - a vector of indices for the mean and standard deviation columns
* merged_data_mean_std - dataframe - 10299 obs. of 81 variables - subsetting the data with only the columns from the vector above
* merged_data_mean_std_descriptive: datafrane - 10299 obs. of 82 variables - same dataframe as above but with the actions' names
* avg_by_activity_subject: dataframe - 180 obs. of 82 variables - the average of each of the measurements by subject and activity