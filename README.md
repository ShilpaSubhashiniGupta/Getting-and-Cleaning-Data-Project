# Getting-and-Cleaning-Data-Project
## Course Project
You should create one R script called run_analysis.R that does the following
1.Merge the training and the test sets to create one data set
2.Extract only the measurements on the mean and standard deviation for each measurement
3.Use descriptive activity names to name the activities in the data set
4. Appropiately labels the data set with descriptive activities names 
5.Create a second, independently tidy data set with the average of each variable for each activity and each subject

## Step to work on this course project
1.Download the data source and unzip it
2. Folder named as UCI HAR Dataset will be created
3. Put run_analysis.R file in the parent folder of UCI HAR Dataset, then set it as working directory
4. Run source("run_analysis.R"), a new file named as "tiny_data.txt" will be generated in working directory
5.To do the required transformation, mentioned till step 4.two packages namely reshape2 and data.table need to be installed
6. Detailed reference is avalilable in CodeBook.md


