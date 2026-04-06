# TrendPulse: Data Cleaning & Analysis

## Project Overview
This project takes messy JSON data from trending stories and cleans it using **Python** and **Pandas**. It prepares the data for analysis by removing duplicates, fixing types, and filtering low-quality content.

## How to Run
1. Ensure you have Python installed.
2. Install Pandas: `pip install pandas`
3. Run the script: `python task2_data_processing.py`

## Cleaning Steps Performed
* Removed duplicate `post_id` entries.
* Handled missing values in titles and scores.
* Converted scores and comments to integers.
* Filtered out stories with a score less than 5.
* Trimmed whitespace from titles.

## Results
The final cleaned data is saved as `trends_clean.csv`.
