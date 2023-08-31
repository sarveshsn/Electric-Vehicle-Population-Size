# Electric-Vehicle-Population-Size

![Electric-vehicles-trends-in-India](https://github.com/sarveshsn/Electric-Vehicle-Population-Size/assets/93898181/344fc2ca-d56f-450b-9c22-885a679855c1)


## Overview

This repository contains the code and analysis on Electric Vehicle Population by Sarvesh Naik , completed on December 22, 2022. The project focuses on analyzing the historical data of Electric Vehicle (EV) population size by county in the state of Washington, USA, from January 2018 to November 2022.

## Analysis

### Part 1: Data Analysis

In this section, the provided R code is used to perform an exploratory analysis of the dataset. Key steps include loading and reading the dataset, cleaning and transforming the data, and generating visualizations using the `ggplot2` package.

- Data loading and cleaning are done to handle missing values and convert date formats.
- The dataset is visualized to show the total number of registered electric vehicles in different counties over time.
- Visual comparisons are made between the start and end of the dataset period to highlight changes in EV populations.
- Further visualizations focus on specific counties to showcase the growth of EV populations over time.

### Part 2: R Package - Patchwork

This section introduces the `patchwork` R package, which facilitates the composition of multiple plots into a single visualization. The package is used to create density plots for Plug-In Hybrid Electric Vehicles (PHEVs) and Battery Electric Vehicles (BEVs) populations in different counties. The resulting plots demonstrate the population density changes over the years.

### Part 3: Regression

In this section, linear regression models are fitted to the data to explore the relationship between the total number of EVs and the populations of BEVs and PHEVs. The code demonstrates how to fit the models, summarize the results, and visualize the observed vs. predicted values.

## Usage

To reproduce the analysis or modify the code, follow these steps:

1. Clone this repository to your local machine.
2. Install the required R packages using the following command:

```
install.packages(c("ggplot2", "dplyr", "lubridate", "hrbrthemes", "viridis", "patchwork", "data.table"))

```

3. Download the csv file from this repository and save the file in the folder as the .rmd file.
4. Open the R script `Electric Vehicles.rmd` in an R-compatible environment (e.g., RStudio).
5. Execute the code step by step or in its entirety to see the results and visualizations.

## Author

- **Sarvesh Sairam Naik** 



