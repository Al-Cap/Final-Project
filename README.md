# Life Span of Satellites

This project will implement some topics learned in DATA601

# Introduction

The project will be using data on satellites. This data consists of various satellites made and operated by different countries and contractors. It also consists of information regarding each satellite such as purpose, mass, orbit, and many other information regarding the satellites.

# Goals

The goal in this project is to determine how long the life span of a satellite.

- Use of a regression line.
- Found predictions using ordinary least squares regression method.

# Motivation & Background

Satellites are a major importance to countries and especially people. Satellites are used for just about everything. Uses range from weather and cellphone service to military and space exploration. Various countries have their own satellites and some countries even have joint ones. However, every satellites has a life span just like everything else. Depending on when and how a satellite is made can determine how long it will last. Furthermore, it is almost impossible to predict just how long one will last since technology in space is still hit or miss has technology continues to improve.

# Table of Contents

- [Data](https://github.com/Al-Cap/Life-Span-of-Satellite/blob/main/data)	: Includes data, both original and modified
- Notebook
	+ [Getting Data](https://github.com/Al-Cap/Life-Span-of-Satellite/blob/main/code/Retrieving%2C%20Cleaning%20and%20Modeling.ipynb)	: Gets the data from an online source along with cleaning and modeling it
	+ [EDA](https://github.com/Al-Cap/Life-Span-of-Satellite/blob/main/code/EDA.ipynb)	: Explores the data
	+ [Report](https://github.com/Al-Cap/Life-Span-of-Satellite/blob/main/code/report.ipynb)	: This is the notebook submitted as part of the DATA601 Final Project
- [Graphs](https://github.com/Al-Cap/Life-Span-of-Satellite/tree/main/graphs)	: Graphs used in project
- Extra:
	+ [Utils](https://github.com/Al-Cap/Life-Span-of-Satellite/blob/main/code/utils.py)	: Function used for regression graph.

# ReadMe Navigation

[Data](https://github.com/Al-Cap/Life-Span-of-Satellite#data) - [Modeling](https://github.com/Al-Cap/Life-Span-of-Satellite#modeling) - [Results](https://github.com/Al-Cap/Life-Span-of-Satellite#results) - [Future](https://github.com/Al-Cap/Life-Span-of-Satellite#future) - [Project Info](https://github.com/Al-Cap/Life-Span-of-Satellite#project-info)

# Data

This is a dataset obtained from [https://www.ucsusa.org/resources/satellite-database](https://www.ucsusa.org/resources/satellite-database) downloaded into an excel file on November 23rd, 2020. Dataset was last updated on the site on August 1, 2020. The dataset contains 67 columns and 2,790 indices. The original data set was modified and cut down to 11 columns and 1,124 indices to contain only relevant data. An addition column was added to hold values gotten from preexisting column. Modified date saved as a csv.

# Modeling

The data used to determine the life span of satellites was the data from columns: 'Expected Lifetime' and 'Year of Launch.' These two columns provided the data to see the life span of the satellites. Life span was determine with linear regression. The linear regression can be seen in the graph which mirrors the ordinary least squares regression table.

![predicted.png](https://github.com/Al-Cap/Life-Span-of-Satellite/blob/main/graphs/predicted.png)

Linear regression is further shown in a modified version of the ordinary least squares regression table seen in the graph.

![predicted_mod.png](https://github.com/Al-Cap/Life-Span-of-Satellite/blob/main/graphs/predicted_mod.png)

# Results

The results of the linear regression show that the first regression model had a R-squared of 0.001 which does show a linear regression, however small.

The second regression model outputs a high R-squared being close to 1 which is fine but due to limitations is not a very accurate linear regression. 

# Future

This project can be improved upon in the future by adding additional parameters to determine the linear regression of the life span. These additional parameters can be anything from orbit of the satellite to the materials or manufacturing processes of the satellite.

# Project Info
<pre>
Contributor	: <a href=https://github.com/Al-Cap>Alexander Caporale</a>
</pre>

<pre>
Language	: Python v. 3.8.3
Tools/IDE 	: Anaconda v. 2020.07, Jupyter Notebook v. 6.0.3
Libraries	: pandas v. 1.0.5, matplotlib v. 3.2.2, numpy v. 1.18.5, statsmodels v. 0.11.1, utils v. 1.0.1
</pre>

<pre>
Duration	: December 2020
Last Update	: 12.08.2020
</pre>
