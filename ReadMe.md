# Data Science Salary Prediction

## Description
This project analyzes and predicts data science salaries using machine learning techniques. The main notebook, `project.ipynb`, explores salary data, performs data cleaning, feature engineering, hypertuning parameters, and builds predictive models to estimate salaries based on various factors such as job title, experience, location, and company size. The dataset is included in the repo

## Features
- Exploratory Data Analysis (EDA) of salary datasets
- Data preprocessing and visualization
- Model training and evaluation (e.g., Linear Regression, Random Forest)

## 📊 Model Performance

After training several models, the best performing result came from using a Stacking ensemble method:
- R² Score: 0.4611
- RMSE: ~$45,000
Note: Salaries are inherently noisy and the dataset is under 4,000 rows, which may limit model performance.

## Getting Started
1. Clone the repository.
2. Open `project.ipynb` in Jupyter Notebook.
3. Install required dependencies listed in `requirements.txt`.
4. Run the notebook cells to reproduce the analysis.

## Requirements
- Python 3.x
- pandas, numpy, matplotlib, seaborn, scikit-learn, jupyter

## Usage
1. Prepare your own salary dataset or use the provided sample data.
2. Adjust the data path in `project.ipynb` if using a different dataset.
3. Run each section of the notebook to perform EDA, preprocessing, and model training.
4. Review the model evaluation metrics to assess prediction performance.
5. Modify features or models as needed to improve results or adapt to your data.

## License
This project is for educational purposes.