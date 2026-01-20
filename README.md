# Femicide in Kenya: Temporal, Spatial, and Contextual Analysis

This project analyzes trends, patterns, and contextual factors surrounding femicide in Kenya. Using reported data, the project aims to identify temporal trends (seasonality), spatial hotspots (county-level analysis), and provide a foundation for forecasting and policy intervention.

## Project Overview

In late 2024, reports indicated a significant rise in femicide cases in Kenya. This project seeks to validate these patterns against historical data using a data-driven approach.

**Key Objectives:**
*   **Temporal Analysis:** Analyze national monthly trends and identify seasonal patterns.
*   **Spatial Analysis:** Examine geographic variations across counties.
*   **Contextual Analysis:** (Planned) Explore relationships between victim/suspect demographics and justice outcomes.

## Folder Structure

```
Femicide-Analysis-and-Forecasting/
├── Data/
│   ├── raw/                  # Raw data files (e.g., Excel/CSV)
│   └── Processed/            # Cleaned and aggregated datasets
├── Notebooks/
│   ├── data_cleaning.ipynb   # Data standardization and preparation
│   └── EDA_analysis.ipynb    # Exploratory Data Analysis (Temporal & Spatial)
├── dashboard/                # (Planned) Interactive dashboard application
├── images/                   # Images and plots generated from analysis
├── Reports/                  # (Planned) Analytical reports
├── README.md                 # Project documentation
└── requirements.txt          # Python dependencies
```

## Prerequisites

To run this project, you need Python installed along with the following libraries:

*   pandas
*   numpy
*   matplotlib
*   seaborn
*   scipy
*   statsmodels
*   openpyxl
*   jupyter

## Installation

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd Femicide-Analysis-and-Forecasting
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

### Running the Notebooks
1.  Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2.  Open `Notebooks/data_cleaning.ipynb` to see the data preparation process.
3.  Open `Notebooks/EDA_analysis.ipynb` to explore the exploratory data analysis, including time-series decomposition.

### Dashboard
*   (Instructions for running `dashboard/app.py` can be added here once the dashboard is implemented.)

## Data Source
The data is compiled from reported femicide cases in Kenya (media monitoring) and obtained from [Africadatahub](https://ckan.africadatahub.org/dataset/kenya-femicide-data)
