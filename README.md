# Financial Transaction Analysis Dashboard

## Access the Dashboard

You can interact with the **Financial Transaction Analysis Dashboard** directly through the following link:  
[**View Tableau Dashboard**](https://public.tableau.com/views/FinancialTransaction_17398829010140/Dashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Table of Contents
1. [Background](#background)
2. [Dataset](#dataset)
3. [Preprocessing](#preprocessing)
4. [Dashboard Visualizations](#dashboard-visualizations)
    - [Filters](#filters)
    - [Visualizations](#visualizations)
5. [Results](#results)
6. [Future Work](#future-work)
7. [Contributors](#contributors)
8. [License](#license)

## Background

The goal of this project is to develop a comprehensive **Financial Transaction Analysis Dashboard** that enables a detailed understanding of transactional activities, customer account statuses, and other key financial trends. This dashboard helps the financial institution better assess its customer base, detect trends in account activity, and identify potential areas for improvement in services offered.

The dataset spans a range of metrics, including account types, transaction volumes, balance distributions, and more. With the rise of big data, the ability to visualize and interact with this data provides key insights that can guide strategic decisions for the business.

## Dataset

The dataset used in this project is composed of four key files:

1. **ref_proyeksi_funding_list_gl.xlsx**: This file contains information about financial accounts such as account types and balances. It also includes details on the types of accounts (e.g., savings or credit accounts) and their associated codes, which are essential for identifying financial statuses and activities.

2. **Ref_HariLibur.xlsx**: This file includes holiday data, marking specific dates as holidays (e.g., national holidays). It helps to examine how holidays impact transactions, providing a view into trends and behavior patterns around special dates.

3. **deposits.xlsx**: This dataset provides detailed information on deposit accounts, including balance amounts, account types, and target amounts. It also contains crucial account metadata such as status (active, closed) and associated numbers for debit accounts.

4. **daily_summary_gl_balance.xlsx**: This file contains daily transaction summaries, including data on account balances, currencies, and the amounts in both local and equivalent currencies. It also tracks the snapshot dates of transactions and is essential for understanding the daily movement of funds and balances.

## Preprocessing

To prepare the dataset for analysis, several preprocessing steps were carried out:
1. **Handling Missing Data**: Missing values were either imputed using statistical methods or dropped based on their relevance.
2. **Data Merging**: Datasets related to transactions and account details were merged to create a complete view of the customer’s financial activity.
3. **Currency Normalization**: All transaction amounts were normalized to a common currency (IDR) to ensure uniformity across the data.
4. **Date Handling**: The date data was processed to create weekly, monthly, and daily aggregations, making it easier to observe trends over time.

## Dashboard Visualizations

![image](https://github.com/user-attachments/assets/3435c9a7-a51b-4561-96cb-87346faecc11)

The dashboard provides an interactive platform to explore key insights from the data through various visualizations. The dashboard is created using **Tableau** and incorporates several types of visual elements for intuitive exploration.

### Filters
To make the dashboard interactive, the following filters were added:
- **Date**: Allows the user to filter data by specific time periods, such as days, weeks, or months.
- **Account Type**: Enables filtering by the type of account (e.g., **Savings**, **Credit**, **Deposits**, **Giro**).
- **Account Status**: Filters the data based on the account's status (e.g., **Active**, **Closed**, **Approved**).

These filters provide users with the flexibility to drill down into the data, uncovering trends and anomalies specific to certain account types, statuses, or time frames.

### Visualizations
The following visualizations are included in the dashboard:

- **Overall Transaction Overview**: Displays key metrics such as the total number of transactions, total inflow and outflow of funds, and the total number of accounts.
  
- **Account Status Distribution**: A pie chart showing the distribution of accounts by their status (**Active**, **Closed**, **Approved**). This helps assess the health of the bank’s accounts.
  
- **Balance Distribution**: A bar chart illustrating the number of customers in different balance ranges, such as **(0 - 1K)**, **(1K - 2K)**, etc. This can help identify customer segments based on wealth.

- **Transaction Calendar**: This heatmap-style calendar visualizes the number of transactions per week, highlighting peaks or valleys in transaction volumes across different days of the week. This is useful for detecting trends based on weekdays or specific weeks.

- **Account Type Analysis**: A bar chart showing the count of different account types, helping to analyze the most popular account types among customers (e.g., **Credit**, **Deposits**, **Tabungan**).

- **Balance Per Day**: A line chart showing daily fluctuations in the total balance. This helps in understanding the daily impact of customer deposits and withdrawals.

- **Transaction Count Per Day**: This visualization shows the daily number of transactions. It helps visualize transaction activity over time and identify high-traffic days.

## Results

The dashboard provides a clear overview of the customer transactions, balance distributions, and account types. Some key findings include:
- A large proportion of accounts are **active**, while a smaller percentage remains **approved** or **closed**.
- The **balance distribution** shows that most customers fall in the **low to mid-range balance** categories.
- The **transaction calendar** revealed that transactions peak during certain weekdays, with Fridays and Saturdays seeing higher transaction volumes.
  
This analysis can help the bank understand the distribution of their customers’ financial behaviors and adjust strategies accordingly, such as targeting higher-value customers or optimizing transaction timing.

## Future Work

- **Enhance Prediction Capabilities**: Adding predictive analytics to the dashboard to forecast future transaction volumes or account balance trends.
- **Real-Time Data Integration**: Integrating real-time transaction data to continuously update the dashboard and provide live insights.
- **User Customization**: Allowing customers or account managers to customize views and receive alerts based on certain thresholds or conditions.

## Contributors

- **Steve Marcello Liem**
- **Matthew Lefrandt**
- **Marvel Martawidjaja**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

This version of the **README** now includes the description of the four datasets, and the link to the **Tableau dashboard** is placed at the beginning to catch users' attention. Let me know if any further changes are needed!
