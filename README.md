### UMich Data Science Course 1 Week 4 Assignment repository 

<b>This assignment makes use of:</b> 
* creating a list of tuples and then using this list of tuples to create a dataframe 
* np.where 
* transpose of DataFrame 
* making index a datetimeIndex with pandas.to_datetime 
* downsampling quarterly and aggregating on mean 
* accessing .year and .month fields of pandas time series of individual series elements (i.e. without using .dt) 
* dropping a column 
* pandas.DataFrame.loc[pandas.DataFrame.index.isin(&lt;list&gt;)] and pandas.DataFrame.loc[~pandas.DataFrame.index.isin(&lt;list&gt;)] wherein the index is a multiindex and the list is a list of tuples 
* pandas.DataFrame.iterrows() to retrieve from a dataframe a generator capable of iterating the dataframe's rows- each time yielding a tuple consisting of the row index and the row contents 
* scipy.stats.ttest_ind with parameter na_policy = 'omit' to perform independent samples t test and omit na values from consideration 
* .dropna() prior to computing mean price ratios for both university towns and non-university towns to be sure that missing values are excluded from consideration 
<hr>

* <b>Included data files:</b> 
    - City_Zhvi_AllHomes.csv 
    - university_towns.txt 
    - gdplev.xls 
* <b>Included IPython Notebook:</b> 
    - Assignment4.ipynb 
* <b>Included html output file:</b> 
    - Assignment4.html 
 