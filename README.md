# Private Acquisition Research Automation
## Use Case
This project automates research on small businesses for sale by scraping data from BizBuySell, extracting key details like selling price, revenue, cash flow/EBITDA, and description to aid acquisition analysis.

## Problem
Manually researching small business listings is time-consuming, requiring aggregation of financial and descriptive data from sites like BizBuySell.

## Solution
We use:
1. **Web Scraping**: `requests` and `beautifulsoup4` to fetch and parse BizBuySell listing pages.
2. **Data Extraction**: Pulls key fields (price, revenue, cash flow, description) into structured JSON.
3. **Output**: Saves results to `/kaggle/working/business_listings.json` for analysis.
