# **PROJECT-1**
![download](https://github.com/Cameron762/Project-1-11/assets/72319764/7f8c363a-026a-429c-be56-127ed8535605)

**PROJECT TITLE:**
The correlation of Tourism with the GDP and Poplation of Global Countries.  

[PROJECT DESCRIPTION](#project-description)   
[CONTRIBUTORS](#contributors)  
[INSTALLATION](#installation)  
[DOCUMENTATION](#documentation)  
[DEVELOPMENT](#development)  
[CONCLUSION](#conclusion)

**PROJECT DESCRIPTION**  
Tourism is a huge global industry and tends to correlate with how well countries perform economically. Explore how tourism arrivals and expenditure correlate with the GDP of a country and examine if the population of a country places any effect on these correlation.
*Research questions to ask:*
1. What country has the most inbound tourists?
2. What country has the highest international tourism receipts?
3. What country has the highest GDP?
4. What is the correlation of these data points?

**CONTRIBUTORS**
- Kelechi Joel Github Link: https://github.com/kcjoel
- Julia Dettman Github Link: 
- Jonathan Rascon Github Link:
- Cameron Carson Github Link: https://github.com/Cameron762
  
**INSTALLATION** 
- Python 
- Code Editor (Visual code, jupyter etc)
- import pandas 
- from pathlib import Path
- import numpy 
- import matplotlib.pyplot 
- import scipy.stats
- No other installations should be needed to run code 

**DOCUMENTATION**

https://fbj.springeropen.com/articles/10.1186/s43093-020-00048-3#:~:text=It%20enhances%20economic%20growth%20by,positive%20externalities%20%5B1%2C%2014%5D

https://www.diva-portal.org/smash/get/diva2:1564594/FULLTEXT01.pdf

*Rough breakdown of tasks:*

 
- Julia Dettman: find data source, work on year 2016
- Cameron Carson: clean the data, work on year 2017
- Jonathan Rascon: work on year 2018
- Kelechi Joel: work on year 2019, Readme
- Group Presentation: All
- Slide Deck: All complete individual slides  

**DEVELOPMENT**  
- Start by downloading the clean3data to your computer
- On a coding editor, install all neccessary installations needed to run the code
- Using pathlib, add a path to call the downloaded data directly to your editor
- Delete unwanted columns and rows using the del function and dropna function
- create a function that helps automatically graph coordinates, this will be used in our correlation analysis for question 4
- Sort the data frame for only certain years and save those files to be analyzed
- To answer Question 1, plot countries vs Arrivals
- sort data for the first 10 countries, and plot that into a pie chart
- To answer Question 2, plot countries vs Tourism receipts
- sort data for the first 10 countries and plot that into a pie chart
- To answer Question 3, plot countries vs GDP
- sort data for the first 10 countries, and plot that into a pie chart.
- To answer question 4, build two scatter plots: one for Inbound tourist vs GDP, and the second for GDP and receipts
- Using the scatter plot information compare and contrast the relationships between these factors.
- note: If any data is a huge outlier, eliminate it and redo processes so analyses can better be understood.

