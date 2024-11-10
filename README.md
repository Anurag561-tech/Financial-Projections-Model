# Financial Projections Model

This project contains a set of three interconnected Excel files to project and analyze financial performance from 2022 to 2026. The files provide comprehensive insights into the **Income Statement**, **Balance Sheet**, and **Statement of Cash Flows**, covering revenue, costs, cash flow, and asset management.

## Table of Contents

- [Overview](#overview)
- [File Structure](#file-structure)
- [Interconnections](#interconnections)
- [Assumptions](#assumptions)
- [Dependencies](#dependencies)
- [Conclusion](#conclusion)

## Overview

This financial model is designed to support strategic planning by projecting financial statements and cash flow, covering all main aspects of financial health: profitability, liquidity, and operational efficiency. The files work together to provide a complete financial view for each forecasted year.

## File Structure

### 1. Income Statement
- **Purpose**: Projects revenue, costs, and net income.
- **Key Components**:
  - **Revenue**: Includes gross revenue and discounts to calculate net revenue.
  - **COGS**: Tracks direct costs like raw materials, fulfillment, and transaction fees.
  - **Operating Expenses**: Includes labor, marketing, and other operational costs.
  - **Profit Metrics**: Calculates gross profit, EBITDA, EBIT, EBT, and Net Income.
- **Outputs**: Net Income, Gross Profit Margin, and Net Income as a % of Revenue, which flow into other sheets.

### 2. Balance Sheet
- **Purpose**: Projects assets, liabilities, and equity over the period.
- **Key Components**:
  - **Assets**: Includes current assets (cash, accounts receivable) and non-current assets (net fixed assets).
  - **Liabilities**: Includes current liabilities (accounts payable, deferred revenue) and non-current liabilities (debt).
  - **Equity**: Common stock and retained earnings, linked to net income.
- **Outputs**: Cash, accounts receivable, and retained earnings, which integrate with other statements.

### 3. Statement of Cash Flows
- **Purpose**: Tracks cash flow from operating, investing, and financing activities.
- **Key Components**:
  - **Operating Activities**: Adjusts net income by changes in working capital (accounts receivable, payable, and deferred revenue).
  - **Investing Activities**: Captures capital expenditures on fixed assets.
  - **Financing Activities**: Reflects debt repayment and any net borrowings.
- **Outputs**: Net Cash Flow feeds into the cash balance in the Balance Sheet.

## Interconnections

The Excel files are interconnected as follows:
- **Income Statement**: Provides net income, which flows to **Retained Earnings** in the Balance Sheet and forms the base for **Operating Cash Flow** in the Statement of Cash Flows.
- **Balance Sheet**: Cash, accounts receivable, and payable changes affect the Statement of Cash Flows; non-current assets link with capital expenditure and depreciation.
- **Statement of Cash Flows**: Net cash flow impacts the cash balance in the Balance Sheet, while depreciation aligns with the Income Statement.

## Assumptions

This model relies on specific assumptions, such as:

- **Revenue Projections**: Based on units sold and price per unit. The model assumes a constant price per cup ($5) and incremental growth in units sold over the five years.
- **COGS and OpEx**: Calculated as a percentage of revenue. The model assumes that COGS and operating expenses grow in line with revenue increases, with fixed percentages applied to revenue for raw materials, labor, marketing, and other expenses.
- **Working Capital Ratios**: Accounts receivable, accounts payable, and deferred revenue are modeled as percentages of sales or costs.
  - Accounts Receivable: 1% of revenue
  - Accounts Payable: 2.3% of COGS
  - Deferred Revenue: 0.7% of revenue
- **Depreciation**: Depreciation is calculated on new fixed assets using the straight-line method based on their useful life:
  - Lemon Crusher (3 years)
  - Ice Machine (7 years)
  - Refrigerator (7 years)

## Dependencies

To work with these Excel files, ensure you have:
- **Microsoft Excel** or a compatible spreadsheet application that supports linked files and formulas.

## Conclusion

This 3-statement financial model provides a comprehensive, integrated view of projected financial performance over a five-year period. By linking the **Income Statement**, **Balance Sheet**, and **Statement of Cash Flows**, the model delivers insights into profitability, liquidity, and cash flow, enabling users to understand the impact of financial decisions across all key areas of the business.

This model is an essential tool for financial planning, budgeting, and analysis, allowing decision-makers to evaluate the financial health and sustainability of the organization with accuracy and strategic clarity.
