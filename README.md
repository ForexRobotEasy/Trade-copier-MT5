# Trade Copier MT5

This is a trade copier code developed in MQL5 language. It allows you to copy trades from a source account to multiple destination accounts. The code is designed to be used in MetaTrader 5 (MT5) platform.

## Installation

1. Copy the code provided in this file.
2. Open your MetaEditor in MT5 platform.
3. Create a new Expert Advisor (EA) file.
4. Paste the copied code into the new EA file.
5. Save the file with a desired name.

## Configuration

Before running the trade copier, you need to configure the following variables:

- `sourceAccountNumber`: This variable should be set to the account number of the source account from where you want to copy trades.
- `destinationAccountNumbers`: This array variable should be set to an array of account numbers of the destination accounts where you want to copy trades. You can add as many account numbers as needed, separated by commas.
- `lotSize`: This variable determines the lot size for the copied trades. By default, it is set to 0.01.
- `executionSpeed`: This variable defines the trade execution speed in milliseconds. By default, it is set to 1000ms (1 second).

## Usage

Once you have configured the variables, you can run the trade copier by following these steps:

1. Compile the EA file in MetaEditor.
2. Open the MT5 platform.
3. Attach the compiled EA to a chart.
4. Make sure the AutoTrading option is enabled in the platform.
5. The trade copier will start copying trades from the source account to the destination accounts.

## Important Information

- The trade copier uses the `Trade` library, so make sure you have it included in your MT5 platform.
- The code is designed to copy the latest trade from the source account to the destination accounts. It does not copy pending orders.
- The trade copier executes trades using the same parameters as the source trade, except for the lot size which is set according to the `lotSize` variable.
- The code includes error handling to log any trade errors that may occur.

## Development Site

This code was developed by [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/trade-copier-mt5-review-real-results-of-professional-forex-trader/).
