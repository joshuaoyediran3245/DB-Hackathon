# DB-Hackathon
### Joshua Oyediran: Contributed Work

#### Overview

In this project, I conducted extensive research on various API networks to identify reliable sources for financial data. One of the primary APIs explored was the `yfinance` API, which provides timely and relevant information regarding the financial reports of publicly traded companies, including Initial Public Offerings (IPOs).

When a user inputs a specific company ticker symbol, the program retrieves and displays critical financial metrics, including Net Income Per Share, Revenue Per Share, Free Cash Flow Per Share, and Tangible Book Value Per Share, all on a quarterly basis. This financial data is structured and presented using a HashMap data structure, allowing for efficient retrieval and clear organization of the information.

#### Parameters

Users can input any ticker symbol of their choice to obtain the corresponding financial metrics. The data displayed is limited to quarterly reports and can only be retrieved for the past two years. This time restriction ensures that users receive up-to-date information, reflecting the most recent financial performance of the selected companies.


Financial Data Retriever

Overview

This Python script retrieves and displays key financial metrics for publicly traded companies using the Yahoo Finance API through the yfinance library. Users can input a specific ticker symbol, and the script will output quarterly financial data including:

Revenue Per Share
Net Income Per Share
Free Cash Flow Per Share
Tangible Book Value Per Share


Features

User-friendly input for ticker symbols.
Fetches quarterly financial data, including income statements and cash flow metrics.
Handles missing data gracefully, ensuring the script runs smoothly even if certain financial metrics are unavailable.
Outputs key financial metrics per share for the specified company.


Prerequisites

Python 3.x
yfinance library
