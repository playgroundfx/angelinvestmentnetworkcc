+++
categories = ["Cryptocurrency", "Blockchain", "SmartContract"]
date = "2021-02-22"
description = "Keltner Channel indicator to trade Forex"
tags = ["Cryptocurrency", "Blockchain", "SmartContract"]
title = "Keltner Channel indicator to trade Forex"
type = "post"
+++

{{<iframe id="large-banner" src="https://www.bounty.group/#slide=4.0" width="100%" height="600" scrolling="no" style="border: 0px solid rgb(216, 221, 230); border-radius: 3px;">}}

2021-02-22

2021-02-22

Keltner Channel IndicatorOleg Tkachenko

 **Keltner Channel**  (Keltner bands) – is a classical indicator of the
technical analysis designed by Chester Keltner in 1960.

Like the [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) indicator, the Keltner Channel draws the
channel of price movements relative to the central EMA line. However,
unlike the BB channel, the Keltner Channel indicator doesn’t widen
following the price. So, the price can go beyond the Keltner Channel,
thereby indicating the trend exhaustion. Read more about Forex trading
with the Keltner Channel in this article.

The article covers the following subjects:

## How to use Keltner Channels indicator

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

## How to trade Keltner Channels?

Keltner Channel indicator looks like three lines: the channel border and
the middle line. It looks like three lines: the channel border and the
middle line. The middle line is the exponential moving average; the
channel borders are the derivatives of the EMA and the ATR indicator.
Unlike the [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) indicator, the Keltner Channel is less
responsive to the price change, allowing it to go far beyond its
boundaries. For the same reason, the indicator does not work in a flat;
it cannot determine it.

## Keltner Channel strategy explained

This strategy employs two technical indicators: the Keltner channel with
the default settings and the [RSI][2] with the period of 14 and a
narrower corridor of the primary price movement (levels of 65 and 35).
The strategy is tested in the M30 timeframe for the [EUR/USD][3]
currency pair.

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

## Keltner channel breakout strategy

In this strategy Keltner Bands indicator are used to indicate market
volatility. The channels are set with the help of the moving average
(10), multiplied by the value of the ATR range in order to determine the
lower and upper limits of the Keltner channel. ATR (Average true range)
is used to gauge volatility of the trading instrument.

In order to use this strategy, you shall download the indicator Keltner
Bands, which will automatically draw the channels. Change the period of
the moving average from 10 to 40.

> When the indicator Keltner Channels for MT4 is downloaded, file it in:
Trading terminal -> Experts -> indicators ****

The pairs used for trading are: EUR/USD, GBP/USD, USD/CHF.

Time frame H4 is used for trading.

Take profit amounts to 65 points.

Stop-loss amounts to 35 points.

Buy position can be opened at the moment when the price breaks out the
upper limit of the Keltner Bands (figure 1).

[][4]

Sell positions can be opened at the moment when the price breaks out the
lower limit of the Keltner Bands. (Figure 2)

[][5]

## Range Trading Strategy: Keltner Channel vs [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html)

For this strategy we are going to use Keltner channel stops  indicator.
It is not quite a standard indicator. Although it is considered a
channel indicator, it does not draw price channels in the chart.

Interestingly, it is based on two classical instruments - Bollinger
Bands and the Keltner channel indicator. The combination of the two
gives a very good result on the foreign exchange market.

Unlike conventional price channel tools, it does not draw the visible
upper and lower boundaries of the price channel, but rather works like
arrow indicators - it draws the visual direction of the trend after the
price reverses to its average value.

Keltner channel stops is a modification of BBStop that uses the Keltner
channel calculation formula. BBStop is a modification of the Bollinger
Bands, which is designed to identify stop levels at the trading range
boundaries.

Instead of the traditional channel range, the Keltner channel stops
paints lines above or below the price. Green means a growing trend,
orange (red) means a downtrend. The color changes when the price touches
the lower or upper boundaries of the channel. You can’t see them in the
chart, but they are built by the indicator based on the algorithm in the
code.

