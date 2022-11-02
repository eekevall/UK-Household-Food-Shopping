# Obesity and UK Household Food Shopping

A machine learning analysis using Python and Tableau to analyse income and spending on food data.

## Project Overview
**Motivation** : Poor diet within the UK is a public health issue and the UK is ranked as one of the worst in Europe for levels of obesity, particularly among children. A [study in the journal Public Health Nutrition](https://www.cambridge.org/core/journals/public-health-nutrition/article/household-availability-of-ultraprocessed-foods-and-obesity-in-nineteen-european-countries/D63EF7095E8EFE72BD825AFC2F331149) showed that families buy more 'ultra-processed' food than other European countries; with these products accounting for more than half of all UK family food purchases. ‘Ultra-processed’ food - food made in a factory with industrial ingredients and additives you wouldn’t find in your kitchen - bears little resemblance to the fruit, vegetables, meat or fish used to cook a fresh meal at home. Could these products be driving the rise in obesity? 

**Objective** : The project investigates if there are any relationships between ‘ultra-processed’ food, household expenditure and obesity. 

**Scope** : The project focuses on the UK and look at data from 2015 up to 2020.

### Data Sets
The following data sets were used during the project:
1. The Living Costs and Food Survey derived Urban and Rural Household Characteristics Data for the years 2015 to 2020 downloaded from the [UK Data Service website](https://beta.ukdataservice.ac.uk/datacatalogue/studies/?Search=living+costs+food+survey#!?Search=living%20costs%20food%20survey&Page=1&Rows=10&Sort=1&DateFrom=440&DateTo=2022).

These files contain information on household composition, household characteristics, aggregate household spending and items that are contained in a household. 

2. [UK_BMI.xlsx](https://github.com/eekevall/UK-Household-Food-Shopping/blob/main/02_Data/02_1_Original_Data/UK_BMI.xlsx)

Regional obesity data for the UK.

3. [uk_regions.geojson](https://github.com/eekevall/UK-Household-Food-Shopping/blob/main/02_Data/02_1_Original_Data/uk_regions.geojson)
A geospatial file for the UK regions.


### Data Analysis Tasks
* Formulating a research hypothesis and sourcing the right data
* Data profiling, quality, transformation and integration
* Exploratory data analysis
* Supervised Machine Learning: Regression
* Unsupervised Machine Learning: Clustering
* Analyzing Time Series Data
* Consolidating analytical insights 
* Create a data dashboard communicating research findings and insights

### Tools
The analysis was carried out using Python and Tableau.

### Hypothesis<br>
**If a household has a higher disposable income, then they buy less ultra-processed foods compared to other food categories.**

## Project Processes and Findings

*The following document contains:*

An overview of the data sets consulted including the assumptions and constraints.
The data profiles documenting the cleaning, wrangling and consistency checking processes.
* [UK_Household_Food_Shopping.pdf](https://github.com/eekevall/UK-Household-Food-Shopping/blob/main/01_Project_Management/01_Project_Management/UK_Household_Food_Shopping.pdf)

*The following Python scripts contain*
Data cleaning, wrangling, transforming, mapping and integrating processes: 
* [UK_BMI_Data_Cleaning.ipynb](https://github.com/eekevall/UK-Household-Food-Shopping/blob/main/03_Scripts/UK_BMI_Data_Cleaning.ipynb)
* [1_LCF_File_Conversion_Join.ipynb](https://github.com/eekevall/UK-Household-Food-Shopping/blob/main/03_Scripts/1_LCF_File_Conversion_Join.ipynb)
* [2_LCF_Data_Cleaning_Descriptive_Stats.ipynb](https://github.com/eekevall/UK-Household-Food-Shopping/blob/main/03_Scripts/2_LCF_Data_Cleaning_Descriptive_Stats.ipynb)
* [3_LCF_Data_Wrangling.ipynb](https://github.com/eekevall/UK-Household-Food-Shopping/blob/main/03_Scripts/3_LCF_Data_Wrangling.ipynb)

Exploratory data analysis:
* [4_LCF_EDA.ipynb](https://github.com/eekevall/UK-Household-Food-Shopping/blob/main/03_Scripts/4_LCF_EDA.ipynb)

Geospatial data analysis:
* [5_LCF_Geospatial_Analysis.ipynb](https://github.com/eekevall/UK-Household-Food-Shopping/blob/main/03_Scripts/5_LCF_Geospatial_Analysis.ipynb)

Machine Learning Regression Analysis:
* [6_LCF_ML_Regression.ipynb](https://github.com/eekevall/UK-Household-Food-Shopping/blob/main/03_Scripts/6_LCF_ML_Regression.ipynb)

Machine Learning Clustering Analysis
* [7_LCF_ML_Clustering.ipynb](https://github.com/eekevall/UK-Household-Food-Shopping/blob/main/03_Scripts/7_LCF_ML_Clustering.ipynb)

Analysing Time Series Data Analysis:
* [8_LCF_Analyzing_Time_Series_Data.ipynb](https://github.com/eekevall/UK-Household-Food-Shopping/blob/main/03_Scripts/8_LCF_Analyzing_Time_Series_Data.ipynb)

### Presenting the findings as a dashboard for the general public
* Link to the [Interactive Story Dashboard in Tableau](https://public.tableau.com/app/profile/elsa2253/viz/ObesityandHouseholdShoppingHabits/UKHouseholdFoodShopping?publish=yes)
