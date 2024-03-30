# PYTHON DATA ANALYSIS
--------------------------------------------------

## Movie DataSet Exploratory Data Analysis (EDA)

### Introduction
This project focuses on conducting an in-depth Exploratory Data Analysis (EDA) on the Movie dataset to extract valuable insights and trends.
- **Main File**: Movie_EDA.ipynb

### Analysis Objectives
1. **Data Understanding**: Gain a comprehensive understanding of the dataset's structure, contents, and attributes.
2. **Data Cleaning**: Implement data cleaning techniques to handle missing values, ensure data integrity, and prepare the dataset for analysis.
3. **Exploratory Data Analysis (EDA)**: Utilize various statistical and visualization methods to explore relationships between features, identify patterns, and extract meaningful insights.
4. **Insights Generation**: Generate actionable insights and recommendations based on the findings from the EDA process.

### Methodology
1. **Data Preparation**:
   - Imported necessary libraries including pandas, numpy, matplotlib, and seaborn to facilitate data manipulation and visualization.
   - Loaded the dataset using `pd.read_csv()` function with appropriate encoding to read the CSV files into pandas DataFrame.
   - Inspected the initial rows of the dataset using `.head()` method to understand its structure and content.
   - Reviewed the columns and their data types using `.columns` and `.info()` methods to identify potential issues.
   - Calculated basic statistical metrics for numerical features using `.describe()` method to gain insights into the data distribution.
2. **Data Cleaning**:
   - Identified missing values using `.isnull().sum()` and addressed them appropriately to ensure data completeness.
   - Visualized missing values using a heatmap with `sns.heatmap()` to identify patterns and understand the extent of missingness.
   - Removed rows with missing values using `.dropna()` method, considering the impact on the analysis and the dataset's integrity.
   - Standardized the format of certain columns (e.g., 'year', 'runtime') to maintain consistency and facilitate analysis.
3. **Exploratory Data Analysis**:
   - **Highest Rated Movies Analysis**: Utilized `.groupby()` and `.sort_values()` functions to identify movies with the highest ratings for each year.
   - **Highest Voted Movies Analysis**: Employed `.groupby()`, `.sort_values()`, and `.iloc[]` methods to extract movies with the highest votes for each year.
   - **Relationship Visualization**: Created scatter plots using `plt.scatter()` to visualize the relationship between votes, gross revenue, and rating, exploring potential correlations.
   - **Genre Analysis**: Investigated popular genres for each year using `.groupby()` and `.idxmax()` to identify the genre with the highest count.
   - **Revenue Analysis**: Utilized `.groupby()` and `.sort_values()` to determine movies with the highest and lowest gross revenue for each year.
   - **Average Duration Analysis**: Calculated the average movie duration for each year using `.groupby()` and `.mean()` functions.
   - **Director Analysis**: Examined the director with the highest number of movies using `.groupby()` and `.idxmax()` to identify the most prolific director.
   - **Rating Distribution Across Genre**: Visualized the distribution of movie ratings across different genres using `.groupby()` and `sns.barplot()` functions.
   - **Top Rated Movies Across Genre**: Identified top-rated movies across genres using `.groupby()`, `.sort_values()`, and `.iloc[]` methods.
   - **Rating Trends Over Years**: Plotted a line graph to analyze the change in movie ratings over the years using `.groupby()` and `sns.lineplot()`.
   - **Rating Trends Across Genre Over Years**: Created line graphs to explore how movie ratings change over the years across different genres using `.groupby()` and `sns.lineplot()`.
   - **Top Stars Analysis**: Determined the top stars appearing in the most movies using `.value_counts()` and `sns.barplot()`.
   - **Revenue Trends Analysis**: Examined the relationship between years and gross revenue using boxplots with `sns.boxplot()`.
   - **Runtime vs. Average Revenue Analysis**: Investigated the relationship between runtime and average revenue using line graphs with `sns.lineplot()`.

### Key Findings
1. **Rating Distribution**: The majority of movies tend to fall within a moderate rating range, with only a few outliers at the extreme ends.
2. **Genre Preferences**: Certain genres exhibit consistent popularity over the years, while others experience fluctuations, indicating changing audience preferences.
3. **Revenue Trends**: Gross revenue demonstrates an overall increasing trend over the years, with occasional fluctuations influenced by various factors such as genre, star cast, and director.
4. **Director Influence**: Certain directors consistently produce successful movies, contributing significantly to the industry's success.
5. **Runtime Impact**: The duration of movies varies widely, with some genres favoring longer runtimes to accommodate intricate plotlines, while others prefer shorter durations for increased viewer engagement.

--------------------------------------------------


## Zomato DataSet Exploratory Data Analysis (EDA)

