

test_x_test:  represents the variable created from reading the X_test.txt file into R to be used for the analysis

test_y_test: represents the variable created from reading the Y_test.txt file into R to be used for the analysis 

test_subject_test:  represents the variable created from reading the subject_test.txt file into R to be used for the analysis

train_x_train: represents the variable created from reading the X_train.txt file into R to be used for the analysis

train_y_train: represents the variable created from reading the Y_train.txt file into R to be used for the analysis

train_subject_train:  represents the variable created from reading the subject_train.txt file into R to be used for the analysis 

features: represents the dataframe created from reading the feature.txt file into R to be used for the analysis

test_data:  represents the dataframe created from combining the data from test_subject_test,test_y_test,test_x_test as columns using the cbind() function

train_data: represents the dataframe created from combining the data from train_subject_train,train_y_train,train_x_train as columns using the cbind() function

data: represents the new dataframe created from combining/mergeing test_data and train_data. Since the two have the same columns, but differing data, we combine on rows unsing the rbind() function


names(data)[1] : This assigns the name "Subject" to the first column in the newly created dateframe called data

names(data)[2]: This assigns the name "Activities" to the first column in the newly created dateframe called data
names(data)[3:563]: This assigns the names of features found in the second column of the features dataframe to the remaining columns in the data dataframe
 

Mean_Cols: Looks for features that contain mean and extracts those from the second column of the feature dataframe using the grep() function
STD_Cols: Looks for features that contain std and extracts those from the second column of the feature dataframe using the grep() function



activity_labels <- First this variable reads the activity label table which has both activity label identifier and activity name. Then, it performs a forloop through the data dataframe where it matches the activity label identifier with the activity name and assigns the name to the rows with the corresponding id 

 

data_subset: creates an index of the columns that will need to be called
data_set: subsets data using the data_subset variable, pulling in only the columns we want to see




