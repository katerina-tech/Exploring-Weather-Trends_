<p align="center">
  <a href="https://www.udacity.com/">
    <img src='https://course_report_production.s3.amazonaws.com/rich/rich_files/rich_files/5511/s300/udacity-logo.png' alt="Udacity logo" width = 100px>
   </a>
</p>
<h3 align="center"><a href='https://www.udacity.com/course/data-analyst-nanodegree--nd002'> Udacity Data Analyst Degree </a></h3>
<h4 align="center">  Project I: Exploring Weather Trends in Berlin </h4>

## Table of Contents
- [Installation](#installation)
- [Summary](#summary)
- [Project Instructions](#pi)
- [Results](#results)

## Installation <a name="installation"></a>
You need to be able to work in a Excel on your computer or you can analize plot with Python or R. 
Also you need have basic knowlefge of SQL to download Data-set through SQL.

### Summary <a name="summary"></a>
In this project, we will analyze local and global temperature data and compare the temperature trends of Seattle city to overall global temperature trends.

### Project Instructions <a name="pi"></a>
Your goal will be to create a visualization and prepare a write up describing the similarities and differences between global temperature trends and temperature trends in the closest big city to where you live. To do this, you’ll follow the steps below:

<ul>
  <li><strong>Extract the data from the database</strong> There's a workspace in the previous section that is connected to a database. You’ll need to export the temperature data for the world as well as for the closest big city to where you live. You can find a list of cities and countries in the city_list table. To interact with the database, you'll need to write a SQL query.</li>
       <ul>  
         <li>Write a SQL query to extract the city level data. Export to CSV.
         <li> Write a SQL query to extract the global data. Export to CSV.</li>
       </ul>
  <li><strong>Open up the CSV</strong> in whatever tool you feel most comfortable using. We suggest using Excel or Google sheets, but you are welcome to use another tool, such as Python or R.
  </li>
  <li><strong>Create a line</strong> chart that compares your city’s temperatures with the global temperatures. Make sure to plot the moving average rather than the yearly averages in order to smooth out the lines, making trends more observable (the last concept in the previous lesson goes over how to do this in a spreadsheet).
  </li>
  <li><strong>Make observations</strong> about the similarities and differences between the world averages and your city’s averages, as well as overall trends. Here are some questions to get you started.
  </li>
  <ul>
    <li>Is your city hotter or cooler on average compared to the global average? Has the difference been consistent over time?</li>
    <li>“How do the changes in your city’s temperatures over time compare to the changes in the global average?”</li>
    <li>What does the overall trend look like? Is the world getting hotter or cooler? Has the trend been consistent over the last few hundred years?</li>
   </ul>
</ul>

## Results <a name="results"></a>
<p align="center">
  <img src="https://github.com/katerina-tech/Exploring-Weather-Trends_/blob/main/moving_averages.jpg">
</p>

<p align="center">
  <img src="https://github.com/katerina-tech/Exploring-Weather-Trends_/blob/main/yearly.jpg">
</p>
