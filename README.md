# user_analysis
This python script will generate an Expected Value for number of users on a future date

## How to Run the Solution
1. Download the repo
2. Make sure you python / Jyupiter notebook installed
3. Open Jyupiter notebook and run all cells


## Important Factors for Running the Solution
1. Make sure you have an ODBC connection to Microsoft SQL Server in order to connect to the Server
2. Pip install any missing libraries
3. Update any filepaths and connection strings if needed
4. Avoid creating NewDb if it already exists


## Ways to Improve the Solution
1. Make a dynamic variable for number of days for calculating the moving average (default = 7)
2. Use functions for repeating processes like connecting to SQL Server and calculating Moving Average
3. Further improvements should be determined by how the project scales