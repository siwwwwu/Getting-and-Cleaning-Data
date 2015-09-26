# Getting-and-Cleaning-Data

The run_analysis.R file consists five parts.

1. The first part is to download the zip file, you could skip this part, if you download the file and unzip it in your workspace directory.

2. The second part is to indentify the directory of each file. Normally, if you unzip the files in the folder "UCI HAR Dataset" under you workspace directory, there is no need to change the code in this part. Otherwise, you should modify to make sure that you could read the files correctly.

3. The third part is to merge the training data set and test data set. Merge the activity and subject information into the data set. Rename the column names, etc. Finally, a data frame called final_data_set which would be created. But it is not the final result of the task.

4. Create a second data set. There is a loop to process all the 79 variables. After that, all the summarized information would be merged into one data frame which is called second_data_set.

5. Write the second_data_set into a txt file which is called "result_data_set.txt". This is the final result tiny data set.
