# Financial Ratios Analysis Project

## Overview

This project is designed to analyze and visualize financial ratios to support critical investment decision-making processes, particularly focusing on profitability and leverage across various industries. The role assumed in this project is that of a financial analyst at a hedge fund, utilizing financial data to address real-world investment challenges.

## Project Objective

The primary objective is the evaluation of profitability and leverage across different industries, with special attention to real estate companies. Insightful analysis is required to determine whether highly leveraged real estate companies exhibit greater profitability.

## Data Description

Two primary datasets are utilized:

- `Balance_Sheet.xlsx`
- `Income_Statement.xlsx`

Both datasets include the following common columns:

- **Company**: Company's ticker symbol.
- **comp_type**: Industry classification (`tech`, `fmcg`, `real_est`).
- **Year**: Reporting year of the financial information.

Additional columns include detailed financial statement information, with Balance_Sheet.xlsx providing balance sheet details and Income_Statement.xlsx providing income statement details.

## Calculation of Financial Ratios

Two key ratios must be calculated and stored in a DataFrame named `df_ratios`:
- **Leverage Ratio**: Debt-to-equity ratio or equity multiplier, stored under the column `leverage_ratio`.
- **Profitability Ratio**: Gross margin ratio or operating margin ratio, stored under the column `profitability_ratio`.

## Analysis Requirements

The following analytical insights must be derived and stored:
- **Lowest Profitability**: Identification of the industry (`comp_type`) with the lowest profitability ratio.
- **Highest Leverage**: Identification of the industry (`comp_type`) with the highest leverage ratio.
- **Leverage-Profitability Relationship**: Analysis of the relationship between leverage and profitability specifically within real estate companies, categorized as `"positive"`, `"negative"`, or `"no relationship"`.

These insights must be recorded in a DataFrame named `df_ratios` and the relationship as a string under the variable `relationship`.

## Deliverables

The analysis will produce:
- A DataFrame named `df_ratios` containing computed leverage and profitability ratios.
- Variables storing industry insights:
  - `highest_leverage`
  - `lowest_profitability`
  - `relationship`

## Usage

The analysis is to be executed in Python, employing libraries such as pandas, numpy, and matplotlib/seaborn for data processing, analysis, and visualization as appropriate.

## Conclusion

Completion of this analysis will support informed investment decision-making, especially regarding the financial viability and risks associated with investing in real estate companies based on their leverage and profitability characteristics.