# Automated-Trading-Algorithm-for-Intraday-Trading

Intraday trading involves buying and selling of stocks within the same trading day. Here stocks are purchased, not with an intention to invest, but for the purpose of earning profits by harnessing the movement of stock indices. Thus, the fluctuations in the prices of the stocks are harnessed to earn profits from the trading of stocks.

## On Balance Volume (OBV)
On Balance Volume (OBV) measures buying and selling pressure as a cumulative indicator that adds volume on up days and subtracts volume on down days. When the security closes higher than the previous close, all of the day’s volume is considered up-volume. When the security closes lower than the previous close, all of the day’s volume is considered down-volume.

## Strategy Description
Combination of Renko charts and On Balance Volume Indicator.
Choose high volume, high activity stocks for this strategy. 
The buying Signal is generated when Renko Bars is greater than or equal to 2 and 5 day OBV Slope is greater than 30 degrees.
The selling signal is generated when Renko bars are less than or equal to 2 and 5 day OBV slope is less than -30 degrees
