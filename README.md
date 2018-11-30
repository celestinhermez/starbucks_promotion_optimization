# Starbucks Promotion Optimization
An exercise based on simulated data from Starbucks to analyze results of an 
experiment and optimize a promotional strategy based on them. 
The main metrics of interest are the incremental response rate (how many more customers
purchased the product with the promotion, as compared to if they didn't receive the
promotion) and the net incremental revenue (how much is made or lost by sending out
the promotion). Mathematical details about these metrics are provided in the notebooks.
The goal of this repository is to display how to analyze an experiment, 
and how to leverage the results to optimize a promotional strategy 
which can yield positive results for the company.

Udacity provided a script assess the promotional strategy devised.

## Installation

The necessary libraries to run this project, along with Python 3.6:
* numpy
* pandas
* statsmodels
* sklearn
* scipy
* matplotlib
* itertools

## Structure

This repository contains the following files:
* **Starbucks.ipynb**: a Jupyter notebook which contains the repoducible analysis on the
Starbucks dataset
* **Starbucks.html**: an HTML version of the Jupyter notebook
* **train.csv**: the training data provided by Starbucks
* **Test.csv**: the test data provided by Starbucks that Udacity uses in their scoring
script
* **test_results.py**: a scoring script provided by Udacity to determine the IRR and
NIR of the promotional strategy on the test dataset

## Usage & Results

In order to replicate this analysis, clone this repository and run the Jupyter notebook,
or simply download the HTML version of the notebook.

The main takeaways:
* using several statistical tests we determined the promotion had a positive impact on 
both metrics of interest
* using a decision tree classifier (build with scikit-learn), we devised a promotional
strategy which outperformed Udacity's benchmark both in terms of IRR and NIR

## License
