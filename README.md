# Google-Play-Store-Data-Analysis
This is the EDA of Google Play Store data.
I have taken this data from 'kaggle.com' and then find some meaningful insights from it.

### Followed some steps to do this EDA:

1) Data Ingestion - Using pd.read_csv(), as my file is a csv file.

2) Data Understanding - Using pd.shape, pd.columns, pd.dtypes, pd.describe(), pd.info() for understanding the data.

   a) pd.shape - Using this we will get the no. of rows and columns in the data.

   b) pd.columns - This will provide the names of all the columns in the data.

   c) pd.dtypes - This will provide the data types of all the columns.

   d) pd.info() - This will provide the non-null values count.

   e) pd.describe() - This will provide the five-point summary of the data i.e., minimum value, count, mean value, std,
   maximum value, quartiles(Q1,Q2,Q3).

3) Data Preparation - Using pd.isnull().sum(), pd.duplicated(), pd.to_datetime
