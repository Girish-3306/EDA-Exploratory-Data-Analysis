What is Exploratory Data Analysis?
Exploratory Data Analysis or (EDA) is understanding the data sets by summarizing their main characteristics often plotting them visually. This step is very important especially when we arrive at modeling the data in order to apply Machine learning. Plotting in EDA consists of Histograms, Box plot, Scatter plot and many more. It often takes much time to explore the data. Through the process of EDA, we can ask to define the problem statement or definition on our data set which is very important.
---------------------------------------------
What is Univariate analysis?
“Uni” means one and “Variate” means variable hence univariate analysis means analysis of one variable or one feature. Univariate basically tells us how data in each feature is distributed and also tells us about central tendencies like mean, median, and mode.
-------------------------------------------
What is Bivariate analysis?
Bivariate analysis:- is performed to find the relationship between each variable in the dataset and the target variable of interest (or) using 2 variables and finding the relationship between them. Ex:-Box plot, Violin plot.
-------------------------------------------
What is Multivariate analysis?
Is performed to understand interactions between different fields in the dataset (or) finding interactions between variables more than 2. Ex:- Pair plot and 3D scatter plot.

-------------------------------------------
EDA - Exploratory Data Analysis on Marketing data set.
------------------------------------------
Data Preprocessing = Data cleansing -> Data Scrubing -> Data processing 
------------------------------------------
Important steps to remember while doing this project.

Step 1:-
Copy the complete data set into temp(temporary) variable
And start working on the temp variable.

Step2:-
Drop the columns which are not required in the analysis.

Step3:-
Make note of the columns which you are removing. Make documentation of what you are doing.

Step4:-
Check for the target varibale ie dependent variable.



Step5:-
Split columns that have combined info(information) into individual columns and drop the original column to avoid doublecounting
eg jobedu - Job and Education

Step6:-
Check for missing values and fix it

Step7:-
Never ever change/impute target variable.

Step8:-
Univariate analysis 

Step9:-
Bivariate analysis

Step10:-
Multivariate analysis


---------------------------------------------

Main purpose of Exploratory Data Analysis (EDA) is to tell the story and getting insight out of it.

---------------------------------------------


Some of the most important commands used in the project are as follows:-

* info()- to get a concise summary of the dataframe.
* head()- to get the first n(5) rows.
* copy()- to create a copy of a Pandas object.
* drop()- to drop specified labels from rows or columns. in this axis=1 = refers to columns.
* apply()- allow the users to pass a function and apply it on every single value of the Pandas series.
* isnull()- Detect missing values for an array-like object.
* sum()- to return the sum of the values for the requested axis by the user.
* isna()- used to detect missing values.
* median()- calculates the median of elements of DataFrame object along the specified axis.
* fillna()- to fill NA/NaN values using the specified method.
* unique()- to get unique values of Series object.
* value_counts()-  returns object containing counts of unique values.
* describe()- to view some basic statistical details like percentile, mean, std etc. of a data frame or a series of numeric values.
* corr()- to find the pairwise correlation of all columns in the dataframe.
* groupby()- used for grouping the data according to the categories and apply a function to the categories.






























