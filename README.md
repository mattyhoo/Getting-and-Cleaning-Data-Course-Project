# Explanation of analysis performing script ('analysis_performing_script.R')

Line 1 ~ 7: read in dataframe from 'subject_test.txt','X_test.txt','y_test.txt','subject_train.txt','X_train.txt','y_train.txt', 'features.txt';

Line 8: bind x_test and x_train by row;
Line 9: bind y_test and y_train by row;
Line 10: bind subject_test and subject_train by row;

Line 11 ~ 13: add descriptive varible names to subject, y, x dataframes;

Line 14: bind subject, y, x dataframes side by side;

Line 15 ~ 21: use descriptive activity names to name the activities in the data set

Line 22: extracts only the measurements on the mean and standard deviation for each measurement;

Line 23: export the tidy data set as 'merged_mean_sd.csv';

Line 24: load dplyr package;

Line 25: create second tidy data set by averaging each variable for each activity and each subject in the first tidy data set;

Line 26: export the second tidy data set as 'ave_merged_mean_sd.csv'


