# IMDb Movies Analysis

This repository contains a data analysis project on the top 1000 movies rated by IMDb. The project involves data exploration, cleaning, analysis, and visualization to uncover insights about the movies and their ratings.

## Repository Structure

- `data/`: Contains raw and processed data.
  - `raw/`: Raw data files.
    - `movies.csv`: Original dataset of 1000 movies.
  - `processed/`: Processed data files.
    - `cleaneddata.csv`: Cleaned dataset after preprocessing.
- `notebooks/`: Jupyter notebooks for different stages of the analysis.
  - `01_data_exploration.ipynb`: Initial data exploration and summary statistics.
  - `02_data_cleaning.ipynb`: Data cleaning and preprocessing steps.
  - `03_data_analysis.ipynb`: In-depth data analysis and insights.
  - `04_visualizations.ipynb`: Data visualization and graphical representation of findings.
- `src/`: Source code for data processing and visualization.
  - `data_processing.py`: Script for data cleaning and preprocessing.
  - `data_visualization.py`: Script for generating visualizations.
  - `analysis_utils.py`: Utility functions for data analysis.
- `.gitignore`: Specifies files and directories to ignore in the repository.
- `README.md`: Project overview and instructions.

## Project Overview

### Data Exploration

The initial exploration involves loading the dataset and understanding its structure and content. This includes:

- Reading the dataset using Pandas.
- Displaying the first few rows of the dataset.
- Generating summary statistics for numerical columns.
- Checking for null values and data types.

### Data Cleaning

Data cleaning is a crucial step to ensure the dataset is ready for analysis. This includes:

- Filling null values.
- Selecting relevant columns.
- Saving the cleaned data to a new CSV file.

### Data Analysis

The analysis involves examining various aspects of the dataset to uncover insights. This includes:

- Identifying and handling outliers.
- Analyzing the distribution of movie ratings.
- Examining the relationship between movie genres and ratings.
- Analyzing the distribution of gross earnings.

### Data Visualization

Visualizations are created to represent the findings graphically. This includes:

- Histograms for univariate analysis.
- Pie charts for genre distribution.
- Box plots for rating distribution by genre.
- Bar plots for average gross revenue by genre.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
