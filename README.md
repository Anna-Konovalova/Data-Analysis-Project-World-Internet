Data Analysis Project
======

World Internet
======

Project Overview
------
The creation of the World Wide Web in 1989 revolutionized our history of communication. In this project, I look at the global expansion of the Internet since then. I give an overview of the state of Internet access and usage in the world. More specifically, I address the following:
1. What are the top 10 countries with the highest internet use (by population share)?
2. What are the top 10 countries with the highest internet use (by number of users)? 
3. What are the top countries with the highest internet use for each of the following regions?
   * 'Middle East & North Africa'
   * 'Latin America & Caribbean'
   * 'East Asia & Pacific'
   * 'South Asia'
   * 'North America'
   * 'Europe & Central Asia'
4. World regions Internet usage over time (by population share)
5. World regions Internet usage over time (by number of users)


Tech
------
I have completed the whole project in Python, using Jupyter Notebooks. For data validation and data wrangling I used Pandas and NumPy. For data visualisation I used Matplotlib, Seaborn and Squarify.


Data
------
The data for this project is sourced from [The World Bank](data.worldbank.org). 

The following csv files have been compiled:

#### internet
- "Entity" - The name of the country, region, or group.
- "Code" - Unique id for the country (null for other entities).
- "Year" - Year from 1990 to 2019.
- "Internet_usage" -  The share of the entity's population who have used the internet in the last three months.

#### people
- "Entity" - The name of the country, region, or group.
- "Code" - Unique id for the country (null for other entities).
- "Year" - Year from 1990 to 2020.
- "Users" - The number of people who have used the internet in the last three months for that country, region, or group.


Data Analysis Summary
------
### 1. What are the top 10 countries with the highest internet use (by population share)?

#### First, I look at the highest internet use (by population share) for the period from 2007 to 2017.
&nbsp;


![Graph_1](https://user-images.githubusercontent.com/78367070/203578083-06d37e6f-9c27-41a9-9106-b796d82f532a.png)


![Graph_1 1](https://user-images.githubusercontent.com/78367070/203587270-50e89842-b056-4f79-9178-d64d773988cf.png)



&nbsp;
* The 
