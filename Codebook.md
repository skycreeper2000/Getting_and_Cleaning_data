Codebook will describe Variables, Data and Transformations

R script run_analysis.R does the following.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

Here goes the step by step description and variables:
1. We should manually download the UCI HAR Dataset and unzip it
2. Make the Working direcvtory and the UCI HAR Dataset (not included in the code)

3. 
Read the data from the files into variables.

test.subject
test.x
test.y

train.subject
train.x
train.y

features
activity.labels

4. 
Merge the test and train subject datasets
Merge the test and train labels
Merge the test and train main dataset,
Merge all three datasets - dataset name "data"

5. Create a smaller dataset containing only the mean and std variables.

data set name - "data.mean.std"

6. Compute the means, grouped by subject/label.

output data set name "means.csv"
