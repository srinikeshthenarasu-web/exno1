# Exno:1
Data Cleaning Process

# AIM
To read the given data and perform data cleaning and save the cleaned data to a file.

# Explanation
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect ,incompleted , irrelevant , duplicated or improperly formatted. Data cleaning is not simply about erasing data ,but rather finding a way to maximize datasets accuracy without necessarily deleting the information.

# Algorithm
STEP 1: Read the given Data

STEP 2: Get the information about the data

STEP 3: Remove the null values from the data

STEP 4: Save the Clean data to the file

STEP 5: Remove outliers using IQR

STEP 6: Use zscore of to remove outliers

# Coding and Output
import pandas as pd
import numpy as np
from scipy import stats
import seaborn as sns
import matplotlib.pyplot as plt
# Step 2: Read the Dataset
# Replace with your actual CSV file
df = pd.read_csv('Data_set.csv')
df.head()
df.info()
df.describe()
df.isnull()
df.isnull()
.sum()
# Fill Missing Values with 0
df1_fill_0 = df.fillna(0)
df1_fill_0
<img width="955" height="759" alt="Screenshot 2026-03-19 083311" src="https://github.com/user-attachments/assets/04c63758-2b75-43ac-b19f-9d4e728da23a" />
<img width="882" height="722" alt="Screenshot 2026-03-19 083323" src="https://github.com/user-attachments/assets/94ffc94f-4615-4b4b-91ea-8859eeda050f" />
<img width="903" height="591" alt="Screenshot 2026-03-19 083330" src="https://github.com/user-attachments/assets/e9c2366e-bc32-4b90-86f5-f8a45f5e731c" />



# Result
          <<include your Result here>>
