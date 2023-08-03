# Data Analyst Job Market Analysis

This project provides a comprehensive analysis of the job market for Data Analysts, Senior Data Analysts, and Data Scientists, including salary prediction, based on data scraped from Google job listings.

## Project Structure

The project consists of three Jupyter notebooks:

1. `google_jobscrape.ipynb`: This notebook contains the initial setup for scraping job data from Google using the SerpApi. However, the code to perform these operations is not included.

2. `sql_eda.ipynb`: This notebook performs preliminary exploratory data analysis on the job dataset using SQL. It involves creating a SQLite database, importing data into it, performing data cleaning, and extracting cleaned data back into a pandas DataFrame.

3. `salary_predict.ipynb`: This notebook provides in-depth exploratory data analysis, data cleaning and preprocessing, feature selection and engineering, model building, and evaluation. It uses Linear Regression model, Word2Vec Embedding in Classification Models, Count vectorizer + TF-IDF with GridSearch, Pretrained GloVe Model, Deep Learning Models with Word Embeddings, pre-trained Word2Vec as the embedding layer to predict salaries for different job roles.

## Detailed Workflow

### Data Scraping

While the `google_jobscrape.ipynb` notebook does not contain the complete code for data scraping, it demonstrates the basic setup for using the SerpApi to scrape Google job listings.

### Data Cleaning and Exploration

The `sql_eda.ipynb` notebook performs the following steps:

1. Loads the scraped job data into a pandas DataFrame.
2. Creates a SQLite database and imports the DataFrame into it as a table.
3. Performs data cleaning by removing rows with null values in certain columns.
4. Extracts cleaned data back into a pandas DataFrame.
5. Saves the cleaned data to a CSV file.

### Data Analysis and Modeling

The `salary_predict.ipynb` notebook performs the following steps:

1. Imports necessary libraries and explains each feature in the dataset.
2. Loads the cleaned data into a DataFrame.
3. Performs further data cleaning, including handling missing values and removing unnecessary columns.
4. Performs exploratory data analysis, including univariate and multivariate analyses.
5. Performs data preprocessing, including feature selection and encoding of categorical features.
6. Splits the data into training and testing sets.
7. Studies multicollinearity among the features.
8. Builds a Linear Regression model and evaluates it using R-squared and Root Mean Squared Error (RMSE) for both training and testing data.

## Conclusion

This project provides a comprehensive analysis of the job market for data-related roles, with a specific focus on predicting salaries. The use of both SQL and pandas for data cleaning and exploration, combined with machine learning for salary prediction, makes this a multifaceted project that demonstrates proficiency in data scraping, data cleaning, exploratory data analysis, and predictive modeling.
