# pandas


```import pandas as pd```
```df= pd.read_csv('data.csv')```
```print(data.head())``` #display first rows
```print(data.describe()) #statistical summary
```filter_data = data[data['column name']>10] #filter data by conditions
```group_data = data.groupby{'category') #group data by category
```['column_name'].mean()``` #mean
```data[`new_column'] = data['column1'] + data['column2']``` #create new columns based on existing
```data.to_csv('new_data.csv, index=False)``` #save modified data to new csv file
```correlation_matrix = data.corr()``` #perform advanced statistical analysis
```data.plot(kind='scatter', x='column', y='column')``` #visualize data

#create df
```
data = {'Column1': [value1, value2, ...], 'Column2': [value1, value2, ...]}
df = pd.DataFrame(data)
```

```df.isnull().sum()``` #check missing values
```df.dropna()``` #drop missing values
```df.fillna(value)``` #fill missing values
```pivot_table = pd.pivot_table(df, values='Value', index='Index', columns='Column')``` #pivot table




   

