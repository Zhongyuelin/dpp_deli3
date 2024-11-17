# Deliverable03-Data-Merging

# International Mathematical Olympiad (IMO) Data Analysis: Data Merging

This repository contains the merged data for the International Mathematical Olympiad (IMO) Data Analysis project, building upon the cleaned data from Deliverable02-Cleaning-and-formatting.

## Project Overview

This project focuses on merging multiple IMO datasets to create a comprehensive dataset for analysis. We combine country results, individual performance data, and competition timeline information to create a unified dataset that enables deeper analysis of IMO trends and patterns.

## Data Files

The merged data is located in the `MergedData` folder within this repository. It consists of:

1. `comprehensive_imo_data.csv`: A comprehensive dataset combining country results, individual results, and timeline information.

## Data Merging Process

The data merging process is documented in detail in the `IMO_Data_Merging_Process.Rmd` R Markdown document. This process includes:

1. Loading cleaned datasets from previous deliverable
2. Preparing individual datasets for merging
   - Summarizing country performance metrics
   - Aggregating individual performance statistics
   - Processing timeline information
3. Merging datasets using common keys (year, country)
4. Adding derived metrics (host country status)
5. Saving the comprehensive dataset

## Repository Structure

* `MergedData/`: Contains the merged dataset
* `IMO_Data_Merging_Process.Rmd`: R Markdown document detailing the merging process
* `index.html`: Rendered HTML report of the merging process

## How to Use

1. Clone this repository to your local machine
2. Open and run the `IMO_Data_Merging_Process.Rmd` file to see the detailed merging process
3. The merged data file in the `MergedData/` folder is ready for analysis

## Code Visualization

The data merging code can be viewed here: [IMO Data Merging Analysis](https://zhongyuelin.github.io/dpp_deli3/)

## Dependencies

* R (version 4.0.0 or higher)
* tidyverse
* curl

## Original Data Source

The original data was obtained from the TidyTuesday project, week 39 dataset of 2024. It comes from the International Mathematical Olympiad official records, scraped from https://www.imo-official.org/.

## Data Range

The dataset covers IMO events from 1959 to 2024.

## Merged Dataset Contents

The comprehensive dataset includes:

1. Team Performance Metrics:
   - Team total scores
   - Medal counts
   - Team size information

2. Individual Performance Statistics:
   - Average individual scores
   - Top rankings
   - Number of contestants

3. Competition Context:
   - Host country and city information
   - Total participating countries
   - Total contestant numbers

## Next Steps

This merged dataset enables various analyses, including:

* Analyzing relationships between team and individual performance
* Studying host country performance advantages
* Investigating participation trends over time
* Examining the correlation between team size and performance
* Analyzing geographical patterns in IMO success

## Contact

For any questions or feedback regarding this data merging process, please open an issue in this repository.
