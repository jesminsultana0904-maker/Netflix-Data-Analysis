# Netflix Movies & TV Shows — Exploratory Data Analysis

## Project Overview
This beginner-level data analytics project explores the Netflix Movies and TV Shows dataset using Python. The notebook includes data inspection, basic cleaning, exploratory analysis, and visualizations to understand the catalogue.

## Objectives
- Compare Movies and TV Shows.
- Explore title release-year patterns.
- Review country and genre entries.
- Examine content ratings and TV Show seasons.
- Identify director entries with the most titles.
- Analyze when titles were added to Netflix.

## Tools
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Workflow
1. Load and inspect the dataset.
2. Handle missing values in selected columns.
3. Convert `date_added` to datetime.
4. Explore dataset counts and unique values.
5. Create visualizations and record observations.
6. Summarize findings and limitations.

## Visualizations
- Movies vs TV Shows (bar and pie charts)
- Titles by release year (line charts)
- Top country entries
- Top genre entries
- Content rating distribution
- TV Shows by number of seasons
- Top director entries
- Content added by year
- Content added by month

## Important Note
The `country`, `listed_in`, and `director` columns may contain multiple comma-separated values. The notebook's simple `value_counts()` analysis counts the full combined text as one entry. Therefore, the country and genre charts are rankings of entries, not individual countries or genres.

## Dataset
Place `netflix_titles.csv` in the same folder as the notebook before running it. Use the original dataset source (for example, the Netflix Movies and TV Shows dataset on Kaggle) and follow its terms.

## How to Run
1. Download or place `netflix_titles.csv` in the project folder.
2. Open `Netflix_Shows_Analysis.ipynb` in Jupyter Notebook or JupyterLab.
3. Run the cells from top to bottom.
4. Review the printed outputs and charts.
5. Fill in the Key Findings section with the actual results from your run.

## Skills Demonstrated
Data cleaning, missing-value handling, datetime conversion, descriptive analysis, Pandas, and data visualization.