This screenshot shows how accurately the Keltner channel stops shows a
strong price movement. Despite a moderate flat in the area highlighted
by a blue rectangle, one could earn on each of these movements. Channel
strategies do give false signals sometimes and there is no way to filter
them yet. Such signals are indicated by yellow arrows.

The strategy built directly on the Keltner Channel indicator is
described in detail in this review. Please note that it was reviewed on
the basis of the LiteForex platform integrated in the Client’s Cabinet.
If you are used to MT4, [open an account in your Cabinet][6], download
the platform and use the Keltner Channel indicator template for MT4,
which can be downloaded [here][7]. The Keltner channel stops indicator
can be downloaded [here][8].

### How to install the Keltner channel stops indicator in MT4:

  * Open the platform and select “File / Open Data Folder” in the top menu.
  * In the window that opens, go to the "MQL4 / Indicators" folder. Copy the indicator template there with the extension .mql4.
  * Restart the trading platform. The indicator will appear in the “Insert / Indicators / Custom” menu.

### 1\. Trading conditions and peculiarities of using Keltner channel
stops

The indicator works well on any liquid currency pair. Timeframe - H4. If
you set a lower interval, a lot of small areas with false signals will
appear. See a similar example in the screenshot below.

#### Keltner channel stops indicator settings:

####  **Conditions for opening a long position:**

We open a position on the next candle. Stop loss is set at a relatively
long distance - 30 points. The moment of signal change can be compared
with the price reaching the channel border and the subsequent reversal.
But inertial movement can give a long shadow in the old direction and
trigger stop orders.

We exit the market as follows. The target profit is 20 points (we are
talking about 4-digit quotes!). Upon reaching it, we move the stop loss
to the breakeven level and set a trailing stop at 20 points. To set it,
right-click on an open order and select the necessary option.

The trailing stop is set in the MT4 platform and not on the broker's
server, like other orders. So the platform must be always on and have
stable connection with the broker’s server. If there is a risk of
disconnection, use the [VPS server rental service][9]. In the worst
case, the position will be closed by stop order, which stays put even in
case of connection failure.

####  **Conditions for opening a short position:**

The conditions for opening a position and exiting the market are
similar.

####  **Peculiarities of using Keltner channel stops:**

  1. Enter the market only on the next candle after the formation of the signal. While the signal candle has not closed, the indicator can repaint its values. If you are absolutely sure that the price will go in the right direction, you can try to open a position on a signal candle.
  2. Trailing stop is mandatory because the price may return to the breakeven level a few candles after the signal.
  3. Control the movement of the indicator. If after a color change the indicator is moving horizontally for more than 4-5 candles, it makes sense to close the position ahead of schedule.
  4. If after the signal candle, a candle appears in the opposite direction, do not open the position yet. If you see three candles in a row in the opposite direction, don’t enter at all.
  5. Signals are relatively rare, since we are talking about a fairly long timeframe. Do not forget about swaps.

### 2\. Examples of the range trading strategy

 **Example 1**

The indicator changes color on the signal candle (signal candles are
marked with vertical blue lines), the next candle is in the signal
direction. On the next candle, open a position (in the first case, a
long position, in the second – a short one). You don’t have to wait for
the indicator to change color to close the trade. After setting the
trailing stop, the position will automatically close almost at the
extreme.

 **Example 2**

This is an example of a situation that shows why you must set a trailing
stop. The yellow arrow indicates the candle, on which a long position
should have been opened in accordance with the signals. Opening price -
1.11491.

We set a trailing stop on the candle marked with a blue arrow (1.11691 -
1.11491 = 200 or 20 points). Now, if the price reverses, everything
above the level of the trailing stop will be profit. The high of the
candle is 1.11726, then the price reversed and went down, despite the
green line of the indicator. Without trailing stop, the position would
have closed by stop order (at the breakeven level, if it had been moved
there). With the trailing stop the profit amounted to 1.11726 - 1.11691
= 35 or 3.5 points. Not much, but at least it’s not a loss.

 **Example 3**

