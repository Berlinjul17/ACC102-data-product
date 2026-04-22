# China Macroeconomic Data Analysis (2000-2024)

## 1. Problem & User
This project analyzes China’s macroeconomic trends (GDP, CPI inflation, and export performance) from 2000 to 2024 to identify key growth patterns and inflation dynamics. The target audience includes students, economic analysts, and anyone interested in understanding China’s post-2000 economic development trajectory.

## 2. Data (source + access date + key fields)
- **Source**: Structured in alignment with World Bank Open Data standards (simulated for academic use, no external API required).
- **Access date**: April 22, 2026.
- **Key fields**: Year (2000-2024), GDP (USD), CPI (%), Exports (USD), GDP Growth Rate (%), Export-to-GDP Ratio (%).

## 3. Methods (main Python steps)
1.  Data initialization: Created a structured dataset containing GDP, CPI, and export values for 2000-2024.
2.  Data cleaning: Checked for missing values, removed null entries, and calculated derived metrics (GDP growth rate, export-to-GDP ratio).
3.  Statistical analysis: Generated descriptive statistics, calculated average growth/inflation rates, and analyzed correlations between economic indicators.
4.  Visualization: Plotted time-series trends (GDP, CPI, export-to-GDP ratio) and distribution charts (GDP growth rate) using matplotlib and seaborn.

## 4. Key Findings (3-5 bullets)
- China’s GDP grew from ~1.2 trillion USD in 2000 to ~18.3 trillion USD in 2024, with an average annual growth rate of 12.33%.
- Average CPI inflation over the period was 2.03%, indicating stable price levels despite rapid economic expansion.
- The export-to-GDP ratio peaked in the mid-2000s, reflecting China’s strong integration into global trade before subsequent structural adjustments.
- GDP growth and CPI inflation showed a weak negative correlation (-0.10), suggesting other factors (e.g., investment, policy) drove most growth.

## 5. How to run
1.  Clone the repository to your local machine.
2.  Open `China_Economic_Analysis.ipynb` in Jupyter Notebook or VS Code.
3.  Run all cells sequentially (no internet/API required).
4.  View generated visualizations and analysis results in the notebook.

## 6. Product link / Demo
- **Notebook link**: [Paste your GitHub notebook URL here]
- **Demo**: 1-3 minute screen recording demonstrating the workflow and key findings.

## 7. Limitations & next steps
### Limitations
- The dataset uses simulated data aligned with World Bank formats (not raw official API data).
- Analysis does not include control variables (e.g., government spending, interest rates) that may influence economic trends.
### Next steps
- Integrate raw data from the World Bank API for real-world validation.
- Add time-series forecasting to predict future GDP/CPI trends.
- Expand analysis to include other macro indicators (e.g., unemployment, inflation components).
