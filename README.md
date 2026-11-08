# Applied Statistics Iris Project

## Purpose

This repository contains my work for the Applied Statistics assignment, using statistical analysis on the Iris Datset. It includes Jupyter Notebook exercises exploring statistical concepts and analysing datasets using Python.

The work includes data manipulation, statistical calculations and visualisations using libraries such as NumPy, Pandas, Matplotlib, SciPy and Scikit-learn.

## Repository Layout

applied_statistics/

│

├── problems.ipynb

├── requirements.txt

├── README.md

├── AGENTS.md

├── .gitignore

│

└── Histograms/

    ├── Petal Length Normal Distribution.png
    
    └── Petal Length Distributions by Species.png

## Repository Contents

problems.ipynb – Main Jupyter Notebook containing the assignment work.

requirements.txt - Python packages required to run the notebook.

README.md - Explains the repository and how to run it.

AGENTS.md - Instructions and guidelines for working in the repository.

.gitignore - Specifies files and folders Git should ignore.

Histograms - Stores the generated histogram images.

## Getting Started

1. Clone the repository

Open a terminal and run:

git clone https:// https://github.com/philipcullen93/applied_statistics.git

Navigate into the repository

cd applied_statistics

2. Install Dependencies

Install the required Python packages:

pip install -r requirements.txt

3. Run the notebook

Launch Jupyter Notebook

Open problems.ipynb and run the cells to view and execute the assignment.

## Problem 1: Analysis of Iris Petal Length

### Overview

Problem 1 investigates the distribution of petal length in the Iris dataset using Python. The analysis applies descriptive statistics and data visualisation to examine petal length across the complete dataset and within each individual species.

The Iris dataset contains 150 flower observations belonging to three species: Setosa, Versicolor, and Virginica. The analysis focuses on petal length and uses histograms, normal distribution curves, the mean, and standard deviation to investigate the data.

### Part 1: Histogram of Petal Length

A histogram is created to examine the distribution of petal length across all 150 observations.

The histogram provides an overview of the frequency of different petal lengths and helps identify patterns within the dataset.

### Part 2: Normal Distribution of Petal Length

The mean and standard deviation of petal length are calculated for the complete dataset.

These values are used to generate a normal distribution curve, which is plotted alongside the histogram.

The visualisation allows the observed distribution to be compared with a theoretical normal distribution to assess whether normality provides a reasonable approximation of the data.

### Part 3: Petal Length Distributions by Species

The dataset is separated into its three species: Setosa, Versicolor, and Virginica.

A separate histogram is created for each species, with a corresponding normal distribution curve.

This allows the distributions to be examined individually and highlights differences in petal length between the species.

### Part 4: Mean and Standard Deviation

The mean and standard deviation of petal length are calculated for the complete dataset and for each individual species.

The results are presented in a table, rounded to two decimal places.

The mean provides a measure of average petal length, while the standard deviation indicates the variation in measurements around the mean.

These statistics allow the central values and spread of petal lengths to be compared between the three species.

### Part 5: Observations and Discussion

The distributions are compared using the histograms and descriptive statistics calculated in the previous sections.

The discussion examines differences in average petal length, variation between observations, and the overall shape of each species' distribution.

It also considers whether a normal distribution appears to be a reasonable model for the complete dataset and for each individual species.

The analysis highlights how combining different species affects the overall distribution and why examining the species separately provides a clearer understanding of petal length.

### Outputs

The analysis produces the following outputs:

A histogram showing the distribution of petal length across the complete dataset.

A histogram with an overlaid normal distribution curve for the complete dataset.

Histograms and normal distribution curves for each of the three Iris species.

A table reporting the mean and standard deviation of petal length for the complete dataset and each species.

A discussion comparing the distributions and evaluating the suitability of a normal distribution.

The generated histogram images can be viewed by running the notebook but are also saved in the Histograms directory.
