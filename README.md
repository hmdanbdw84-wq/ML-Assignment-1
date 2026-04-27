Name : Abdulrahman Ismail Hamdan
ID : 1320221891

This project applies comprehensive data preprocessing and exploratory data analysis (EDA) to the House Prices: Advanced Regression Techniques dataset from Kaggle. The goal is to prepare a clean, engineered dataset ready for machine learning modeling.

Key Features

Data Cleaning: Handled missing values by identifying features where "NaN" represents a specific category  and treated them accordingly.


Outlier Management: Identified and removed significant outliers in ground living area to improve model training.


Target Transformation: Applied logarithmic transformation (np.log1p) to the SalePrice to normalize its distribution.

Feature Engineering: Created a new TotalSF feature and implemented Label/One-Hot encoding for categorical variables.Memory Optimization: Demonstrated efficient data loading by optimizing column data types.

Project Structure

data/: Contains train.csv and test.csv.


Assignment_1_ML.ipynb: The main Jupyter notebook containing all code, visualizations, and logic.


requirements.txt: List of necessary dependencies (pandas, numpy, seaborn, plotly, etc.).

How to Run
Clone this repository.

Ensure you have the datasets in the data/ folder.

Install dependencies: pip install -r requirements.txt.

Run the Jupyter notebook from start to finish.

Instructor: Ibrahim O. Kaware 
Course: Machine Learning - Assignment 1
By : Abdulrahaman Ismail Hamdan
ID : 1320221891
