# Withdrawal Rate Calculator

An interactive historical retirement withdrawal calculator using monthly real returns for:

- S&P 500 total return
- Treasury-like bond returns approximated from long rates, CPI, and selected duration

The calculator tests rolling historical retirement start months from July 1923 through June 2023. It supports a simple mode for core assumptions and an advanced mode for spending rules, withdrawal timing, rebalancing cadence, bond duration, start-date filters, CAPE filters, percentile outcomes, and worst-path analysis.

## Data Source

Data comes from the Shiller-style S&P 500 monthly dataset mirrored by DataHub:

https://datahub.io/core/s-and-p-500

Stock returns are month-over-month real total returns approximated from real price plus one month of real dividends. Bond returns are an approximation, not a dedicated bond total-return series.

This is historical stress testing, not a forecast or financial advice.
