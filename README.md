Getting-and-Cleaning-Data-Assignment
====================================

Coursera Course: Getting and Cleaning Data

Assignment Submission Files
- [run_analysis.R](https://github.com/zyng2016/Getting-and-Cleaning-Data-Assignment/blob/master/run_analysis.R)
- [README.md](https://github.com/zyng2016/Getting-and-Cleaning-Data-Assignment/blob/master/README.md)
- [CodeBook.md](https://github.com/zyng2016/Getting-and-Cleaning-Data-Assignment/blob/master/CodeBook.md)

This is the course project for the Getting and Cleaning Data Coursera course. The R script, run_analysis.R, does the following:

1. Download the dataset if it does not already exist in the working directory
2. Load the activity and feature info
3. Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation
4. Loads the activity and subject data for each dataset, and merges those columns with the dataset
5. Merges the two datasets
6. Converts the activity and subject columns into factors
7. Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.

The end result is shown in the file tidy.txt.

Dependencies

1. The R script assumes you have 'data.table' installed using install.packages("data.table")

More Information

For more information on the data set, please refer to http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones