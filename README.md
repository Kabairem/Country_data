# Country Data Analysis

This project explores a country-level dataset and applies exploratory data analysis (EDA), statistical summaries, and clustering techniques to understand how countries compare across key socioeconomic indicators.

## Project overview

The dataset contains country-level indicators including:

- child mortality
- exports and imports
- health expenditure
- income
- inflation
- life expectancy
- total fertility rate
- GDP per capita

The analysis in the notebook focuses on:

- data cleaning and validation
- descriptive statistics and missing-value checks
- distribution and outlier analysis
- correlation analysis
- feature scaling
- K-Means clustering
- hierarchical clustering
- principal component analysis (PCA)

## Repository structure

- `Countrydata.ipynb` — main exploratory analysis and clustering notebook
- `Notebook/Countrydata.ipynb` — duplicate notebook copy within the `Notebook/` folder
- `Rawdata/Country-data.csv` — source dataset used in the analysis
- `countryvenv/` — local Python virtual environment used for the project

## Dataset

The raw data is stored in `Rawdata/Country-data.csv` and includes one row per country. Each row contains the socioeconomic variables used in the clustering experiments.

Example columns:

- `country`
- `child_mort`
- `exports`
- `health`
- `imports`
- `income`
- `inflation`
- `life_expec`
- `total_fer`
- `gdpp`

## Requirements

The notebook uses Python packages such as:

- pandas
- matplotlib
- seaborn
- scikit-learn
- scipy

## Setup

From the project root, create and activate a virtual environment:

```bash
python -m venv countryvenv
# Windows
countryvenv\Scripts\activate
# macOS/Linux
source countryvenv/bin/activate
```

Install the required dependencies:

```bash
pip install pandas matplotlib seaborn scikit-learn scipy jupyter
```

## Run the analysis

Open the notebook in Jupyter:

```bash
jupyter notebook
```

Then open `Countrydata.ipynb` from the project root and run the cells in sequence.

## Use case

This project is useful for exploring how countries can be grouped based on economic and social indicators, helping to identify patterns, similarities, and clusters across nations.

## License

This repository does not currently include a formal license file. If this project will be shared publicly, consider adding an open-source license such as MIT or Apache 2.0.
