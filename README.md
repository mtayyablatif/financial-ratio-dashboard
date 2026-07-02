# 📊 Financial Ratio Dashboard

An Excel-based financial analysis dashboard that transforms raw financial statement data into an automated assessment of a company's financial health.

---

## Overview

This project automates the calculation and interpretation of key financial ratios from a company's financial statements.
Instead of manually calculating ratios every time a new company is analyzed, users simply enter the financial statement figures once. The workbook automatically computes all ratios, evaluates them against predefined benchmarks, and produces an overall financial health assessment.

---


### Dashboard
<img width="637" height="387" alt="Dashboard" src="https://github.com/user-attachments/assets/d955c9ef-3266-4552-b130-527b1a5964aa" />



### Master Input Sheet
<img width="957" height="365" alt="MasterSheet" src="https://github.com/user-attachments/assets/533860e9-2aa6-4702-baa3-318b8f3a8326" />


## Features

* Calculates **19 financial ratios**
* Covers **5 major financial analysis categories**

  * Liquidity
  * Profitability
  * Efficiency
  * Leverage
  * Investor
* Automatic **Good / Average / Weak** evaluation for every ratio
* Category-level financial health assessment
* Overall company financial health verdict
* Radar chart for category comparison
* Profit & Loss structure visualization
* Structured ratio log for multi-company comparison
* Fully formula-driven (no duplicate data entry)

---

## Workbook Structure

### 📄 Master

The only worksheet requiring user input.
Enter financial statement figures for:

* Balance Sheet
* Income Statement
* Cash Flow Statement

All other worksheets update automatically using named ranges and Excel formulas.

---

### 📈 Ratio Worksheets

Separate worksheets calculate ratios for each category:

* Liquidity
* Profitability
* Efficiency
* Leverage
* Investor

Each ratio includes:

* Formula calculation
* Benchmark value
* Automated performance rating

  * Good
  * Average
  * Weak

---

### 📊 Dashboard

The dashboard consolidates all ratio results into an executive summary.

It includes:

* Category performance
* Overall financial health status
* Ratio score summary
* Profit & Loss structure chart
* Financial health radar chart

Overall verdicts are displayed as:

* ✅ Strong
* ⚠️ Moderate (Mixed Signals)
* ❌ Weak (Needs Attention)

---
## Scoring Methodology

Each ratio is classified as:

* Good
* Average
* Weak

Category performance is determined using the following rules:

| Result   | Logic                                      |
| -------- | ------------------------------------------ |
| Strong   | 60% or more ratios are rated Good          |
| Moderate | Good + Average ratings together exceed 60% |
| Weak     | Otherwise                                  |

The same methodology is applied across all 19 ratios to generate the company's overall financial health verdict.

---

## How to Use

1. Open the **Master** worksheet.
2. Replace the sample financial statement figures with the company's actual data.
3. Review the automatically updated ratio worksheets.
4. Open the **Dashboard** to view the financial health assessment.
5. Copy the Dashboard score values (Paste Special → Values Only) into a new row of **Ratio_Log** to build a historical comparison dataset.

---

## Skills Demonstrated

* Financial Statement Analysis
* Ratio Analysis
* Credit Analysis Concepts
* Excel Formula Engineering
* Named Ranges
* Dashboard Design
* Data Validation
* Financial Modeling
* Business Reporting
* Data Visualization

---


