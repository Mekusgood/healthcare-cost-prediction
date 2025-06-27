# Healthcare Cost Prediction with Machine Learning

This project builds a machine learning model to predict individual healthcare charges using demographic and behavioral data. The model is trained and evaluated using Random Forest Regressor with hyperparameter tuning via GridSearchCV.

## 🔧 Technologies
- Python (pandas, scikit-learn, seaborn, matplotlib)
- Jupyter Notebook
- Streamlit (for optional dashboard)

## 📁 Contents
- `Healthcare_Cost_Prediction.ipynb`: Complete analysis, model training, and evaluation
- `data.csv`: Sample dataset (or instructions to load it)
- `requirements.txt`: Python dependencies

## 📊 Key Results
- Best model RMSE: ~$4,800
- R² Score: ~0.82
- Major cost drivers: Smoking status, BMI, Age

## 🚀 Run It
Clone the repository and open the notebook with Jupyter:

```bash
git clone https://github.com/Mekusgood/healthcare-cost-prediction.git
cd healthcare-cost-prediction
jupyter lab
