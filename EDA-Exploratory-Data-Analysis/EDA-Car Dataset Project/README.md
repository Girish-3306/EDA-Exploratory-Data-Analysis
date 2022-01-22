
<h3>In this project, we are basically doing the basic analysis of raw data and trying to find insights out of it on CAR DATASET.</h3>

The commands that we used in this project :</br>

* import pandas as pd -- To import Pandas library</br>
* pd.read_csv - To import the CSV file in Jupyter notebook</br>
* head() - It shows the first N rows in the data (by default, N=5)</br>
* shape - It shows the total no. of rows and no. of columns of the dataframe</br>
* df.isnull( ).sum( ) - It detects the missing values from each column of the dataframe.</br>
* fillna() - To fill the null values of a column with some particular value</br>
* value_counts - In a column, it shows all the unique values with their count. It can be applied to a single column only.</br>
* isin() - To show all records including particular elements</br>
* apply() - To apply a function along any axis of DF</br>

-------------------------------------------------------------------------------------------------------------------------------------------------------------

Q. 1) Instruction ( For Data Cleaning ) - Find all Null Values in the dataset. If there is any null value in any column, then fill it with the mean of that column.</br>
Q. 2) Question ( Based on Value Counts )- Check what are the different types of make are there in our dataset. And, what is the count (occurrence) of each make in the data ?</br>
Q. 3) Instruction ( Filtering ) - Show all the records where Origin is Asia or Europe.</br>
Q. 4) Instruction ( Removing unwanted records ) - Remove all the records (rows) where Weight is above 4000.</br>
Q. 5) Instruction ( Applying function on a column ) - Increase all the values of 'MPG_City' column by 3.</br>
