# Dual-Thrust 策略
传统的开盘区间突破策略，是指通过在开盘区间的上下加减预定的数值范围进行交易。而Dual-Thrust策略实际上则是对传统开盘区间突破策略的一个改进。<br>
两个策略均是对当日开盘价加减某个数值（记为Range），获得一个区间，突破区间上轨做多，突破区间下轨做空。开盘区间突破策略通过前一个交易日的最高价和最低价确定Range的值，<br>
而Dual-Thrust策略使用前N日的4个价格：前N日最高价HH、前N日最低价LL、前N日最高收盘价HC、前N日最低收盘价LC，来确定Range的值，并引入更多参数，使得通过Range确定的区间可以是非对称的（见下图）。<br>
<div align=center> <img src="/images/Dual-Thrust.jpg"/> </div>
