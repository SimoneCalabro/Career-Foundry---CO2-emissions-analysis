# Career Foundry - CO2 emissions analysis
This repository contains data (including my Jupyter notebooks and scripts) related to the project "CO2 emissions analysis".

The project was part of the Data Analytics program I attended at Career Foundry.

All analysis have been performed using **Python** (Anaconda navigator plus Jupyter).

## Project overview:

This project was different from the previous, because I had the freedom to source myself the dataset and define the key questions to analyze during the development.

I decided to use a dataset that includes measurements of CO2 emissions, energy consumption, energy production, GDP, Population, divided by year, Country and different energy types (such as, coal, natural gas, petroleum, nuclear and renewable).

My goal was to investigate air pollution, focusing primarly on:

- Relationships between CO2 emissions and other variables
- Geospatial analysis (which Countries produce more CO2 emissions on average)
- Differences between energy source (which of them are more polluting and more consumed by Countries)

## Folders:
Here you will find a list of folders contained in the repository, along with a short description.

- **CO2 emissions analysis:** the main folder. It contains 5 sub folders:
  - **01. Documentation:** Contains the following PDF files:
   - sdshdsudsd 
  - **03. Scripts:** Contains all Python scripts (Jupyter notebooks). Within my scripts you can find all data manipulations described in the _"Skills"_ section below.
  - **04. Analisys/Visualizations:** Contains all the charts and visualizations created while carrying out the project.
  - **05. Sent to client:** Contains an excel report that summarize the population flow, all wrangling steps, consistency checks, columns derived and answers to the key questions (the analysis' main goal).

**Note:** Section _02._ is missing because it contained the datasets used, both _Original data_ (raw) and _Prepared Data_ (manipulated).
Since files size was higher than 25 MB, it was impossible to upload them.

## Dataset:
As explained above, Instacart made their data open source.

Keep in mind that sensitive contents (such as prices and customers information) have been fabricated for the purpose of this project.

Below you can find a link to download the orders dataset, the customers dataset and a Github data dictionary containing a brief description of the variables.

[The Instacart Online Grocery Shopping Dataset 2017](https://www.instacart.com/datasets/grocery-shopping-2017)

[Customers data set](https://s3.amazonaws.com/coach-courses-us/public/courses/data-immersion/A4/A4_Data_Assets/customers.zip)

[Data dictionary](https://gist.github.com/jeremystan/c3b39d947d9b88b3ccff3147dbcf6c6b)

## Tools:
- Anaconda
  - Jupyter

## Libraries:
Here you can find a list of all libraries installed and imported into my scripts:

- pandas
- numpy
- os
- matplotlib
- seaborn
- scipy

## Skills:
A summary of what I applied:

- Cleaning data
  - Data wrangling (renaming columns, dropping columns, transposing, changing columns datatype)
  - Consistency checks (handling missing values, duplicates and mixed-type data)
- Creating a data dictionary
- Creating a Subset
- Calculating descriptive statistics
- Grouping and aggregating data
- Creating crosstabs
- Deriving new variables (if-statements, loc function and for-loops)
- Creating visualizations (histograms, bar charts, stacked bar charts, line charts, pie charts, scatterplots)
- Merging two dataframes (concatenating, append, join merge)
- Exporting dataframes (both in CSV and PKL format)
