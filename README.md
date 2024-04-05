# Data-1202
For the purpose of this lab is to learn different techniques to encode the categorical features to numeric quantities. To keep it simple, you will apply these encoding methods only on one column. However, the same approach can be extended to all columns.
# Prerequisites
Make sure you have installed the following:

Anaconda
Jupiter Notebook
MYSQL Workbench
# You can install the required libraries using the following commands:
pip install pandas
pip install numpy
# Running the test
Part 1: Replacing Values
In this exercise, you'll learn how to replace categorical values with user-defined numerical values using the replace() function in pandas. This method allows you to assign specific numbers to categories based on your business requirements.

Part 2: Label Encoding
This exercise introduces label encoding, a technique that converts each category in a column to a numerical label between 0 and n_categories-1. You'll use the cat.codes method to perform this encoding.

Part 3: One-Hot Encoding
In this part, you'll create a new binary column for each unique category using the get_dummies() function in pandas. This method is commonly used for machine learning models that require categorical features to be represented as numerical values.
# Deployment
Make sure you have a MySQL database setup before deploying this script, and adjust the script's connection parameters. To load the data into the database, run the script after that.
# Author
Anamika
# License
This project is provided for educational purposes. 

# Acknowledgement
I express my sincere gratitude to all team members who have contributed to this project by offering their time, insights, and expertise. Your dedication and effort have been invaluable in shaping and improving this repository.
