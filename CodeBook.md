Getting Data Project CodeBook
=============================
This file describes the data and transformations to clean up the data.  
* Data Source
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones      
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip  
* The run_analysis.R script:   
 1. Downloads and Unzips data
 2. Merges Training/Test files into data frame
 3. Extracts mean and std deviation from features 
 4. Names Activities
 5. Labels Activity Names
 6. Creates 2nd dataset with averages
 7. Writes mean_data.txt
