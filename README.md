# Agricultural Financial & Seasonal Performance Analytics

**AICTE | IBM SkillsBuild Academic Internship — Data Analytics with AI**

## Project Overview

This project analyzes a seasonal agricultural performance dataset containing farm-level agronomic, environmental, operational, and financial information. The analysis focuses on crop yield, cultivation cost, revenue, profit, and seasonal performance using Python.

The project applies an end-to-end data analytics workflow:
- data loading and inspection
- missing-value treatment using median imputation
- exploratory data analysis (EDA)
- season-wise yield and profit comparison
- correlation analysis of key numeric variables
- visualization using bar charts, a histogram, and a correlation heatmap

## Dataset

The notebook expects the following Excel file in the same folder as the notebook:

`seasonal_agriculture_performance_dataset.xlsx`

Once the dataset is uploaded to the GitHub repository, it can be accessed here:

[Dataset — seasonal_agriculture_performance_dataset.xlsx](./seasonal_agriculture_performance_dataset.xlsx)

**Note:** The dataset file was not included with the submitted notebook/report files, so it must be added to the repository before running the notebook from GitHub.

## Technologies Used

- Python 3
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab
- Excel (XLSX dataset)

## Project Files

- `PrajvalKadam_AgriFinancialAnalytics.ipynb` — complete project code
- `requirements.txt` — Python dependencies
- `PrajvalKadam_AgriFinancialAnalytics_ProjectReport.docx` — project report
- `README.md` — project documentation and run instructions
- `seasonal_agriculture_performance_dataset.xlsx` — input dataset (add to repository)

## How to Run

### Option 1: Google Colab

1. Open the `.ipynb` notebook in Google Colab.
2. Upload `seasonal_agriculture_performance_dataset.xlsx` to the Colab session.
3. Run the notebook cells from top to bottom.

### Option 2: Jupyter Notebook

1. Install the dependencies:

```bash
pip install -r requirements.txt
```

2. Keep these files in the same folder:
   - notebook
   - `seasonal_agriculture_performance_dataset.xlsx`
3. Open the notebook in Jupyter and run the cells from top to bottom.

## Analysis Performed

### 1. Data Loading

The notebook loads the Excel dataset using Pandas and checks the dataset shape and first records.

### 2. Data Cleaning

Missing values are checked and median imputation is applied to:

- `Rainfall_mm`
- `Soil_Moisture_pct`
- `Yield_Tonnes_Ha`

### 3. Visual Analysis

The notebook generates five visualizations:

1. Distribution of records by season
2. Distribution of crop yield
3. Average crop yield by season
4. Average financial profit by season
5. Correlation heatmap of key numeric variables

## Key Findings

According to the project report, the dataset contains 4,000 farm-level records across 8 Indian states, 10 districts, 8 major crops, and 3 seasons: Kharif, Rabi, and Zaid.

The report identifies Kharif as having the highest average yield and average profit in the analyzed dataset, while Zaid has a negative average profit. The correlation analysis reports a strong relationship between profit and revenue and a weaker direct relationship between weather variables and yield.

## Outputs

The notebook saves the generated plots as:

- `plot1_season_distribution.png`
- `plot2_yield_distribution.png`
- `plot3_avg_yield_by_season.png`
- `plot4_profit_by_season.png`
- `plot5_correlation_heatmap.png`

## Author

**Prajval Anandrao Kadam**

AICTE | IBM SkillsBuild Academic Internship — Data Analytics with AI
