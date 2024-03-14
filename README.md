# Respiratory Disease DataFrame Visualization

This repository contains Python code for visualizing data related to respiratory diseases using DataFrame operations and data visualization techniques. The main steps include:

## Data Loading and Preprocessing:
- Importing the respiratory disease dataset.
- Exploring the dataset and handling missing values.
- Normalizing the data and applying dimensionality reduction techniques for visualization.

## DataFrame Visualization:
- Creating separate tables for different genders.
- Visualizing the distribution of diagnoses across genders using bar and pie charts.
- Visualizing the distribution of diagnoses for men and women in a stacked bar chart.
- Calculating the total number of patients with each type of disease and their percentage in the total number of patients.
- Visualizing the number and percentage of diagnoses using bar and pie charts.

## Dimensionality Reduction Techniques:
- Applying Principal Component Analysis (PCA) to create new DataFrames containing principal components.
- Applying t-distributed Stochastic Neighbor Embedding (t-SNE) to create new DataFrames containing t-SNE features.
- Tuning parameters for better visualization of DataFrame using t-SNE.

## Repository Structure
- **README.md**: This file containing information about the project, dataset, methods, and results.
- **data**: Directory containing the dataset (Dataset.xlsx).
- **visualization.ipynb**: Jupyter notebook containing the Python code for data preprocessing, visualization, and dimensionality reduction.

## Instructions for Running the Code
1. Ensure you have Python installed on your system along with the necessary libraries specified in the notebook.
2. Download the dataset (Dataset.xlsx) and place it in the `data` directory.
3. Open and run the `visualization.ipynb` notebook using Jupyter or any compatible environment.
4. Follow the instructions and execute the code cells sequentially to perform data preprocessing, visualization, and dimensionality reduction.

## Results Summary
- By completing this work, the following goals were achieved:
    - The project enhances understanding of respiratory diseases by visualizing the distribution of diagnoses across genders and the entire dataset.
    - Data preprocessing techniques such as handling missing values and normalization prepare the data for analysis, enabling deeper insights into disease patterns.
    - The application of dimensionality reduction techniques like PCA and t-SNE aids in visualizing high-dimensional data, making it easier to interpret and identify underlying patterns.
    - The project explores parameter tuning for t-SNE to achieve better visualization results, improving the clarity and interpretability of the visualizations.
- The skills utilized in this project, including data preprocessing, visualization, and dimensionality reduction, are valuable for data analysis and interpretation in various domains, particularly in healthcare and medical research.
