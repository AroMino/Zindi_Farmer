# Zindi - DigiCow Farmer Training Adoption Challenge

This repository contains data, notebooks, and reports for the **DigiCow Farmer Training Adoption Challenge** hosted on Zindi.

## Objective
The goal of this project is to build a predictive model to determine whether a farmer will adopt training recommendations within a given timeframe (7 days, 90 days, or 120 days) following their first training session.

## Repository Structure

### Data Files
- **Train.csv**: The main training dataset containing farmer information, training sessions, and target adoption metrics.
- **Test.csv**: The test dataset on which predictions are made.
- **Prior.csv**: Supplementary prior dataset for further historical context.
- **SampleSubmission.csv**: A sample submission file showing the expected output format.
- **dataset_data_dictionary.csv**: Explains the features available in the datasets.

*Note: The raw challenge data zip archive (`digicow-farmer-training-adoption-challenge...zip`) and its manifest file are also present.*

### Notebooks
- **StarterNotebook.ipynb**: Provides an initial baseline modeling and setup script.
- **exploration.ipynb**: In-depth exploratory data analysis (EDA), data cleaning, feature engineering, and advanced model training.

### Reports
- **Report.tex**: The LaTeX source file for the final project report.
- **Zindi_Farmer_Report.pdf**: The compiled PDF version of the final project report detailing the methodology, algorithms used, and results.
- **figures/**: Directory containing visualizations and plots generated during EDA and used in the report.

## Data Dictionary Overview
Key features in the dataset include:
- `ID`: unique identifier for each farmer entry
- `gender`, `age`: Demographic details
- `registration`, `belong_to_cooperative`: Farmer background
- `county`, `subcounty`, `ward`: Geographic location
- `trainer`, `topics`: Information regarding the training delivered
- `first_training_date`: Date of the first training session

**Target Variables:**
- `adopted_within_07_days`
- `adopted_within_90_days`
- `adopted_within_120_days`

## Getting Started
To reproduce the work:
1. Ensure you have Jupyter Notebook or JupyterLab installed.
2. Open `exploration.ipynb` for the full analysis pipeline.
3. Check `StarterNotebook.ipynb` for a quick overview of the baseline model.
