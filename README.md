# Exploratory-Data-Analysis-

## Overview
I used Python to explore the dataset that conisted of the countries of the world. I also used visualization library in Python to visualize the explored dataset,

I used:
- Line plot
- Heatmap
- Boxplot

Special codes in this project include

```Python
df3 = df2.transpose()
  ````
 
   ``` Python
df2 = df.groupby('Continent').mean().sort_values(by = '2022 Population', ascending = False)
```


```Python
sns.heatmap(df.corr(), annot = True)
plt.rcParams['figure.figsize'] = (20, 10)
plt.show()
```


```Python
df.select_dtypes(include = 'object')

``` 


And many more.
[View the full code here](https://github.com/TommyDatageek01/Exploratory-Data-Analysis-/blob/main/EDA.ipynb) 


