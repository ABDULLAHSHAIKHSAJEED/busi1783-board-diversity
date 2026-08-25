# Board Gender Diversity and Firm Performance: UK FTSE 100 (2019-2024)

MSc Business Analytics Project (BUSI1783), University of Greenwich

## Overview
Panel data analysis examining the relationship between board gender 
diversity and firm financial performance among UK FTSE 100 firms, 
with attention to the FCA Listing Rule 9.8.6R (April 2022).

## Data Sources
- FTSE Women Leaders Review / Hampton-Alexander Review (board composition)
- ORBIS, Bureau van Dijk (financial data)
- Yahoo Finance via yfinance (market data)

## Structure
- `notebooks/` — analysis pipeline in execution order
- `data/raw/` — original downloads (unmodified)
- `data/processed/` — cleaned analysis-ready panel
- `outputs/` — figures and tables used in the dissertation

## Environment
Python 3.11 — pandas, numpy, statsmodels, linearmodels, 
scikit-learn, shap, matplotlib, seaborn, yfinance, pdfplumber
