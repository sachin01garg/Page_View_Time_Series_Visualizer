# Page View Time Series Visualizer

For this project you will visualize time series data using a line chart, bar chart, and box plots. You will use Pandas, Matplotlib, and Seaborn to visualize a dataset containing the number of page views each day on the freeCodeCamp.org forum from 2016-05-09 to 2019-12-03. The data visualizations will help you understand the patterns in visits and identify yearly and monthly growth.

Use the data to complete the following tasks:
* Use Pandas to import the data from "fcc-forum-pageviews.csv". Set the index to the `date` column.
* Clean the data by filtering out days when the page views were in the top 2.5% of the dataset or bottom 2.5% of the dataset.
* Create a `draw_line_plot` function that uses Matplotlib to draw a line chart similar to "examples/Figure_1.png". The title should be `Daily freeCodeCamp Forum Page Views 5/2016-12/2019`. The label on the x axis should be `Date` and the label on the y axis should be `Page Views`.
* Create a `draw_bar_plot` function that draws a bar chart similar to "examples/Figure_2.png". It should show average daily page views for each month grouped by `year`. The legend should show month labels and have a title of `Months`. On the chart, the label on the x axis should be Years and the label on the y axis should be Average `Page Views`.
* Create a `draw_box_plot` function that uses Seaborn to draw two adjacent box plots similar to "examples/Figure_3.png". These box plots should show how the values are distributed within a given year or month and how it compares over time. The title of the first chart should be `Year-wise Box Plot (Trend)` and the title of the second chart should be `Month-wise Box Plot (Seasonality)`. Make sure the month labels on bottom start at `Jan` and the x and y axis are labeled correctly. The boilerplate includes commands to prepare the data.

For each chart, make sure to use a copy of the data frame. Unit tests are written for you under `test_module.py`.

## Development
For development, you can use main.py to test your functions. Click the "run" button and main.py will run.

## Testing
We imported the tests from test_module.py to main.py for your convenience. The tests will run automatically whenever you hit the "run" button.

## Languange and Libraries :
![Python](https://img.shields.io/badge/Python-3670A0?style=flat&logo=python&logoColor=ffdd54)
![NumPy](https://img.shields.io/badge/Numpy-%23013243.svg?style=flat&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3670A0?style=flat&logoColor=ffdd54)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3670A0?style=flat&logoColor=ffdd54)
## Link of Solution:

https://replit.com/@sachin89garg/page-view-time-series-visualizer