Codebook will describe Variables, Data and Transformations

Here goes the step by step description and variables:

1. We should manually download the UCI HAR Dataset and unzip it

2. Make the Working direcvtory and the UCI HAR Dataset (not included in the code)

3. Read the data from the files into variables.

test.subject
test.x
test.y

train.subject
train.x
train.y

features
activity.labels

4. Merginf datasets.
Merge the test and train subject datasets
Merge the test and train labels
Merge the test and train main dataset,
Merge all three datasets - dataset name "data"

5. Create a smaller dataset containing only the mean and std variables.

data set name - "data.mean.std"

6. Compute the means, grouped by subject/label.

Used - Subject and Label as id variables in melt and dcast function.
Output dataset - "means"

7. output data set name "means.csv" using write.csv function


