# Data-Mining

##final project, Amirkabir University of Technology, spring 2020


1.	The data of this question named Data preprocessing is attached in the file of this exercise. Our intention in this question is to learn data preprocessing.
#### An explanation about the dataset: This dataset is about several different countries in which there are features such as the population of these countries, population growth and tourist status, with the help of these features we are going to build a regression model that shows the number of patients with the corona virus in Estimate other countries. Of course, please note that due to the small number of data and that the features are not necessarily exact features, we do not expect an exact result and it is only for the purpose of learning.

  I.	Use different ways to deal with Missing Values and which one of the ways do you think is the most appropriate? Can you give a general opinion? (All the ways are mentioned in the data preprocessing video and also in the classroom that you can use).
  
  II.	 Why can't Categorical Variables be used for data mining and should be converted to numerical features? How can they be converted into numerical variables? Apply this method on this dataset.
  
  III.	Do you think we need Scaling Feature in this dataset or not? Why? If your answer is positive, apply different Scaling Feature methods on this dataset and which one is more appropriate in your opinion?
  
  IV.	Identify outliers in this dataset and remove them. Do you think it is the right way to delete outlier data? If your answer is no, provide an alternative solution.
  
  V.	Suppose all our data is training data. Apply Linear Multiple Regression on this pre-processed dataset. Report the model in full. The purpose of the model report is to specify the coefficients, width from the origin, MSE, RMSE and output errors with the help of Statsmodels. Analyze your report.
  
  VI.	Suppose we put the column population Total in variable X and put the column number of people infected with the corona virus in variable y. Now we want to create a regression model in the form c + bX + aX2 = y. Get the unknown parameters.



2.	The data of this question named Customers Ecommerce is attached in the file of this exercise. Note the following explanation about our goal in this question as well as the dataset.

“Congratulations! You just got some contract work with an Ecommerce company based in New York City that sells clothing online but they also have in-store style and clothing advice sessions. Customers come in to the store, have sessions/meetings with a personal stylist, then they can go home and order either on a mobile app or website for the clothes they want. 
The company is trying to decide whether to focus their efforts on their mobile app experience or their website. They’ve hired you on contract to help them figure it out! We’ll work with the Ecommerce Customers csv file from the company. It has Customer info, such as Email, Address, and their color Avatar. Then it also has numerical value columns:
Avg. Session Length: Average session of in-store style advice sessions.
Time on App: Average time spent on App in minutes
Time on Website: Average time spent on Website in minutes
Length of Membership: How many years the customer has been a member.“

  I.	First, comment on the correlation of the columns with the help of pairplot and heatmap.
  
  II.	Apply Linear Multiple Regression on this dataset. Report the model in full.
The purpose of the model report is to specify the coefficients, the width from the origin, the MSE errors of the training data, the RMSE of the training data and the output with the help of Statsmodels. Analyze your report.

  III.	Approximate the test error using validation cross fold − k.
  
  IV.	Now, using the obtained model, predict the test data and obtain the RMSE of the test. According to the test and training data error, whether overfit or underfit has occurred. Express your opinion about the bias and variance of this model. If the model did not work well, explain why. (Of course, be careful in real problems, we never have access to the value of the target variable of the test data, and we have to evaluate our model by approximating the test error)
  
V.	Now, according to your evaluation of the model, respond to the company.
Do you think the company should focus more on their mobile app or on their website?


3.	In this section, ROC, Matrix Confusion and Report Classification criteria should be stated in the output of all questions.
  I.	Download the dataset
  
 http://archive.ics.uci.edu/ml/datasets/Arrhythmia.
 
 As can be seen, this dataset has missing values. Perform data preprocessing with one of the ways to deal with missing data.
 
  II.	Apply the nearest neighbor algorithm for k = 1 and k = 30 with the Euclidean distance criterion on the downloaded dataset. Obtain and analyze all training metrics for this training and test data.
  
  III.	Obtain the optimal value of k and the best distance criterion (cosine, Euclidean and Manhattan) using the cross fold - k validation method. Now apply this algorithm for these optimal values on the downloaded dataset. Obtain and analyze all training metrics for training and test data.
