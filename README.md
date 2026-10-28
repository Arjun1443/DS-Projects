# Weather Data Analysis

Weather-data learning materials for exploring a tabular dataset and its accompanying analysis report.

## Why this project matters

Exploratory analysis starts with understanding a dataset's structure, missing values, and distributions before drawing conclusions.

## Repository contents

- [1. Weather Data.csv](<1. Weather Data.csv>)
- [Weather Data Set.pdf](<Weather Data Set.pdf>)

## Explore the data

Open the PDF report in GitHub to review the supplied analysis. Load the CSV in a spreadsheet or Python environment to investigate the underlying records.

```python
import pandas as pd

df = pd.read_csv("1. Weather Data.csv")
print(df.shape)
print(df.head())
print(df.isna().sum())
```

Install pandas with `python -m pip install pandas` if needed.

## Project scope

The inspected repository contains data and a PDF report, without an executable analysis notebook. It is presented as analysis material rather than a deployed application. Review dataset provenance, collection dates, and field definitions before using findings outside this exercise.
