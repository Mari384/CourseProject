# CourseProject
Tidy Data Set
I downloaded the data file and created the local data folder.
I then unzipped the file.
The unzipped files are placed in the UCI Har dataset folder. I asked for a list of all the files to check.
I looked at the readme.txt for detailed information of the dataset. The files used to load the data are these ones:
test/subject_test.txt
test/X_test.txt
test/y_test.txt
train/subject_train.txt
train/X_train.txt
train/y_train.txt
More useful info is that:
1. Values of Varible Activity consist of data from “Y_train.txt” and “Y_test.txt”
2. values of Varible Subject consist of data from “subject_train.txt” and subject_test.txt"
3. Values of Varibles Features consist of data from “X_train.txt” and “X_test.txt”
4. Names of Varibles Features come from “features.txt”
5. levels of Varible Activity come from “activity_labels.txt”
So we will use Activity, Subject and Features as part of descriptive variable names for data in data frame.
I then read the data from the files into the variables (dataActivityTest,dataActivityTrain etc) = Activity, Subject and Features files.
I looked at the properties of the variables (str(DataActivityTest) etc)
I concatenated the data tables by rows using rbind.
I then set names to the variables.
I merged the columns to get the data frame "data" for all the data.
I subset the name of Features using measurements of the mean and standard deviation.
Checked the struture of the data frame - str(Data)
Read the descriptive activity names from "activity_labels.txt"
I added labels to the data with descriptive variable names (See codebook.md)
Created a second independent tidy data set by installing and using the packages Plyr and Knitr

