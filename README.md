# Project-disasters
Data Mining project
We have taken a dataset from twitter social media platform as most of all disasters happen in various locations around the world and United states.It has 5 columns and more than 11,371 rows including missing values.
First of all, we need to clean the data.The first step is to remove the missing values or null values and find the duplicate values.After removing the empty cells from the file we have exactly 7952 rows and 5 columns.So, we have removed approximately 4000 records which are missing data.The next step is whether to replace the missing values or not. If so which column, Then we ran program to fo find the number of columns with missing values just like we did to find the above informatiom. We got 3418 missing values in only one of the column while other columns have zero missing values.To continue with the next step first we need to understand the data.So,the columns in the file are
id
keyword
location
text
target
Out of these 5 columns the column which has missing values is location.So the next step in the analysis is to find different values in location column and their counts.  As we got that location is nominal type ,we find the unique value count which is 4505.It has 4505 unique values in it.By calculating the mode which is 96,It is way small when compared to the records.So, It is best to remove these records.After removing these missing records the missing values in each column is 0.The column and their data types are
Column      Dtype  
 id          int 
 keyword     object
 location    object
 text        object
 target      int
 After the above cleaning and analysis the number of rows and columns are 7952 and 5.
 Then next step is to remove any duplicate data from above analysed data,After doing that the number of rows and columns are exactly same which is 7952 nad 5.Therefore the number of duplicates are exactly zero.
