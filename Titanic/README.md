
---

# Titanic Survival Prediction

This repository contains a machine learning project focused on predicting the survival of passengers aboard the RMS Titanic. The dataset used for this project is the well-known Titanic dataset provided by Kaggle, which includes various features such as age, sex, passenger class, and more.

## Project Overview

The goal of this project is to build a predictive model that estimates the probability of survival for passengers on the Titanic based on the available features. The project demonstrates various steps involved in a typical machine learning workflow, including data preprocessing, feature engineering, model training, and evaluation.

## Dataset

The dataset consists of the following key columns:

- **PassengerId**: Unique identifier for each passenger
- **Survived**: Survival indicator (0 = No, 1 = Yes)
- **Pclass**: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name**: Name of the passenger
- **Sex**: Gender of the passenger
- **Age**: Age of the passenger
- **SibSp**: Number of siblings/spouses aboard the Titanic
- **Parch**: Number of parents/children aboard the Titanic
- **Ticket**: Ticket number
- **Fare**: Passenger fare
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Project Structure

The repository is structured as follows:

- `archive/`: Contains the dataset files.
- `Titanic/`: Jupyter notebooks demonstrating data analysis, preprocessing, and model development.
- `README.md`: Project description and overview.

## Notebooks

The Jupyter notebooks in the `notebooks/` directory cover the following steps:

1. **Data Exploration and Visualization**: Initial exploration of the dataset to understand the distributions and relationships between features.
2. **Data Preprocessing**: Handling missing values, encoding categorical variables, and scaling numerical features.
3. **Feature Engineering**: Creating new features based on existing ones to improve model performance.
4. **Model Training and Evaluation**: Training various machine learning models and evaluating their performance using metrics such as accuracy, precision, recall, and ROC-AUC.

## Scripts

The `Titanic/` directory contains modular Python scripts for:

- **Data Preprocessing**: Cleaning and preparing the dataset for modeling.
- **Feature Engineering**: Creating and transforming features.
- **Model Training**: Training and tuning machine learning models.

## Installation and Usage

To run the code in this repository, you will need Python 3.x and the necessary dependencies. You can install the dependencies using `pip`:

```bash
pip install -r requirements.txt
```

## Running the Notebooks

To run the Jupyter notebooks, navigate to the `notebooks/` directory and start Jupyter Notebook:

```bash
jupyter notebook
```

Open the desired notebook and run the cells to see the analysis and model training steps.

## Contributing

Contributions are welcome! If you have any improvements or suggestions, feel free to create a pull request or open an issue.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

