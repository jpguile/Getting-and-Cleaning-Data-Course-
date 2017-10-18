# Getting-and-Cleaning-Data-Course-


The script run_analysis.R went performs.

Download and unzip the dataset store in variables:

Load activity labels + features store in variables: 

activityLabels
features

Extract only the data on mean and standard deviation and store in variables:

featuresWanted

Load the datasets and store in variables:

train
trainActivities
trainSubjects
test

merge datasets and add labels and store in variables:

allData

turn activities & subjects into factors and replace column of variables:

allData$activity
allData$subject
allData.melted
allData.mean

finally created file tidy.txt contains the relevant averages 

