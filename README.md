# Finch-in-Python
creating Rob Booker's Finch in Python

Rob Booker is a trader and has created a few expert advisors that are primarily used in MetaTrader 4, written using MQL4.
Rob Booker's website: https://robbooker.com

Rob Booker developed a automated trading robot based on a custom indicator that he made (called Knoxville Divergence). This is primarily used to show potential areas for reversals. Rob explains Knoxville Divergence in this video: https://youtu.be/woznTG64Xg4

Knoxville Divergence has 3 criteria:
1. RSI is overbought (>70) for a sell signal or oversold (<30) for a buy signal
AND
2. The momentum oscillator is falling at the same time that RSI signal posts.
AND
3. Price is either rising (sell signal) or falling (buy signal)

Rob named his Knoxville Divergence robot "The Finch": https://youtu.be/Q7TyK1aVOR0

How the finch works:
1. Take either a buy or sell trade based on Knoxville Divergence. (This trade will be a very small size, the smaller the better. Trade will not have a stop loss)
2. If trade goes into drawdown, after a certain amount of drawdown then the Finch will place a second trade that is larger. (This is to average down into the trade.)
3. Close both trade 1 and trade 2 after profit target is met.

Issues with the finch:
1. can be stuck in drawdown for a significant amount of time
2. isn't the best strategy for those who want set amount of risk.

GOAL:
This project is merely for exploratory purposes and practice. I am not convinced that this is a successful strategy long term or that this is an effective robot.
