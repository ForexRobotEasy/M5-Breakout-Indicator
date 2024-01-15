README

M5 Breakout Indicator

Developer: Forex Robot Easy Team
Site: forexroboteasy.com

## Description
This code is a sample implementation of the M5 Breakout Indicator. The indicator checks for breakouts in the market and places buy orders accordingly. It calculates the stop loss and take profit levels based on the previous high and low prices. The breakout period and risk percentage for stop loss can be adjusted as input parameters.

## How it works
1. The code initializes by setting the necessary input parameters and global variables.
2. On each new bar formation, the code checks if a breakout has occurred.
3. If a breakout is detected, the code calculates the stop loss and take profit levels based on the previous high and low prices and the risk percentage.
4. It then places a buy order with the calculated stop loss and take profit levels.
5. The code updates the previous high and low prices and the last bar time for future calculations.

## Input Parameters
- BreakoutPeriod: The breakout period in minutes. Default value is 20 minutes.
- RiskPercentage: The risk percentage for stop loss. Default value is 2.0%.

## Custom Function
- NormalizeDouble: A custom function to calculate the normalized double value.

## Notes
- This code is a sample implementation and not the official product.
- For detailed reviews and trading results of the official M5 Breakout Indicator, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/m5-breakout-indicator-review-trusted-forex-software/).
- The official developer of this product can be found using MQL5.

For more information and support, please visit [forexroboteasy.com](https://forexroboteasy.com/).
