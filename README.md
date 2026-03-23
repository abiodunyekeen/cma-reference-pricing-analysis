
# CMA Reference Pricing Analysis

## Overview

This project analyses retail pricing data to identify patterns that may indicate potentially misleading reference pricing practices (e.g. “Was £100, now £60”).

The objective is to support non-technical policy stakeholders in understanding:

* where such behaviours may be occurring
* how widespread they are
* and their potential severity

The analysis is exploratory and intended to highlight areas for further investigation rather than provide definitive conclusions.

---

## Project Structure

* `data/`
  Contains the input dataset used for analysis.

* `notebook/analysis.ipynb`
  Main analysis notebook, including data cleaning, feature engineering, and insights.

* `requirements.txt`
  Python dependencies required to run the notebook.

---

## How to Run

1. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

2. Open the notebook:

   ```bash
   jupyter notebook notebook/analysis.ipynb
   ```

3. Run all cells from top to bottom.

---

## Approach

The analysis follows a structured approach:

1. Data cleaning and validation
2. Feature engineering (e.g. discount percentage)
3. Definition of indicators for potentially misleading behaviour
4. Aggregation and visualisation
5. Interpretation of results

A set of practical indicators was used to identify potential concerns, including:

* inflated reference prices relative to typical selling price
* persistent discounting over time
* unusually high discount levels

---

## Key Outputs

The notebook includes:

* Summary statistics and retailer-level comparisons
* Visualisations of discount behaviour
* Identification of products and retailers with higher concentrations of flagged behaviour

---

## Assumptions and Limitations

This analysis assumes that a genuine reference price should reflect a price used over a meaningful period. Due to data limitations, proxy thresholds were used.

The dataset does not include sales volumes or full pricing histories, so findings should be interpreted as indicative rather than conclusive.

---

## Author

Abiodun Yekeen
