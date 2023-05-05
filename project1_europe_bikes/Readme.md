# **European Bike Sales**

This project uses machine learning techniques to predict the unit prices of bicycles based on various features. The dataset used in this project can be found on Kaggle. 

## **Requirements**
This project requires the following libraries:

pandas
numpy
matplotlib
seaborn
scikit-learn
You can install them using the following command:

``` bash
pip install pandas numpy matplotlib seaborn scikit-learn 
```
## **Usage**
To run this project, follow these steps:

1. Clone the repository to your local machine:
```bash
git clone https://github.com/abneribeiro/european-bike-sales.git
```
2. Navigate to the project directory:
```bash
cd european-bike-sales
```

3. Open the Jupyter notebook:
``` bash
jupyter notebook
```

4. Run the cells in the notebook to see the results of the analysis.

## **Dataset**
The dataset used in this project contains information about the sales of bicycles in Europe. The dataset includes the following features:

- Day
- Year
- Customer_Age
- Order_Quantity
- Unit_Cost
- Profit
- Cost
- Revenue

The objective of this project is to use these features to predict the unit prices of bicycles.

## **Analysis**
The analysis is divided into the following sections:

1. Data Cleaning: The dataset is cleaned by removing any missing or duplicate values.

2. Exploratory Data Analysis: The relationships between the features and the target variable are explored using visualizations.

3. Feature Engineering: New features are created based on the existing features in order to improve the performance of the machine learning models.

4. Machine Learning: Two machine learning models are trained and evaluated using the dataset: Linear Regression and Decision Tree Regressor.

## **Results**
The machine learning models were evaluated using the following metrics:

Mean Absolute Error (MAE)
The results of the analysis show that the Decision Tree Regressor outperformed the Linear Regression model in all three metrics.

## **Conclusion**
This project demonstrates how machine learning techniques can be used to predict the unit prices of bicycles based on various features. The Decision Tree Regressor was found to be the best model for this dataset, and achieved better results than the Linear Regression model. This project provides a framework for future work in the field of bicycle sales forecasting.

## **License**
This project is licensed under the MIT License. 