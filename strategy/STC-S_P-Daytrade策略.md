# STC S&P Daytrade trading system
该系统每月平均交易10 笔左右，每天交易不超过2 笔。市场总是有起有伏，该系统首先采用"Price Trend Indicator"价格趋势指数来判断市场是超买还是超卖，超买的市场应该卖出头寸，超卖的市场应该买入头寸。第一笔交易进场方法是根据开盘价设一个区间，高于开盘价某些点位即买入，低于开盘价某些点位即卖出。日趋势通常会在3-4 天后改变方向，或是遇到跳空开盘，这些日子被称为"key reversal days"关键转折日。这种日子在目前的市场正在不断增多，因此有一套"Superior Clear-OutReversal Enhancement"系统来帮助找出反转信号并开始新方向的交易。最后，该系统每天都有不同的风险暴露，因此需要设臵止损，系统采用"Dynamic Risk Exposure Stops"方法止损。
