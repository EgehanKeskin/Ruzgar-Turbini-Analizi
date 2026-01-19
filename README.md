# Wind Turbine Power Curve Analysis (Numerical Methods)

This repository contains a comprehensive MATLAB project focused on analyzing wind turbine performance data using numerical analysis techniques. 

## Project Overview
The goal of this project is to process raw wind sensor data, remove measurement errors, and create a reliable mathematical model for the power curve.

## Key Features & Methodology
* **Data Cleaning:** Identification and removal of gross errors, specifically focusing on non-physical zero or negative power values.
* **Missing Data Recovery:** Utilizing **Cubic Spline Interpolation** to fill gaps in the dataset and ensure signal continuity.
* **Signal Smoothing:** Application of a **Running Mean Filter** to eliminate random Gaussian noise and stabilize the output.
* **Mathematical Modeling:** Development of a 3rd-degree **Polynomial Regression** model to define the relationship between wind speed and power generation.

## File Descriptions
* `Ruzgar_Turbini_Analiz_Projesi.mlx`: The main MATLAB Live Script containing all processing steps and visualizations.
* `T1.csv`: The raw dataset used for the analysis.
* `Ruzgar_Turbini_Analiz_Projesi.pdf`: Detailed project report explaining the findings.

## Technologies Used
* **Language:** MATLAB
* **Concepts:** Numerical Analysis, Signal Processing, Data Science
