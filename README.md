# Obie ADX Trading Robot

This code is a trading robot developed for the MT4 platform. It utilizes the ADX indicator to generate buy or sell signals based on the crossover of the DI and DI- values. The robot also includes a function to display buy signals using a blue arrow.

## How it Works

1. The `MonitorDI()` function fetches the DI and DI- values from the MT4 platform using the `iADX()` function.
2. The fetched values are then processed to determine the current market trend.
3. The `IsCrossover()` function fetches the current and previous DI and DI- values to check if there is a crossover.
4. If a crossover occurs, the `GenerateSignal()` function generates a buy signal, otherwise, it generates a sell signal.
5. The `DisplaySignal()` function takes the generated signal as input and displays a blue arrow on the chart to represent a buy signal.
6. The `OnTick()` function is the main function that executes the Obie ADX system. It calls the `MonitorDI()` function to monitor DI values, generates buy or sell signals based on the crossover using the `GenerateSignal()` function, and displays buy signals with blue arrows using the `DisplaySignal()` function.

## How to Use

To use this trading robot, follow these steps:

1. Install the MT4 platform.
2. Open the MT4 platform and login to your trading account.
3. Attach the Obie ADX Trading Robot to a chart of your choice.
4. The robot will monitor the DI and DI- values and generate buy or sell signals based on the crossover.
5. Buy signals will be displayed on the chart with blue arrows.

## Development Site

For more information about the Obie ADX Trading Robot, visit the [development site](https://forexroboteasy.com/forex-robot-review/obie-adx-review-optimizing-forex-with-buy-sell-signals/).

*Note: This code is provided as-is and does not guarantee any profits in trading. Use it at your own risk.*
