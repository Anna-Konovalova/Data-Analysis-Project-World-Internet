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

<img width="655" alt="Graph_01" src="https://user-images.githubusercontent.com/78367070/203588110-7ea08143-de1a-4cdc-b977-5b5df5d810b2.png">
&nbsp;
* In the 10 year period from 2007 to 2017 Scandinavian and Northern European contries dominated in terms of the highest internet usage by population share. This suggests that these are the top countries in the world where majority of people in all geographic areas (e.g. urban, rural) are connected to the internet.
&nbsp;

&nbsp;
#### Second, I look at the highest internet use (by population share) for the year 2017 only.
&nbsp;

<img width="655" alt="Graph_2 3" src="https://user-images.githubusercontent.com/78367070/203590921-fbdbfb86-792d-402a-9911-0ce2171e94af.png">
&nbsp;
* Narrowing down the previous analysis to 2017 only, shows that out of all the countries dominating the 2007-2017 period, Lichtenstein, Iceland, Denmark, Luxembourg and Bermuda are still standing at the top.
* However, in 2017 compared to 2007-2017 there several other contries with the highest Internet use by population share. Specifically, Kuwait (Middle East), Qatar (Middle East), Aruba (South America) and Monaco (Western Europe). 
&nbsp;

&nbsp;
### 2. What are the top 10 countries with the highest internet use (by number of users)?
&nbsp;

<img width="655" alt="Graph_03" src="https://user-images.githubusercontent.com/78367070/203594437-e7515193-0e2f-4b25-b08c-ec2392afe2b4.png">
&nbsp;
* The top countries with the highest internet use by number of users include China, India, United States, Brazil, Indonesia, Russia, Japan, Mexico, Egypt and Germany. 
* These countries differ significantly to the top countries with the highest internet use by population share (shown before). Noticeably, most of these countries have larger populations comparing to Scandinavian and Northern European countries. This suggests that with a bigger population, more people are connected to the internet. However, this does not necessarily mean that all geographical areas within those countries are proportionally connected to the Web.
&nbsp;

&nbsp;
### 3. What are the top countries with the highest internet use in different World regions?
&nbsp;

![Graph_4](https://user-images.githubusercontent.com/78367070/203596384-ca235cb8-6607-409a-891e-de92c023027d.png)
&nbsp;
* Noticeably, South Asian countries have the lowest population proportions using Internet. 
&nbsp;

&nbsp;
### 4. World regions Internet usage over time (by population share)
&nbsp;

![Graph_5 2](https://user-images.githubusercontent.com/78367070/203601560-c579e7c9-269a-431f-a549-c719f038c581.png)
&nbsp;
* Global Internet usage has expanded substantially from being close to 0% of the total world population in 1990. 
* The biggest expansion is seen by North America. Just over 80% of the population in North America was connected to the Internet in 2010, and around 90% in 2015. 
* North America is followed by Europe and Central Asia, with just over 70% of the population connecting to the Web in 2015.
* Middle East and North Africa, Latin America and Caribbean, East Asia and Pacific are all between 50 and 70% of their respective population shares in 2017.
* The slowest growth in Internet usage over the years is seen by South Asia, having just under 30% of population using the Internet in 2017.

&nbsp;
### 5. World regions Internet usage over time (by number of users)
&nbsp;

![Graph_6 3](https://user-images.githubusercontent.com/78367070/203603136-ca3ed4f8-84a3-4380-b12a-c8e86df0b466.png)
&nbsp;
