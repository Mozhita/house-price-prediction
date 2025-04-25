# 🏠 House Price Prediction (Ames Housing Dataset)

This project predicts house prices using the Ames Housing dataset, applying multiple regression models including Linear Regression, Random Forest, and XGBoost.

## 📊 Models and Results

| Model              | R² Score | MAE         |
|--------------------|----------|-------------|
| Linear Regression  | 0.8952   | 16247.95    |
| Random Forest      | 0.9110   | 15701.46    |
| XGBoost            | 0.9100   | 16028.78    |

## 🔧 Technologies
- Python, Pandas, NumPy
- Scikit-Learn, XGBoost
- Matplotlib, Seaborn
- Jupyter Notebook

## 📁 Repository Structure
house-price-prediction/ ├── data/ # Placeholder for dataset (e.g. AmesHousing.csv) │ └── .gitkeep # Ensures the folder is tracked by git ├── notebooks/ # Jupyter notebooks for EDA and modeling │ ├── eda.ipynb # Exploratory Data Analysis │ └── modeling.ipynb # Model training & evaluation (Linear, RF, XGBoost) ├── outputs/ # Output files like plots or saved models │ └── feature_importance.png # XGBoost feature importance plot ├── README.md # Project documentation and overview ├── requirements.txt # List of dependencies for reproducibility └── .gitignore # Files/folders to ignore in git (e.g., data files)

## 📈 Feature Importance (from XGBoost)

The model found features like Lot Area, Lot Frontage, and Gr Live Area to be highly influential in price prediction.
![Feature Importance](notebooks/feature_importance.png)
