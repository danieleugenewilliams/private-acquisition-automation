# Private Acquisition Research Automation
## Use Case
This project automates small business acquisition research by parsing OCR’d PDF text from business-for-sale listings, using Generative AI with @tool stubs to extract and analyze financial data (price, revenue, cash flow), and outputting structured JSON with insights.

## Problem
Manual research of business listings is slow, and web scraping faces blocks; parsing PDF text provides a reliable data source for Gen AI analysis.

## Solution
We use:
1. **Data Collection**: Read PDF text from Kaggle input (Class Element: Data Collection).
2. **Gen AI Extraction Tool**: `@tool extract_financials` stub to parse financials (Class Element: Gen AI Extraction).
3. **Gen AI Analysis**: Agent analyzes extracted data, computes metrics, and generates insights (Class Element: Gen AI Application).
