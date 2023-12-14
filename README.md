# Di Napoli Squat MT4 ReadMe

## Introduction
Di Napoli Squat MT4 is a powerful indicator developed by the Forex Robot Easy Team. It is designed to identify Fibonacci support and resistance levels in the Forex market. This ReadMe file provides an overview of the code and explains how the indicator works.

## Indicator Constants
The following constants are defined in the code:
- `INDICATOR_NAME`: The name of the indicator, which is set to 'Di Napoli Squat'.
- `INDICATOR_VERSION`: The version number of the indicator, which is set to '1.0'.
- `INDICATOR_AUTHOR`: The author of the indicator, which is set to 'Forex Robot Easy Team'.

## Indicator Parameters
The indicator has the following parameters:
- `Period`: The period for calculating Fibonacci levels, with a default value of 14.
- `RetracementLevel`: The Fibonacci retracement level for identifying support/resistance, with a default value of 0.618.
- `StopLossRatio`: The ratio of stop loss to take profit, with a default value of 0.01.

## Global Variables
The code defines the following global variables:
- `g_StopLoss`: The stop loss level.
- `g_TakeProfit`: The take profit level.

## Indicator Init
The `OnInit` function is called when the indicator is initialized. It performs the following tasks:
- Sets the indicator title and parameters.
- Sets the indicator buffers.
- Sets the indicator style and color.

## Indicator Start
The `OnCalculate` function is called for each new tick. It calculates the Fibonacci levels, determines the stop loss and take profit levels, and plots them on the chart.

## Product Description
Di Napoli Squat MT4 is a powerful indicator developed by the Forex Robot Easy Team. It is designed to identify Fibonacci support and resistance levels in the Forex market. The indicator uses a period of 14 and a Fibonacci retracement level of 0.618 to calculate the support and resistance levels. It also allows users to customize the stop loss ratio.

To use the indicator, simply attach it to a chart in MetaTrader 4 and adjust the parameters as desired. The indicator will plot the stop loss and take profit levels on the chart, making it easy to identify potential trade entry and exit points.

Please note that ForexRobotEasy is not the official developer of this product. We are only providing a sample code that can work as described in this product. To find the official developer of this product, please refer to the MQL5 community.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/review-di-napoli-squat-mt4-a-powerful-indicator-for-fibonacci-support-and-resistance/).
