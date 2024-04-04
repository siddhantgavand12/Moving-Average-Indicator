# Moving Average Indicator

## Description
The Moving Average Indicator project is built using Python and utilizes the `yfinance`, `pandas`, and `matplotlib` libraries. It generates buy and sell signals based on the Moving Average Convergence Divergence (MACD) indicator. The logic for generating signals is as follows: when the 20-day Exponential Moving Average (EMA) crosses above the 50-day EMA, a buy signal is generated, and when the 20-day EMA crosses below the 50-day EMA, a sell signal is generated. These signals are visually represented by green and red arrows, respectively, on the price chart.

## Table of Contents
- [Description](#description)
- [Requirements](#requirements)
- [Installation](#installation)
- [Setup](#setup)
- [Output Image](#output-image)

## Requirements
To run this project, you need the following Python libraries installed:
- `yfinance`
- `pandas`
- `matplotlib`

## Installation
You can install the required libraries using pip:

  ```bash
  pip install yfinance pandas matplotlib

Usage
1.
