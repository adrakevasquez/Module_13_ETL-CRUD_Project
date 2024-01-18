# Module_13_ETL-CRUD_Project

For the ETL mini project, an ETL pipeline was built using Python, Pandas, and  Python dictionary methods/regular expressions to extract and transform data. After create four CSV files and use the CSV file data to create an ERD and a table schema. Upload the CSV file data into a Postgres database.

Two options for extracting and transforming the data from the Excel data:

Option 1: Use Python dictionary methods.

Option 2: Use regular expressions(REGEX).

If you chose Option 1, complete the following steps:

Import the contacts.xlsx file into a DataFrame.
Iterate through the DataFrame, converting each row to a dictionary.
Iterate through each dictionary, doing the following:
Extract the dictionary values from the keys by using a Python list comprehension.
Add the values for each row to a new list.
Create a new DataFrame that contains the extracted data.
Split each "name" column value into a first and last name, and place each in a new column.
Clean and export the DataFrame as contacts.csv and save it to your GitHub repository.

If you chose Option 2, complete the following steps:

Import the contacts.xlsx file into a DataFrame.
Extract the "contact_id", "name", and "email" columns by using regular expressions.
Create a new DataFrame with the extracted data.
Convert the "contact_id" column to the integer type.
Split each "name" column value into a first and a last name, and place each in a new column.
Clean and then export the DataFrame as contacts.csv and save it to your GitHub repository.

