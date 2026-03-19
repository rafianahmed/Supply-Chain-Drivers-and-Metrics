# Supply Chain Driver & Financial Metrics Analyzer

A browser-based analytics tool that evaluates a company’s supply chain efficiency and financial performance using key operational and financial metrics.

The application allows users to upload financial statements, extract relevant data, compute important supply chain ratios, and generate visual dashboards and automated performance reports.

## Features

### Financial Statement Upload
Users can upload up to three financial statements:
- Income Statement
- Balance Sheet
- Cash Flow Statement or Supporting Document

Supported formats:
- PDF
- CSV
- TXT

The system extracts financial information and auto-fills the input fields. Manual input is also available if extraction is incomplete.

### Metrics Calculated
The tool calculates a combination of supply chain metrics and financial efficiency ratios:

#### 1. Little's Law
**Formula:** `I = D × T`

Where:
- `I` = Inventory / Work In Process
- `D` = Demand rate
- `T` = Flow time

This estimates the average inventory required to support operational throughput.

#### 2. Return on Equity (ROE)
**Formula:** `ROE = Net Income / Average Shareholder Equity`

Measures how effectively a firm generates profits from shareholder capital.

#### 3. Return on Assets (ROA)
**Formula:** `ROA = (Net Income + Interest Expense × (1 − Tax Rate)) / Average Total Assets`

Measures asset efficiency in generating profits.

#### 4. Accounts Payable Turnover (APT)
**Formula:** `APT = Cost of Goods Sold / Accounts Payable`

Measures how quickly a company pays its suppliers.

#### 5. Inventory Turnover (INVT)
**Formula:** `INVT = Cost of Goods Sold / Inventory`

Measures how efficiently inventory is sold or used.

#### 6. Accounts Receivable Turnover (ART)
**Formula:** `ART = Revenue / Accounts Receivable`

Measures how quickly the firm collects payments from customers.

#### 7. Property, Plant & Equipment Turnover (PPET)
**Formula:** `PPET = Revenue / PPE`

Measures how efficiently fixed assets generate revenue.

#### 8. Cash-to-Cash Cycle (C2C)
**Formula:** `C2C = Inventory Days + AR Days − AP Days`

Where:
- `Inventory Days = 365 / INVT`
- `AR Days = 365 / ART`
- `AP Days = 365 / APT`

Measures the time between paying suppliers and receiving customer payments.

## Visual Analytics
The application generates the following charts:
- Operational Efficiency Chart
- Cash Conversion Cycle Chart
- Financial Performance Chart
- Little's Law Visualization

## Automated Supply Chain Report
The system generates a written analysis including:
- Profitability assessment
- Operational efficiency interpretation
- Working capital analysis
- Cash conversion cycle evaluation
- Supply chain performance insights

## Technology Stack

### Frontend
- HTML
- CSS
- JavaScript

### Libraries
- Chart.js for data visualization
- PDF.js for financial statement text extraction

