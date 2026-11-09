# Data Mining, Modeling And Analytics – Assignment
## Overview
This repository contains two machine learning project-based assigments. The projects demonstrate the application of classification and regression techniques to real-world datasets.
The analysis was conducted using Python and Jupyter Notebook.

## Project 1: Bank Marketing Classification
### Objective
To develop machine learning models that identify customers who are likely to subscribe to a term deposit following a bank marketing campaign.

### Dataset
The Bank Marketing dataset contains customer demographic, financial and campaign-related information.

### Methods
- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Majority-class baseline
- Logistic Regression
- Random Forest
- HistGradientBoosting
- Model evaluation using accuracy, precision, recall, F1-score and ROC-AUC
- Decision threshold analysis

### Best Model
Logistic Regression was selected based on its ability to identify potential subscribers. A decision threshold of 0.60 was selected using validation data.

## Project 2: Concrete Compressive Strength Regression
### Objective
To predict concrete compressive strength using mixture composition and curing age.

### Dataset
The Concrete Compressive Strength dataset contains 1,030 observations and nine numerical variables, including eight input features and the target variable.

### Methods
- Exploratory Data Analysis (EDA)
- Data cleaning and duplicate removal
- Mean-prediction baseline
- Linear Regression
- Random Forest Regressor
- HistGradientBoosting Regressor
- Model evaluation using MAE, RMSE and R-squared
- Residual analysis
- Five-fold cross-validation

### Best Model
HistGradientBoosting achieved the best performance, with:
- MAE: 3.0369 MPa
- RMSE: 4.5496 MPa
- R-squared: 0.9306

Five-fold cross-validation was also used to assess model consistency.

## Repository Structure

```text
Data_mining_Assignment-Nabyonga_
Theresa-B35752/
│
├── bank-additional-full-README.txt
├── Concrete_Data_README.txt
├── Project_1_report.pdf
├── Project_2_report.pdf
├── Project_1_Bank_Marketing.ipynb
├── Project_2_Concrete_Strength.ipynb
├── requirements.txt
└── README.md
```

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

## Installation and Execution

### 1. Clone the repository

```bash
https://github.com/teddypatricia/Data-Mining-Assignment-B35752
```

### 2. Navigate to the project folder

```bash
cd Data_Mining_Assignment_B35752
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```powershell
venv\Scripts\activate
```

### 4. Install dependencies
```bash
pip install -r requirements.txt
```

### 5. Run the notebooks

Open Jupyter Notebook or VS Code and execute:

- `Project_1_Bank_Marketing.ipynb`
- `Project_2_Concrete_Strength.ipynb`

Run each notebook from beginning to end.

## Reproducibility

The notebooks use fixed random states for data splitting and model training where applicable. The dependency list is provided in `requirements.txt` to support reproducibility.

## Conclusion

The two projects demonstrate how machine learning can be applied to classification and regression problems. They also highlight the importance of data exploration, baseline comparisons, model evaluation, residual analysis and reproducibility.
