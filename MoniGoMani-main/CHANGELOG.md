# **Legacy ChangeLog / BackTest Results**:
*(Testing rough 2 week -4.83% market time period, default coin pairs, 75% Total Buy, 25% Total Sell)*
- v0.0.1 (20-03-2021 - Weight Table, RSI)  -15% profit...
- v0.1.0 (21-03-2021 - Buy/Sell Weight Table, Total Buy/Sell Signal %, ADX, Up/Down, MACD) -8% profit..
- v0.2.0 (22-03-2021 - SMA Death/Golden Cross, BugFixed Signals) -0.29% profit!
- v0.2.1 (23-03-2021 - Refactored to SMA Long Death/Golden Cross + EMA Long Death/Golden Cross) **1.15% profit!** :partying_face:
- v0.2.2 (23-03-2021 - SMA and EMA Short Death/Golden Cross) 1.15% profit
- v0.2.3 (24-03-2021 - Bollinger Band Re-Entrance after upward/downward breakout) 1.16% profit
- v0.3.0 (24-03-2021 - 0 weight = No Weighted Signal DataFrame entry)
- v0.3.1 (24-03-2021 - Turn On/Off all Weighted Signal DataFrame entries with a true/false)
- v0.3.2 (24-03-2021 - VWAP Cross) 1.24% profit
- v0.4.0 (25-03-2021 - Added HyperOpt for Weight Tables) **62.88% profit** (HyperOpt Result..)
- v0.4.1 (25-03-2021 - HyperOpt Params Real -> Integer, SortinoHyperOptLossDaily) **1322.78% profit** :sunglasses: :chart_with_upwards_trend:  (2 month HyperOpt Result, Mid January - Mid March)
- v0.4.2 (27-03-2021 - Main/Sub Plot Configurations for all indicators used)
- v0.5.0 (27-03-2021 - Rewrote Weight tables for Upward/Downward trends, Upward/Downward/Sideways trend detection & Auto table allocation or wait if sideways, Scrapped 0 weight = No Weighted Signal DataFrame entry, Scrapped the configurable Up/Down signals) **2,568.61% profit!** :partying_face: 
- v0.6.0 (28-03-2021 - Added Sideways Trend Detecting Buy/Sell Signal Weight Influence Tables & Checks - Updated HyperOpt file - Changed Test results from .txt to .log for better color code in VSCodium - Added .ignore file)
- v0.6.1 (28-03-2021 - Improved speed by reformatting a lot of & checks so more lazy evaluations will occur - Fixed .gitignore file)
- v0.6.2 (28-03-2021 - Added setting to Enable/Disable Trading when trend goes sideways)
- v0.6.3 (28-03-2021 - Enable/Disable Trading when Sideways made HyperOptable - Spoiler Alert, it should be False, for now...)
- v0.6.4 (29-03-2021 - BugFixed Debuggable Dataframe + Added (HyperOptable) Settings to Enable/Disable Buys/Sells for Upwards/Downwards trends too)
- v0.7.0 (31-03-2021 - Making Hyperopt Results Copy/Paste-able) 
- v0.7.1 (01-04-2021 - Added Total Overall Signal Importance Calculator)
- v0.7.2 (02-04-2021 - Huge code refactor - Changed original trend array to buy_params & sell_params - Removed unneeded debuggable_weighted_signal_dataframe from MoniGoManiHyperOpted)

This page has been made **legacy** in `v0.8.0`, for newer changelog notes please see the [Releases section](https://github.com/Rikj000/MoniGoMani/releases)