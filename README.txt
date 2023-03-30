GGE6505 Final Project Github
Group 10
Members: Avery Grouette, Ngoc Phuong Anh Nguyen, and Sreemathy Maheswaramoorthy

For data collection, storage and preperation, it is all done in Data_Collection_Storage_Preperation.ipynb

Within Data_Collection_Storage_Preperation.ipynb, the data was analyzed in depth looking at cleanign the datframe to allow for easier use such as changing the column names and replacing the null values.

For replacing the null values:
There were 18059 instances where null values were found for the end station. These instances were replaced with the following:
es_id = no_return
es_latitude, es_longitude and es_id = 0

For replacing the 240321 instances where no birth age was given, the values were all replaced with 0