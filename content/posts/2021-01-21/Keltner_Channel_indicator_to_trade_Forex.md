+++
categories = ["Cryptocurrency", "Blockchain", "SmartContract"]
date = "2021-01-21"
description = "Keltner Channel indicator to trade Forex"
tags = ["Cryptocurrency", "Blockchain", "SmartContract"]
title = "Keltner Channel indicator to trade Forex"
type = "post"
+++

{{<iframe id="large-banner" src="https://www.bounty.group/#slide=27.0" width="100%" height="600" scrolling="no" style="border: 0px solid rgb(216, 221, 230); border-radius: 3px;">}}

2021-01-21

2021-01-21

Keltner Channel IndicatorOleg Tkachenko

Like the [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) indicator, the Keltner Channel draws the
channel of price movements relative to the central EMA line. However,
unlike the BB channel, the Keltner Channel indicator doesn’t widen
following the price. So, the price can go beyond the Keltner Channel,
thereby indicating the trend exhaustion. Read more about Forex trading
with the Keltner Channel in this article.

The article covers the following subjects:

## Forex trading with the Keltner Channel indicator

Channel [trading strategies](https://www.fintechee.com/forex-trading-strategies/) are based on market psychology. The price is
in the channel about 80% of the time, moving to its borders on both
sides but somehow returning to the middle, that is, to the equilibrium
value. Depending on the market participants’ strength and fundamental
factors, the price can break through the channel boundaries. Some
channel [trading strategies](https://www.fintechee.com/forex-trading-strategies/) are based on channel breakouts. Other
strategies involve trading on the rebound from the channel borders.

There is only one channel indicator in MT4 - [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html). Its
disadvantage is that when a trend appears, the channel borders expand
following the price, making it impossible to indicate the breakout
moment or the subsequent correction clearly. Therefore, the developers
added more advanced indicators, the Donchian channel and Keltner
Channel, to the [LiteForex][1] trading toolkit. I will explain the
Keltner Channel trading strategy below.

### Keltner Channel [Forex trading](https://www.fintechee.com/forex-trading-strategies/) strategy: description and rules

First, the Keltner Channel indicator was first introduced in 1960. It
looks like three lines: the channel border and the middle line. The
middle line is the exponential moving average; the channel borders are
the derivatives of the EMA and the ATR indicator. Unlike the Bollinger
Bands indicator, the Keltner Channel is less responsive to the price
change, allowing it to go far beyond its boundaries. For the same
reason, the indicator does not work in a flat; it cannot determine it.

### System of trading with Keltner Channel

This strategy employs two technical indicators: the Keltner channel with
the default settings and the [RSI][2] with the period of 14 and a
narrower corridor of the primary price movement (levels of 65 and 35).
The strategy is tested in the M30 timeframe for the [EURUSD][3] currency
pair.

Conditions to enter a long position:

  * The price has been for some time inside the channel, then the market breaks out the upper border and is moving up. An additional signal is when the previous candlestick and/or the candlestick, when the price breaks the channel border, has a greater body compared to the previous candlesticks.
  * The RSI at the same candlestick (that breaks the channel border) breaks through level 65 and moves up in the overbought zone.

The channel breakout signals a strong price momentum, which should
exhaust quite soon, and the point is to pick this momentum up. RSI
confirms this short-term movement. When the price is breaking through
the channel border, we enter a trade at the signal candlestick (it is
too late to open a position at the next candlestick). The stop loss is
10 pips. The target profit level is 10-20 pips. We exit the trade when
there appears a reversal candlestick and the RSI turns in the opposite
direction simultaneously.

The arrows point to the moments when both conditions occur at the same
time. We could have exited the trade already at the moment when the
first red candlestick appeared. The profit would be 28 points, and it
would correct according to the risk management rules. More risky traders
would exit higher (the yellow oval).

 **The conditions to enter a short trade:**

  * The price has been within the channel for some time. Next, it is breaking through the channel border and is moving down. An additional signal is when the previous candlestick and/or the candlestick, when the price breaks the channel border, has a greater body compared to the previous candlesticks.
  * The RSI at the same candlestick (that breaks the channel border) breaks through level 35 and is moving down in the oversold zone.

6 out of 7 signals are profitable. The green line highlights the signal
that hasn’t worked out. Nonetheless, the trade is not exited by a stop-
loss; it is exited manually when the price goes back into the channel,
and we lost only the spread amount. TTherofitable trades yield is from
6-7 pips (the first trade) and more. Note that almost in all cases, the
candlestick breaking out of the channel is significantly different from
other candlesticks. We do not know about the candlestick body size at
the time of entering the trade; its closing with such a body is an
additional confirming signal that we are right.

You don’t need to follow the exit rules strictly. The most recent
screenshot that the reversal candlestick in some cases is small, and the
price continues falling. So, I would rather act like this: do not hurry
to exit the trade at the moment when the reversal candlestick appears,
which can close in the trend direction and signal the trend
continuation. One should exit the trade when the body of the reversal
candlestick (even not closed) is at least 1/3 of the last candlestick
body in the trend direction. If the reversal candlestick closes with a
small body (¼ and less of the previous one), do not hurry to exit the
trade, the price could continue moving in the trend.

 **Example 1:**

The green candlestick closes with a body equal to 1/3 of the red
candlestick. We exit the trade (turn the long position into the short
one). The profit is about 8-9 pips.

 **Example 2:**

The green candlestick has a small body, we can take a risk - do not exit
the market yet. And the risk turned out to be justified - the price for
one more candlestick continued its downward trend.

However, this exit rule doesn’t always work out, especially when the
candlestick hasn’t yet closed. Therefore, monitor the chart and exit the
trade according to your strategy rules. The example shows one of the
exit [options](https://www.fixpro.org/post/options-liquidity/).

There is another interesting moment. If the price breaks out the
channel, and the oscillator goes to the border levels of the overbought
and oversold zones, then it would be logical to assume its subsequent
rapid reversal. The screenshots show that in most cases, the reversal
occurred after 2-4 candlesticks. And although the return to the center
of the channel has a more horizontal shape, a few pips could be earned
on the return movement.

 **Conclusion.** The Keltner Channel sends more accurate signals than
[Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html). There could be false signals, but they are few if you
employ additional filters. You can find strategies using moving averages
as a filter on the Internet, but the oscillator seems to me to be a
better option. If you have any questions or have comments on the
strategy, I invite you to the discussion below. I would also like to
know if the article has been useful to you.

* * *

P.S. Did you like my article? Share it in social networks: it will be
the best “thank you" :)

Ask me questions and comment below. I’ll be glad to answer your
questions and give necessary explanations.

 **Useful links:**

  * I recommend trying to trade with a reliable broker [here][4]. The system allows you to trade by yourself or copy successful traders from all across the globe.
  * Use my promo-code BLOG for getting deposit bonus 50% on LiteForex platform. Just enter this code in the appropriate field while [depositing][5] your trading account.
  * Telegram chat for traders: <t.me/liteforexengchat>. We are sharing the signals and trading experience
  * Telegram channel with high-quality analytics, Forex reviews, training articles, and other useful things for traders <t.me/liteforex>

The content of this article reflects the author’s opinion and does not
necessarily reflect the official position of LiteForex. The material
published on this page is provided for informational purposes only and
should not be considered as the provision of investment advice for the
purposes of Directive 2004/39/EC.

Rate this article:

{{value}}

( {{count}} {{title}} )

   1. my.liteforex.com/trading/chart?symbol=GBPUSD
   2. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/best-technical-indicators/rsi-relative-strength-index/
   3. my.liteforex.com/trading/chart?symbol=EURUSD
   4. my.liteforex.com/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=keltner-channel-indicator&openPopup=%2Fregistration%2Fpopup&utm_source=blog&utm_medium=article&utm_campaign=bonus
   5. my.liteforex.com/deposit/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=keltner-channel-indicator&promo_code=BLOG&utm_source=blog&utm_medium=article&utm_campaign=bonus