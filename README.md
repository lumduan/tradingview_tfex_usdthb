# USDTHB TFEX Strategy

This repository contains a Pine Script™ strategy for trading USD/THB on TFEX. The strategy uses pivot points to determine entry and exit points for long and short trades.

## Strategy Overview

The strategy identifies swing highs and swing lows to determine potential entry points for long and short trades. It also calculates monthly and yearly profit and loss (P&L) percentages and displays them in a table on the chart.

## Parameters

- **RISK_FREE_RATE**: The risk-free rate used for calculating the Sharpe ratio.
- **HIGH_PRICE_BAR_COLOR**: The color of the bar when a high price is detected.
- **LOW_PRICE_BAR_COLOR**: The color of the bar when a low price is detected.
- **HIGH_PRICE_BAR_WIDTH**: The width of the bar when a high price is detected.
- **LOW_PRICE_BAR_WIDTH**: The width of the bar when a low price is detected.
- **CONTACT_PER_ORDER**: The number of contracts per order.
- **COMMISSION_PRICE**: The commission price per contract in THB.
- **leftBars**: The number of bars to the left for pivot calculation.
- **rightBars**: The number of bars to the right for pivot calculation.
- **prec**: The precision of return percentages.
- **show_table**: Boolean to show or hide the P&L table.

## Usage

1. Open TradingView and create a new Pine Script™ strategy.
2. Copy and paste the code from `usd_thb_tfex_strategy.pine` into the Pine Script™ editor.
3. Adjust the input parameters as needed.
4. Add the strategy to your chart to start using it.

## Table Colors

- **TABLE_HEADER_COLOR**: The background color of the table header.
- **TABLE_INDEX_COLOR**: The background color of the table index.
- **TABLE_CELL_COLOR**: The background color of the table cells.
- **TABLE_YEAR_CELL_POSITIVE_COLOR**: The background color of the table cells for positive yearly P&L.
- **TABLE_YEAR_CELL_NEGATIVE_COLOR**: The background color of the table cells for negative yearly P&L.

## License

This Pine Script™ code is subject to the terms of the Mozilla Public License 2.0. For more details, see [Mozilla Public License 2.0](https://mozilla.org/MPL/2.0/).

© lumduan
