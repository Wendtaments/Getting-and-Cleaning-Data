###CodeBook Project-Run


##The Dataset

The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

Data source: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

You will find a detailed description of the dataset with all its variables here: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones


##Transformation of the data

From downloading the date there are 5 steps to recreate the analysis in Project Run:

-The first step merge the test and training sets to create one single data set.
-The second step extract only the mean and standard deviation measurements for each record.
-The third uses descriptive "activity names" to name the activities in the dataset.
-The fourth step appropriately labels the dataset with descriptive activity names.
-The final step creates a second tidy dataset with the average of each variable for each activity and each subject.


##Replication:

To recreate the transformations above you need to:

-Install and load the reshape2 and data.table librareis.
-Load both test and train data
-Load the features and activity labels.
-Extract the mean and standard deviation column names and data.
-Process the data. There are two parts processing test and train data respectively.
-Merge data set.