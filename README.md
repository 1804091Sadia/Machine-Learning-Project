# Laptop Prices Analysis and Prediction

A **Machine Learning project** analyzing a dataset of laptops to understand price determinants and predict laptop prices and types. This project involves **data analysis, visualization, and machine learning** using Python.

---

## Project Description

This project explores a dataset containing information on various laptop models, including:

* Brand, Product, and Type
* Screen size and resolution
* RAM, storage, and CPU/GPU specifications
* Operating system, weight, and price in euros

The goal is to **analyze the factors affecting laptop prices**, build **predictive models**, and visualize data patterns.

---

## Dataset

The dataset `laptop_prices.csv` contains the following columns:

* `Company`, `Product`, `TypeName`, `Inches`, `Ram`, `OS`, `Weight`
* `Price_euros`, `Screen`, `ScreenW`, `ScreenH`, `RetinaDisplay`
* `CPU_company`, `CPU_freq`, `CPU_model`
* `PrimaryStorage`, `SecondaryStorage`, `PrimaryStorageType`, `SecondaryStorageType`
* `GPU_company`, `GPU_model`

---

## Project Goals

The project addresses the following tasks:

1. **Brand Analysis:** Identify the top 5 laptop brands by the number of products.
2. **Price Analysis:** Calculate average laptop prices per brand and find the highest/lowest average.
3. **Correlation Analysis:** Find correlations between `Price_euros` and numeric features like `CPU_freq`, `Ram`, `Inches`, and `Weight`.
4. **Feature Engineering:** Create a new feature `StorageTotal` = `PrimaryStorage` + `SecondaryStorage`.
5. **Regression Modeling:** Predict `Price_euros` using features like `Ram`, `Inches`, `CPU_freq`, `PrimaryStorage`, and `GPU_company`. Suggest the best regression model.
6. **Classification Modeling:** Predict `TypeName` using features like `Inches`, `Ram`, `PrimaryStorage`, and `Weight`. Identify important features and the best classification model.

---

## Usage

1. Load the dataset in a Jupyter Notebook or Google Colab:

```python
import pandas as pd

df = pd.read_csv("laptop_prices.csv")
```

2. Perform analysis and modeling using Python libraries like `pandas`, `numpy`, `matplotlib`, `seaborn`, and `scikit-learn`.

3. Follow the project goals to answer all analysis and modeling questions.

---

## Libraries Required

* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `scikit-learn`

Install via pip if needed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```



MIT License
you want me to do that?