An example of Peculiarity #4. In the first case, the indicator changes
color to orange, signaling the possibility of opening a short position.
But the candle after the signal is growing, as are the subsequent ones.
Three growing candles after a “down” signal - we do not open a trade.

In the second case, the situation is similar. When the signal is “up”,
the next candle after the signal is bearish, and the next one. The third
candle is growing (yellow arrow), we open a long position on it.

 **Example 4**

#### False signal

The indicator changed color, the candle after the signal is falling, but
the position we open on it (yellow arrow) could close by stop order
because of the long growing candle (blue arrow). However, mind that the
green line of the indicator is horizontal, the orange line is almost
horizontal. This indicates a weak signal (Peculiarity #3).

In conclusion, I’ll add that you will find even more interesting
articles about indicators and analysis of strategies on the LiteForex
blog. All you need to go from a novice trader to a professional is:

  * Register (the "Registration" button in the upper right corner on any page of the [website](https://www.playgroundfx.com/blog/website-for-forex-trading/)). It only takes a couple of minutes of minutes. Verification is not required to open a demo account!
  * Get to know the [functions](https://www.fintechee.com/tutorial-for-forex-trading/basic-functions/) of LiteForex Client’s Cabinet. The article [“LiteForex Client’s Cabinet”][10] will help you with this.
  * Download and install MT4 or use the built-in LiteForex platform.
  * Follow recommendations in strategy reviews.

##  **Conclusion**

The Keltner Channel sends more accurate signals than [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html).
There could be false signals, but they are few if you employ additional
filters. You can find strategies using moving averages as a filter on
the Internet, but the oscillator seems to me to be a better option. If
you have any questions or have comments on the strategy, I invite you to
the discussion below.

Keltner channel stops is a non-standard combination of two indicators.
It gives you not only a channel, but also a trend strategy with a
minimum level of risk. Remember that any strategy needs to be tailored
to your own trading style. You also need to learn [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) see signals and
entry points. If you have little experience, start testing the strategy
on a demo account. Sign up, test the strategy and ask questions in the
comments. I would also like to know if the article has been useful to
you.

Nice bonus! To celebrate its 15th anniversary, LiteForex is drawing
prizes worth 350 thousand dollars. Anyone can participate. Learn more
about the conditions of the draw - [follow this link and register][11].
It's free! Good luck!

* * *

P.S. Did you like my article? Share it in social networks: it will be
the best “thank you" :)

Ask me questions and comment below. I’ll be glad to answer your
questions and give necessary explanations.

 **Useful links:**

  * I recommend trying to trade with a reliable broker [here][12]. The system allows you to trade by yourself or copy successful traders from all across the globe.
  * Use my promo-code BLOG for getting deposit bonus 50% on LiteForex platform. Just enter this code in the appropriate field while [depositing][13] your trading account.
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
   4. cdn.liteforex.com/cache/images/uploads/kelt1.png?q=75&s=f999455d01543f2606fc270f7636a327
   5. cdn.liteforex.com/cache/images/uploads/kelt2.png?q=75&s=dc4ce6b0253dfd3403c725271e5c2b66
   6. my.liteforex.com/
   7. drive.google.com/file/d/1rT71wHVA511hYKx4qSxi0RaXX8UTbTLY/view
   8. drive.google.com/file/d/1KlFOnl7jBWBX0xdqqSVltxLS_g497X7u/view
   9. liteforex.com/trading/additional-services/vps-services/
   10. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/lets-look-into-liteforexs-new-client-space/
   11. liteforex.com/contests/dream-draw/
   12. my.liteforex.com/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=best-technical-indicators&slug2=keltner-channel&openPopup=%2Fregistration%2Fpopup&utm_source=blog&utm_medium=article&utm_campaign=bonus
   13. my.liteforex.com/deposit/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=best-technical-indicators&slug2=keltner-channel&promo_code=BLOG&utm_source=blog&utm_medium=article&utm_campaign=bonus