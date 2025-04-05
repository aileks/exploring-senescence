# Senescence Significance Testing

## Overview
This repository contains code and data for analyzing cellular senescence through statistical significance testing. The project focuses on exploring the (GenAge human dataset)[https://genomics.senescence.info/download.html], which catalogs genes associated with human aging and longevity.

## Repository Structure
- **Presentation.Rmd**: R Markdown presentation file containing the analysis and visualizations
- **data/**: Directory containing the dataset
  - **genage_human.csv**: Database of genes potentially associated with human aging and longevity

## Data Description
The GenAge dataset contains information about genes linked to cellular senescence and aging processes, including:
- Gene identifiers
- Gene symbols and names
- Reasons for inclusion in the database
- References to biological databases (Entrez, UniProt)

## Features
- Statistical analysis of gene associations with aging
- Visualization of gene categories and inclusion reasons
- Exploration of cellular senescence mechanisms
- Significance testing framework for aging-related hypotheses

## Requirements
- R (version 4.0+)
- Required R packages:
  - ggplot2
  - dplyr
  - plotly
  - reshape2
  - knitr
  - broom
  - corrplot

## Usage
1. Clone this repository
2. Open the `Presentation.Rmd` file in RStudio
3. Install any missing R packages
4. Knit the R Markdown file to generate the presentation

## Presentation Details
The presentation covers:
- Introduction to cellular senescence
- Overview of the GenAge dataset
- Principles of statistical hypothesis testing
- Visualization of gene categories and their relationships (TODO)
- Analysis of various aging-related pathways (TODO)
