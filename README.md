# Getting and Cleaning Data

## Course Project

You should create one R script called run_analysis.R that does the following.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Steps to work on this course project

1. Set the working directory of R or RStudio to the location of ```run_analysis.R```.
2. Run ```run_analysis.R```.
3. ```run_analysis.R``` will download and unzip the datasets and install the dependencies automatically. It depends on ```data.table```. 
4. ```run_analysis.R``` will output a file in the same directory called ```tidy_data.txt```

## Dependencies

```data.table``` - automatically loaded by  ```run_analysis.R``` 
