# YourFirstMachineLearningProject
This is a step by step walk through of your first machine learning project


Step 1 - import all dependencies ( ie. libraries funtions and objects)
  Pandas is the go to library to load the dataset.
  Matplotlib as the name suggest is the most popular plotting library for python.
  Sklearn provides basic Machine learning algorithms so you dont have to start from scratch.

Step 2 - Load Dataset- Using pandas we begin by loading CSV file

Step 3 - Summarize the Dataset 
	3.1 Dimensions of Dataset give you insight on how many rows and columns your dataset 
	3.2 Peek the data to get a feel for the data you are working with
	3.3 Statistical Summary this includes the count, mean, the min and max 
	3.4 Class Distribution Let’s now take a look at the number of instances (rows) that belong to each class. 

Step 4 - Data Visualization (we are going to look at 2 types of plots)
	4.1 universal plots to better understand each atrribute.
	4.2 Multivariate plots to better undertand the relationship between attributes
	
Step 5 - Evaluate Some Algorithms 
	5.1 Create a Validation Dataset
	5.2 Test Harness We will use 10-fold cross validation to estimate accuracy.
	5.3 Build Models we will use 6 different algorithms
	5.4 Select Best Model

Step 6 - Make Predictions 
After testing all algorithms The KNN algorithm was the most accurate. Now we want to get an idea of the accuracy of the model on our validation set.
This will give us an independent final check on the accuracy of the best model. It is valuable to keep a validation set just in case you made a slip during training, such as overfitting to the training set or a data leak. Both will result in an overly optimistic result.
