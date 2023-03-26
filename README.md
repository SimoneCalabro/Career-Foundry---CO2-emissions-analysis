# Career Foundry - CO2 emissions analysis
This repository contains data (including my Jupyter notebooks and scripts) related to the project "CO2 emissions analysis".

The project was part of the Data Analytics program I attended at Career Foundry.

All analysis have been performed using **Python** (Anaconda navigator plus Jupyter).

## Project overview:
[![image](https://www.linkpicture.com/q/Picture1.jpg)](https://www.linkpicture.com/view.php?img=LPic640c7ff6b7d0f2097178861)

I covered the role of a data analyst working for an existing company, Instacart, an online grocery store that operates through an app.

The goal was to uncover more informations about _sales patterns_ (such as, busiest day and busiest hours from an order number perspective) and _customers purchasing behaviour_ (segmentation according to age, income,  regions, and other variables).

**Note:** Instacart is a real company that’s made their data available online. However, sensitive contents (such as prices and customers information) have been fabricated for the purpose of this project.

## Folders:
Here you will find a list of folders contained in the repository, along with a short description.

- **Instacart basket analysis:** the main folder. It contains 4 sub folders:
  - **01. Project management:** Contains the _Project brief_ (additional information on project's overview, context and goal).
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
