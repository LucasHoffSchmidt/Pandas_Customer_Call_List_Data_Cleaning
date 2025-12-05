# Pandas Customer Call List Data Cleaning
In this project we used pandas to clean a customer call list. 

## Quick Links
- Original customer call list dataset: [Customer Call List Dataset](customer_call_list.xlsx)
- Cleaned customer call list dataset: [Cleaned Customer Call List Dataset](cleaned_customer_call_list.png)
- Jupyter Notebook of cleaning the customer call list dataset: [Jupyter Notebook](customer_call_list_data_cleaning_project.ipynb)
- Other projects I have made: [Portfolio Website](https://lucashoffschmidt.github.io/)

## Technologies Used
- **Jupyter Notebook**: Web-based interactive computing environment. 
- **Pandas**: Data cleaning.

## Process
- Created a new Jupyter Notebook, imported pandas and loaded the customer call list dataset into a dataframe using read_excel().
- Removed duplicates and irrelevant columns with drop_duplicates() and drop().
- Cleaned last name values with str.strip().
- Standardized phone numbers and categorical columns with apply() and str.replace().
- Split the address column into multiple columns with str.split().
- Replaced not available and NaN values with empty strings using replace() and fillna().
- Removed rows marked Do_Not_Contact using a for loop, loc[] and drop().
- Reset the index with reset_index().

## Cleaned Customer Call List
![Cleaned Customer Call List](cleaned_customer_call_list.png)
