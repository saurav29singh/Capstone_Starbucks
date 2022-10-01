# Starbucks Capstone Project

## Table of Contents

- [Objective](#Objective)
- [Scope](#Scope)
- [Problem Statement](#Statement)
- [Project Components](#components)
- [Dependencies](#Dependencies)
- [File Structure](#FileStructure)
- [Acknowledgement](#Acknowledgement)


***

## Objective<a name="Objective"></a>

The goal of the project is to analyze historical data about Starbucks' app usage in order to develop an algorithm
that finds the most suiting offer type for each customer.


### Problem Statement<a name="Statement"></a>
Starbucks wants to find a way **to give to each customer the right in-app special offer**. There are 3 different kind of offers: *Buy One Get One* (BOGO), classic *Discount* or *Informational* (no real offer, it provides informations)
on a product.

Our goal is to analyze historical data about app usage and offers / orders made by the customer to develop an algorithm that associates each customer to the right offer type. We will develop 3 different models, one
for each type of offer: each model will evaluate the customer's propension towards that kind of offer returning a score. Given the 3 propensity scores, we will build an algorithm to make the final decision for each customer.


## Scope<a id='Scope'></a>

We have divided the process into 3 phases, 
- **Data preparation:** first look at the data, then join all the datasets to recreate the customer's journey
- **Feature Engineering:** enrichment of the dataset, creating new features from available data
- **Modeling:** choosing the best one in terms of performance


## Project Components<a id='components'></a>

<ol>
    <li> Importing Libraries and Reading Dataset </li>
    <li> Data Wrangling </li>
    <li> Exploratory Data Analysis </li>
        <ol>
            <li> Univariate Analysis </li>
                <ol>
                    <li> Distplot </li>
                    <li> Bar Plot</li>
                </ol>
            <li> Bivariate/Multivariate Analysis </li>
                <ol>
                    <li> Count Plot </li>
                    <li> Box Plot</li>
                    <li> Correlation</li>
                </ol>
         </ol>
     <li> Explanatory Data Analysis </li>
     <li> Model Building </li>
     <li> Hyperparameter Tuning </li>
     <li> Conclusion </li>
</ol>




## Dependencies<a name="Dependencies"></a>

This project uses **Python 3.6** and the following necessary libraries:
* pandas
* matplotlib
* seaborn
* numpy
* progressbar2
* scikit-plot
* sklearn


## File Structure<a name="FileStructure"></a>
```
    - \data
        - portfolio.json        #containing offer ids and meta data about each offer (duration, type, etc.)
        - profile.json          #demographic data for each customer
        - transcript.json       #records for transactions, offers received, offers viewed, and offers completed
    - clean.csv                 #File created during processing and analysis
    - combined.csv              #File created during processing and analysis
    - final.csv                 #File created during processingand analysis
    - README.md
    - Starbucks_Capstone_notebook.html  #html version of notebook
    - Starbucks_Capstone_notebook.ipynb #notebook file used for this project.
```




## Acknowledgements<a name="Acknowledgement"></a>
Thanks to [Udacity](https://www.udacity.com/) Data Scientist Nanodegree program.
