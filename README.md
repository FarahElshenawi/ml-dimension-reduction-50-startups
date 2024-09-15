# ml-dimension-reduction-50-startups
Dimensionality reduction on 50 Startups dataset using statsmodels

## Overview

This project applies dimensionality reduction techniques to the **50 Startups** dataset. The dataset includes information about startup companies such as R&D spend, administration costs, marketing spend, state, and profit. The goal is to analyze the impact of these features on profitability using statistical methods.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis](#analysis)

## Introduction

This project demonstrates the use of dimensionality reduction techniques and statistical analysis to understand and predict startup profitability. We use the `statsmodels` library for advanced statistical modeling.

## Dataset

The dataset `50_StartUp.xlsx` includes the following columns:

- **R&D Spend**: Amount spent on research and development.
- **Administration**: Amount spent on administration.
- **Marketing Spend**: Amount spent on marketing.
- **State**: The state in which the startup is located (New York, California, Florida).
- **Profit**: Profit earned by the startup.

### Example Data

| R&D Spend  | Administration | Marketing Spend | State      | Profit   |
|------------|----------------|-----------------|------------|----------|
| 165349.20   | 136897.80      | 471784.10       | New York   | 192261.83 |
| 162597.70   | 151377.59      | 443898.53       | California | 191792.06 |
| ...        | ...            | ...             | ...        | ...      |

## Installation

To run this project, you need to install the following Python packages. Use `pip` to install them:

```bash
pip install numpy pandas seaborn matplotlib scikit-learn statsmodels openpyxl
```
## Usage

### Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/ml-dimension-reduction-50-startups.git
```
### Navigate to the Project Directory

Change into the project directory:

```bash
cd ml-dimension-reduction-50-startups
```
### Run the Jupyter Notebook

Launch Jupyter Notebook and open the notebook:

```bash
jupyter notebook notebooks/ml_project_notebook.ipynb
```
### Execute the Python Script

Alternatively, you can run the Python script directly:

```bash
python scripts/main.py
```
## Analysis

The analysis process includes the following steps:

1. **Data Preprocessing**
   - Load and inspect the dataset.
   - Encode categorical variables and prepare the data for modeling.

2. **Model Building**
   - Train a linear regression model.
   - Perform statistical analysis using statsmodels.

3. **Dimensionality Reduction**
   - Apply Backward elimination technique to reduce dimensionality and enhance model performance.

4. **Evaluation**
   - Measure model performance using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

