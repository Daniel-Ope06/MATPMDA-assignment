# The Commute Chronicles

***An Analysis of Travel Efficiency, Weather Impacts, and Crowding***

This project applies statistical methods to a dataset of my bus trips. The goal was to quantify the factors affecting my journey.

## Statistical Methods Applied

- **Paired t-test:** Comparing trips to campus versus trips back home.

- **Linear Regression:** Predicting arrival time based on departure time.

- **Fisher's Exact Test:** Analyzing the dependency between rain and bus overcrowding.

- **Pearson's Chi-Square:** Testing for daily crowding patterns (The "Thursday Rush").

- **Bayesian Inference:** Quantifying the risk multiplier of rain on the probability of bus overcrowding.

## Repository Structure

- `The_Commute_Chronicles.pdf`: The final compiled report.

- `The_Commute_Chronicles.Rmd`: The R Markdown source code.

- `bus_data.txt`: The dataset (Comma-Separated Values).

- `bus_data_origin.jpg`: Image of how the data was collected.

## Requirements to Reproduce

To knit the `.Rmd` file locally, ensure you have the following installed:

- R & RStudio
- LaTeX Distribution
- Fonts: *Lato* and *Source Code Pro*

If these fonts are missing, comment out the `\usepackage` lines in the YAML header.

---

**Context:** Developed for the *Mathematical and Statistical Foundations* module at *University of Stirling*.
