This code book describes the variables, data, and any transformations or work performed to clean up the data.

Data Source
The dataset used in this analysis is the UCI-HAR dataset. This dataset is a collection of recordings of 30 human subjects performing activities of daily living while carrying a waist-mounted smartphone with embedded inertial sensors.

Data Cleaning
The following steps were taken to clean and transform the data:

Download the dataset from the link provided and extract the files.

Load the necessary packages and libraries in Python. Pandas and NumPy libraries are commonly used in data preprocessing tasks.

Load the feature names and activity labels from their respective files.

Load the training and testing data, as well as their corresponding activity and subject data.

Merge the training and testing data and assign column names.

Extract only the mean and standard deviation measurements.

Use descriptive activity names to name the activities in the data set.

Appropriately label the data set with descriptive variable names.

Merge the subject, activity, and mean/std data into one dataframe.

Create a second, independent tidy data set with the average of each variable for each activity and each subject.

Variables
feature_names: a data frame containing the names of the features.
activity_labels: a data frame containing the names of the activities.
X_train, y_train, subject_train: data frames containing the training data, training activity labels, and training subject IDs.
X_test, y_test, subject_test: data frames containing the test data, test activity labels, and test subject IDs.
X, y, subject: data frames containing the merged training and test data, activity labels, and subject IDs.
mean_std_cols: data frame containing only the mean and standard deviation measurements.
activity_labels_dict: a dictionary containing the activity labels and their corresponding names.
data: merged data frame containing the subject, activity, and mean/std data.
tidy_data: a data frame containing the average of each variable for each activity and each subject.
Units
The units for the different features are not provided in the original dataset, but all features are assumed to be normalized and unitless.

Other Information
The README file in the Github repository explains the analysis files and the steps taken to clean and transform the data.
