# Fundamentals-Assessment-2019
![tipping](/Images/tipping.png)
## scope
To describe and analyse of the Tips dataset. Fundamentals of data analysis module project 2019
[See here for instructions](https://github.com/ianmcloughlin/project-2019-fundda/raw/master/project.pdf)
## Table of Contents
1. Overview of Project
2. Description of the tips dataset
3. Regression of dataset to determine if a relationship between total bill and tip amount exists
4. Further analysis of the tips dataset

## Overview of project
The purpose of this project is to use jupyter and the python seaborn package to describe and analyse the tips dataset. Jupyter is a python package used to present code and plots all in one browser environment, making it a very useful tool for presenting and sharing work in python. Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics [1]. The project will firstly create a jupyter notebook that uses descriptive statistics to describe the tips data set. It will then use a statistical method called regression to discuss and analyse if there is a relationship between two variables in the tips dataset (Total bill and Tip). Finally, the project will extend the above to analyse other possible relationships within the dataset.

## Description of the dataset
The tips dataset is a well known dataset consisting of information recorded by a waiter about each tip received over a period of a few months working in one restaurant. This data consisted of 7 variables (Total bill, Tip, Gender(Sex), Smoker(Y/N), Day, Time and Size (Party size)). This dataset has been used as a good basis to learn and understand statistics and analysis of data. The raw data collected for the tips dataset can be seen [here](/Data/tips.csv).

To best explain and discuss the tips dataset, please follow the below link to a jupyter notebook
[tips dataset jupyter notebook](https://nbviewer.jupyter.org/github/BarryClarke/Fundamentals---Assessment-2019/blob/master/Tips%20dataset.ipynb)

*Note: As this notebook contains certain text formatting that is not loading into GitHub, nbviewer is the best location to open this file.

Firstly, we look at the use of the pandas package to present and analyse the data. Pandas offers some very useful tools that can help manipulate and present the data in a meaningful manner. For instance, in the jupyter noetbook, two expressions of the data can be viewed through the use of the pandas and matplotlib packages. These plots give the viewer a good general idea as to the relationship between the total bill and the tip in each record of the tips dataset. Using this, the analyst can make general statements about the data. For example, generally speaking, the average tip varies bwteen 10% and 25%. Or, there is 1 outlier where the customer paid a tip of 70% of the total bill. These are all good starting points for analysing data 

A second package in Python that allows for descriptive statistical analysis is the Seaborn package. It is built on top of matplotlib and closely integrated with pandas data. Used in conjunction with Matplotlib, Seaborn offers greater plotting options and styling, which can all improve the visuaization and understanding of the data. Typical uses of the seaborn package are used on the tips dataset in the notebook 

## References
[1]. https://seaborn.pydata.org/ - Introduction to the seaborn package
[2]. 







