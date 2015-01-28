# How the code works:
Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement. 
Integrates the Subject numbers and the activity names (not numbers) to the combined table.
Uses descriptive activity names to name the activities in the data set.
Appropriately labels the data set with descriptive variable names. 

# The tidy_data table constraction
The first two columns are for Subject numbers and the activities measured. 
All other columns are mean and standard deviation values of the following measures:
tBodyAcc-XYZ
tGravityAcc-XYZ
tBodyAccJerk-XYZ
tBodyGyro-XYZ
tBodyGyroJerk-XYZ
tBodyAccMag
tGravityAccMag
tBodyAccJerkMag
tBodyGyroMag
tBodyGyroJerkMag
fBodyAcc-XYZ
fBodyAccJerk-XYZ
fBodyGyro-XYZ
fBodyAccMag
fBodyAccJerkMag
fBodyGyroMag
fBodyGyroJerkMag

# The average_data table constraction
contains the average value for each of the columns in the tidy_data table, for each subject, in each activity.
