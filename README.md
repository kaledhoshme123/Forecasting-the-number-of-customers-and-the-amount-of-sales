# Forecasting the number of customers and the amount of sales
The following study, trying to find a recurrent neural network capable of predicting the number of customers who visit a store, and the amount of sales per month, was able to reach an accuracy of 94 percent.

The following study, trying to find a recurrent neural network capable of predicting the number of customers who visit a store, and the amount of sales per month, was able to reach an accuracy of 94 percent.

Since the dataset does not include a large number of records (the available records are not enough), and therefore we need to follow a specific methodology through which we can reach the desired result, the methodology that was followed in this study focuses on the following steps:
# Steps:
## Attempting to find a mathematical formula through which the number of customers who visit the store can be linked to the amount of sales the store gets:

The mathematical relationship here, depends on the use of unsupervised learning in a case to collect data into a number of clusters (20 clusters were adopted), where kmeans will be used to collect data on the number of customers and the amount of sales and try to aggregate them into 20 clusters.

![download (41)](https://user-images.githubusercontent.com/108609519/180472473-ca095c2d-3b32-468b-a56c-0e759692c34f.png)

At this point, a new column will be generated that includes the aggregation process that has been accessed and that includes data whose value ranges between 0 and 19.
Thus, at this stage, we were able to simplify the sorting process, moving from regression to classification.

We reviewed the chart that shows the sorting of data (the number of customers and the amount of sales), so that it shows the groups (clusters) in addition to identifying the centers of those clusters.

## The second stage, which includes trying to approximate the values ​​of the remaining two columns, which are the main criteria in the classification process, where StandardScaler was used for this task.

## Suggesting a structure for a recurrent neural network through which the relationship between the store space and the number of items in the store can be studied, in order to identify the number of customers who can visit the store and the amount of sales that can be obtained.

![download (42)](https://user-images.githubusercontent.com/108609519/180472560-fbdfe7a5-154a-4e76-a0fb-99c6c20e2c09.png)
