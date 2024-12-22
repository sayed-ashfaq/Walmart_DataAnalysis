# Walmart Black Friday Purchase Behavior Analysis

## About Walmart
Walmart, an American multinational retail corporation, operates a vast network of supercenters, discount departmental stores, and grocery stores worldwide. With over **100 million customers globally**, Walmart is a leader in the retail industry.

This project analyzes customer purchase behavior during **Black Friday**, a significant shopping event generating high transaction volumes.

---

## Objective
The primary objective of this project was to:
- Explore customer purchase behavior during Black Friday.
- Visualize spending patterns and central tendencies using box plots and distribution analysis.
- Assess whether purchase amounts follow a normal distribution.

---

## Dataset
The dataset used for this analysis contains transactional data of customers who purchased products at Walmart during Black Friday.

**Dataset Features**:
- **`User_ID`**: Unique customer identifier.
- **`Product_ID`**: Unique product identifier.
- **`Gender`**: Customer’s gender (Male/Female).
- **`Age`**: Customer’s age group (in bins).
- **`Occupation`**: Encoded occupation identifier.
- **`City_Category`**: City category (A, B, or C).
- **`StayInCurrentCityYears`**: Number of years the customer has lived in their current city.
- **`Marital_Status`**: Marital status (0 = Single, 1 = Married).
- **`ProductCategory`**: Encoded product category.
- **`Purchase`**: Amount spent by the customer on a product.

---

## Key Insights
1. **Gender-Based Spending**:
   - Box plots revealed distinct spending patterns between male and female customers.

2. **Age and Purchase Behavior**:
   - Central tendency measures showed variations in spending across age groups.

3. **City Category Trends**:
   - Customers from category "A" cities demonstrated higher purchase amounts compared to "B" and "C" cities.

4. **Normal Distribution Check**:
   - Assessed purchase amounts for normality using visual distribution analysis.

---

## Process Overview
### 1. **Data Cleaning**:
   - Addressed missing values and ensured dataset consistency.

### 2. **Exploratory Data Analysis (EDA)**:
   - Visualized purchase patterns using:
     - **Box plots** to understand distribution and detect outliers.
     - **Histograms** to examine overall data spread and normality.
   - Analyzed central tendencies (mean, median, mode) for different demographic groups.

### 3. **Insights**:
   - Focused on visual and descriptive statistics to identify patterns in the dataset.

---

## Tools and Libraries
This project was implemented using:
- **Python**:
  - `Numpy` & `Pandas` for data manipulation.
  - `Matplotlib` and `Seaborn` for visualization.
- **Jupyter Notebook** for interactive analysis and documentation.

---

## Repository Structure
- **`data/`**: Contains the dataset used for analysis.
- **`notebooks/`**: Jupyter Notebooks documenting the analysis process.
- **`visualizations/`**: Saved plots and charts used in the project.
- **`README.md`**: Overview of the project (this file).

---

## Acknowledgments
- **Dataset Source**: Provided by Scaler for this project.
- **Libraries Used**: Thanks to the Python data science community for open-source tools.

---

## License
This project is for educational and non-commercial use only. Please credit the repository if using its resources.

---

## Next Steps
Future extensions of this project could include:
1. Applying feature engineering to enhance insights.
2. Conducting statistical testing to validate observed patterns.
3. Developing predictive models to forecast purchase behavior.
