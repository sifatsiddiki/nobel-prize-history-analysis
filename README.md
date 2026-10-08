# nobel-prize-history-analysis
A data science project evaluating historical Nobel Prize datasets to uncover demographic shifts, national distribution trends, and gender representation patterns using Python.

Historical Analysis of Nobel Prize Laureates


Project Overview

This repository contains a data science project dedicated to exploring the historical patterns of Nobel Prize winners since its inception. The primary goal is to examine demographic shifts, identify trends in specific research fields, and analyze the distribution of prizes across different nations and genders over the past century.
The analysis is executed using Python within a Jupyter Notebook environment, shifting raw historical figures into structural charts to understand the evolution of global scientific and cultural achievements.

Directory Structure

The repository consists of the following primary components:
• notebook.ipynb contains the complete analytical workflow, including data preprocessing, group-by aggregations, time-series transformations, and statistical charting.
• Nobel_Prize.png is an exported visualization demonstrating a core trend identified during the exploratory data analysis phase.
• workspace/data/nobel.csv serves as the primary dataset containing historical columns such as prize categories, laureate names, birth dates, genders, and institutional affiliations.

Technical Implementation

The data pipeline relies on standard open-source Python libraries:
• Pandas for structural data manipulation, datetime parsing, and multi-index grouping operations.
• NumPy for array-based logical filtering and handling missing metadata.
• Matplotlib and Seaborn for plotting distributions, historical trends, and gender proportion changes over decade-long intervals.

Key Operational Insights

The notebook investigates several distinct dimensions of the historical data:
• National Distributions: Identification of which countries have historically dominated specific categories and how these geographical centers of research have shifted over time.
• Demographic Evolution: Evaluation of the average age of laureates at the time of receiving the award across different fields such as Physics, Medicine, and Literature.
• Gender Disparity Tracking: Measurement of the proportion of female winners across different eras to isolate historical patterns and progress in academic representation.

Execution Instructions

To replicate the dataset analysis locally:
1. Clone the repository to your local system using a Git terminal interface.
2. Verify that Python 3 is installed alongside pandas, matplotlib, and seaborn packages.
3. Ensure the nobel.csv file remains inside the designated data directory path to prevent file ingestion errors.
4. Open the Jupyter Notebook and execute the cells in sequential order to re-generate the dataframes and visual trend graphs.
