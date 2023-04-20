# Capstone_Project :

## Introduction :
This is a dataset that tracks relevant population statistics and employment rates per US state since 1976. And I will be using Python to create visulization that provides insights into unemployment trends for different US states .



===============================================================================================

## Objective:

#### The objective of a Python project using the unemployment data provided in the Unemployment in America Per US State.csv is to

#### Clean and preprocess the data: Load the CSV file into a Pandas DataFrame and perform data cleaning operations such as removing duplicates, handling missing values, and correcting data types.

#### Explore and visualize the data: Use Matplotlib or other visualization libraries to generate charts and graphs to analyze the data and identify trends or patterns.

#### objective of the visualization created in this project is to explore and analyze the trends and patterns of unemployment rates across different states in the United States over the period ,. The visualization aims to provide insights into the changes in unemployment rates over time and identify the states that are most affected by unemployment. The visualization includes various graphs and charts, such as line charts, bar charts, and heatmaps, to represent the data in an interactive and intuitive manner. Through this visualization, the user can easily identify the states with the highest and lowest unemployment rates, Top 10 State with High mean Unemployment Rate,Top 10 State with High percentage of Labour Force, observe the changes in unemployment rates over time, and compare the unemployment rates across different states. Overall, the objective is to provide a comprehensive and insightful analysis of the unemployment rates in the United States using visualizations.
=================================================================================================
## Scope:

#### Data Sources

The primary data source for this project is the Bureau of Labor Statistics (BLS), which publishes monthly updates on unemployment rates for US states since January 1976. The BLS also provides a technical note that gives an overview of their unemployment data, methodology, and definitions for the variables tracked, providing essential contextual knowledge to create a meaningful dataset.

 #### 1. Statistics Being Tracked
 
 ##### 2.  FIPS Code of State/Area

 ##### 3. Year/Month of Statistic

 ##### 4. Total Civilian Non-Institutional Population in State/Area

 ##### 5. Total Civilian Labor Force in State/Area

 ##### 6. Percent (%) of State/Area's Population

 ##### 7. Total Employment in State/Area

 ##### 8. Percent (%) of Labor Force Employed in State/Area

 ##### 9. Total Unemployment in State/Area

 ##### 10. Percent (%) of Labor Force Unemployed in State/Area

### Key Performance Indicators (KPIs): 

The dashboard should display the following KPIs:

1. Unemployment rate by state.

2. Top 10 states with highest mean unemployment rate.

3. Top 10 states with highest percent of labour force.

4. Unemployment trends by year and month

### Visualization Requirements:
should include the following visualizations:

Bar chart.

Line chart .

Pie chart.

## Technologies Used

[.matpolib](https://matplotlib.org/)  

[.pandas](https://pandas.pydata.org/)

[.seaborn](https://seaborn.pydata.org/)

=====================================================================================================================================

## Steps:

 
 Importing Required Libraries: This step involves importing the necessary libraries for the project such as pandas, numpy, matplotlib, and seaborn.

![alt text](https://github.com/Kingm11/Capstone_Project/blob/main/visulization%20using%20python/import.png)

Loading the Dataset: In this step, the dataset is loaded into the notebook using pandas.

![alt text](https://github.com/Kingm11/Capstone_Project/blob/main/visulization%20using%20python/read.png)

Data Cleaning: This step involves data cleaning, where data is checked for missing values and any outliers.

![alt text](https://github.com/Kingm11/Capstone_Project/blob/main/visulization%20using%20python/info.png)

We can see that there are 29892 entries and each column has a non-null count of 29892 so we can infer that there are no null values in this dataset even without using df.isnull.sum()
  

Creating Function: Creating function which will perform predefined action

![alt text](https://github.com/Kingm11/Capstone_Project/blob/main/visulization%20using%20python/function.png)
  

 Exploratory Data Analysis (EDA): EDA is performed using various graphical and statistical methods to understand the data better.To see unemployment trend during initial spread of covid from may to july 20202.

 Data Visualization: Data visualization is performed using different libraries like matplotlib, seaborn, and plotly to create various plots and charts to visualize the data.


## Visulization


![alt text](https://github.com/Kingm11/Capstone_Project/blob/main/visulization%20using%20python/Screenshot%202023-04-19%20031354.png)
#### Top 10 state % of population which was unemployed during the month of  april and may 2020


![alt text](https://github.com/Kingm11/Capstone_Project/blob/main/visulization%20using%20python/Screenshot%202023-04-19%20031432.png)
#### Top 10 state % of population which was unemployed during the month of  june and july 2020


![alt text](https://github.com/Kingm11/Capstone_Project/blob/main/visulization%20using%20python/Screenshot%202023-04-19%20031512.png)
#### Contribution of top 10 state % of population which was unemployed during the month of  April to the total % of unemployed people in US


![alt text](https://github.com/Kingm11/Capstone_Project/blob/main/visulization%20using%20python/piemay.png)
#### Contribution of top 10 state % of population which was unemployed during the month of  May to the total % of unemployed people in US
  

![alt text](https://github.com/Kingm11/Capstone_Project/blob/main/visulization%20using%20python/piejune.png)
#### Contribution of top 10 state % of population which was unemployed during the month of  June to the total % of unemployed people in US


![alt text](https://github.com/Kingm11/Capstone_Project/blob/main/visulization%20using%20python/piejuly.png)
#### Contribution of top 10 state % of population which was unemployed during the month of  July to the total % of unemployed people in US


![alt text](https://github.com/Kingm11/Capstone_Project/blob/main/visulization%20using%20python/un5.png)
#### Top 10 statewith high % of labour force 


![alt text](https://github.com/Kingm11/Capstone_Project/blob/main/visulization%20using%20python/un4.png)
#### Top 10 state with high mean unemployment rate


![alt text](https://github.com/Kingm11/Capstone_Project/blob/main/visulization%20using%20python/un6.png)
#### Unemployment rate in Arizona from 1976-2022

## Documentation

[Video Explaning the notebook ](https://github.com/Kingm11/Capstone_Project/tree/main/Video)  
[.ipynb file ](https://github.com/Kingm11/Capstone_Project/blob/main/Capstone.ipynb)  
[.py file ](https://github.com/Kingm11/Capstone_Project/blob/main/capstone.py)  
[Data](https://github.com/Kingm11/Capstone_Project/tree/main/Data)