### Introduction
This project focuses on conducting an in-depth Exploratory Data Analysis (EDA) on the Zomato dataset.
- **main file**: Zomato EDA.ipynb
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


# Game DataSet Exploratory Data Analysis (EDA)

## Introduction
This project focuses on conducting an in-depth Exploratory Data Analysis (EDA) on the Game dataset to extract valuable insights and trends.
- **Main File**: Game_EDA.ipynb

## Analysis Objectives
1. **Data Understanding**: Gain a comprehensive understanding of the dataset's structure, contents, and attributes.
2. **Data Cleaning**: Implement data cleaning techniques to handle missing values, ensure data integrity, and prepare the dataset for analysis.
3. **Exploratory Data Analysis (EDA)**: Utilize various statistical and visualization methods to explore relationships between features, identify patterns, and extract meaningful insights.
4. **Insights Generation**: Generate actionable insights and recommendations based on the findings from the EDA process.

## Methodology
1. **Data Preparation**:
   - Imported necessary libraries including pandas, numpy, matplotlib, and seaborn to facilitate data manipulation and visualization.
   - Loaded the dataset using `pd.read_csv()` function with appropriate encoding to read the CSV files into pandas DataFrame.
   - Inspected the initial rows of the dataset using `.head()` method to understand its structure and content.
   - Reviewed the columns and their data types using `.columns` and `.info()` methods to identify potential issues.
   - Calculated basic statistical metrics for numerical features using `.describe()` method to gain insights into the data distribution.
2. **Data Cleaning**:
   - Identified missing values using `.isnull().sum()` and addressed them appropriately to ensure data completeness.
   - Visualized missing values using a heatmap with `sns.heatmap()` to identify patterns and understand the extent of missingness.
   - Removed rows with missing values using `.dropna()` method, considering the impact on the analysis and the dataset's integrity.
   - Standardized the format of certain columns (e.g., 'release_year', 'platform') to maintain consistency and facilitate analysis.
3. **Exploratory Data Analysis**:
   - **Highest Rated Games Analysis**: Utilized `.groupby()` and `.sort_values()` functions to identify games with the highest ratings for each year.
   - **Most Popular Games Analysis**: Employed `.groupby()`, `.sort_values()`, and `.iloc[]` methods to extract the most popular games based on user ratings and sales for each year.
   - **Relationship Visualization**: Created scatter plots using `plt.scatter()` to visualize the relationship between user ratings, sales, and platform, exploring potential correlations.
   - **Genre Analysis**: Investigated popular genres for each year using `.groupby()` and `.idxmax()` to identify the genre with the highest count.
   - **Sales Revenue Analysis**: Utilized `.groupby()` and `.sort_values()` to determine games with the highest and lowest sales revenue for each year.
   - **Average Playtime Analysis**: Calculated the average playtime for each year using `.groupby()` and `.mean()` functions.
   - **Publisher Analysis**: Examined the publisher with the highest number of games using `.groupby()` and `.idxmax()` to identify the most prolific publisher.
   - **Rating Distribution Across Genre**: Visualized the distribution of game ratings across different genres using `.groupby()` and `sns.barplot()` functions.
   - **Top Rated Games Across Genre**: Identified top-rated games across genres using `.groupby()`, `.sort_values()`, and `.iloc[]` methods.
   - **Rating Trends Over Years**: Plotted a line graph to analyze the change in game ratings over the years using `.groupby()` and `sns.lineplot()`.
   - **Rating Trends Across Genre Over Years**: Created line graphs to explore how game ratings change over the years across different genres using `.groupby()` and `sns.lineplot()`.
   - **Top Developers Analysis**: Determined the top developers with the most games released using `.value_counts()` and `sns.barplot()`.
   - **Sales Revenue Trends Analysis**: Examined the relationship between years and sales revenue using boxplots with `sns.boxplot()`.
   - **Playtime vs. Average Revenue Analysis**: Investigated the relationship between playtime and average revenue using line graphs with `sns.lineplot()`.

## Key Findings
1. **Rating Distribution**: The majority of games tend to have moderate ratings, with a few outliers at the extreme ends.
2. **Genre Preferences**: Certain genres maintain consistent popularity over the years, while others experience fluctuations, reflecting changing user preferences.
3. **Sales Revenue Trends**: Overall, there is a positive trend in sales revenue over the years, influenced by factors such as genre, platform, and marketing strategies.
4. **Publisher Influence**: Certain publishers consistently release successful games, contributing significantly to the gaming industry's success.
5. **Playtime Impact**: Game playtime varies widely across different genres and platforms, with some games offering longer playtime to accommodate complex storylines or multiplayer features, while others focus on shorter, more engaging experiences.

--------------------------------------------------
