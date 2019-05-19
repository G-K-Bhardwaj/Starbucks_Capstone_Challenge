# Data Scientist Nanodegree
# Recommendation Engine
## Project: Starbucks Capstone Challenge

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

This project requires **Python 3**, **Jupyter Notebook** and the following Python libraries installed:

- [Pandas](https://pandas.pydata.org/)
- [NumPy](http://www.numpy.org/)
- [matplotlib](http://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/installing.html)
- [progressbar](https://pypi.org/project/progressbar2/)


## Project Motivation<a name="motivation"></a>

In this project we will explore the data provided by Starbucks. This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app.

Based on the data provided we will make recommendations. Making recommendations we will be performed in two parts:

1. Recommending “Top n popular offers” to the new customers or the customer for whom we can not make recommendations on user-user similarity basis.
2. Recommending based “User-User Similarity” to the customers for whom we can find similar customers.

Note: Our recommendation should exclude the offers that customer has already completed or ignored (“offer received by the customer”, “automatically completed the offer” but “never viewed that offer”).

## File Descriptions <a name="files"></a>

There are 4 files available here to showcase work related to the above questions. 
1. "Starbucks_Capstone_notebook.ipynb": This files contains the steps followed and code pursued. Markdown cells were used to assist in walking through the thought process for individual steps.
2. portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.) 
3. profile.json - demographic data for each customer 
4. transcript.json - records for transactions, offers received, offers viewed, and offers completed. 
5. Starbucks_Capstone_Challenge.html: This file is just on export of notebook "Starbucks_Capstone_notebook.ipynb". 

Data files portfolio.json, profile.json, transcript.json are in folder named "data" where the "Starbucks_Capstone_notebook.ipnb" is located.

## Results<a name="results"></a>

Successfully created a recommendations system for Starbucks Challenge. Made target based recommendations and recommendations for all customers.

## Acknowledgements<a name="licensing"></a>

Must give credit to Starbucks and Udacity for the data. 

