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
    - **A6 Project brief:** Criteria and limitations of the project. Guidelines provided by Career Foundry.
    - **Exploratory data analysis:** A brief report including the wrangling steps, the consistency checks, the data dictionary and my initial research questions.
    - **Population flow:** Here I describe the shape and the main differences between the different versions of the dataframe (see next folder).
  
  - **02. Data:** Contains two subfolders:
    - **Original data:** Includes the original csv file (emissions.csv) and two JSON files used for geospatial analysis. <br>
      One of the two had to compressed in a rar file because of the max file size limitation of GitHub.
    - **Prepared data:** Includes different PKL file (different versions of the dataframe, see "Population flow" PDF for more informations). <br>
      The last version is also available in csv and xlsx (I needed it to create visualizations on Tableau).
  
  - **03. Scripts:** Contains all Python scripts (Jupyter notebooks). <br>
    Within my scripts you can find all data manipulations described in the _"Skills"_ section below. <br> 
    Please note that script number 3 had to be compressed in a rar file because of the max file size limitation of GitHub.
  
  - **04. Visualizations:** Contains some of the charts and visualizations created in Python while carrying out the project. <br>
    Actually, most of visualizations were created in the ending phase of the project, using Tableau.
  
  - **05. Deliverables:** Contains the final presentation in format Tableau Packaged Workbook. <br>
    You can see the datastory directly on Tableu Public, clicking by [here](https://public.tableau.com/app/profile/simone.calabro/viz/CO2emissionsanalysis-ProjectbySimoneCalabro/Datastory).

## Dataset:
The dataset is publicly disclosed open data collected by the US Energy Administration.

I downloaded it on Kaggle. It is composed by different datasets pulled from the US Energy Information Administration, and then joined them all together into one dataset.

Below you can find links to download the CO2 emissions dataset, the time series dataset (only used in script 6) and the JSON file used for Geospatial Analysis.

[Yearly CO2 Emission, Energy Con/Prod, GDP, Population and more by Countries](https://www.kaggle.com/datasets/lobosi/c02-emission-by-countrys-grouth-and-population?resource=download)

[Carbon Dioxide (CO2) Emmissions - USA](https://data.nasdaq.com/data/BP/C02_EMMISSIONS_USA-carbon-dioxide-co2-emmissions-usa)

[Country Polygons as GeoJSON](https://datahub.io/core/geo-countries#data)

## Deliverables:
The most relevant results of my analysis were all packed together in a Tableau Datastory. <br>
If you're interested in seeing my results, click [here](https://public.tableau.com/app/profile/simone.calabro/viz/CO2emissionsanalysis-ProjectbySimoneCalabro/Datastory).

## Tools:
- Anaconda
  - Jupyter
- Tableau

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
