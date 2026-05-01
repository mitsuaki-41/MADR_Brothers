# MADR_Brothers
Customizable multi-timeframe MADRs (Moving Average Deviation Rates) based Expert-Advisor (EA) for Metatrader5 (MT5) algorithmic trading, optional grid-mode and martingale-mode is also available.  
  
----Basic  Set Up ----  
Trend following = true:
&emsp;Long MADR Bullish, MADR Oversold -> Buy, Long MADR Bearish MADR Overbought -> Sell.
Trend following = false:"
&emsp;Long MADR Bullish MADR Overbought -> Buy, Long MADR Bearish, MADR Oversold -> Sell.
  
---- Lot Calculation ----  
Initial Lot = Equity * Coefficient Value * / 1000  
The Maximum Initial Lot Size is Calculated based on the Lot Multiplier, Loss Count, Division Value.  
  
<img alt="preview1" src="https://github.com/mitsuaki-41/MADR_Brothers/blob/main/madr_brothers_preview1.png?raw=true" width="836" />  
  
---- Tips ----  
Setting is not optimized, find better configuration.  
When MT5 restarts, a Long MADR Signal is reset to Initial-Trend-Signal value. Therefore, if you can recognize that a Long MADR Signal is within a trend at that time, you need to manually set a Initial-Trend-Signal value.  
  
<img alt="preview2" src="https://github.com/mitsuaki-41/MADR_Brothers/blob/main/madr_brothers_preview2.png?raw=true" width="516" />  
