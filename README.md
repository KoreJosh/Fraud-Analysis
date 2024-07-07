# Fraudulent Transactions Analysis
![](https://github.com/KoreJosh/Fraudulent-Transactions-Analysis/blob/main/fraud1.jpg)


# Introduction
The following documentation provides a detailed analysis of fraudulent transactions for the year 2023-2024. This analysis aims to identify trends, patterns, and insights into the types and volumes of fraudulent activities, helping financial institutions and businesses enhance their fraud detection and prevention mechanisms.

# Data Collection 
The data was sourced using chatgpt to prompt a fraudulent transaction data, which required adquate cleaning and preprocessing.
Therefore the data was prepared using a python code and saved locally.

# Data Cleaning and processing
![](https://github.com/KoreJosh/Fraudulent-Transactions-Analysis/blob/main/fraud1.png)

The data, haven been saved as an excel document was open using Microsoft Excel and transformed using power query.

![](https://github.com/KoreJosh/Fraudulent-Transactions-Analysis/blob/main/fraud0.png)

Using conditional formatting the time of transaction was sorted into 'Moring', 'Afternoon', "Evening', 'Night'.
Duplicated values and nulls values were deleted .
The date columns were duplicated twice to generate the month and year varibles separetely.
Checked if the data columns were in the right type (date was in the datetime format, transaction type is in the string fprmat, transacton amount in the number format)

# Dashboard Overview
![](https://github.com/KoreJosh/Fraudulent-Transactions-Analysis/blob/main/Fraud.png)

The Fraud Transaction Dashboard visualizes data related to fraudulent transactions across various dimensions, including transaction type, merchant, location, and time. The dashboard components are as follows:

- Fraudulent Transactions by Merchant: 
  The bar chart shows the number of fraudulent transactions for different merchants. It helps identify which merchants are most affected by fraudulent activities.
- Fraudulent Transactions by Location:
  The bar chart indicates the number of fraudulent transactions occurring in different locations, providing insights into geographical fraud trends.
- Fraudulent Transactions by Year:
  This line chart tracks the number of fraudulent transactions month-by-month for the period from July 2023 to July 2024, highlighting trends over time.
- Fraudulent Transactions by Transaction Type:
  This pie chart displays the distribution of fraudulent transactions across different transaction types (Deposit, Purchase, Transfer, Withdrawal), allowing for an understanding of which 
  types are most susceptible to fraud.
- Fraudulent Transaction Amount by Transaction Type:
  This bar chart shows the total amount of money involved in fraudulent transactions, categorized by transaction type.
- Transaction Amount by Transaction Type:
  This bar chart presents the overall transaction amounts for different transaction types, providing a comparison between the fraudulent and total transaction amounts.
  
## Detailed Analysis

### Fraudulent Transactions by Merchant:

Merchants such as "Smith-Anderson," "Andrews Inc," and "Smith LLC" show a higher number of fraudulent transactions compared to others.
This information is crucial for these merchants to tighten their security measures and investigate potential vulnerabilities.

### Fraudulent Transactions by Location:

Locations like "Boston," "Houston," and "San Francisco" report a higher frequency of fraudulent activities.
This geographic analysis can guide local authorities and financial institutions in these areas to implement stronger fraud detection systems.

### Fraudulent Transactions by Year:

The trend line indicates fluctuations in the number of fraudulent transactions, with peaks observed in November 2023, January 2024, and May 2024.
Notably, there is a significant drop in fraudulent transactions in July 2024, which might be indicative of effective fraud prevention measures being implemented.

### Fraudulent Transactions by Transaction Type:

The pie chart reveals that withdrawals and transfers constitute the highest percentage of fraudulent transactions, at 27.44% and 26.53% respectively.
Purchases and deposits also represent significant portions, suggesting that all transaction types are susceptible to fraud.

### Fraudulent Transaction Amount by Transaction Type:

Withdrawals account for the highest fraudulent transaction amount, totaling $1.20M, followed by transfers ($1.13M), purchases ($1.06M), and deposits ($1.02M).
This indicates that fraudulent withdrawals involve larger sums of money compared to other transaction types.

### Transaction Amount by Transaction Type:

The bar chart shows that the overall transaction amounts are quite high for all types, with purchases and withdrawals leading at $23M each, and transfers and deposits at $22M each.
Comparing these amounts with the fraudulent transaction amounts highlights the scale of the fraud issue.

# Conclusion & Recommendation
The 2023-2024 Fraudulent Transaction Analysis reveals significant insights into the nature and patterns of fraudulent activities across various dimensions. Key findings include:

1. High-Risk Merchants and Locations: Certain merchants and locations exhibit higher instances of fraudulent transactions, indicating targeted areas for enhanced security measures.
2. Transaction Types: Withdrawals and transfers are the most common types of fraudulent transactions, both in frequency and monetary value.
3. Trends Over Time: The analysis shows fluctuations in fraudulent activities, with notable peaks and a significant drop in July 2024, suggesting effective fraud prevention measures may have been implemented during this period.

   ## Recommendation
Based on the findings, the following recommendations are proposed to mitigate and prevent fraudulent transactions:

1. Enhanced Security for High-Risk Merchants and Locations:

- Implement additional authentication and verification processes for transactions involving high-risk merchants and locations.
- Conduct regular audits and provide targeted training to merchants in these areas to recognize and prevent fraud.

2. Focus on High-Risk Transaction Types:

- Strengthen monitoring and detection systems for withdrawals and transfers, using advanced machine learning algorithms to identify suspicious patterns.
- Introduce transaction limits and multi-factor authentication for large withdrawals and transfers.

3. Continuous Monitoring and Adaptation:

- Establish a dedicated fraud detection team to continuously monitor transaction data and adapt strategies based on emerging fraud patterns.
- Invest in real-time analytics and automated alert systems to quickly respond to potential fraudulent activities.

4.Collaborative Efforts:

- Foster collaboration between financial institutions, merchants, and law enforcement agencies to share information and best practices on fraud prevention.
- Participate in industry-wide initiatives and forums to stay updated on the latest fraud trends and prevention techniques.
- 
By implementing these recommendations, organizations can significantly reduce the risk of fraudulent transactions, protect their financial assets, and maintain customer trust.







