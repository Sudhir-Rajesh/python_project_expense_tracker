# Financial Expense Analyzer

This Python script analyzes monthly expenses for multiple people from a CSV file, calculates totals, averages, and savings, and provides interactive visualizations.

---

## Features

- Read and clean CSV data (removes commas, converts to numbers)
- Automatically excludes rows with `Month = 'Budget'`
- Calculate:
  - Total expenses per person
  - Average monthly expenses per person
  - Savings per person (based on budget)
- Visualize data:
  - Pie chart of total expenses
  - Bar chart of total expenses
  - Individual pie/bar charts of monthly expenses
- Display summary table using **tabulate**
- Interactive menu for user-friendly operation

---

## Requirements

Install dependencies:

```bash
pip install pandas numpy matplotlib tabulate
