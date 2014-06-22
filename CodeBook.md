#CodeBook
====================================

# Objective of the codebook:
- Description of  the output files from "run_analysis.R": "TidyData.txt" and  "TidyDataWithAverages.txt" 

##1. Raw data source:
- Data collected from the accelerometers from the Samsung Galaxy S smartphone:
- URL repository: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

##2.run_analysis.R: steps to clean data 
###2.1 Merge the training and the test sets to create one data set. Function to perfom: 
- Object to use: read.table() and rbind()

###2.2 Extracts only the measurements on the mean and standard deviation for each measurement.
- Object to use: read.table (), names(),grep(), features(), gsub() and tolower()  
### 2.3 Uses descriptive activity names to name the activities in the data set
- Object to use: read.table() adn names()

##3.run_analysis.R: generating "TidyData.txt" 
## 3.1 Appropriately labels the data set with descriptive variable names and generate the file
- Object to use: names(), cbind() and write.table()

##4.run_analysis.R: generating "TidyDataWithAverages.txt"
## 4.1 Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 
- Object to use: unique(),length(), dim(), cleaned(), write.table()
