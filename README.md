# XCap Trader

**Developer:** Forex Robot Easy Team

**Developer's Site:** [forexroboteasy.com](https://forexroboteasy.com/)

---

This code represents the implementation of XCap Trader, a hybrid scalping robot designed for hedge accounts. It uses the MQL4 language and is compatible with the MetaTrader 4 platform.

## Functionality

The XCap Trader code includes the following functionality:

1. **Include necessary libraries:** The required libraries for trading and array operations are imported.

2. **Define constants:** Several constants are defined, such as the maximum trade count, maximum lot size, stop loss, and take profit.

3. **Define global variables:** Global variables for the `CTrade` and `CArrayObj` objects are declared.

4. **Initialization function:** The `OnInit()` function is called when the code is initialized. It initializes the trade object with deviation and magic number values, and resizes and frees the trades array.

5. **Deinitialization function:** The `OnDeinit()` function is called when the code is deinitialized. It closes all open trades by iterating through the trades array and calling the `Close()` method.

6. **Entry point function:** The `OnTick()` function is called on every tick of the market. It checks if the number of open trades is less than the maximum trade count. If so, it generates a random lot size and calculates the stop loss and take profit levels. It then opens a new trade in both the buy and sell directions using the `Buy()` and `Sell()` methods of the trade object. The trade tickets are added to the trades array.

## Product Description

XCap Trader is a hybrid scalping robot developed by the Forex Robot Easy Team. It is designed specifically for hedge accounts and operates on the MetaTrader 4 platform.

This expert advisor aims to generate profits by taking advantage of short-term market movements. It utilizes a combination of scalping strategies to identify and execute trades in both the buy and sell directions.

Some key features of XCap Trader include:

- Hybrid scalping strategy: The robot incorporates multiple scalping strategies to identify optimal entry and exit points in the market.

- Hedge account compatibility: XCap Trader is specifically designed for hedge accounts, allowing for simultaneous buy and sell trades.

- Flexible trade management: The expert advisor includes options to set stop loss and take profit levels, providing risk management capabilities.

- Easy customization: Traders can adjust parameters such as maximum trade count, lot size, stop loss, and take profit to suit their individual trading preferences.

Please note that Forex Robot Easy is not the official developer of XCap Trader. We have provided this sample code to showcase the functionalities of the product. For detailed reviews and trading results, please visit the official developer's website using the following link: [XCap Trader Review](https://forexroboteasy.com/forex-robot-review/xcap-trader-review-hybrid-scalping-robot-for-hedge-accounts/).

To obtain the official version of XCap Trader or for any further inquiries, please refer to the official developer's website or the MQL5 marketplace.
