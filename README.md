# Student Score Prediction


Project STAR (Student/Teacher Achievement Ratio) was a randomised experiment 
conducted in Tennessee from 1985 to 1989. The study assigned K–3 students to either small 
classes (about 15 students) or regular classes (around 22 students) across 79 schools. STAR 
demonstrated that classroom environments – including class size, teacher quality, and peer 
composition – have a significant impact on early test performance and are strongly correlated 
with long-term outcomes such as college attendance and earnings.
Building on this foundation, our project uses a cross-section of 4,588 kindergarten students
(after removing NAs) to develop models predicting student’s reading and mathematics
scores. By exploring a range of econometric and machine learning predictive models, we aim 
to identify the models and variables that best forecast student performance and, in turn, help 
inform strategies for improving educational outcomes.

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

- **OLS Regression**:  linear and non-linear 
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

Regina Pan | Callum Hudson | Luke Wynd | Nather Truong 

## 📝 License

For academic purposes only.
