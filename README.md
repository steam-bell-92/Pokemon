# Pokemon Stats Analysis

## Overview

This project performs an exploratory data analysis of Pokemon stats using Python data science libraries. The notebook and script inspect type distributions, stat relationships, and several Pokemon-specific questions while preserving the original analysis flow.

## Problem Statement

The goal is to understand how Pokemon attributes such as HP, Attack, Defense, Speed, and typing vary across the dataset and to identify notable patterns, extremes, and comparisons.

## Dataset

Source: Kaggle Pokemon with stats dataset.

Dataset file used in this repository: `data/raw/W1_Pokemon.csv`.

## Technologies Used

- Python
- pandas
- matplotlib
- seaborn
- plotly

## Project Structure

- `data/raw/` stores the source dataset.
- `notebooks/` contains the cleaned analysis notebook.
- `src/` contains the Python analysis script.
- `images/` stores project images and exported visual assets.
- `README.md` documents the project.
- `requirements.txt` lists the Python dependencies used by the analysis.

## Workflow

1. Load the Pokemon dataset from a configurable path.
2. Inspect the structure and basic statistics of the data.
3. Clean and transform a small set of fields used in the analysis.
4. Answer several stat-based questions about Pokemon types and generations.
5. Visualize relationships across the core Pokemon attributes.

## Results

The analysis highlights clear differences in Pokemon stats by type, shows how legendary Pokemon cluster differently from non-legendary ones, and surfaces several maxima and distribution patterns across the dataset.

## Future Improvements

- Add reusable helper functions for repeated queries.
- Add automated checks to validate the dataset schema before analysis.
- Expand the notebook with a separate model-building workflow if prediction becomes part of the project scope.
