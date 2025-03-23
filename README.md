# Life Expectancy Prediction

This project predicts life expectancy across countries using a variety of health, economic, and demographic indicators, leveraging advanced machine learning techniques.

## Overview
The dataset includes data from multiple countries over several years, with features like population, health statistics, GDP, and education levels. The goal is to build a robust model to forecast life expectancy accurately.

### Dataset
- **Source**: `train.csv` (2,848 rows), `test.csv` (80 rows)
- **Features**: 17 independent variables (e.g., Country, Year, Status, GDP, Health indicators)
- **Target**: `Life expectancy` (in years)

## Requirements
- Python 3.10+
- Libraries: `pandas`, `numpy`, `lightgbm`, `scikit-learn`

Install dependencies:
```bash
pip install -r requirements.txt
