# Empirical Analysis of a Surrogate Methodology for Sampling Bayesian Posteriors.

* **Author**: Jay Kanda
* **Date**: 27/08/25

## Description
This repository contains all of the code for my MSc thesis. The primary goal of my research is to evaluate the practical performance of a novel surrogate posterior methodology for generating samples from a Bayesian posterior distribution.

## File Descriptions

* `Thesis_code.Rmd`: The R Markdown source code containing all simulations for the thesis.
* `README.md`: This file.

## Data
The data for this research is simulated using the `generate_data` function within the `Thesis_code.Rmd` file.

## Running the code
To reproduce this analysis on your own machine, you will need R and RStudio. Follow these steps:
1) Clone or download this repository.
2) Open the project in RStudio.
3) Install the required packages by running the following command in the R console:
   ```r
   install.packages(c("dplyr", "ggplot2", "coda", "rmarkdown", "readr"))
   ```
4) Open the Rmd file `Thesis_code.Rmd`
