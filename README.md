# Cybersecurity Traffic Data Analysis

## Project Overview
This project focuses on the **Data Preprocessing** and **Exploratory Data Analysis (EDA)** of network traffic logs. The goal is to clean synthetic cyber attack datasets and extract meaningful insights regarding traffic distributions and malicious behavior.

## Key Features
* **Data Cleaning:** Handled missing categorical values (`Protocol`) and filled numerical gaps using median imputation.
* **Outlier Detection:** Filtered and corrected anomalous packet sizes exceeding theoretical network limits (65,535 bytes).
* **Data Visualization:** Developed statistical plots using `Matplotlib` and `Seaborn` to analyze the distribution of Normal, Malicious, and Suspicious traffic.

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
