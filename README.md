
The analysis files in the GitHub repository contain a set of scripts used to clean and transform the UCI-HAR dataset. The README in the repository explains the steps taken to clean and transform the data, as well as the contents of each file.

The following steps were taken to clean and transform the data:

Load the feature names and activity labels from their respective files.

Load the training and testing data, as well as their corresponding activity and subject data.

Merge the training and testing data and assign column names.

Extract only the mean and standard deviation measurements.

Use descriptive activity names to name the activities in the data set.

Appropriately label the data set with descriptive variable names.

Merge the subject, activity, and mean/std data into one dataframe.

Create a second, independent tidy data set with the average of each variable for each activity and each subject.

The README in the repository provides a clear and understandable explanation of each file in the repository:

README.md: This file provides an overview of the repository and the steps taken to clean and transform the data.

UCI-HAR-dataset-cleaning.ipynb: This Jupyter notebook contains the code used to clean and transform the data.

tidy_data.csv: This file contains the second, independent tidy data set with the average of each variable for each activity and each subject.

codebook.md: This file provides a detailed description of each variable in the tidy data set, including its name, description, and units.
