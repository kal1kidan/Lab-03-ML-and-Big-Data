# Lab 03 – ML and Big Data

**Name:** Kalkidan Asdesach
**ID:** UGR/5481/16
**Department:** Software Stream, 4th Year

## Project

Binary classification on a synthetic ticket-escalation dataset (`escalated`: 1 = escalated, 0 = not escalated). The focus is on choosing metrics and decision thresholds based on the cost of mistakes, not only on accuracy.

## Contents

- `escalation_classification.ipynb` – the notebook (data inspection, preprocessing pipelines, baseline / logistic regression / LDA / k-NN, threshold and cost analysis, cross-validation, recommendation)
- `classification_escalation.csv` – the dataset

## How to run

1. Install dependencies: `python -m pip install pandas numpy matplotlib scikit-learn ipykernel`
2. Open the notebook in VS Code (or Jupyter) next to the CSV file.
3. Select a Python kernel and run all cells.