# Twitter Data Extraction Tool
## Overview
This tool allows you to easily extract data from a Twitter account by providing the username. Follow the simple steps below, and you'll have a CSV file containing the last approximately 850 posts from the specified account.

## Usage Instructions
### Step 1: Prerequisites
Make sure you have the required libraries installed in your Python environment. You can install them using the following commands: `pip install pandas selenium`

### Step 2: Run the Code
1. Open your Jupyter environment or any Python environment of your choice.
2. Copy and paste the provided code into a code cell.
3. Enter the Twitter username of the account you want to extract data from.

### Step 3: Execute the Code
Run the code cell containing the script. A Chrome browser window will open, prompting you to enter your Twitter ID and password within approximately 1 minute.

### Step 4: Data Extraction
Sit back and relax! The script will automatically fetch the last around 850 posts from the specified Twitter account. The data will be loaded into a Pandas DataFrame.

### Step 5: Save to CSV
The extracted data will be saved to a CSV file named "twitter_data.csv" in the same directory as your script. You can now use this CSV file for further analysis or visualization.

### Note
1. This code is designed for local execution. Please avoid running it on Colab.
2. Ensure you have a stable internet connection during the process.
3. Use this tool responsibly and respect Twitter's terms of service.
