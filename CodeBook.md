
Load the libraries
Create a data folder in the working directory
Download and unzip the data files to the data folder
Read the following files into data frames:
        features.txt, which contains feature names
        activity_labels.txt, which contains the mappings from activity codes to descriptive activity names
        X_train.txt and X_test.txt, which contain the vectors of features
        y_train.txt and y_test.txt, which contain the activity codes
        subject_train.txt and subject_test.txt, which contain the subject identifiers
Give meaningful labels to the columns of the feature vector data frames features.test and features.train using the feature name data frame feature.names
Give meaningful labels to the columns of the subject and activity data frames
Bind together the respective subject identifier, activity code and feature vector data frames to create the test and training data frames, raw.dataset.test and raw.dataset.train
Bind together raw.dataset.test and raw.dataset.train to make one large data frame raw.dataset
Retain in a slimmed-down data frame slim.raw.dataset only those feature columns pertaining to standard deviation and mean
Use the descriptive activity labels retrieved from the activity_labels.txt file to replace the activity codes in the relevant column of slim.raw.dataset
Create a tidy data set tidy.dataset with the average of each variable for each activity and each subject, by melting slim.raw.dataset and recasting it as required
Write tidy.dataset to tidy_dataset.txt
