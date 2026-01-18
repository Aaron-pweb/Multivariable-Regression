# Boston House Price Valuation Model 🏡💰

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Sklearn](https://img.shields.io/badge/scikit--learn-Regression-green)

## 📖 Overview

Welcome to the **Boston House Price Valuation Model** project. This project simulates a real-world task for a real estate development company in the 1970s. The objective is to build a robust multivariable regression model to estimate the price of residential properties in Boston, Massachusetts, based on various socioeconomic and structural characteristics.

By analyzing the famous Boston Housing dataset, this project demonstrates the end-to-end process of data science, from exploratory data analysis (EDA) to model evaluation and price prediction.

## 🎯 Objectives

1.  **Analyze & Explore**: deep dive into the Boston house price data.
2.  **Data Splitting**: Separate data into training and testing sets to ensure model validity.
3.  **Regression Modeling**: Implement Multivariable Linear Regression.
4.  **Evaluation**: Analyze coefficients, p-values, and residuals to check for model assumptions.
5.  **Optimization**: Use data transformations (e.g., log transformation) to improve performance.
6.  **Valuation**: Create a tool to estimate property prices based on user inputs.

## 📊 Dataset: `boston.csv`

The dataset contains information collected by the U.S. Census Service concerning housing in the area of Boston Mass.

| Feature     | Description                                                         |
| :---------- | :------------------------------------------------------------------ |
| **CRIM**    | Per capita crime rate by town                                       |
| **ZN**      | Proportion of residential land zoned for lots over 25,000 sq.ft.    |
| **INDUS**   | Proportion of non-retail business acres per town                    |
| **CHAS**    | Charles River dummy variable (1 if tract bounds river; 0 otherwise) |
| **NOX**     | Nitric oxides concentration (parts per 10 million)                  |
| **RM**      | Average number of rooms per dwelling                                |
| **AGE**     | Proportion of owner-occupied units built prior to 1940              |
| **DIS**     | Weighted distances to five Boston employment centres                |
| **RAD**     | Index of accessibility to radial highways                           |
| **TAX**     | Full-value property-tax rate per $10,000                            |
| **PTRATIO** | Pupil-teacher ratio by town                                         |
| **B**       | 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town      |
| **LSTAT**   | % lower status of the population                                    |
| **PRICE**   | Median value of owner-occupied homes in $1000's                     |

## 🛠️ Technologies Used

- **Python**: Core programming language.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computing.
- **Matplotlib / Seaborn / Plotly**: Data visualization.
- **Scikit-Learn**: Machine learning (Linear Regression, train_test_split).

## 🚀 Getting Started

1.  **Clone the repository**

    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2.  **Install Dependencies**
    Ensure you have Python installed. It is recommended to use a virtual environment.

    ```bash
    pip install pandas numpy matplotlib seaborn plotly scikit-learn jupyter
    ```

3.  **Run the Notebook**
    ```bash
    jupyter notebook "Multivariable_Regression_and_Valuation_Model_(start).ipynb"
    ```

## 📸 Project Gallery

Here are some snapshots of the analysis and model development process:

![Analysis Snapshot 1](images/Screenshot%202026-01-18%20at%2007-34-28%20Multivariable-Regression_Multivariable_Regression_and_Valuation_Model_%28start%29.ipynb%20at%20main%20·%20Aaron-pweb_Multivariable-Regression.png)

![Analysis Snapshot 2](images/Screenshot%202026-01-18%20at%2007-34-49%20Multivariable-Regression_Multivariable_Regression_and_Valuation_Model_%28start%29.ipynb%20at%20main%20·%20Aaron-pweb_Multivariable-Regression.png)

![Analysis Snapshot 3](images/Screenshot%202026-01-18%20at%2007-35-09%20Multivariable-Regression_Multivariable_Regression_and_Valuation_Model_%28start%29.ipynb%20at%20main%20·%20Aaron-pweb_Multivariable-Regression.png)

![Analysis Snapshot 4](images/Screenshot%202026-01-18%20at%2007-35-18%20Multivariable-Regression_Multivariable_Regression_and_Valuation_Model_%28start%29.ipynb%20at%20main%20·%20Aaron-pweb_Multivariable-Regression.png)

![Analysis Snapshot 5](images/Screenshot%202026-01-18%20at%2007-35-29%20Multivariable-Regression_Multivariable_Regression_and_Valuation_Model_%28start%29.ipynb%20at%20main%20·%20Aaron-pweb_Multivariable-Regression.png)

![Analysis Snapshot 6](images/Screenshot%202026-01-18%20at%2007-35-45%20Multivariable-Regression_Multivariable_Regression_and_Valuation_Model_%28start%29.ipynb%20at%20main%20·%20Aaron-pweb_Multivariable-Regression.png)

![Analysis Snapshot 7](images/Screenshot%202026-01-18%20at%2007-36-11%20Multivariable-Regression_Multivariable_Regression_and_Valuation_Model_%28start%29.ipynb%20at%20main%20·%20Aaron-pweb_Multivariable-Regression.png)
