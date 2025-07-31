# Google-Ads-Datasets
This repository contains two versions of a Google Ads dataset:
- **Google Ads.cleaned.xlsx**: The cleaned version, processed using Excel to correct formats (e.g., Ad_Date to YYYY-MM-DD), fix errors (e.g., Conversion Rate as Conversions / Clicks), and handle some missing values.
- **GoogleAds_DataAnalytics_Sales_Uncleaned.csv**: The original, raw dataset with potential inconsistencies (e.g., misspellings like "data anaytics training") and missing data.

## Table of Contents
- [Google Ads Datasets](#google-ads-datasets)
- [About the Data](#about-the-data)
- [Usage](#usage)
- [Notes](#notes)
- [Contributions](#contributions)
- [Last Updated](#last-updated)

## About the Data
-**Source**: Collected from Google Ads campaigns in Hyderabad, India, covering November 2024.
- **Metrics**: Includes clicks, impressions, conversions, conversion rate, cost, leads, sale amount, ad date, location, device, and keyword.
- **Cleaning Process**: The cleaned file was processed using Excel on July 30, 2025, to standardize data and improve usability for analysis.

## Usage
- **Cleaned File**: Use Google Ads.cleaned.xlsx for immediate analysis in Excel, Python (with pandas), or R.
- **Uncleaned File**: Use GoogleAds_DataAnalytics_Sales_Uncleaned.csv for reference or to replicate the cleaning process.
- **Tools**: Open with spreadsheet software or data analysis tools.

## Notes
- The cleaned file contains 2,601 rows with standardized formats, while the uncleaned file retains the original 2,601 rows.
- Missing values (e.g., clicks, cost) are partially addressed in the cleaned version; further imputation may be needed.
- If the uncleaned file contains sensitive data, anonymize it before sharing.

## Contributions
- Feel free to fork this repository, suggest improvements, or add analysis.
- Create a pull request with your changes.

  ## Last Updated
- Last updated: July 31, 2025
