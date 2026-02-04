# Stock Screening & Valuation Model

An Excel-based comparative valuation model for screening equity investments across multiple sectors using fundamental metrics and analyst consensus.

## Overview

This model analyzes stocks using a multi-factor approach that combines:
- **Valuation Ratios**: P/E, PEG, Price-to-Book
- **Dividend Metrics**: Dividend yield and sustainability
- **Growth Indicators**: Year-over-year growth and long-term projections
- **Analyst Consensus**: Price targets from Morningstar, Wells Fargo, and Yahoo Finance

## Features

- **Sector-Based Analysis**: Separate sheets for Communications Services, Technology, and Industrials sectors
- **Proprietary Scoring System**: Weighted composite scores across PEGY, P/5Y Target, and P/E metrics to rank investment opportunities
- **Expected Return Calculations**: Compares current price to average 5-year target values to identify potential upside
- **Buy Signal Generation**: Automated scoring combining valuation metrics with expected returns to generate investment recommendations

## Methodology

### Scoring Components

1. **PEGY Score**: P/E ratio divided by (Growth Rate + Dividend Yield) - identifies growth-adjusted value
2. **Price-to-Target Score**: Current price relative to 5-year analyst price targets
3. **P/E Score**: Standalone P/E evaluation against historical and sector benchmarks
4. **Expected Return Score**: Projected 5-year return based on analyst targets

### Buy Signal Logic

The model generates buy signals by combining:
- 50% weight on PEGY Score (valuation quality)
- 50% weight on Expected Return Score (upside potential)

Lower composite scores indicate stronger buy candidates.

## File Structure

- **Comm Services Sheet**: Analysis of communication and media stocks
- **Tech Sheet**: Technology sector screening
- **Industrials Sheet**: Industrial sector analysis

Each sheet contains standardized metrics enabling cross-sector comparison.

## Data Sources

- Stock prices and fundamentals: Real-time market data
- Analyst price targets: Morningstar, Wells Fargo, Yahoo Finance
- Growth projections: FinViz long-term growth estimates

## Use Cases

- Identifying undervalued stocks within specific sectors
- Comparing relative valuations across different industries
- Screening for investment candidates based on multiple fundamental criteria
- Benchmarking against analyst consensus for validation

## Author

Alexander Grant  
Economics & Data Science, Rutgers University
