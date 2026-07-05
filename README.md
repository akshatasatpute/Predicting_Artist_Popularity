# Spotify Artist Popularity Prediction using Multiple Linear Regression

Predicting an artist's popularity using Spotify audio features through **Multiple Linear Regression (MLR)** and statistical analysis.

---

## Project Overview

This project aims to predict an artist's **popularity** using various Spotify audio features. A Multiple Linear Regression model is developed after performing exploratory data analysis, checking model assumptions, handling multicollinearity, and reducing dimensionality.

The project demonstrates a complete statistical modeling workflow, from data preprocessing to model fitting using **Ordinary Least Squares (OLS)**.

---

## Problem Statement

Predict an artist's **popularity** based on the following independent variables:

- Acousticness
- Danceability
- Duration (ms)
- Energy
- Instrumentalness
- Liveness
- Loudness
- Speechiness
- Tempo
- Key
- Valence
- Mode

The objective is to determine how these audio characteristics influence an artist's popularity and identify the most significant predictors.

---

## Dataset

Spotify publishes an annual playlist containing the songs streamed most frequently worldwide. This project analyzes these tracks to understand what characteristics contribute to song popularity.

### Dataset Information

| Attribute | Details |
|-----------|---------|
| Dataset | top2018.csv |
| Source | Kaggle |
| Original Source | Spotify Web API |
| Observations | 27,622 |
| Features | 13 |
| Response Variable | Popularity |
| Independent Variables | 12 Audio Features |

---

## Features Used

- Artist
- Popularity *(Target Variable)*
- Acousticness
- Danceability
- Duration_ms
- Energy
- Instrumentalness
- Liveness
- Loudness
- Speechiness
- Tempo
- Key
- Valence
- Mode

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Scikit-learn

---

## Methodology

The following steps were performed during model development:

- Data Import & Cleaning
- Missing Value Analysis
- Correlation Analysis
- Heatmap Visualization
- Multicollinearity Check (VIF)
- Principal Component Analysis (PCA)
- Multiple Linear Regression (OLS)
- Model Interpretation

---

## Repository Structure

```text
Spotify-Artist-Popularity-Regression/
│
├── data/
│   └── artist.csv
│
├── docs/
│   └── Multiple regression Final Report.docx
|
├── notebooks/
│   └── Predicting Artist popularity using Multiple linear regression LM code.ipynb
├── README.md
├── requirements.txt
```

---

## Statistical Techniques

The project makes use of the following statistical methods:

- Multiple Linear Regression
- Ordinary Least Squares (OLS)
- Correlation Analysis
- Heatmap Visualization
- Variance Inflation Factor (VIF)
- Principal Component Analysis (PCA)

---

## Workflow

```
Import Dataset
        │
        ▼
Data Inspection
        │
        ▼
Missing Value Analysis
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Correlation Analysis
        │
        ▼
Heatmap Visualization
        │
        ▼
Multicollinearity Detection (VIF)
        │
        ▼
Feature Selection
        │
        ▼
Principal Component Analysis (PCA)
        │
        ▼
Multiple Linear Regression (OLS)
        │
        ▼
Model Interpretation
```

---

## Results

The analysis produced the following observations:

- The response variable (**Popularity**) exhibits relatively low correlation with most individual predictor variables.
- Several independent variables are highly correlated with one another, indicating multicollinearity.
- Variables with **VIF greater than 5** were removed to improve model stability.
- **Principal Component Analysis (PCA)** was applied to reduce dimensionality and minimize redundant information.
- The final regression model was fitted using the **Ordinary Least Squares (OLS)** method to estimate the regression coefficients.

---

## Key Learnings

- Importance of checking regression assumptions before model fitting.
- Detecting and handling multicollinearity using VIF.
- Using PCA for dimensionality reduction.
- Building and interpreting Multiple Linear Regression models using OLS.
- Performing exploratory data analysis to understand relationships among variables.

---

## Running the Project

### Clone the repository

```bash
git clone https://github.com/akshatasatpute/Predicting_Artist_Popularity
```

### Install the required libraries

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook:

```
Predicting Artist popularity using Multiple linear regression LM code.ipynb
```

Run all cells sequentially to reproduce the complete analysis.

---

## Data Source

- Kaggle
- Spotify Web API
- Spotify Python Library

The audio feature values were extracted using the Spotify Web API and calculated by Spotify.

---
