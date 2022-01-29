<h2>In this project, we are basically doing the basic analysis of raw data and trying to find insights out of it on LONDON HOUSING DATASET.</h2>

The commands that we used in this project :</br>

* import pandas as pd -- To import Pandas library</br>
* pd.read_csv - To import the CSV file in Jupyter notebook</br>
* df.count() - It counts the no. of non-null values of each column.</br>
* df.isnull().sum() - It detects the missing values from the dataframe.</br>
* import seaborn as sns - To import the Seaborn library.</br>
* import matplotlib.pyplot as plt - To import the Matplotlib library.</br>
* sns.heatmap(df.isnull()) - It will show the all columns & missing values in them in heat map form.</br>
* plt.show() - To show the plot.</br>
* df.dtypes - To show the datatype of each column.</br>
* pd.to_datetime(df.Date_Time_Col) - Converts the data-type of Date-Time Column into datetime[ns] datatype.</br>
* df.Time_Col.dt.year - Creating a new column with only year values</br>
* df.Time_Col.dt.month - Creating a new column with only month values.</br>
* df.insert( index , ‘new_column_name’, new_column_values) - To insert a New column at a particular position with values in it.</br>
* df.drop(['Col_name'] , axis=1 , inplace = True) - To drop a column from the dataframe permanently.</br>
* df.groupby(‘Col_name’) - To form groups of all unique values of the column.</br>
* df[df.Col_1 = = ‘Element1’] - Filtering – We are accessing all records with Element1 only of Col_1.</br>
* df.groupby(‘Col_1’)[‘Col_2’] .mean( ) - To create groups - Two Keys – Apply on Col_2 grouped by Col_1.</br>
</br>
--------------------------------------------------------------------------------------------------------------------------------------------

Q. 1) Convert the Datatype of 'Date' column to Date-Time format.</br>
Q. 2) Add a new column ''year'' in the dataframe, which contains years only.(B.2) Add a new column ''month'' as 2nd column in the dataframe, which contains month only.</br>
Q. 3) Remove the columns 'year' and 'month' from the dataframe.</br>
Q. 4) Show all the records where 'No. of Crimes' is 0. And, how many such records are there ?</br>
Q. 5) What is the maximum & minimum 'average_price' per year in england ?</br>
Q. 6) What is the Maximum & Minimum No. of Crimes recorded per area ?</br>
Q. 7) Show the total count of records of each area, where average price is less than 100000.</br>
