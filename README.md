📺 Viewership Analysis Project
📌 Overview
This project analyzes video viewership data from an Excel file. The workflow includes:

Importing essential Python libraries

Installing dependencies for consistent execution

Loading data into a Pandas DataFrame

Displaying and exploring the dataset for further analysis

🛠️ Requirements
The following libraries are required:

python
import pandas as pd
import numpy as np
Additional dependency for Excel support:

bash
%pip install openpyxl
pandas → Data manipulation and analysis

numpy → Numerical operations

openpyxl → Required for reading .xlsx files

✅ Note: After installing new packages, restart the kernel using %restart_python or dbutils.library.restartPython() to ensure updates are applied.

📂 Data Source
The dataset is stored in an Excel file:

Code
/Workspace/Users/khozabonginkosi6@gmail.com/Viewership Analysis .xlsx
This file contains viewership logs with the following columns:

Column	Description
DateID	Date of the event (YYYYMMDD format)
CustomerID	Unique identifier for the customer
TotalTimeWatched	Total viewing time in seconds
Platform	Platform used (e.g., Leanback, Mobile)
PlayEventType	Type of event (e.g., LiveTV, Other)
VideoTitle	Title of the video watched
📥 Loading the Data
python
# Location of the Excel file
data_path = "/Workspace/Users/khozabonginkosi6@gmail.com/Viewership Analysis .xlsx"

# Read the Excel file into a DataFrame
df = pd.read_excel(data_path)

# Display the data
display(df)
📊 Sample Output
Example of the dataset:

DateID	CustomerID	TotalTimeWatched	Platform	PlayEventType	VideoTitle
20201101	EW1DENH0EC1J3M9WAOZF9LSV004O	300	Leanback	LiveTV	F1 '20: Emilia Romagna GP
20201101	6TS2LLY0L3G66FVY86Q0JEZE000K	360	Leanback	Other	Chasing The Sun
20201101	6PMV67PLJ2S47S68J0Y30XFK003C	120	Leanback	LiveTV	Sonic The Hedgehog
