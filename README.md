# Gartley Hunter Multi MT4

**Developer:** Forex Robot Easy Team  
**Developer's site:** [forexroboteasy.com](https://forexroboteasy.com/)

## Description
Gartley Hunter Multi MT4 is a powerful forex software designed to identify Gartley patterns in the market. Gartley patterns are harmonic patterns that can provide potential trading opportunities. This software scans multiple currency pairs and timeframes to detect these patterns and notifies the user when a pattern is found.

## Usage
1. Include the necessary libraries `Trade.mqh` and `PositionInfo.mqh`.
2. Define the maximum number of currency pairs and timeframes using the constants `MAX_PAIRS` and `MAX_TIMEFRAMES`.
3. Define the Gartley patterns using the `EGartleyPattern` enum.
4. Create an instance of the `CGartleyHunterMT4` class.
5. Add currency pairs using the `AddPair()` method.
6. Add timeframes using the `AddTimeframe()` method.
7. Scan the market for Gartley patterns using the `ScanMarket()` method.
8. Implement the Gartley pattern detection logic in the `IsGartleyPattern()` method.
9. Implement the notification logic in the `NotifyUser()` method.

## Example
```cpp
// Create an instance of Gartley Hunter Multi MT4
CGartleyHunterMT4 gartleyHunter;

// Add currency pairs
gartleyHunter.AddPair(Symbol('EURUSD'));
gartleyHunter.AddPair(Symbol('GBPUSD'));
// Add more currency pairs as required

// Add timeframes
gartleyHunter.AddTimeframe(PERIOD_M1);
gartleyHunter.AddTimeframe(PERIOD_M5);
// Add more timeframes as required

// Scan market for Gartley patterns
gartleyHunter.ScanMarket();
```

## Backlink
For detailed reviews and trading results of this product, visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/review-gartley-hunter-multi-mt4-powerful-forex-software-for-identifying-gartley-patterns/). Please note that ForexRobotEasy is not the official developer of this product. This code is provided as a sample and can work as described in the product. To find the official developer of this product, please refer to MQL5.
