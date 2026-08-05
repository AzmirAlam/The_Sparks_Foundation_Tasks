# Task 3: Retail Data Analysis

This Jupyter Notebook explores the Sample Superstore dataset to identify sales, profitability and customer-segment patterns.

## Planned workflow

- Clean and validate the dataset
- Examine sales and profitability
- Compare regions, categories and sub-categories
- Investigate customer segments
- Identify loss-making categories, sub-categories and markets
- Present evidence-based business recommendations

## Files

- [`retail-eda.ipynb`](./retail-eda.ipynb) — complete exploratory analysis notebook
- [`data/sample_superstore.csv`](./data/sample_superstore.csv) — source dataset
- [`requirements.txt`](./requirements.txt) — Python dependencies

## Run the notebook

Install the dependencies, then open the notebook in JupyterLab or Jupyter Notebook:

```bash
pip install -r requirements.txt
jupyter lab
```

## Data limitations

The supplied data has no product name, customer ID, order ID or order date. The notebook therefore analyses categories, sub-categories, regions and customer segments; it does not make product-level, customer-level or time-series claims.
