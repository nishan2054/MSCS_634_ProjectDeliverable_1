# MSCS 634 – Project Deliverable 1
## Data Collection, Cleaning, and Exploration

### Dataset
This project uses the Customer Personality Analysis dataset, which contains demographic and purchasing behavior information for 2240 customers. The dataset includes attributes such as age, income, education level, marital status, and spending on various product categories.

### Data Cleaning
The following data preprocessing steps were performed:

- Loaded the dataset using Pandas
- Checked dataset structure and data types
- Identified missing values
- Filled missing values in the Income column using the median value
- Checked for duplicate records

### Exploratory Data Analysis
Several visualizations were created to explore the dataset:

- Age distribution histogram
- Income distribution histogram
- Correlation heatmap between numerical features
- Scatter plot of income vs wine spending
- Boxplot for detecting income outliers

### Key Insights
The exploratory analysis revealed several patterns:

- Most customers are between 40 and 70 years old.
- Customer income distribution is right-skewed, with most incomes between $20,000 and $90,000.
- Income shows a positive relationship with product spending.
- Spending variables across product categories are positively correlated.
- Some high-income outliers were detected in the dataset.

### Challenges
One challenge encountered during the analysis was handling missing values in the Income column. This issue was addressed by replacing missing values with the median income value. Additionally, correlation analysis required selecting only numerical features to avoid errors caused by categorical variables.
