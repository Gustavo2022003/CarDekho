Here’s the English translation of the content:

---

# CarDekho Project - Car Price Prediction

## Technologies
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

## Description:
This project aims to build a predictive model using car sales data from India, provided by [Kaggle](https://www.kaggle.com/datasets/akshaydattatraykhare/car-details-dataset). The model will be trained to predict car prices based on various vehicle features.

## Goal:
Develop a regression model to predict the selling price of used cars, maximizing the accuracy of predictions.

## Data Dictionary:
- **name**: Car model name.
- **year**: Year of manufacture.
- **selling_price**: Car selling price.
- **km_driven**: Vehicle mileage.
- **fuel**: Type of fuel used (e.g., petrol, diesel).
- **seller_type**: Type of seller (individual or dealer).
- **transmission**: Type of transmission (manual or automatic).
- **owner**: Number of previous owners.

## Libraries Used:
- **pandas**: For data manipulation.
- **seaborn**: For data visualization.
- **matplotlib**: For plotting graphs.
- **numpy**: For mathematical operations.
- **Jupyter lab**: For coding environment.

You can install all the required dependencies with the following command:

```bash
pip install -r requirements.txt
```

## Project Steps:
1. **Data Loading**: The dataset was imported and inspected.
2. **Exploratory Analysis**: Descriptive statistics and visualizations were used to understand the key characteristics of the data.
3. **Model Creation**: A regression model was trained to predict car selling prices.
4. **Model Evaluation**: The model was evaluated based on performance metrics to assess its accuracy.

## How to Run:
1. Clone the repository:
```bash
git clone https://github.com/Gustavo2022003/CarDekho.git
```
2. Ensure dependencies are installed:
```bash
pip install -r requirements.txt
```
3. Run the Jupyter Notebook: Open the `main.ipynb` file in a Jupyter environment:
```bash
jupyter lab main.ipynb
```
