# Loan Performance Analysis of Fannie Mae Data                                                                  

## Overview

This project analyzes the **Fannie Mae Single-Family Loan Performance Data**, a comprehensive dataset that tracks mortgage loan performance and risk. The goal is to provide valuable insights into mortgage trends, loan default risks, and borrower behaviors using **PySpark** and other analytical tools.

## Project Objectives

The primary objectives of this project include:

1. **FICO Score Analysis:**  
   - Compare the average FICO scores across two assigned years.

2. **Delinquency Trends:**  
   - Analyze monthly delinquency rates (30, 60, 90 days past due) and how they vary by loan term.

3. **Credit Score Distribution:**  
   - Create a stacked bar chart showing credit score distribution by mortgage type and state for first-time buyers.

4. **Correlation Analysis:**  
   - Investigate relationships between FICO score, Loan-to-Value (LTV) ratio, and interest rates with loan status.

5. **Loan Status Distribution:**  
   - Examine distributions of FICO scores, LTV ratios, and interest rates across different loan statuses (performing, delinquent, defaulted).

6. **Default Rate Trends:**  
   - Assess how default risks have evolved by comparing loans originated in different quarters.

7. **Loan Recovery Analysis:**  
   - Evaluate the percentage of loan amounts recovered after defaults via foreclosure or other means.

8. **Property Price Trends:**  
   - Plot statistics (average, median, variance) of property price changes over time, grouped by month.

## Data Source

The dataset used in this project is sourced from the **Fannie Mae Single-Family Loan Performance Data**, which is publicly available on the [Fannie Mae website](https://capitalmarkets.fanniemae.com/credit-risk-transfer/single-family-credit-risk-transfer/fannie-mae-single-family-loan-performance-data). 

The dataset includes:

- **Acquisition Data:**  
  Static loan characteristics at the time of origination (e.g., credit scores, loan terms).

- **Performance Data:**  
  Monthly updates on loan performance, including delinquency status, payments, and modifications.

### Data Coverage

- **Time Period:** 2000 - 2023  
- **Updates:** Quarterly  
- **Granularity:** Loan-level data  

## Tools and Technologies Used

- **Programming Language:** Python  
- **Big Data Processing:** PySpark (Google Colab)  
- **Data Visualization:** Matplotlib, Seaborn  
- **Data Storage:** Parquet (for efficient processing)  
- **Documentation:** Markdown within notebooks  

4. **Run the analysis notebooks in Google Colab:**

   - Upload the dataset to your **Google Drive**, convert CSV files to Parquet format, and process using PySpark.

## Key Findings

Some of the key insights discovered from the analysis include:

- **FICO Score Analysis:**  
  - The average FICO score comparison across years revealed [add summary of insights].  

- **Delinquency Rates:**  
  - Trends in delinquency rates showed [add findings about loan delinquency].  

- **Default Rate Trends:**  
  - The comparison of default rates across quarters suggested [key takeaways about default risks].  

## Contributing

Contributions to this project are welcome! Feel free to submit issues, feature requests, or pull requests.

## Contact

For any questions or collaboration opportunities, feel free to connect via:

- [LinkedIn](https://www.linkedin.com/in/swathimuralisrinivasan/)  
- Email: `swathi.muralisrinivasan@gmail.com`  

---

**Happy Analyzing! 🚀**
