+++
categories = ["Cryptocurrency", "Blockchain", "SmartContract"]
date = "2020-11-26"
description = "Range trading strategy using the Keltner channel stops indicator"
tags = ["Cryptocurrency", "Blockchain", "SmartContract"]
title = "Range trading strategy using the Keltner channel stops indicator"
type = "post"
+++

{{<iframe id="large-banner" src="https://www.bounty.group/#slide=12.0" width="100%" height="600" scrolling="no" style="border: 0px solid rgb(216, 221, 230); border-radius: 3px;">}}

2020-11-25

2020-11-26

Range Trading StrategyOleg Tkachenko

Welcome to the LiteForex traders blog where we analyze simple but
effective strategies based on unique indicators. Today we will analyze
the range trading strategy, in which we use the Keltner channel stops
indicator. We will find out what this indicator is for and what the
entry and exit conditions are. I will also talk about its peculiarities
and give examples.

The article covers the following subjects:

## Forex range strategy for the non-standard Keltner channel stops
indicator

Keltner channel stops is not quite a standard indicator. Although it is
considered a channel indicator, it does not draw price channels in the
chart. Interestingly, it is based on two classical instruments -
[Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) and the Keltner channel indicator. The combination of
the two gives a very good result on the foreign exchange market. Unlike
conventional price channel tools, it does not draw the visible upper and
lower boundaries of the price channel, but rather works like arrow
indicators - it draws the visual direction of the trend after the price
reverses to its average value.

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
If you are used to MT4, [open an account in your Cabinet][1], download
the platform and use the Keltner Channel indicator template for MT4,
which can be downloaded [here][2]. The Keltner channel stops indicator
can be downloaded [here][3].

 **How to install the Keltner channel stops indicator in MT4:**

  * Open the platform and select “File / Open Data Folder” in the top menu.
  * In the window that opens, go to the "MQL4 / Indicators" folder. Copy the indicator template there with the extension .mql4.
  * Restart the trading platform. The indicator will appear in the “Insert / Indicators / Custom” menu.

### 1\. Trading conditions and peculiarities of using Keltner channel
stops

The indicator works well on any liquid currency pair. Timeframe - H4. If
you set a lower interval, a lot of small areas with false signals will
appear. See a similar example in the screenshot below.

Keltner channel stops indicator settings:

 **Conditions for opening a long position:**

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
disconnection, use the [VPS server rental service][4]. In the worst
case, the position will be closed by stop order, which stays put even in
case of connection failure.

 **Conditions for opening a short position:**

The conditions for opening a position and exiting the market are
similar.

 **Peculiarities of using Keltner channel stops:**

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

False signal. The indicator changed color, the candle after the signal
is falling, but the position we open on it (yellow arrow) could close by
stop order because of the long growing candle (blue arrow). However,
mind that the green line of the indicator is horizontal, the orange line
is almost horizontal. This indicates a weak signal (Peculiarity #3).

In conclusion, I’ll add that you will find even more interesting
articles about indicators and analysis of strategies on the LiteForex
blog. All you need to go from a novice trader to a professional is:

  * Register (the "Registration" button in the upper right corner on any page of the [website](https://www.playgroundfx.com/blog/website-for-forex-trading/)). It only takes a couple of minutes of minutes. Verification is not required to open a demo account!
  * Get to know the [functions](https://www.fintechee.com/tutorial-for-forex-trading/basic-functions/) of LiteForex Client’s Cabinet. The article [“LiteForex Client’s Cabinet”][5] will help you with this.
  * Download and install MT4 or use the built-in LiteForex platform.
  * Follow recommendations in strategy reviews.

Remember that you can always ask your question about strategies in the
comments.

Something isn’t working? The strategy is not so effective when you use
it? Have ideas on [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) [optimize](https://www.fintecher.org/2020/03/17/added-genetic-algorithm-for-trading/) it? Please join us in the comments.

Nice bonus! To celebrate its 15th anniversary, LiteForex is drawing
prizes worth 350 thousand dollars. Anyone can participate. Learn more
about the conditions of the draw - [follow this link and register][6].
It's free!

Conclusion. Keltner channel stops is a non-standard combination of two
indicators. It gives you not only a channel, but also a trend strategy
with a minimum level of risk. Remember that any strategy needs to be
tailored to your own trading style. You also need to learn [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) see
signals and entry points. If you have little experience, start testing
the strategy on a demo account. Sign up, test the strategy and ask
questions in the comments. Good luck!

* * *

P.S. Did you like my article? Share it in social networks: it will be
the best “thank you" :)

Ask me questions and comment below. I’ll be glad to answer your
questions and give necessary explanations.

 **Useful links:**

  * I recommend trying to trade with a reliable broker [here][7]. The system allows you to trade by yourself or copy successful traders from all across the globe.
  * Use my promo-code BLOG for getting deposit bonus 50% on LiteForex platform. Just enter this code in the appropriate field while [depositing][8] your trading account.
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

   1. my.liteforex.com/
   2. drive.google.com/file/d/1rT71wHVA511hYKx4qSxi0RaXX8UTbTLY/view
   3. drive.google.com/file/d/1KlFOnl7jBWBX0xdqqSVltxLS_g497X7u/view
   4. liteforex.com/trading/additional-services/vps-services/
   5. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/lets-look-into-liteforexs-new-client-space/
   6. liteforex.com/contests/dream-draw/
   7. my.liteforex.com/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=range-trading-strategy&openPopup=%2Fregistration%2Fpopup&utm_source=blog&utm_medium=article&utm_campaign=bonus
   8. my.liteforex.com/deposit/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=range-trading-strategy&promo_code=BLOG&utm_source=blog&utm_medium=article&utm_campaign=bonus