# Pandas Customer Call List Data Cleaning
In this project we use pandas to clean a customer call list. 

## Quick Links
- Raw customer call list dataset: [Raw Customer Call List](customer_call_list.xlsx)
- Cleaned customer call list dataset: [Cleaned Customer Call List](cleaned_customer_call_list.xlsx)
- Jupyter Notebook of the cleaning process: [Jupyter Notebook](customer_call_list_data_cleaning_project.ipynb)
- Other projects I have made: [Portfolio Website](https://lucashoffschmidt.github.io/)

## Technologies Used
- **Jupyter Notebook**: Web-based interactive computing environment. 
- **Pandas**: Data cleaning.

## Process
- Created a new Jupyter Notebook, imported pandas and loaded the customer call list dataset into a dataframe
<img src="images/read_excel.png" alt="Converting excel file to pandas dataframe" width="350">

- Removed duplicate rows
<img src="images/drop_duplicates.png" alt="Dropping duplicate rows" width="400">

- Removed redundant columns
<img src="images/drop_redundant.png" alt="Dropping redundant columns" width="350">

- Removed irrelevant characters from last name values
<img src="images/last_name.png" alt="Cleaning last name values" width="600">

- Standardized phone numbers
<img src="images/phone_values.png" alt="Standardizing phone values to the format 000-000-0000" width="800">

- Standardized Paying Customer and Do_Not_Contact columns
<img src="images/standardize.png" alt="Standardizing columns to Y and N for yes and no" width="700">

- Split the address column into its constituent elements
<img src="images/address.png" alt="Splitting the address column into street, state and zip code" width="650">

- Replaced not available and NaN values with empty strings
<img src="images/NaN.png" alt="Replacing NaN and N/a values with empty strings" width="450">

- Removed customers that may not want to be contacted
<img src="images/no_contact.png" alt="Removing customer with Y or empty string in Do_Not_Contact column" width="600">

- Removed customer that cannot be contacted
<img src="images/cant_contact.png" alt="Removing customers with no phone number associated with them" width="500">

- Dropped columns that only contained empty strings
<img src="images/empty_strings.png" alt="Dropping any column with only empty string across all rows" width="400">

- Reset the index
<img src="images/reset_index.png" alt="Resetting the index to show incremental numbers from 0" width="400">

- Saved cleaned dataframe to an excel file
<img src="images/save_excel.png" alt="Saving dataframe to an excel file" width="600">

## Raw Customer Call List
<img src="images/raw_customer_call_list.png" alt="Raw customer call list before any cleaning has been done" width="1000">

## Cleaned Customer Call List
<img src="images/cleaned_customer_call_list.png" alt="Cleaned customer call list after cleaning is done" width="1000">
