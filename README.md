# PYTHON DATA ANALYSIS
--------------------------------------------------
## Zomato DataSet Exploratory Data Analysis (EDA)

### Introduction
This project focuses on conducting an in-depth Exploratory Data Analysis (EDA) on the Zomato dataset.
main file: (Zomato EDA.ipynb)
### Analysis Objectives
1. **Data Understanding**: Gain insights into the structure and content of the dataset.
2. **Data Cleaning**: Handle missing values and ensure data integrity.
3. **Exploratory Data Analysis**: Analyze the numerical and categorical variables, explore relationships between features, and visualize key trends.
4. **Insights Generation**: Draw actionable insights and recommendations based on the analysis.

### Methodology
1. **Data Preparation**:
   - Imported necessary libraries including pandas, numpy, matplotlib, and seaborn.
   - Loaded the dataset using `pd.read_csv()` function with encoding.
   - Inspected the first few rows of the dataset using `.head()` to understand its structure.
   - Checked the columns and data types using `.columns` and `.info()` methods.
   - Explored basic statistics of numerical features using `.describe()`.
2. **Data Cleaning**:
   - Checked for missing values using `.isnull().sum()` and identified columns with missing values.
   - Visualized missing values using a heatmap with `sns.heatmap()` to identify patterns.
   - Removed rows with missing values using `.dropna()` method and verified the removal.
   - Merged the cleaned dataset with the country code dataset using `pd.merge()`.
3. **Exploratory Data Analysis**:
   - **Online Delivery Analysis:** Utilized seaborn's `countplot()` to analyze online delivery options.Extracted relevant data and visualized distribution.
   - **Geographic Analysis:** Employed matplotlib's `pie()` to analyze restaurant distribution.Extracted top city data and created pie chart.
   - **Cuisine Analysis:** Utilized matplotlib's `pie()` to analyze cuisine distribution. Extracted top cuisines data and created pie chart.

### Key Findings
1. **Rating Distribution**: The majority of restaurants fall within the rating range of 2.5 to 3.4.
2. **Online Delivery Availability**: Online delivery options are prevalent in India and UAE, indicating potential market opportunities.
3. **Customer Preferences**: Indian customers contribute significantly to zero ratings, suggesting potential areas for improvement in service quality.
4. **Popular Cuisines**: Indian, Chinese, and Italian cuisines emerge as the top preferences among consumers, highlighting potential demand trends.

--------------------------------------------------
