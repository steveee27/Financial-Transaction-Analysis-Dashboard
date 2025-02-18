# Financial Transaction Analysis Dashboard

## Table of Contents
1. [Background](#background)
2. [Dataset](#dataset)
3. [Preprocessing](#preprocessing)
4. [Dashboard Visualizations](#dashboard-visualizations)
    - [Filters](#filters)
    - [Visualizations](#visualizations)
5. [Results](#results)
6. [Contributors](#contributors)
7. [License](#license)

## Background

The goal of this project is to develop a comprehensive **Financial Transaction Analysis Dashboard** that enables a detailed understanding of transactional activities, customer account statuses, and other key financial trends. This dashboard helps the financial institution better assess its customer base, detect trends in account activity, and identify potential areas for improvement in services offered.

The dataset spans a range of metrics, including account types, transaction volumes, balance distributions, and more. With the rise of big data, the ability to visualize and interact with this data provides key insights that can guide strategic decisions for the business.

This project is developed as part of a larger **Data Science Competition**, where the goal is to provide actionable insights for businesses to improve operations based on transaction data analysis.

## Dataset

The dataset used in this project includes several files containing transaction-related data:
- **Account Details**: Information regarding account types, balance, and status.
- **Transactions**: Transaction history, including amounts, transaction types, and dates.
- **Holiday Data**: Information on public holidays to analyze trends based on holiday impact.

## Preprocessing

To prepare the dataset for analysis, several preprocessing steps were carried out:
1. **Handling Missing Data**: Missing values were either imputed using statistical methods or dropped based on their relevance.
2. **Data Merging**: Datasets related to transactions and account details were merged to create a complete view of the customer’s financial activity.
3. **Currency Normalization**: All transaction amounts were normalized to a common currency (IDR) to ensure uniformity across the data.
4. **Date Handling**: The date data was processed to create weekly, monthly, and daily aggregations, making it easier to observe trends over time.

## Dashboard Visualizations

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

- **Account Type Distribution**: A bar chart representing the count of different account types, helping to analyze the most popular account types among customers (e.g., **Credit**, **Deposits**, **Tabungan**).

- **Balance Per Day**: A line chart showing daily fluctuations in the total balance. This helps in understanding the daily impact of customer deposits and withdrawals.

- **Transaction Count Per Day**: A line chart showing the daily number of transactions. This helps visualize transaction activity over time and identify high-traffic days.

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
