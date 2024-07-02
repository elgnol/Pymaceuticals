# Pymaceuticals

## Overview
Given two data sets containing information on the mice, their drug regimen, and tumor volume. 
This assignment is broken down into the following tasks:
- Prepare the data.
- Generate summary statistics for tumor volume.
- Create bar charts and pie charts displaying number of observed mouse timepoints for each drug regimen
and gender distribution respectively.
- Calculate quartiles, find outliers, and create a box plot for tumor volume for the four most promising drug regimen.
- Create a line plot showing one mouse tumor volume relative to timepoints on one of the promising
drug regimen and a scatter plot displaying the correlation between tumor volume and weight of the mice.
- Calculate correlation and regression of weight vs. tumor volume.

## Analysis
Looking at our boxplot graph we can see the the two most effective drug regimen based on our data are Capomulin and Ramicane since their tumor volume is smaller
than the other two drug regimens.
![Image of Boxplot for the four promising drug regimens](https://github.com/elgnol/Pymaceuticals/blob/main/images/box_plot.png)

Although, with our current data Capomulin and Ramicane seems to have the most effectiveness they had more number of observed timepoints which can skew the data to their favor as we don't have
the same number of observed timepoints for the other drug regimen.
![Image of barchart displaying  the number of observed timeponts for each drug regimen](https://github.com/elgnol/Pymaceuticals/blob/main/images/bar_chart.png)

The correlation between the mice's weight versus the tumor volume is positive. The more the mouse weigh the larger the volume of the tumor is displayed by the scatter plot that
was plotted in our code. 
![Image of scatter plot with regression line Weight vs. Tumor Volume](https://github.com/elgnol/Pymaceuticals/blob/main/images/regression_line.png)



