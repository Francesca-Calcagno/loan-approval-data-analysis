# Loan Approval Data Analysis
Data cleaning and analysis of a loan dataset with Python (pandas, matplotlib, scipy).


## Overview
Exploratory Data Analysis (EDA) on a loan dataset (~4k records) to understand patterns behind **approved vs. rejected** applications.  
The project covers **data cleaning**, **descriptive statistics**, and **visualizations** to identify the most relevant drivers for loan approval.

## Features
- Data cleaning: missing values, type casting, outlier checks, categorical normalization.
- Target understanding: class balance and approval rate.
- Descriptive statistics and grouping (by income, employment, education, marital status, etc.).
- Visualizations: distributions, group comparisons, trend and relationship plots.
- Insight extraction: factors associated with higher/lower approval likelihood.

## Tech Stack
- **Python**: pandas, numpy, matplotlib, scipy  
- **Notebook**: Jupyter  


## Project Structure
```plaintext
Loan_Approval_Analysis.ipynb   # Main notebook (cleaning, EDA, visuals, insights)
Loan_Approval_Dataset.csv      # dataset to obtain it
requirements.txt                # Project dependencies
README.md                       # Project documentation
```

## How to Run  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/YourUsername/loan-approval-data-analysis.git
   cd loan-approval-data-analysis
   
2. **Create a virtual environment**
   ```bash
   python -m venv venv

   Activate it with:
  - Windows: venv\Scripts\activate
  - macOS/Linux: source venv/bin/activate

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   
4. **Run the notebook**
   ```bash
   jupyter notebook

Open Loan_Approval_Analysis.ipynb and run the cells.


## Author  

**Francesca Calcagno**  
M.Sc. Data Science @ University of Catania  

[LinkedIn](https://linkedin.com/in/francesca-calcagno-9554a5381/)  
[GitHub](https://github.com/Francesca-Calcagno)  


