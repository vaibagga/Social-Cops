# Improving Healthcare in Maharashtra

Solution to improve healthcare in Maharashtra (part of Social Cops challenge)
This repository contains solution for the problem "Improving Healthcare in Maharashtra"

# Data Sources

All datasets used are open source:
1. https://www.kaggle.com/c/predict-impact-of-air-quality-on-death-rates/data: Dataset containing mortality rate and pollution levels in various regions of England.
2. https://data.gov.in/node/1148961/download: Dataset containing pollution levels in Maharashtra in the year 2015.

# Code

analysis.ipynb: Interactive Python Notebook. Contains analysis of distribution of data and correlation among variables. Also contains graphs (histograms, scatter plots, etc.) for visualisation of data.

regression.ipynb: Interactive Python Notebook. Using Linear Regression to predict mortality rate based on pollution levels on England dataset.

# Language(s)

Python 3.6.x

# Libraries

1. Pandas
2. Numpy
3. Scipy
4. Matplotlib
5. Seaborn
6. OS

# Summary

Maharashtra consists of industrial cities like Nagpur, Mumbai which leads to higher pollution. This pollution poses a high risk to life. Mumbai is among the four most polluted cities in the World (https://timesofindia.indiatimes.com/city/mumbai/mumbai-4th-most-polluted-megacity-in-world-9-in-10-people-breathe-bad-air/articleshow/63993044.cms), and the condition is continuously deteriorating. (https://timesofindia.indiatimes.com/city/mumbai/air-quality-dips-in-mumbai-bkc-is-worst/articleshow/66324429.cms) <br>
In this project, we aim to find relation between health and various pollution level indicators. We compare the pollution levels of Maharashtra to that of other regions and find the regions of Maharashtra which are prone to health hazards due to pollution, so that measures may be taken to improve the condition of pollution. <br>
We use Linear Regression to predict mortality rate on a given day using pollution level indicators, and test the Linear Regression model. <br>
To conclude, we suggest gathering dataset to analyse the dependence of health on high level of pollution in case of severely high pollution.
