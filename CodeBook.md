   Getting and Cleaning Data Final Project
   Human Activity Recognition Using Smartphones Data Set
   
   
   Background
Information relevant to the data used may be found at: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
The researchers responsible for compiling and preparing this information describe it as:

“Abstract: Human Activity Recognition database built from the recordings of 30 subjects performing activities of daily living (ADL) while carrying a waist-mounted smartphone with embedded inertial sensors.”
Files Used:

X_train.txt: 	Contains the training data for each event captured (observations)
X_test.txt:    	Contains the test data for each event captured (observations)
Features.txt	The label for each variable measured.


Process and Variables:

1. Read data

test: Flat read for train.txt file
test_mat: Matrix for train.txt file
test_df: Dataframe for train.txt file.

test: Flat read for train.txt file
test_mat: Matrix for train.txt file
test_df: Dataframe for train.txt file.

train: Flat read for train.txt file
train_mat: Matrix for train.txt file
train_df: Dataframe for train.txt file.

train: Flat read for train.txt file
train_mat: Matrix for train.txt file
train_df: Dataframe for train.txt file.


2. Merge data and label variables.
   
   features: read features.txt file
   human_activity_recog_df: Merged dataframe data with labels.
   
3. Extract mean and stardard deviation

mean_mat: Intermediate matrix to store mean

human_activity_recog_mean_df: Final mean dataframe

sd_mat: Intermediate matrix to store standard deviation

human_activity_recog_sd_df: Final mean dataframe

avg_mat: Intermediate matrix to store avg

human_activity_recog_avg_df: Final avg dataframe





   
   
