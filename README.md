# Titanic-project
This is my first Project..
here I told How to build this project...<br>
In this project first step is Data Cleaning so that many syntax as work for Data cleaninng.
  <br>
  <br>
df.shape (for count a number of rows & columns)
  <br>
df.head() (Describe a data of CSV file)
  <br>
df.info() (Describe a columns datatypes)
  <br>
df.drop(['columns name'], inplace =True) (Here inplace is work like save cmd bcs we not creat inplace than data are not save after drop value)
  <br>
pd.isnull(df).sum() (For find null values in dataset)
 <br>
df.dropna(inplace=True) (For removw drop values row in dataset)
  <br>
df.['columns name'].dtype (For check the columns datatypes)
 <br>
df.rename(columns={'c name': 'WYW'}) (For rename the columns name)
  <br>
df.describe() (For this method returns summuries of the data in the dataset (i.e.-count, mean, min, max, etc..))
  <br>
<br>
After Data Cleaning we create a Data Visulization for over Dataets.
<br>
If Describes for any counts grafs:
<br>
sns.countplot(x="columns name", data=df)
<br>
plt.show()
<br>
<br>
sns.scatter(x_values, y_values, marker='o', color='r', label='Scatter Plot') (create scater plots..)
<br>
sns.set(rc= {"figure.figsize":(15,5)}) ( For visulise the graphs canvas)
<br>
<br>
<br>
Top 6 libraries in jupyter notebook for Data Science..
<br>
1. TENSRFLOW
2. NUMPY
3. PANDAS
4. SEABORN
5. SCIPY
6. METPLOTLIB
   








