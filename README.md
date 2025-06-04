# decision_tree_regression
Decision Tree Regression on Tabular Data (Scikit-learn, Python)

# Decision Tree Regression on Tabular Data

This repository contains a Jupyter Notebook that demonstrates the use of a **Decision Tree Regressor** on structured tabular data using Python's `scikit-learn` library. The goal is to predict continuous target values from a dataset with multiple input features.

## 📁 Contents

- `ML_CW.ipynb` - Main notebook containing all steps from data loading to model evaluation
- `train_x.csv`, `train_y.csv` - Training feature and target datasets
- `test_x.csv`, `test_y.csv` - Testing feature and target datasets

## 🧠 Key Features

- Data loading and preprocessing using `pandas`
- Renaming and aligning feature columns for consistency
- Training a `DecisionTreeRegressor`
- Visualizing the decision tree structure with `matplotlib`
- Evaluating model performance using:
  - Root Mean Squared Error (RMSE)
  - R² Score (Coefficient of Determination)

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/decision-tree-regressor.git
   cd decision-tree-regressor
   ```

2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook ML_CW.ipynb
   ```

## 📊 Example Output

- Decision tree plot of model structure
- RMSE and R² score comparison between predictions and true values

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Scikit-learn
- Pandas
- Matplotlib
- NumPy
