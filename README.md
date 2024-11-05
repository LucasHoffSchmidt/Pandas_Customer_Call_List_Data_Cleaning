# Python Pandas Customer Call List Data Cleaning
In this project we used python in Jupyter Notebook to clean a customer call list using the python library of pandas.

## Tools and technologies
- **Jupyter Notebook**
- **Python**: Data cleaning
  - Pandas 

## Project Objectives
- Clean the data to only show customers that are available to be called

## Data Sources
- [Customer Call List](customer_call_list.xlsx)

## Analysis steps
- **Data Cleaning**:
  - Imported pandas
  - Transformed the customer call list excel file to a dataframe using read_excel()
  - Removed duplicates using drop_duplicates()
  - Removed irrelevant columns using drop()
  - Removed irrelevant characters from the beginning and end of last name values using str.strip()
  - Standardized all phone number values to the same format using apply() and str.replace()
  - Standardized values in the columns Paying Customer and Do_Not_Contact using str.replace()
  - Split the address column into distinct columns using str.split()
  - Replaced not available and NaN values with empty strings using replace() and fillna()
  - Removed irrelevant rows based on the Do_Not_Contact column using a for loop, loc[] and drop()
  - Reset the index to show numbers incrementally from 0 using reset_index()

## Visualizations
**Cleaned Customer Call List**

![Cleaned Customer Call List](cleaned_customer_call_list.png)
