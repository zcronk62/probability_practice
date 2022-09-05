# Detecting Product Defects with Probability

## Introduction

The purpose of this project is to use Poisson distribution features to detect and predict defects for a given product. The project preamble states that the rate parameter of the Poisson is 7 defects per day.

This project seeks to investigate attributes of the Poisson distribution with the previously stated rate parameter. The analysis will be conducted using Jupyter Notebook.

## Description

This project uses Python 3 to calculate some probability statisitcs assuming a Poisson distribution describing the number the of defective products on a per-day basis. In this analysis, I create a simulated experimental Poisson distribution using a rate parameter of 7 defects produced per day. I then calculate probabilities related to observing more or less than some given number of defects.

Also, I compare the simulated experimental distribution to what one would expect if the number of defects observed per day was constant 7. 

Finally, I extend my analysis to determining the number of defects in a day that would put that day in the 90th percentile. I then calculate the propotion of the year in which we observe more defects than the 90th percentile.