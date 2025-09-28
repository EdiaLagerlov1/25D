# Find Best Line Algorithm

A Python script that finds the optimal line fit for randomly generated 2D points using Monte Carlo search.

## Installation & Usage
```bash
pip install numpy matplotlib
python find_best_line.py
```

## What it does
Generates random points in [0,1] space, tests multiple random lines (y = ax + b), and finds the one with minimum average vertical distance. Outputs visualizations and statistics of the best-fit line and search process.
