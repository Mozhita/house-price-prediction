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
house-price-prediction/
├── data/                   # Folder to store the dataset
│   └── .gitkeep            # Keeps the empty folder in Git
├── notebooks/              # Jupyter notebooks for EDA and modeling
│   ├── eda.ipynb           # Notebook for data exploration
│   └── modeling.ipynb      # Notebook for training and evaluating models
├── outputs/                # Output files such as plots or model files
│   └── feature_importance.png  # Feature importance plot from XGBoost
├── README.md               # Project documentation
├── requirements.txt        # List of Python packages used
└── .gitignore              # Specifies files and folders to ignore in Git

## 📈 Feature Importance (from XGBoost)

The model found features like Lot Area, Lot Frontage, and Gr Live Area to be highly influential in price prediction.
![Feature Importance](notebooks/feature_importance.png)
