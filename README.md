# COVID-19 Employment & Unemployment Analysis (2019–2020)

Analysis of how the COVID-19 pandemic affected employment and unemployment rates across regions in India. Using government datasets from 2019 and 2020, the project explores labour participation trends, peak unemployment periods, and the regions most impacted during the crisis.

## Key Objectives

- Analyze labour force participation and employment trends before and during COVID-19
- Identify regions with the highest and lowest unemployment impact
- Visualize critical events and peak unemployment with time series and comparative plots

## Techniques Used

- Time series decomposition
- Regional aggregation and comparative analysis
- Annotated peak unemployment and COVID-period span

## Project Structure

| File | Description |
|------|-------------|
| `covid19_unemployment_analysis.ipynb` | Main analysis notebook (data cleaning, EDA, visualizations) |
| `Data Analysis Report_ COVID-19 Employment and Unemployment Trends (2019-2020).pdf` | Written report summarizing findings |

## How to Run

1. Place the required CSV datasets in the project root (or update paths in the notebook):
   - `Unemployment in India.csv`
   - `Unemployment_Rate_upto_11_2020.csv`
2. Open `covid19_unemployment_analysis.ipynb` in Jupyter or VS Code / Cursor.
3. Run all cells.

### Dependencies

```text
pandas
numpy
matplotlib
seaborn
plotly
```

Install with:

```bash
pip install pandas numpy matplotlib seaborn plotly
```

## Insights

The analysis helps show how different states responded to the economic shock and how recovery varied across India.
