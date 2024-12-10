# Score Prediction 
I used a T20 international dataset in which I build Machine Learning models like Linear Regression, Lasso, Ridge from which I chose the model with the least Mean Absolute Error and on that model. I predicted the score by giving some of my inputs and according to that inputs it will show how much the team will score in the remaining overs and also the predicted range in which the first innings score will lie.
I downloaded the dataset from the [cricsheet website](https://cricsheet.org/downloads/t20s_csv2.zip) 

## Installation

In this project you need to first install the jupyter notebook to run the code. After that download the dataset from the above link. After downloading the dataset you need to remove the info.csv from the file. Then create a new notebook in that notebook import pandas and glob library. After importing glob type glob.glob and give the path where you have saved the dataset file after removing all info.csv file and after merging all the file save that dataset. After saving the dataset create a new notebook again and import all the libraries like pandas, numpy, sklearn, and from sklearn import libraries like linear regression, Ridge. 


## Usage
In my notebook you can see cell no. 50 where you can give inputs according to you like overs, Run, Run Rate, Wickets etc.
