# Mini-Auto-GPT
A mini Auto-GPT for csv files.

The program is an interactive tool that accepts English queries from users for data manipulation, preprocessing and visualization tasks on a pandas DataFrame 'df'. Here our 'df' is credit_risk_dataset, and our user can be a bank employee, dealing with this dataset. The objective of program is to empower a bank employee without the prior knowledge of python or pandas libraries to handle this dataframe.

The program utilizes the OpenAI API to convert the queries into corresponding python commands and code. These code blocks are then automatically executed. Proper error handling ensures smooth execution and enhances user safety during code execution. 

The csv file used here is [credit_risk_dataset.csv](credit_risk_dataset.csv)
