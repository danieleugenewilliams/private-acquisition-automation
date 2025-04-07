# Private Acquisition Research Automation
## Use Case
This project automates small business acquisition research by scraping business-for-sale listings, using Generative AI with @tool-annotated functions to extract and analyze financial data (price, revenue, cash flow), and outputting structured JSON with insights.

## Problem
Manual research of business listings is slow, and Gen AI needs real data inputs to avoid fabrication, requiring tools for scraping and extraction.

## Solution
We use:
1. **Web Scraping Tool**: `@tool` to fetch listing data from BizBuySell (Class Element: Data Collection).
2. **Gen AI Extraction Tool**: `@tool` with Gemini to parse financials from scraped text (Class Element: Gen AI Extraction).
3. **Gen AI Analysis**: Agent analyzes extracted data, computes metrics, and generates insights (Class Element: Gen AI Application).
