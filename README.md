# Pandas Customer Call List Data Cleaning
In this project we used pandas to clean a customer call list. 

## Quick Links
- Original dataset: [Customer Call List Dataset](customer_call_list.xlsx)
- Cleaned dataset: [Cleaned Customer Call List Dataset](cleaned_customer_call_list)
- Jupyter Notebook of data cleaning with pandas: [Jupyter Notebook](customer_call_list_data_cleaning_project.ipynb)
- Other projects I have made: [Portfolio Website](https://lucashoffschmidt.github.io/)

## Tools Used
- **Jupyter Notebook**: Web-based interactive computing environment. 
- **Pandas**: Data cleaning.

## Project Objective
- Create a clean list of unique customers that we can call. 

## Data Source
- [Customer Call List](customer_call_list.xlsx)

## Process
- Created a new Jupyter Notebook. 
- Imported pandas.
- Transformed the customer call list dataset to a dataframe using read_excel().
- Removed duplicates using drop_duplicates().
- Removed irrelevant columns using drop().
- Removed irrelevant characters from the beginning and end of last name values using str.strip().
- Standardized all phone number values to the same format using apply() and str.replace().
- Standardized values in the columns Paying Customer and Do_Not_Contact using str.replace().
- Split the address column into distinct columns using str.split().
- Replaced not available and NaN values with empty strings using replace() and fillna().
- Removed irrelevant rows based on the Do_Not_Contact column using a for loop, loc[] and drop().
- Reset the index to show numbers incrementally from 0 using reset_index().

## Cleaned Customer Call List
![Cleaned Customer Call List](cleaned_customer_call_list.png)
