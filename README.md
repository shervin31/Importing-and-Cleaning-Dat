# Data Import and Cleaning Project

## Overview

This project involves importing, cleaning, and transforming multiple datasets related to climate awareness, color scales, ad targeting, and storm data. The goal is to prepare these datasets for analysis using best practices for data wrangling and visualization.

## Datasets

1. **NOAA Storm Data**: Storm data cleaned for analysis, specifically focusing on attributes like damage and fatalities.
2. **Climate Awareness & Happening Data**: Merged dataset containing scores on climate awareness and happening for various countries.
3. **ColorBrewer Scales**: Color scales data transformed from a JSON file into a tidy format.
4. **Xandr Ad-Targeting Data**: Cleaned data from the Xandr platform, focused on audience segments.

## Steps Taken

- Merged climate data based on country.
- Tidied ColorBrewer color scales into a format with RGB values.
- Cleaned Xandr ad-targeting data, including handling duplicates and filtering for specific keywords.
- Visualized record counts per data provider in the Xandr dataset.
- Cleaned and prepared NOAA storm data for further analysis.

## Setup

1. Install required R packages: `tidyverse`, `jsonlite`, `stringr`, `ottr`.
2. Clone or download the repository.
3. Run the R scripts to import, clean, and transform the data.

## Output

The project provides clean datasets ready for analysis, including climate scores, ColorBrewer color scales, ad-targeting data from Xandr, and NOAA storm data.
