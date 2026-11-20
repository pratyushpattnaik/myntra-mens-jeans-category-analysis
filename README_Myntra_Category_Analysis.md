# Myntra Men's Jeans Category Analysis

**Author:** Sriman Pratyush Pattnaik

## Project overview

This project analyses a dataset of Myntra men's jeans listings to understand catalogue composition across brands, jeans styles and price segments, and to examine patterns in customer ratings and discounts.

The analysis uses descriptive statistics, grouped summaries, correlation analysis and visualisations to develop category-level insights.

## Key dataset metrics

| Metric | Result |
|---|---:|
| Product records analysed | 35,073 |
| Unique brands | 417 |
| Jeans-style categories | 15 |
| Average listed selling price | ₹1,618.15 |
| Average customer rating | 3.98 / 5 |
| Average discount | 51.7% |

## Main findings

- **Leading brand by product count:** United Colors of Benetton (3,300 listings).
- **Largest price segment:** Mid-range (17,461 listings; 49.78% of the analysed catalogue).
- **Most represented jeans style:** Slim Fit (12,006 listings; 34.23%).
- **Highest average rating by price segment:** Premium (4.04 / 5).
- **Discount-band observation:** Average rating ranges from 4.04 in the 0–30% discount band to 3.88 in the 70–100% band.

## Analysis covered

1. Dataset overview and analytical scope
2. Brand-level product count, average price and average rating
3. Jeans-style distribution and performance
4. Budget, Mid-range and Premium price segmentation
5. Customer ratings across discount bands
6. Pearson and Spearman correlation analysis
7. Category insights and recommendations

## Tools and techniques

- Python
- Google Colab / Jupyter Notebook
- pandas for data manipulation and aggregation
- Matplotlib for visualisation
- Descriptive statistics and correlation analysis

> Confirm the imports in the final notebook and update this tools list if your implementation uses additional libraries.

## Repository structure

```text
myntra-mens-jeans-category-analysis/
├── README.md
├── notebooks/
│   └── Myntra_Category_Analysis.ipynb
├── reports/
│   └── Myntra_Mens_Jeans_Category_Analysis_Submission_Report.docx
├── images/
│   └──                 # Optional charts exported from the notebook
└── .gitignore
```

## How to run

1. Open `notebooks/Myntra_Category_Analysis.ipynb` in Google Colab or Jupyter Notebook.
2. Add the dataset only if you have permission to share and use it.
3. Update the notebook's dataset-loading path to match your local or Colab file location.
4. Run the notebook cells in order.

## Important data note

The reported product counts describe catalogue listings in the analysed dataset. They are **not** sales volume, revenue, conversion, profitability or sales market share. Correlation results describe association and do not establish causation.

The source dataset is not included in this repository. Do not publish Myntra-owned, confidential, personally identifiable or otherwise restricted data. Include only data that you have the right to redistribute; otherwise document how an authorised reviewer can reproduce the analysis.

## Project report

The `reports/` folder contains the written project report with the dataset overview, methodology, findings, tables and recommendations.
