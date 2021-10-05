Create R script called run_analysis.R and include following:


In the firest donwload file and assign data tables to variables.


1.Merges the training and the test sets to create one data set.

Merges x_train and x_test in x variable
and y_train and y_test in y variable
and subject_train & subject_test in subject variable

Merges all data by use cbind() function


2.Extracts only the measurements on the mean and standard deviation for each measurement. 

create tidyData by measurement mean and SD.


3.Uses descriptive activity names to name the activities in the data set

replace with corresponding activity taken from second column


4.Appropriately labels the data set with descriptive variable names. 

replace "Acc" to "Accelerometer"
replace "Gyro" to "Gyroscope"
replace "BodyBody" to "Body"
replace "Mag" to "Magnitude"
replace start with "t" to "Time"
replace start with "f" to "Frequency"
replace "tBody" to "TimeBody"
replace "angle" to "Angle"
replace "gravity" to "Gravity"



5.From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

create means of each variable



export to FinalData.txt
