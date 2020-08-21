STEP 0: Data preparation
dataActivityTest  is a Dataframe from Test
dataActivityTrain is a Dataframe from Train
dataSubjectTrain is a Dataframe from Subject_train
dataSubjectTest is a Dataframe from Suject_test
dataFeaturesTest is a Dataframe from X_text
dataFeatruesTrain is a Dataframa from X_train

STEP 1: Merges the training and the test sets to create one data set
dataSubject is the concatenation of dataSubjectTrain anda dataSubjectTest by rows
dataActivity is the concatenation of dataActivityTrain and dataActivityTest by rows
dataFeatures is the concatenation of dataFeaturesTrain and dataFeaturesTest by rows

dataCombine  merges the columns of dataSubject and dataActivity
Data merges the columns of dataFeatures and dataConbine

STEP 2: Extracts only the measurements on the mean and standard deviation for each measurement 
subdataFeaturesNames is a subset of Features with mean() an std()
selectedNames is a Dataframe which subsets de Data Dataframe by selected names of Features


STEP 3: Uses descriptive activity names to name the activities in the data set
activityLabels contains descriptive activity names from "activity_labels.txt"

STEP 4: Appropriately labels the data set with descriptive variable names
No new variables.  In this part, names of Features will be labeled using descriptive variable names only.

STEP 5: Creates a second,independent tidy data set and ouput it
Data2 cointains the data for the new file.  It will be created with the average of each variable for each activity and each subject based on the data set in step 4.


