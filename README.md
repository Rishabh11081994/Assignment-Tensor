# Assignment-Tensor

Hi,
There are two assignment solutions for the given proble over emails. I have used Apache 3.1 with pyspark to sovle the assignment. Please feel free to connect for any query. The detail about the assignment is mentioned below. 

## 1
In the assignment first the spark session is created the file first read from the HDFS file system with read function 
for apacher spark. 

First operation includes finding Items having the least rating , the code is simple and self explanatory

Second operation includes finding Items having the most rating , only sort operation is reverse in this case to obtain desired results.

Third operation includes Items with longest review, this could not perform on the dataset which I downloades as it containce only review, not textual review. I created the new dataframe to perform date wise and longest review operation. One user defined function is developed for this transformation and rest code is self explainotry.

To change the date into mm--dd-yyyy format,  with column transformation and date_format functon was implemented and rest of the code is self explanatory.

At last I mentioned about join, broadcast join and cache which I learnt recently . This code was implemented using dummy data as two tables was required to perform join operation.

## 2

In second assignemt we read the file, in this case I used the order's file as date transformation was required to perform and order data contains the date column. Same dateformat function was implemented to transformation the date into mm-dd-yyyy format


The data was saved into table , dummy code is shown to save the data to sql server as my apache spark was not connected to database.

The last step was to save the file in parquet format, which was completed with write object of Spark. 




