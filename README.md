# Gathering and Cleaning Data course Project

The `run_analysis.R` does the following:
1. Downloads the Human Activity Recognition using Smartphones Dataset
2. Loads the `activity_labels.txt`, `features.txt`, train and test dataset
3. Loads the activity and subject data for each dataset, and merges those
   columns with the dataset
4. Merges the train and test dataset
5. Converts the `activity` and `subject` columns into factors
6. Creates a tidy dataset that consists of the average (mean) value of each
   variable for each subject and activity pair.

The output of the script is stored in `tidy.txt`
