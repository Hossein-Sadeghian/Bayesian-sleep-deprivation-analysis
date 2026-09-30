# Bayesian Sleep Deprivation Analysis

This project explores the relationship between sleep deprivation and reaction times using Bayesian statistical modeling. It demonstrates how to analyze datasets using probabilistic programming to quantify uncertainty and estimate individual responses to sleep loss.

## Project Overview
The analysis uses the "sleep deprivation" dataset to model the reaction time of subjects over multiple days of restricted sleep. By applying a Bayesian hierarchical model, we can account for individual differences and estimate the impact of sleep deprivation more robustly than with frequentist methods.

## Tools and Libraries
- **Python**: Core programming language.
- **PyMC**: For Bayesian modeling and MCMC sampling.
- **Pandas**: For data manipulation and processing.
- **Matplotlib & Seaborn**: For data visualization.
- **ArviZ**: For Bayesian diagnostic and posterior analysis.

## Prerequisites
To run this project, make sure to install the required dependencies:
```bash
pip install pymc pandas matplotlib arviz
```

## How to Run
1. Clone the repository or download the files.
2. Ensure `Real Sleep.csv` is located in the same directory as the notebook.
3. Open and run `Bayesian_sleep_analysis.ipynb` in Jupyter Notebook, VS Code, or Google Colab.

## Key Insights & Visualizations
- **Hierarchical Modeling:** Accounts for baseline reaction times across subjects as well as individual degradation rates per day of sleep deprivation.
- **Subject-Level Predictions:** Quantifies posterior distributions and risk assessments for vulnerable vs. resilient individuals.
