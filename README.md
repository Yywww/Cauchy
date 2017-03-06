# Cauchy



# Overview

Cauchy is small application written by Yiwen Luo to read SAS dataset and produce summary statistics, frequency table and plots. No SAS software is required to run this application. This is a project for me to practice python plotting and tkinter interface.

Below is the main window of this application
![Alt text](./Example/Main Window.png?raw=true "Optional Title")
# Functionality
Before use any of below functions, users will need to load their SAS dataset. Click 'Load SAS dataset' and choose your dataset.
![Alt text](./Example/Choose dataset to load.png?raw=true "Optional Title")


1)Frenquency Table

This function will list all variable find in the dataset and give their frequency table one by one. All variable have a addition row stating the unique value count of this variable. If missing are found in this variable, another row is added with the number of missing observations of this variable.
![Alt text](./Example/Variable Frequency.png?raw=true "Optional Title")

2)Summary Statisitcs

This function returns summary statistics for all numeric variable found in dataset. Every variable will have six column, which are : number of nonmissing observations, max value, min value, mean, median, number of missing observations.
![Alt text](./Example/Variable Statistics.png?raw=true "Optional Title")

3)Filter

This feature allow you to subset loaded dataset based on criteria you can specify. All other functions result will be updated to the new subset of dataset. The filter information will be shown at the botton of main window. It also allow user to remove filter.
![Alt text](./Example/Filter.png?raw=true "Optional Title")

4)Bar Plot

Will give bar plot based the variable you choose.
![Alt text](./Example/Bar Plot.png?raw=true "Optional Title")

5)Scatter Plot

At the bottom of poped window, you could choose two numeric variable and produce their scatter plot. On that plot, you can use mouse to circle any one or more data point to see their value. You can also see that data point other variable's value be check additional variable box in the plot setting window.
![Alt text](./Example/Scatter Plot Setting.png?raw=true "Optional Title")
![Alt text](./Example/Scatter Plot.png?raw=true "Optional Title")


6)Histogram Plot

Same as bar plot, will produce histogram.







