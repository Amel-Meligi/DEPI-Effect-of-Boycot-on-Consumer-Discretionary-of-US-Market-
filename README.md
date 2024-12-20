# Effect of Boycott on Consumer Discretionary in USA

This project assesses the impact of boycotts on Consumer Discretionary stocks, specifically McDonald's (MCD) and Starbucks. This analysis helps investors, analysts, and businesses understand the potential financial risks associated with boycotts.

## Key Performance Indicators (KPIs)

To effectively measure the impact of boycotts, we focus on the following KPIs:

*   **Stock Return:** Tracking stock returns for MCD and Starbucks, comparing them to historical trends and benchmarks to identify potential investment opportunities or risks.
*   **Revenue:** Analyzing quarterly and annual revenue figures to assess the direct impact of boycotts on sales.
*   **Competitor Performance:** Tracking competitor performance in the same industry to isolate the impact of boycotts on the specific companies.

## Profitability Ratios

*   **Gross Margin Ratio:** Measures the percentage of revenue remaining after accounting for the cost of goods sold. A decline could indicate increased costs or an inability to pass on price increases due to the boycott.

    `Gross margin ratio = Gross profit / Net sales`

*   **Operating Margin Ratio:** Calculates the percentage of revenue remaining after deducting operating expenses. A drop might suggest difficulty controlling costs or a decline in sales.

    `Operating margin ratio = Operating income / Net sales`

*   **Return on Equity (ROE):** Measures the profitability of a company's equity investments. A decrease could indicate a compromised ability to generate profits from shareholders' investments.

    `Return on equity ratio = Net income / Shareholder’s equity`

## Liquidity Ratios

*   **Current Ratio:** Assesses a company's ability to meet short-term obligations. A decline might suggest liquidity challenges due to decreased cash inflows or increased short-term liabilities.

    `Current ratio = Current assets / Current liabilities`

*   **Cash Ratio:** Provides a more conservative liquidity measure, focusing on cash and cash equivalents. A decline could indicate difficulty maintaining sufficient cash reserves.

    `Cash ratio = Cash and Cash equivalents / Current Liabilities`

*   **Operating Cash Flow Ratio:** Measures a company's ability to generate cash from core operations. A decrease might suggest the boycott is affecting cash flow generation.

    `Operating cash flow ratio = Operating cash flow / Current liabilities`

## Leverage Ratios

*   **Debt Ratio:** Measures the proportion of a company's assets financed by debt. An increase could indicate heavier reliance on debt, which can be risky during a boycott.

    `Debt ratio = Total liabilities / Total assets`

*   **Debt-to-Equity Ratio:** Compares a company's debt to its equity. A rise suggests taking on more debt relative to equity, increasing financial risk.

    `Debt to equity ratio = Total liabilities / Shareholder’s equity`

## Data Sources and Collection

We utilize the following data sources:

*   **News and Websites:** For images, company data, and reasons for boycotts.
*   **Financial Data:** Yahoo Finance.
*   **yfinance (Python Library):** Used for efficient extraction of historical stock prices, balance sheet, and income statement data.

## Data Cleaning and Preparation

Collected data undergoes thorough cleaning and preparation:

*   **Data Validation:** Ensuring data accuracy and consistency.
    *   Changing the data type.
    *   Scanning data for inconsistencies.
*   **Data Transformation:** Converting data into a suitable format for analysis.
    *   Appending different tables into one.
*   **Data Standardization:** Handling missing values and outliers.

## Analytical Techniques

We employ a combination of statistical and analytical techniques:

*   **Event Study Analysis:** Assessing the impact of specific events (e.g., boycott announcements) on stock returns.
*   **Industry Benchmarking:** Comparing the KPIs of boycotted companies to industry peers to assess the relative impact of the boycott.
*   **Trend Analysis:** Analyzing changes in KPIs over time to identify trends and patterns emerging from the boycott.
