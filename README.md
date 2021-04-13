# user_analysis
This python script will generate an Expected Value for number of users on a future date


## How to Run the Solution
1. Download the repo
3. Open .ipynb file in Jupyter notebook and run all cells


## Important Factors for Running the Solution
1. Make sure you have Python / Jupyter notebook installed
2. Make sure you have an ODBC connection to Microsoft SQL Server in order to connect to the Server
3. Pip install any missing libraries
4. Update any filepaths and connection strings if needed
5. Avoid creating NewDb if it already exists


## Ways to Improve the Solution
1. Make a dynamic variable for number of days for calculating the moving average (default = 7)
2. Project the gender distribution and age range of new users on a future date
3. Use functions for repeating processes like connecting to SQL Server and calculating Moving Average
4. Execute SQL queries as stored procedures
5. Further improvements should be determined by how the project scales