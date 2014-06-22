GettingAndCleaningData
======================

# Course project with peer assessment

## Context: 
- Wearable computing reprensents business opportunities 
- Companies are racing to develop the most advanced algorithms to attract new users.
- Wearable computing the most exciting areas in all of data science right now

## Objectives of the analysis
- Analyse the data collected from the accelerometers from the Samsung Galaxy S smartphone:
- URL repository: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
- URL for more readings on the topic:http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones


## Result of the analysis 4 files: 
### 1. Readme.md, for introduction and description purpose
### 2. One R code: run_analysis.R
- Merges the training and the test sets of UCIHAR Dataset
- Extracts only the measurements on the mean and standard deviation for each measurement 
- Uses descriptive activity names to name the activities in the data set
- Labels the data set with descriptive variable names, ref the file  "TidyData.txt"
- Creates a second, independent tidy data set with the average of each variable for each activity and each subject: ref "TidyDataWithAverages.txt"
### 3. codebook.md
- Describes the output files from "run_analysis.R": "TidyData.txt" and  "TidyDataWithAverages.txt" each variable and its value in the tidy data set
- Describes the variables, the data, and work that performed to clean up the data

### 4&5. 2 txt files: output files from "run_analysis.R":
- "TidyData.txt" and  
- "TidyDataWithAverages.txt"

