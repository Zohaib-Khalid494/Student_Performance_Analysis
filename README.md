# Student Performance Analysis

## Student Information
Name: Zohaib Khalid 
Roll Number: SP24-BAI-049

## Project Description

<<<<<<< HEAD
This project performs advanced student performance analysis.
=======
This project performs advanced student performance analysis and provide thoughtful insights.
>>>>>>> branch01

## Project Structure

- assignemnt_03.ipynb: Main notebook with the full workflow (loading, cleaning, analysis, and plots).
- StudentsPerformance.csv: Original dataset.
- messy_students.csv: Synthetic messy dataset with missing values, duplicates, and outliers.
- cleaned_students.csv: Cleaned dataset after imputation, outlier filtering, and deduplication.
- best_visualization.png: Exported multi-plot figure from the notebook.

## Tools Used

- Python 3.8+
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Git & GitHub
- Jupyter Notebook

## Quick Start

1. Create and activate a virtual environment (optional but recommended).
2. Install dependencies:

   pip install pandas numpy matplotlib seaborn

3. Open and run the notebook:

   assignemnt_03.ipynb

## Workflow Summary

1. Load the raw dataset and inspect summary statistics.
2. Create a messy version of the data with:
   - Missing values in math scores
   - Duplicated rows
   - An extreme outlier
3. Detect data issues via info(), missing counts, duplicate counts, and IQR outlier checks.
4. Clean the data by imputing missing values, removing outliers, and dropping duplicates.
5. Analyze performance by demographic categories and visualize correlations and distributions.
6. Export a combined visualization to best_visualization.png.

## Outputs

- cleaned_students.csv: cleaned dataset ready for analysis.
- best_visualization.png: summary visualization produced by the notebook.

## Notes

- The messy dataset is generated for learning purposes; it is not the original dataset.
- The notebook uses the mean to impute missing math scores and IQR to filter outliers.