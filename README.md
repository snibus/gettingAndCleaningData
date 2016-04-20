"# gettingAndCleaningData" 
Getting and Cleaning Data Course Assignment
========================================

# Requirements for running the R Script:
# 1. Make the folder where your R Script is as work directory


# run_analysis.R

This R script performs the following steps, as per the project assignment instructions:

1. Unzips the "getdata_projectfiles_UCI_HAR_Dataset.zip" file to get the input files
2. Creates a dataset by merging the train and test sets.
3. For each measurement, mean and standard deviation is extracted.
4. Uses descriptive activity names to name the activities in the dataset
5. Appropriately labels the dataset with descriptive activity names. 
6. Creates files calculated_tidy_data.txt.