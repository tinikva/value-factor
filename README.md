# Value/Growth Strategy

A quantitative value/growth factor investing repository that ingests financial data, computes multi-factor signals, backtests strategies, and visualizes performance results.

## Project Structure

```
value_growth_strategy/
├── data/                  # Raw and processed data files
├── notebooks/             # Exploration and analysis Jupyter notebooks
├── src/                   # Python package modules (currently empty – add your modules here)
├── requirements.txt       # Pinned dependencies
├── README.md              # Project overview and instructions
```

## Installation
1. Create and activate a conda environment:
   ```bash
   conda create -n vg_strategy python=3.10
   conda activate vg_strategy
````

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. (Optional) Install in editable mode:

   ```bash
   pip install -e .
   ```

## Key Scripts and Notebooks

* `notebooks/Full_Run.ipynb`: End-to-end example demonstrating data loading, signal creation, backtest, and results visualization.

