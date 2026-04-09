---
layout: page
title: Homework 6 Visualization
---

## Plot 1

<iframe src="plot1.html" width="700" height="500"></iframe>

This visualization shows the number of licenses for each license type in the dataset. I used a bar chart because it makes it easy to compare how many records fall into each category. The x-axis represents the number of licenses, which is a quantitative variable, and the y-axis represents the license type, which is categorical. I also used color to distinguish between the different license types so it is easier to read and compare across the chart. In my analysis, I cleaned the data by removing missing values and focused on the top 10 most common license types so the chart would not be too crowded.

## Plot 2

<iframe src="plot2.html" width="700" height="500"></iframe>

This visualization shows how license expiration years are distributed across different license types. I used a scatter plot to show how the data is spread out over time for each category. The x-axis represents the expiration year, and the y-axis represents the license type. I kept the color encoding consistent with the first chart so the categories are easy to follow. In my notebook, I converted the expiration date column into a datetime format and extracted the year so it could be used clearly in the visualization.

## Interactivity

I added a click interaction where selecting a category in the first chart filters the second chart. This helps make the visualization clearer because it allows the user to focus on one group at a time instead of looking at all of the data at once.

## Links

[The Data](https://github.com/UIUC-iSchool-DataViz/is445_data/raw/main/licenses_fall2022.csv)

[The Analysis](https://github.com/dphelan3/dphelan3.github.io/blob/main/HW5-2.ipynb)
