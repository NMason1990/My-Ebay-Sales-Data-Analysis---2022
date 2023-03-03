# Ebay Sales Data Analysis for 2022

For this project I have taken all sales data of transactions from my eBay store for 2022 and imported them. 
 I want to clean the csv, analyze and visualize the data to see my total gross sales per month for the year,total net sales per month, avg. sale price of items, total fees and shipping, and the density of where people are ordering from. I will be using pandas,matplotlib, and pyplot to accomplish this. 

## Relevant Python Packages

See Requirements.txt file



## Read data in 

Read in data from a local csv,
excel file, json, or any other
file type. There are many
ways to do this, but using
Pandas read_ functions is
pretty easy. I did this in the first code cell

## Manipulate and Clean Data

1. Use built-in pandas or numpy
functions to do things like
remove 0’s and null values
where they don’t belong in
your dataset. Did this in code cells 2-4 By filtering columns I need, changing date column to date time and splitting into 3 new columns, changing Month column to abbreviated months instead of 1-12. Then changing that column to categorical so they displayed in the correct order.

2. Use custom functions or
lambdas to perform specific
operations to clean or manipulate your data, return
those values, then use them
in other parts of your project. Did this in code cells 6 and 7. Used lambda to add costs to data by subtracting net from gross sales. Also used lambda in the code for the bar graph as the key. 

## Analyze Data!

Do 5 basic calculations with
Pandas, like finding the
sum(), median(), mean(), or
mode() of a column. You
could divide two columns by
each other. You could
multiple a column by a
random integer. You could
use string operations and find
the most common letter in a
given entry. - Did this in code cells 6-7 using lambda and pandas functions to aggregate total net and gross sales per month, subtracting those two totals to get a new data point called costs, then using those totals to also calculate the mean of those 3 data points to know average per month of all of these. Also using the same blocks of code I calculated and got the same calculations for the entire year. 

Use at least 5 different built-in
Python functions to find out
something about your data. If
you had a list for example,
finding the length of that list
with len(<list>) does tell us a
little bit about the data. - Used pandas functions to find date time, to find out the total sales per month. 

## Visualize Data

Make 2 basic plots with
matplotlib, seaborn, or any
other kind of visualization
library that you think looks
interesting. - Did this in code cells - Made two plots one with Sales per month. Net and gross, as well as costs per month, Also averages for net and gross per month, Did the same in a separate plot for the year. 

## Interpret Data Graphical Output

Write markdown cells in
Jupyter explaining your
thought process and code. If
you make a few plots with
matplotlib, explain what the
reader is seeing and why you
chose to plot things that way.