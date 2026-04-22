# Financial Analysis System

## 1. Problem & User
I developed a financial analysis system for ACC102 Information Systems for Accountants to help users understand and analyze financial data. This system aims to provide a comprehensive view of a company's financial performance by calculating key metrics, generating visualizations, and producing reports. It is designed for accounting and finance students, as well as professionals who want to quickly analyze financial data.

## 2. Data
- **Source**: Simulated data for demonstration purposes
- **Access Date**: April 2026
- **Key Fields**:
  - Total Revenue
  - Net Income
  - Operating Income
  - Total Assets
  - Total Liab
  - Total Current Assets
  - Total Current Liabilities
  - Total Stockholder Equity

## 3. Methods (main Python steps)
1. **Data Generation**: Create realistic financial data using pandas DataFrames
2. **Data Cleaning**: Convert dates to datetime format, remove empty rows, and fill missing values
3. **Financial Metrics Calculation**:
   - Net Profit Margin = Net Income / Total Revenue
   - Debt Ratio = Total Liab / Total Assets
   - ROE = Net Income / Total Stockholder Equity
   - Current Ratio = Total Current Assets / Total Current Liabilities
   - Operating Margin = Operating Income / Total Revenue
4. **Data Visualization**: Generate trend charts for each financial metric using matplotlib and seaborn
5. **Report Generation**: Display financial analysis results in the console

## 4. Key Findings (3-5 bullets)
- **Financial Performance Trend**: 
  - Net profit margin ranges from 20.68% to 27.18%, with an average of 23.73%
  - Debt ratio remains consistently high at around 80%, indicating high financial leverage
  - ROE is very high, averaging 119.64%, suggesting strong profitability relative to equity
  - Current ratio averages around 1.29, indicating reasonable short-term liquidity

## 5. How to run (optional but valuable)

### Prerequisites
- Python 3.7+
- pandas
- matplotlib
- seaborn
- Jupyter Notebook

### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/financial-analysis-system.git
   cd financial-analysis-system