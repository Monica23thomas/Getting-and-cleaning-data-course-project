# Getting-and-cleaning-data-course-project
Getting and cleaning data course project - coursera
# Getting and Cleaning Data Project

This repository contains the submission for the "Getting and Cleaning Data" Coursera course project.

## Files

- **run_analysis.R**: Main R script that performs all data cleaning steps.
- **tidy_data.txt**: Final tidy dataset (output of the script).
- **CodeBook.md**: Describes the variables, data, and transformations.
- **README.md**: Overview of the project and instructions.

## How the script works

1. Downloads the dataset if not already present.
2. Loads training and test data into R.
3. Merges the data into one dataset.
4. Extracts measurements on mean and standard deviation.
5. Replaces activity codes with descriptive names.
6. Labels dataset with descriptive variable names.
7. Creates a tidy dataset with averages for each activity and subject.
8. Writes the tidy dataset to `tidy_data.txt`.

## Running the script

```r
source("run_analysis.R")
