# Getting-and-Cleaning-Data-Week-4-Assignment

This repo was created to finish the assignment for week 4 of Getting and Cleaning Data Coursera course.
* First, download and unzip the data file into your R working directory approximately of 60 MB.
* Second, download the R source code into your R working directory.
* Finally, execute R source code to generate tidy data file.

The decription and data link is given in the course assginment.

### The code was written based on the instruction of this assignment as given in coursera course.
Read training and test dataset into R environment.
Read variable names into R envrionment.
Read subject index into R environment.

1. Merges the training and the test sets to create one data set.
Use command rbind to combine training and test set
2. Extracts only the measurements on the mean and standard deviation for each measurement.
Use grep command to get column indexes for variable name contains "mean()" or "std()"
3. Uses descriptive activity names to name the activities in the data set
Convert activity labels to characters and add a new column as factor
4. Appropriately labels the data set with descriptive variable names.
Give the selected descriptive names to variable columns
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
Use pipeline command to create a new tidy dataset with command group_by and summarize_each in dplyr package
