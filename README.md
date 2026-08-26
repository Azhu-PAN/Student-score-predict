# Student Score Prediction

**ECON5403 Group Assignment** - Group 3

Predicting student math and reading scores based on school and teacher characteristics using machine learning models.

## 📁 Project Structure

```
├── data/
│   ├── raw/              # Original dataset
│   └── processed/        # Cleaned dataset
├── notebooks/
│   ├── implementation.ipynb    # Main implementation
│   └── SHAP_analysis.ipynb     # Model interpretation (SHAP values)
├── reports/
│   └── Group Assignment.pdf    # Written report
├── results/              # Model outputs & evaluation results
├── figures/             # Visualizations
├── models/              # Saved trained models
└── src/                 # Utility functions (if any)
```

## 🔧 Setup

```bash
# Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## 📊 Models Used

- **OLS Regression** (baseline)
- **Regularization**: Ridge, Lasso, Elastic Net
- **Tree-based**: Random Forest, Bagging, Gradient Boosting
- **Neural Network**: Multi-layer Perceptron (MLP)
- **Model Averaging**

## 📋 Contents

1. Data Loading & Cleaning
2. Exploratory Data Analysis (EDA)
3. Model Training & Comparison
4. Cross-Validation for Hyperparameter Tuning
5. Model Interpretation (SHAP values)

## 👥 Group Members

Group 3

## 📝 License

For academic purposes only.
