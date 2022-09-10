# PineScripts

This is our Public repository where we contribute various PineScript indicators and stragegies we are developing over time. 

These pinescript can be easily added to your own TradingView platform.

How?

- Just go to the PineEditor tab below in your TradingView panel:

![image](https://user-images.githubusercontent.com/6500149/181534803-53615657-b91b-42b2-bd0b-4acc505cb985.png)

- Copy-paste the script into it.

- Save it with any name you prefer.

![image](https://user-images.githubusercontent.com/6500149/181536349-1a020ac2-4267-4307-827b-bbf453de3aa3.png)


- Click on "Add to Chart". That's all.

![image](https://user-images.githubusercontent.com/6500149/181537426-7c4fca03-5bb4-426f-85f1-7fde2b345f0b.png)


- Optionally you can also mark it as your favourite! How? Just click the Star:

![image](https://user-images.githubusercontent.com/6500149/181539030-899a0d65-d74d-4dcc-ae89-d1dbe1e844b7.png)



--------------
Twitter: @pradip_
TradingView username: [pradipandsuvra](https://in.tradingview.com/u/pradipandsuvra/ "pradipandsuvra")
Youtube: [Pradip Speaks](https://www.youtube.com/channel/UCXg6ZfqGJiidI-2o03a9jWQ "Pradip Speaks")


Enjoy.

---------------


## Brief Introduction of Various Scripts:

1. stragegy_ht_ce_pd_rsi_combined.ps : It's a stragegy works well with Heiken Ashi (HA) candles in 15m timeframe, a nice blending of multiple interesting indicators, combined as strategy. It has enough knobs to control it's strict (less trades, better accuracy) or relaxed (more trades, false positives).
2. stragegy_scalping_1m_HA_SMA_RSI.ps : It's a very simple Heiken Ashi (HA), 1m timeframe scalping stragegy works well for impatient fellows. 
3. my_candlestick.ps : It's plain, old Candlestick pattern identifier. Just that it can smartly detect not only single and double candles patterns, but also 3-candle patterns (e.g Morning Star, Evening Star). It marked all the patterns nicely with dotted boxes such that anyone new to this can use to learn it. It also provides control of which all patterns you're interested in (e.g you can only keep inside-candle and engulping patterns)
4. indicator_bb_dc_rsi_ssma_ema.ps: This is an indicator combining Bollinger Band, Donchian Channel, RSI, simple-smoothen moving average and exponential moving average. It has all you need .. you can just control which all suits your taste (e.g. Donchian with EMA or Bollinger Band with RSI).
5. RSI_based_support_resistance: This indicator tracks when the stock is overbought (RSI > 70) or oversold (RSI < 30), picks up the highest/lowest points of the OB/OS regions and draw resistance/support (or supply/demand) lines respectively.
6. Price_Action_in_Action:  This indicator, also in PineScript-v5 (not all warnings are cleaned up), has the various RSI based support/resistance, demand-supply and candlestick patterns (1-candle, 2-candles, 3-candles, everything) integrated into a single indicator. It also shows the strenght of the support/resistance by showing the number as tiny labels with count 1, 2. It has the volume indication also, if the current bar's volume is more than the last 20 bars volume-weigted-moving-average (VWMA). So one indicator is sufficient for your Price-Action trading.
7. Strategy_CMEMA_BraidFilter_ADXDI_combined: This script describes a strategy devised and shared by "Trade Domination" in his youtube channel on 08/22/2022. Video name: "I Found The Best 1 Minute Scalping Strategy That Will Change Your Life!". Link: https://www.youtube.com/watch?v=jGHXDDwjj8I. Link of the channel: https://www.youtube.com/c/TradeDomination. The strategy code is culminated by TradingView user @pradipandsuvra (Pradip-And-Suvra), amalgamating all the Indicators used (after converting everything in PineScript v5, originally Indicators are in v4). Indicators combined : 1. CM EMA Trend Bars by ChrisMoody, 2. Braid Filter by Mango2Juice (Robert Hill), 3. ADX and DI by BeikabuOyaji
8. Strategy_OLH: This is a simple strategy with Open-High-Low (OLH).






