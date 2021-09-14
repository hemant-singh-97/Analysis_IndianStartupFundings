# Analysis on Indian Startups Fundings from 2015 – 2020 

## 1) Overview :

The purpose of the project is to vizualise different developments of the state of funding and different startups over the years 2015 – 2020. To achieve the goal and answer some questions through the visualizations, the data needs to be cleaned first. So, the project is divided into two major parts :-

**1) Data Cleaning**

**2) Visualizations**


### 1.1) Data Cleaning :

The dataset used can be found in [source](https://www.kaggle.com/sudalairajkumar/indian-startup-funding). Also mentioned in the **Visualizations.ipynb** while reading data, and I have included this file as well by the name **startup_funding.csv**.

So, this CSV file had 10 columns, with the columns I will tell their inclusion or exclusion status for the further analysis. These columns are :
1. Sr No : Excluded
2. Date dd/mm/yyyy : Included(Very Important) 
3. Startup Name : Included(Very Important)
4. Industry Vertical : Included
5. SubVertical : Included
6. City Location : Included(Important)
7. Investors Name : Included(Important)
8. Investement Type : Included(Important)
9. Amount in USD : Included(Most Important)
10. Remarks : Excluded

The reason for the column’s inclusion and exclusion can be found inside **Visualizations.ipynb**


### 1.2) Visualizations :

These Visualizations answers the following questions :
1. Trend of the frequency of investment from 2015 – 2020
2. Top 10 cities with the most number of startups
3. Top 10 cities with the most amount of funding
4. Percentage Distribution of 4 major funding types
5. Top 5 industries that recieves most funds
6. Top 10 startups to have the most amount of funding
7. Top 10 startups with the most funding rounds
8. Top 5 most frequent investors
9. Trend of the 4 major types of funding over years 2015 - 2020
10. Trend of funding status of the top 5 most funded startups

## 2) Technical Details :

### 2.1) Python Libraries used :

* pandas
* re
* datetime
* numpy
* matplotlib
* Counter (from collections)

### 2.2) Main Code File :

**Visualizations.ipynb** has all the code for data cleaning and visualizations as discussed in the *Overview* section.

### 2.3) Plots :

All the plots can be found in the folder **Plots**


## 3) Example Plots :

The first two plots are as follows :

### 3.1) Trend of the frequency of investment from 2015 – 2020 :

![Plot 1](/Plots/fig_1.png)

### 3.2) Top 10 cities with the most number of startups :

![Plot 2](/Plots/fig_2.png)
