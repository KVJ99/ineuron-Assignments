Q1. How do you load a CSV file into a Pandas DataFrame?
    Using read_csv() method.

Q2. How do you check the data type of a column in a Pandas DataFrame?
    Using dtypes 
    df.dtypes['CloumnName'] or df.dtypes

Q3. How do you select rows from a Pandas DataFrame based on a condition?
    Using [] - x[10:15]
    Using head(n) for top n rows
    Using tail(n) for bottom n rows

Q4. How do you rename columns in a Pandas DataFrame?
    using rename() function
    eg- x.rename(columns={'a':'b'})

Q5. How do you drop columns in a Pandas DataFrame?
    Using drop() with axis=1 for columns
    eg- x.drop(['a','b'], axis=1)

Q6. How do you find the unique values in a column of a Pandas DataFrame?
    using unique()
    x.a.unique() where x is dataframe a is column name

Q7. How do you find the number of missing values in each column of a Pandas DataFrame?
    df.isnull().sum()

Q8. How do you fill missing values in a Pandas DataFrame with a specific value?
    using fillna() 
    eg- df.fillna("No Data")

Q9. How do you concatenate two Pandas DataFrames?
    using merge()

Q10. How do you merge two Pandas DataFrames on a specific column?
    df1.merge(df2[['A','B']])

Q11. How do you group data in a Pandas DataFrame by a specific column and apply an aggregation function?
    using groupby().groups

Q12. How do you pivot a Pandas DataFrame?
    using pivot()

Q13. How do you change the data type of a column in a Pandas DataFrame?

Q14. How do you sort a Pandas DataFrame by a specific column?
    using sort_values

Q15. How do you create a copy of a Pandas DataFrame?
    Using copy()

Q16. How do you filter rows of a Pandas DataFrame by multiple conditions?
    using loc

Q17. How do you calculate the mean of a column in a Pandas DataFrame?
     Using Discribe() we can see the mean and several other stats for the dataframe
     Or using mean()

Q18. How do you calculate the standard deviation of a column in a Pandas DataFrame?
     Using discrbe() or std()

Q19. How do you calculate the correlation between two columns in a Pandas DataFrame?
    Using corr()

Q20. How do you select specific columns in a DataFrame using their labels?
    Using loc or iloc

Q21. How do you select specific rows in a DataFrame using their indexes?
    using iloc
    df.iloc[2]

Q22. How do you sort a DataFrame by a specific column?
    Using sort_values()

Q23. How do you create a new column in a DataFrame based on the values of another column?
    using apply() function or loc[] property    

Q24. How do you remove duplicates from a DataFrame?
     Using drop_duplicates()

Q25. What is the difference between .loc and .iloc in Pandas?
iloc uses system generated indexes while loc uses indexes with particular colums by the user
