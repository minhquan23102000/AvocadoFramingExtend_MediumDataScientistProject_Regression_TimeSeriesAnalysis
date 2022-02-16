# Avocado Farming Regression And Time Series Analysis

#### -- Project Status: Completed

## Project Intro/Objective
Our company has been sought avocados in all over US, with two type of avocado. They are sought in bags (Small, Large, XLarge) each time.
Now the company wanna to extends their business, so they want to know, "where, which, when" to do that. Also, recently, they have been collected a lots of invoice data, about the shop in regions all over the US. So, do we can use the data collected, to answer their question?


### Methods Used
* Inferential, Descriptive Statistics
* Machine Learning
* Data Visualization
* Regressing Modeling
* Time Series Analysis
* Exploratory Data Analysis

### Technologies
* Python
* Pandas, Sckit-learn
* Fbprophet, AutoArima, Holt Winter (time series analysis libraries)
* Seaborn, matplotlib (data visualization)


## Project Description
The core of this problem is Exploratory Data Analysis, so in this project, i looked deeply at the data, and extract insight from its.
Also, I build a regression model to predict avocado price, to know the price we should sell, buy avocado in each region.

Data was collected directly in all over retail stores ò the company base on their sale. It was collected from 4/2015 to 3/2018.
The average price in the csv file, is reflect only for per avocado in total.
Also the product lookup code in data is only for hass avocado, not for any other type of product.

The data was saved in a csv file name "avocado.csv" with total 18249 records, and 10 colums as description bellow:
+ Date - The date records
+ AveragePrice – Average price per avocado
+ Type - conventional / organic
+ Region – The region the retail shop locate
+ Total Volume – Total volumes have been sought
+ 4046 – Total volumes of avocado with PLU id 4046
+ 4225 - Total volumes of avocado with PLU id 4425
+ 4770 - Total volumes of avocado with PLU id 4770
+ Total Bags – Total bas has been sought
+ Small/Large/XLarge Bags – Total bas has been sought group by bag's size
## Needs of this project

- data science pipeline
- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- writeup/reporting

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept ['data/avocado.csv']
    
3. Exploratory data analysis and building regressing model script is kept at ['Part1_RegressionAvocadoPrice.ipynb']

4. Time series analysis script is kept at ['Part2_TimeSerires_Analysis.ipynb']


## Contact
* My email: minhquan23102000@gmail.com