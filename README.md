# Restaurant Sales Analysis (Tips Dataset)

A short exploratory data analysis of restaurant billing and tipping behavior, using Python's Pandas and Matplotlib.

## Objective

Analyze restaurant sales data to identify patterns in customer spending and tipping behavior across different days of the week.

## Dataset

The built-in `tips` dataset from the `seaborn` library — real-world restaurant transaction data including total bill, tip amount, day, time, and party size.

## Process

1. Loaded the dataset using `seaborn.load_dataset('tips')`
2. Grouped and aggregated total bill amounts by day using Pandas `groupby()`
3. Calculated tip percentage (`tip / total_bill * 100`) per transaction
4. Compared average tip percentage across days
5. Visualized average bill by day using Matplotlib

## Key Findings

- **Sunday** has the highest average total bill of the week — customers spend the most on Sundays.
- **Tip percentage varies by day** — customers don't tip a flat rate; generosity shifts depending on the day, suggesting day-of-week is a meaningful factor in both spend and tipping behavior.

## Visualization

![Average Bill by Day](avg_bill_by_day.png)

## Tools Used

- Python
- Pandas
- Seaborn (dataset only)
- Matplotlib

## What I'd improve next

- Break down findings further by lunch vs. dinner
- Test whether party size correlates with tip percentage
- Build an interactive dashboard version (e.g. with Plotly or Streamlit)
