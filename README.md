# Predicting Energy Prices

This repository contains the code and data for a data science project aimed at predicting energy prices. The project explores various data preprocessing techniques, feature engineering, and predictive modeling to build accurate and interpretable models for forecasting energy prices.


## Overview

Energy price prediction is a crucial task for energy companies, policy makers, and consumers. Accurate predictions can help in optimizing resource allocation, managing demand, and reducing costs. This project involves multiple iterations of analysis and modeling, where each iteration builds on the previous one.

Key features of this project include:

- **Data Preprocessing**: Cleaning and preparing energy demand and market price data.
- **Feature Engineering**: Extracting meaningful features to enhance predictive performance.
- **Modeling**: Using machine learning techniques to predict energy prices.
- **Iterative Improvements**: Experimenting with different approaches and refining the models over multiple cycles.


## Repository Structure

| File/Directory            | Description |
|---------------------------|-------------|
| `Data/`                   | Directory containing the raw and processed data files. |
| `1st Cycle.ipynb`         | First iteration of the analysis and modeling process. |
| `2nd Cycle.ipynb`         | Second iteration with refined preprocessing and modeling. |
| `3rd Cycle.ipynb`         | Third iteration with enhanced feature engineering. |
| `4th Cycle.ipynb`         | Fourth iteration focusing on advanced modeling techniques. |
| `5th Cycle.ipynb`         | Fifth and final iteration with the most optimized model. |
| `README.md`               | Project documentation (this file). |
| `demand_processing.ipynb` | Notebook for preprocessing energy demand data. |
| `market_price_processing.ipynb` | Notebook for processing market price data. |


## Data

The `Data` directory contains the datasets used in this project. The data includes:

1. **1_year_lag.csv**: Historical energy data with a 1-year lag for feature generation.
2. **demand_1dayahead.csv**: Energy demand data for one-day-ahead forecasting.
3. **demand_forecast.csv**: Forecasted energy demand data.
4. **n2ex_2019.xlsx**: Energy market data for the year 2019.
5. **n2ex_2020.xlsx**: Energy market data for the year 2020.
6. **n2ex_prices.csv**: Consolidated price data from the N2EX market.
7. **price_data.csv**: Processed price data used for modeling.
8. **weather_data 16.37.01.csv**: Weather data relevant to energy demand and pricing.

The data is preprocessed and cleaned in the `demand_processing.ipynb` and `market_price_processing.ipynb` notebooks.

## Installation and Usage

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook
- Required libraries (install using `requirements.txt`):

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebooks:
   ```bash
   jupyter notebook
   ```

4. Run the notebooks in sequence for a step-by-step analysis.


