# CPSC 392 Assignment 2

The assignment was to implement the KNN function in Python. The KNN function is the only thing that was modified, all other functions were provided. The training dataset contained missing values, so I had to clean the data accordingly. 


The first step I took in cleaning up the missing data was to find outliers. I did this in Excel by using the quartile function to find the upper and lower bounds of each column for each class (setosa, versicolor, virginica). I then used conditional formatting to highlight any cells that contained values that were either above or below the bounds, and deleted those values. The next step was to replace the missing values, which was done by computing the average of each column for each class, and replacing the missing values with the averages. 


The accuracy on the provided data is about 86.6%. 
