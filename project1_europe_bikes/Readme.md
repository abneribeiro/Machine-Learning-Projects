# **European Bike Sales**

This project is focused on utilizing advanced machine learning techniques to accurately predict the unit prices of bicycles based on a wide range of features. The dataset utilized for this project can be acquired from Kaggle.

## **Requirements**
To effectively run this project, the following libraries are essential:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can effortlessly install these libraries using the provided command:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## **Usage**
To execute this project successfully, follow the step-by-step instructions below:

1. Clone the repository to your local machine:
```bash
git clone https://github.com/abneribeiro/european-bike-sales.git
```

2. Navigate to the project directory:
```bash
cd european-bike-sales
```

3. Launch the Jupyter notebook:
```bash
jupyter notebook
```

4. Run the notebook cells to observe the comprehensive analysis results.

## **Dataset**
The dataset used in this project encompasses crucial information concerning bicycle sales throughout Europe. It includes the following essential features:

| Feature        | Description           |
| ------------- |-------------|
| Day      | The day of the transaction |
| Year      | The year of the transaction      |
| Customer_Age | The age of the customer     |
| Order_Quantity | The quantity of bicycles ordered     |
| Unit_Cost | The unit cost of the bicycle     |
| Profit | The profit generated from the sale     |
| Cost | The cost of the bicycles     |
| Revenue | The total revenue from the sale     |

The primary objective of this project is to leverage these features to accurately predict the unit prices of bicycles.

## **Analysis**
The analysis is meticulously divided into several key sections:

1. Data Cleaning: The dataset undergoes thorough cleansing procedures to eliminate any missing or duplicate values.

2. Exploratory Data Analysis: Utilizing powerful visualizations, we delve into the intricate relationships between the features and the target variable.

3. Feature Engineering: We engineer new features derived from the existing ones to significantly enhance the overall performance of our machine learning models.

4. Machine Learning: We train and evaluate two advanced machine learning models using the dataset: Linear Regression and Decision Tree Regressor.
   

### **Data Cleaning**

To ensure data reliability and consistency, a meticulous data cleaning process was carried out on the European bike sales dataset. The following key steps were performed during this phase:

1. **Missing Values Verification**: All fields in the dataset, comprising a total of **113,036 records**, were checked for missing values. It was determined that no missing values were present, eliminating the need for data imputation or removal procedures.

2. **Duplicate Detection**: A thorough examination was conducted to identify and handle any potential duplicate records. Fortunately, no duplications were found, indicating that no further action was required to remove duplicate entries.

3. **Data Type Correction**: During the analysis, it was observed that some columns required adjustments to their data types to ensure proper representation and compatibility. For instance, the "Date" column was initially stored as a string but was converted to the **datetime64[ns]** format for better handling and analysis. This conversion enabled more effective utilization of the temporal information contained within the column.

4. **Value Validation**: The values in various columns were validated to ensure they corresponded to the expected categories and fell within acceptable ranges. The following table summarizes the columns and their predefined categories:

| Column           | Description                             |
|------------------|-----------------------------------------|
| Day              | Day of the month                        |
| Month            | Month of the year                       |
| Year             | Year                                    |
| Customer_Age     | Age of the customer                      |
| Age_Group        | Age group of the customer                |
| Customer_Gender  | Gender of the customer                   |
| Country          | Country of sale                          |
| State            | State/region of sale                     |
| Product_Category | Category of the product                  |
| Sub_Category     | Subcategory of the product               |
| WeekDay          | Day of the week                          |

The validation process ensured the consistency and conformity of the values in these columns with their respective predefined categories.

Following the completion of these data cleaning steps, the dataset was prepared for Exploratory Data Analysis (EDA) to extract meaningful insights about bike sales in Europe.


### **Exploratory Data Analysis**

During the Exploratory Data Analysis (EDA) phase, the medians of profit for different age groups were calculated. The results are presented in the table below:

| Age Group         | Median Profit |
|-------------------|---------------|
| Adults (35-64)    | 111.0         |
| Seniors (64+)     | 76.5          |
| Young Adults (25-34) | 113.0         |
| Youth (<25)       | 71.0          |

These medians represent the middle value of the profit distribution for each specific age group. The median is a measure of central tendency that indicates the value separating the upper half from the lower half of the data.

Insights:
- The age group of Young Adults (25-34) has the highest median profit of 113.0, indicating that this age group tends to generate more profit compared to other age groups.
- The age group of Seniors (64+) has the lowest median profit of 76.5, suggesting that this age group may have lower purchasing power or engage in fewer high-profit transactions.
- Adults (35-64) and Youth (<25) have median profits of 111.0 and 71.0, respectively, showcasing the variations in profit across different age groups.

These insights provide valuable information about the profit distribution among different age groups, allowing for a better understanding of the revenue generated from bicycle sales.

- Based on the analysis of the graph, it is evident that the Adults (35-64) group generates the highest sales volume. Furthermore, within this group, men stand out as they generate a greater number of sales compared to women. This information highlights the influence of gender on sales generation within the adult group.
    ![Sales by Age group](images/age_group.png)

- By examining the graph, it becomes apparent that the United States had the highest sales rate according to our dataset. This finding underscores the significant market demand and consumer interest in the United States, positioning it as a key region for bicycle sales. The robust sales performance in the United States suggests favorable market conditions, potential business opportunities, and the importance of targeting this market segment for future growth and strategic decision-making.

    ![ country ](images/country.png)

- We also observe that there is a higher proportion of men compared to women in bicycle purchases. This finding indicates a gender disparity in the consumer market for bicycles, with men being the dominant buyers. This insight suggests the need for targeted marketing strategies and product offerings that appeal to both genders, ensuring inclusivity and addressing the specific preferences and needs of female customers.

    ![ Sales by genre ](images/MF.png)

- Based on this graph, we can observe that the year 2015 had the highest number of sales, reaching 20 million units, while the lowest number of sales was recorded in 2011, with 9 million units. This information highlights the significant growth in sales over the years and indicates the potential for further analysis and strategies to maximize revenue. The graph provides a visually appealing representation of the sales trend over time, allowing stakeholders to easily identify the peak and low points in sales performance. This valuable insight can guide decision-making processes and inform business strategies to capitalize on successful sales years and address challenges during periods of lower sales.
  
    ![ sales_per_year ](images/sales_per_year.png)
## **Results**
The machine learning models are thoroughly evaluated utilizing the following critical metrics:

- Mean Absolute Error (MAE)

The comprehensive analysis results conclusively demonstrate that the Decision Tree Regressor model consistently outperforms the Linear Regression model across all three metrics.

## **Conclusion**
This project serves as a comprehensive showcase of the practical application of advanced machine learning techniques for accurate prediction of unit prices in the bicycle sales domain. The Decision Tree Regressor has emerged as the most suitable model for this specific dataset, delivering superior performance when compared to the Linear Regression model. This project lays a strong foundation for future endeavors in the field of bicycle sales forecasting.

## **License**
This project is licensed under the MIT License.

Please note that as a text-based AI model, I am unable to directly include images in the README file. However, you can incorporate relevant images and visualizations to enhance the professional presentation of your project.