# Taller-1_Arep
jose castillo

# Stellar Luminosity Regression Analysis

This project explores the relationship between stellar mass, temperature, and luminosity using linear and polynomial regression models. The objective is to analyze model convergence, feature engineering, interaction effects, and the limitations of linear regression for non-linear astrophysical data.

The project is implemented using two Jupyter notebooks that progressively increase model complexity.

---

## Getting Started

These instructions will help you run the project locally for development and experimentation.

### Prerequisites

You need the following software installed:

- Python 3.8 or later
- Jupyter Notebook
- NumPy
- Matplotlib

Install dependencies with:

```bash
pip install numpy matplotlib jupyter
```

---

### Installing

1. Download or clone the project.
2. Navigate to the project directory.
3. Start Jupyter Notebook:

```bash
jupyter notebook
```

4. Run the notebooks in order:
   - `01_part1_linreg_1feature.ipynb`
   - `02_part2_polyreg.ipynb`

---

## Project Structure

- **01_part1_linreg_1feature.ipynb**  
  Single-feature linear regression using gradient descent, including convergence analysis and learning rate experiments.

- **02_part2_polyreg.ipynb**  
  Polynomial and interaction-based regression models, feature engineering, and inference on new data.

---

## Running the Experiments

This project does not include automated tests. Model evaluation is performed through:

- Cost function convergence plots
- Prediction accuracy comparisons
- Feature and interaction analysis
- Inference demonstrations

All outputs are visualized directly in the notebooks.

---

## Built With

- Python
- NumPy
- Matplotlib
- Jupyter Notebook
