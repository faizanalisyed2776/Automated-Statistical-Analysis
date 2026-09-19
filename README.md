# Automated Statistical Analysis & Hypothesis Testing

## About
This project uses **Python** to perform rigorous statistical analysis on datasets and **automatically generates a formatted Word document (.docx)** detailing the results. It is designed to transform raw data into **statistically validated insights**.

## Features
* **Independent T-Test:** Analyzes significant differences between categorical groups (e.g., impact of discounts on profits).
* **Pearson Correlation:** Measures the linear relationship between continuous variables (e.g., sales vs. profit).
* **Linear Regression:** Models and predicts outcomes based on independent variables.
* **Automated Reporting:** Uses `python-docx` to write the **P-values, test statistics, and automated interpretations** directly into a final Word file.

## Prerequisites
Ensure you have Python installed, then install the required statistical and reporting libraries:

```bash
pip install pandas numpy scipy statsmodels python-docx
