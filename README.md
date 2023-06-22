# college-major-vs-your-salary-exploratory-data-analysis-using-pandas
Learn Data Exploration with Pandas by Analysing the Post-University Salaries of Graduates by Major

https://jovian.com/anilpiparaiya/college-major-vs-your-salary-exploratory-data-analysis-using-pandas

## Learning Points & Summary




* Use ```.head()```, ```.tail()```, ```.shape``` and ```.columns``` to explore your DataFrame and find out the number of rows and columns as well as the column names.

* Look for NaN (not a number) values with .findna() and consider using .dropna() to clean up your DataFrame.

* You can access entire columns of a DataFrame using the square bracket notation: df['column name'] or df[['column name 1', 'column name 2', 'column name 3']]

* You can access individual cells in a DataFrame by chaining square brackets df['column name'][index] or using df['column name'].loc[index]

* The largest and smallest values, as well as their positions, can be found with methods like .max(), .min(), .idxmax() and .idxmin()

* You can sort the DataFrame with .sort_values() and add new columns with .insert()

* To create an Excel Style Pivot Table by grouping entries that belong to a particular category use the .groupby() method



I've attached the completed notebook to this lesson as a .zip file. If you have any issues, unzip the file, upload it to google drive and open it as a Google Colab Notebook.




