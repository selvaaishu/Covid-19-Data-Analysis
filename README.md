# COVID-19 Data Analysis (Web Extraction + Cleaning + Visualization)

## Project Overview
This project focuses on extracting real-world COVID-19 data from an online source using HTTP requests, performing data cleaning and preprocessing in Python, and generating insights through analysis and visualization.

The dataset was filtered for India and prepared for trend-based analysis such as daily cases, deaths, and rolling averages.

---

## Tools & Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  
- HTTP Requests (Data extraction from website)

---

## Dataset Source
COVID-19 dataset extracted from an online website (Our World in Data) using HTTP request.

---

## Workflow / Steps Followed

### 1. Data Extraction
- Connected to the website using an HTTP request
- Loaded the COVID dataset into a Pandas DataFrame

### 2. Data Cleaning & Preprocessing
- Converted date column into proper datetime format
- Filtered the dataset for India
- Handled missing values using appropriate fill methods
- Removed null values and ensured correct column types
- Checked duplicates and validated dataset consistency

### 3. Feature Engineering
- Created additional useful columns such as:
  - Daily cases
  - Daily deaths
  - 7-day rolling average for better trend understanding

### 4. Data Analysis
- Performed trend-based analysis on:
  - Total cases
  - New cases
  - Total deaths
  - Smoothed daily trends

### 5. Visualization
- Created plots to visualize:
  - COVID case growth over time
  - Daily case trends
  - Daily death trends
  - Rolling average patterns

---

## Key Insights
- Identified how COVID cases increased across different time periods in India
- Observed the peak periods of cases and deaths
- Smoothed values helped reduce daily noise and highlight real trends

---

## Output
- Cleaned and processed COVID-19 dataset for India
- Trend-based analysis and visual insights using graphs

---

## Files Included
- `corona db analysis.ipynb` → Complete analysis notebook  
- `README.md` → Project documentation  

---

## How to Run the Project

1. Clone the repository
```bash
git clone <your-github-repo-link>
