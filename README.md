
# CSV Data Cleaning and Preprocessing

A Python script for cleaning, transforming and preprocessing CSV datasets using Pandas, NumPy and Scikit-learn.

## Features

- Removes duplicate records
- Identifies numerical and categorical columns
- Handles missing numerical values using mean imputation
- Handles missing categorical values using mode imputation
- Performs feature engineering using squared and logarithmic transformations
- Converts categorical variables using one-hot encoding
- Normalises numerical features using MinMaxScaler
- Generates cleaned CSV output
- Produces a data-cleaning report
- Generates distribution plots using Seaborn and Matplotlib

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/csv-data-cleaning-and-preprocessing.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Run the script:

```bash
python data_preprocessing.py
```

Enter the path to your CSV dataset when prompted.

## Generated Files

The script automatically generates:

- `cleaned_data.csv` – cleaned and transformed dataset.
- `report.txt` – summary of the original and final dataset dimensions and column types.
- Distribution PNG files – visualisations of the first three numerical columns.

## Purpose

This project demonstrates practical data preprocessing techniques commonly used in data analysis and machine learning workflows.
