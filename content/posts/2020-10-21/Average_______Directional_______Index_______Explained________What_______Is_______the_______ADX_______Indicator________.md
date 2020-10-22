+++
categories = ["Cryptocurrency", "Blockchain", "SmartContract"]
date = "2020-10-21"
description = "Average‌ ‌Directional‌ ‌Index‌ ‌Explained‌. ‌What‌ ‌Is‌ ‌the‌ ‌ADX‌ ‌Indicator?‌ ‌"
tags = ["Cryptocurrency", "Blockchain", "SmartContract"]
title = "Average‌ ‌Directional‌ ‌Index‌ ‌Explained‌. ‌What‌ ‌Is‌ ‌the‌ ‌ADX‌ ‌Indicator?‌ ‌"
type = "post"
+++

{{<iframe id="large-banner" src="https://www.bounty.group/#slide=13.0" width="100%" height="600" scrolling="no" style="border: 0px solid rgb(216, 221, 230); border-radius: 3px;">}}

2020-10-22

2020-10-22

[Average Directional Index](https://www.algotradesoft.org/custom-indicator/average-directional-index.html) (ADX indicator)Oleg Tkachenko

The ADX indicator is an effective combination of a trending indicator
and an oscillator. It may seem complicated: there are no clear signals
for opening trades and the formula for calculating the index is hard to
understand.

Nevertheless, ADX is included in the basic MetaTrader 4 package and is
often used in trading systems as a signal confirmation instrument.

The article covers the following subjects:

In this guide, we will examine the ADX indicator in great detail and see
[how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) calculate it, work with it, and find signals. Also, this article
will analyze practical examples of opening trades with screenshots and
ADX [trading strategies](https://www.fintechee.com/forex-trading-strategies/).

## What Is ADX indicator, it’s Definition & History

Let me explain ADX meaning.

The ADX ([Average Directional Index](https://www.algotradesoft.org/custom-indicator/average-directional-index.html), Directional Movement Indicator, or
DMI) is a trend oscillator that shows a trend’s direction and its
strength. It’s represented by one main, solid ADX line and two dashed
lines +DI (+Di), -DI (-Di) – directional components that are placed
below the price chart.

Installing and setting up the ADX indicator in the LiteForex terminal:

 **Step 1.** Select the "For [beginners](https://www.playgroundfx.com/blog/forex-for-beginners/) / Open a demo account" tab in the
top menu on the LiteForex page. You will be automatically redirected to
the demo version of the terminal, with no registration needed.

 **Step 2.** In the lefthand menu, select the "Trade" section and choose
an asset. For example, you can pick the [EURUSD currency pair][1].

 ****

 **Step 3.** Select the indicator: "Indicators / Average Directional
Index (ADX)."

 ****

It will appear below the price chart. It will look like this:

 ****

The dotted lines are the additional +DI and -DI lines; the solid one is
the ADX indicator line. The upper line displays the settings and current
level values ​​of each line. You can see the same levels on the right.
The text color of the level matches the line color.

So what does the ADX average direction indicator shows? The price
movement can be of two types: horizontal movement in a narrow range,
called "sideways" or flat and trending up or down. One group of trading
systems involves searching for signals when the price exits the flat
range and opening a trade when the trend starts. But:

  * How strong is the trend? Will the price reverse after a few candles?
  * Does the break from the flat range mean the beginning of a trend, or is it just a correction?

The index helps to answer these questions.

 **What you need to know about the ADX indicator:**

  * The index measures the strength of a trend regardless of its direction. It takes on the same value for both upward and downward price movements.
  * The indicator’s movement ranges from 0 to 100%. If the value is 0-20%, it means the strength of the trend is insignificant. 40% and more signifies a strong trend. The indicator line rarely rises above 60%.
  * It suits any trading asset. It works well for any currency pair, including cross rates. There are many successful examples of indicator trading on the stock and commodity market assets.

 **Recommendations for using ADX:**

  * Use the directional indicator only on trending price movements. The index determines the direction and strength of the trend. Therefore, during the flat movement, it will give a lot of false signals.
  * The recommended timeframe is H1 and higher. The creator of the index suggested using the D1 interval. On short intervals like M5-M15, the oscillator produces too many false signals because of price noise.
  * When the oscillator’s main line exits the 0-20% zone (in some cases, 0-25%), it signifies the beginning of a trend. When the main indicator line enters the 50-60% zone, it’s a signal that the trend is possibly ending soon.
  * The ADX index gives the most accurate signals after consolidation - when the price exits the flat range. During sharp price movements against the trend and when the main direction of price movement changes, the number of false signals increases.

### How ADX Was Created

The ADX indicator was first introduced by J. Wells Wilder Jr. in 1978.
In his book "New Concepts in Technical Trading Systems," he described a
system of directional price movement, which was called DMS (Directional
Movement System). It includes a series of indicators that describe the
nature of the trend price movement - its direction and strength. You are
already familiar with one of them - one of the main MT4 indicators -
[ATR][2], average true range.

The oscillator was originally designed to be used in volatile
derivatives markets - futures and [options](https://www.fixpro.org/post/options-liquidity/). Later, the main indicator
within this system - the ADX direction index - was repeatedly refined by
analysts. As a result, it gained smoothness and additional filters. What
you are learning about now is its final version, which is included in
the Metatrader platform as one of the basic tools.

## How is ADX indicator calculated & ADX indicator Formula

The formula for the average directional movement indicator is complex.
But you should at least have a general idea of what it is to read its
signals.

The ADX is built on two other tools developed by Welles Wilder:

  * The Positive Directional Indicator (+DI). This is the exponential moving average of the difference between the current high and the previous high, divided by the true range (TR - true range). The default period is 14.
  * The Negative Directional Indicator (-DI). The calculation is similar, only here, you take the current and previous lows.

These are the dashed lines on the MT4 chart and the LiteForex terminal.

 **Here is a step-by-step ADX formula and ADX calculation example:**

1\. Calculate +M and -M:

  * +M = High (i) - High (i-1)
  * -M = Low (i-1) - Low (i)

High and Low are the maximum and minimum values, while i and i-1 are the
current and prior periods, meaning the current and prior bars or
candles. To avoid the need to redraw, it’s appropriate to take the
current High and the current Low of the newly formed closed candlestick.

2\. Calculate +DM and -DM:

  * +DM = +M, if +M> -M and +M> 0;
  * +DM = 0, if +M 
  * -DM = -M, if -M> +M and -M> 0;
  * -DM = 0 if -M 

DM can be of either the M value calculated during the previous step or
0, depending on whether the algorithm condition is met. +M is an
absolute positive price movement, -M is an absolute negative price
movement.

3.   Calculate DI:

 ****

 ****

The[EMA][3] indicator is an exponential moving average and TR means true
range, which shows the entire range of an asset price.

TR = Max (High (i), Close (i-1)) - Min (Low (i), Close (i-1))

Max and Min are the highest values for the given period and High and Low
are the highest and lowest values of the candlestick. Close is a close
price of the candlestick and i and i-1 are current and prior candles.

4\. Calculate ADX:

 ****

The EMA period (the number of candles used to calculate the indicator)
can be set in the Index settings.

### Example of ADX indicator calculation in excel

The table for calculating the Directional Movement Index in Excel looks
like this:

 ****

Let me describe the steps for ADX indicator calculation in excel in more
detail:

1\. We fill in the first three columns: the highest and lowest prices
and the close price. You can download these values from MT4 by pressing
F2, selecting the needed symbol, and exporting the file. Then, you will
need to correct the format display in Excel. Alternatively, you can ask
your broker for quotes.

2\. Calculate TR. Enter the formula in cell E3:

  * = MAX (B3-C3; ABS (B3-D2); ABS (C3-D2))

Take notice of the syntax. For example, if you’re writing the formula in
a different language, it may look slightly different. Apply the formula
to the entire table.

3\. Calculate positive (+DM) and negative (-DM) directional movement.
Formula for cell F3:

  * =IF(B3-B2> C2-C3; MAX (B3-B2; 0); 0)

Formula for cell G3:

  * =IF(C2-C3> B3-B2; MAX (C2-C3,0); 0)

Apply the formulas to the entire table.

4\. Apply the smooth function to all three values. Since it uses period
14 by the default settings, smoothing is calculated using the data from
4 candles. Formula for cell H16:

You don't need to extend the formula.

  * =TRUNC((J16-(J16/14)+G17);3)

Formula for cell I16:

Formula for cell J16:

Now is the smoothing itself, which takes into account the values for the
past periods from the above calculations instead of the arithmetic mean.

Formula for cell H17:

  * =TRUNC((H16- (H16 / 14) + E17); 3)

Formula for cell I17:

  * =TRUNC((I16- (I16 / 14) + F17); 3)

Formula for cell J17:

  * =TRUNC((J16- (J16 / 14) + G17); 3)

Apply the last three smoothing formulas to the entire table.

5\. Calculate DI for period 14. Formula for cell K16:

  * = INT (100 * (I16 / H16))

Formula for cell L16:

  * = INT (100 * (J16 / H16))

Apply the formulas to the entire table.

6\. Calculate the absolute difference between +DI and -DI. Formula for
cell M16:

7\. Sum +DI and -DI in the next column. Formula for cell N16:

8\. Calculate DX, which is the ratio between the absolute difference
between +DI and -DI and their sum. Formula for cell O16:

  * = INT (100 * (M16 / N16))

9\. Smooth DX by the last 14 candles. For this, we take the average DX
values. Formula for cell P28:

The formula doesn’t need to be extended.

10\. Smooth and calculate ADX. Formula for cell P29:

  * = INT (((P28 * 13) + O29) / 14)

You can download the Excel calculation template for the ADX Indicator
[here][4]. This is a completed table with all formulas entered. All you
need to do is enter the price data in columns B, C, and D.

## How to Read ADX Indicator

The reason why the ADX indicator is so popular is that it is very
informative.

  * The main line ADX shows the strength of the trend.
  * Additional +DI and -DI lines define the trend direction.

When interpreting the ADX, keep in mind that the oscillator is
auxiliary. To confirm the signal, you need to analyze where all three
lines of the index are positioned relative to each other and to the
0-100% range. Below, I will describe each of the signals in detail.

### Determining the Trend’s Strength

The trend’s strength means how much the buying volume exceeds the
selling volume or how much the selling volume exceeds the buying volume.
If they are equal, the price is flat, and the main oscillator line is
reaching 0. If the order volume on one side rises sharply, the price
starts moving upward or downward, and the indicator line moves towards
100%.

Range values of the main indicator line can be interpreted as follows:

  * 0-20% is a market equilibrium, or “not in a trend.” Traders aren’t rushing to place orders and increase transaction volumes. The price moves in a narrow range between strong support and resistance levels. This is the period for waiting and observing.
  * 20-30% is the beginning of a trend. The price breaks out the resistance or support level. It’s too early to open a trade as it may be a false breakout. At this point, it makes sense to analyze the position of the +DI and -DI lines relative to each other and see whether patterns are starting to form.
  * 30-40% is a confirmation of the trend movement. This is the best moment to open a trade.
  * 40-50% is a strong trend that is gaining momentum. Here, you can add to a position if there are no opposite signals according to other tools. There is still a risk of a price reversal.
  * 50-100% is the peak area where the trend is ending. At this time, start looking for opportunities to exit the market. This does not mean that the price will reverse. There might be a consolidation or a small local rollback, after which the main movement will continue. But a reversal is also possible.

ADX can help you estimate the rate of price change. If the oscillator
moves horizontally, it means the price is flat. If it moves up closer to
100%, it signifies that the bearish or bullish trend's strength is
increasing. If it moves closer to 0, then the market is consolidating
following the trend peak.

Some sources refer to the 0-25% zone as the violet range. This is true
for currency pairs that have relatively low liquidity. All values of
levels and settings depend on the market situation and should be seen as
recommendations.

 **Example:**

Here you can see the [EURUSD][1] currency pair chart on the H1
timeframe. The gray horizontal dotted line corresponds to the 23.3
level. 20-25% is the signal zone, and if the indicator line exits it,
you need to look for signals. In both situations, if the blue is moving
upward from 25%, it’s a signal of a trend.

In the first scenario, the downtrend movement ended as soon as the index
reached the 50th level. In the second scenario, the downtrend continued
but gradually transitioned into a sideways movement.

### Determining the Trend Direction

The main ADX line only helps determine the strength of the trend. The
direction is determined by the relative position of the +DI and -DI
lines and their crossing.

#### Position of lines +DI and –DI

Possible relative positions of the +DI and -DI lines are:

 **1.Crossover:**

  * If the +DI line is above -DI after crossing and continues to move upward, it signifies a beginning of an uptrend.
  * If the +DI line is below -DI after crossing and continues to move downward, it signifies a beginning of a downtrend.

 **2\. Maximum divergence:**

  * If +DI is above, it’s an uptrend and its primary movement may end soon.
  * If -DI is above, it’s a downtrend and its primary movement may end soon.

The crossing of the +DI and -DI lines means that the market is in
equilibrium (the buying and selling volumes are equal). If the lines
diverge after crossing, it means that the balance of buyers and sellers
is getting disturbed. If there are more buy orders, the price starts to
rise, and +DI moves upward. If there are more sell orders, -DI goes up.

The maximum distance between + DI and -DI indicates that the trend is at
its peak. The greater the distance between + DI and -DI, ​​the more
likely we’ll see a price reversal or temporary consolidation soon. When
+ DI and -DI begin to converge again, this indicates the trend is
gradually fading.

 **Example:**

The main index line has been removed to avoid making the ADX chart look
cluttered. During the divergence, you can see that the trend movement is
getting stronger – there are changes in the slope angle. The point that
the arrow points to is where the +DI and -DI lines swapped.

The signal is lagging - the trend has already reversed. But it still
confirms that this reversal isn’t a correction but a major bullish trend
transitioning into a bearish one.

#### Crossover of the +DI and –DI Lines With a Rise of ADX

An independent trading system is based on the analysis of how all three
lines are positioned and move relative to each other and levels:

  * If the market goes into a bearish or bullish trend, the distance between +DI and -DI increases after the crossover. At the same time as the divergence, the index crosses the 20% level from the bottom upwards towards the 40-60% zone. If +DI is above -DI, it’s a bullish trend; if a +DI is below -DI, it’s a bearish trend.
  * If the distance between +DI and -DI decreases, the lines start to converge, and the index line plummets to the 0-20% zone. This signifies a decrease in trading activity. There is a possibility of a trend reversal or transition to a flat.

The gist of the ADX strategy is as follows. We are waiting for the
dotted +DI and -DI lines to start diverging and when the index line
begins to exit the 0-20% zone at the same time. We open a trade in the
trend’s direction 2-3 candles after the ADX crossed the 20th level. The
best moment to exit the market is when +DI and -DI (after the maximum
divergence) begin to converge and/or the index line goes down and
crosses the 30% level.



 **Example:**



A sharp divergence begins at point 1. +DI goes up, indicating a bullish
trend. The ADX indicator starts moving upward from the 12% level. As
soon as it breaks through the 25-30% level, you can open a long
position.

At point 2, the lines + DI and -DI swap. The main index line started to
decline but is still close to the 40% level. This suggests that the
trend movement is still strong, but there may be a reversal. Open a
short position 3-4 candles after the crossover of the +DI and -DI
divergence.

At point 3, the trend direction is likely to change again - the dotted
lines converge, and the index line has turned upwards. At point 4, we
close all short positions if it wasn’t done at point 3 because the
indicator line goes below the 20% level.

  *  **Important!** The convergence and divergence of +DI and -DI, ​​combining additional lines with the index, and the index line moving into the active zones above 30% - these are only auxiliary, confirmation signals. I don’t recommend using only ADX to open positions. It’s better to add other direction indicators or add [Price Action][5] elements to the strategy.

## How does ADX Indicator Work

If the price is flat, then the oscillator line will be below the 20th
level and move horizontally. The distance between +DI and -DI is narrow.
If the market forms a trend, the oscillator will begin to rise, and the
distance between +DI and -DI will increase. The larger the difference
between +DI and -DI, the higher the ADX rises. The maximum divergence in
the positive and negative direction and the index line being above
40-50% correspond to the overbought and oversold zones, respectively.

### Rules and Tips for Using the ADX Indicator

Any technical indicator only provides additional information on whether
there is a trend and how strong it is. The tool that provides the most
information is the price chart. Above all, a trader should assess the
nature of price movement: how quickly it’s moving in a certain
direction, the angle of inclination, etc. And only then should they
focus on the ADX data.

The strongest price movements occur when the market is in a flat. Flat
means an equal number of buyers and sellers, and equilibrium is when the
order volumes from both parties are approximately the same. When this
balance is disrupted, it creates an impulse that pushes the price out of
the flat range. This impulse often turns out to be a trap for traders.
It is often mistaken for a breakout of key levels, while it stays local
without receiving confirmation and the price goes back to the flat
corridor.

The ADX indicator confirms the price action. Its signals are lagging,
but when the price exits the consolidation zone or changes its main
direction, the index shows whether the price will continue moving in a
strong trend after a breakout or there is a local correction on the
chart.

In theory, the indicator provides entry signals in two situations:

1\. Opening a trade when the price is exiting a flat. The two following
conditions should be met at the same time:

  * Crossover of +DI and -DI
  * During the crossover, ADX should be below the 20% level and, after the crossover, exit the 0-20 zone.

If you rely solely on the dotted lines, it will provide false signals in
more than 50% of the cases. Meeting the second condition – crossing the
20th level from the bottom up – is essential. It signals that the price
is exiting the flat, and there is a directional movement (i.e., a trend)
forming. Some people recommend opening a trade only after crossing the
30th level.

2\. Opening a trade during the reverse crossover of +DI and -DI, ADX is
above the 40th level. This situation is an extension of the previous
one. After the price exits the flat, it reaches its maximum, where it
could possibly reverse. The index line is still showing a strong trend,
while +DI and -DI swap. This corresponds to entering the overbought or
oversold market.

 **Tips for using ADX:**

  * Start technical analysis by assessing the price direction, patterns, and levels. Use the indicator to confirm your assumptions.
  * Try to measure the trend’s strength. Select the main oscillator’s signal levels for the trading asset: flat zone, the start of a trend zone, active phase, and overbought/oversold. Let me remind you that the index position below 20% is considered a flat, the breakout is the beginning of a trend, 30-40% is an active phase, and 50-60% and above is an overbought/oversold zone. These values ​​may differ for each currency pair.
  * Find the optimal positions of the +DI and -DI to open a trade. In theory, open a trade when lines cross, and the index goes above the 20th level. Close when +DI and -DI start to converge.
  * When ADX is above 20-25%, use trend indicators; when it is below 20%, use channel indicators and intra-channel [trading strategies](https://www.fintechee.com/forex-trading-strategies/).

### Best ADX settings

 **1\. Installing and setting up the ADX indicator in MT4**

ADX is one of the basic indicators in MT4 and MT5. If you accidentally
deleted it from the Indicators folder, you can download ADX to the
directory on the MQL5 developer [website](https://www.playgroundfx.com/blog/website-for-forex-trading/). Here is what you should do:

 **Step 1.** Open the currency pair quote chart in the terminal by
clicking File - New Graph in the top menu.

 **Step 2.** Apply the indicator on the chart. On the top menu, click
Insert / Indicators / Trend / Average Directional Movement Index.

 **Step 3.** Enter the settings:

  * Period is the number of candles for calculating the indicator value. The default is 14. This means that EMA smoothing is performed on the last 14 candles.
  * Apply To means the price type used in calculations. In the formula, the indicator is applied to the exponential moving average.
  * Fix – This one fixes the set levels on the indicator chart.

In the Colors tab, change the color and line type of +DI and -DI.

In the Levels tab, add fixed horizontal levels to visually limit the
main range of movement of the indicator and overbought/oversold zones.

In the Display tab, specify the timeframes where you want to display the
indicator window when switching to charts of other intervals.

 **2\. Setting up ADX in the LiteForex terminal**

Your Personal Account built into the LiteForex platform is more
convenient from a practical perspective compared to MT4. It contains
only what you need; you can combine active trading with social trading
and get familiar with its functionality without registering.

Apply the indicator to the chart of the needed currency pair. Click on
the settings icon and enter the parameters.

Settings:

  * ADX smoothing is a sensitivity parameter. The greater its value, the less sensitive the main indicator line is to price changes. Leave it at 14 until you learn [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) adjust the oscillator individually for each currency pair.
  * DI length is the period (the number of candles that are used to do calculations).
  * Precision is the number of decimal places for the levels. The default is 4.

In the Style tab, you can change the thickness and color of indicator
lines.

The main setting parameter is the period, DI length. The default is 14,
but the parameter is adjusted separately for each pair and the current
volatility level. Other commonly used values in strategies are 12, 14,
18, 21. There is no need to go beyond the7-30 range:

  * When the period decreases, it speeds up the indicator movement and increases the number of false signals.
  * When the period increases, it slows down the indicator’s reaction to sharp price changes. The number of false signals is lower but, because of the lag, the index provides a signal when it is too late.

## How to Use ADX indicator in Forex Trading

Having sorted out the theory, let’s look at some practical examples.

Let me remind you: when two conditions are met simultaneously, it will
be your signal:

  * The dotted lines cross and begin to diverge.
  * At the time of a crossover, the main line is below the 20% level and, after that, the dotted lines start moving upward.

The crossover is indicated by the arrow. As soon as ADX rises above 20%,
open a short position as -DI is at the top. The stop-out level is the
previous candle high, the yellow line. It’s reasonable to set a trailing
stop instead of the regular stop.

Start looking for an opportunity to exit the trade when the dotted lines
are at the maximum distance and begin to converge. In the area
highlighted by the red rectangle, the index line reverses inside the
range in addition to the dotted lines' reversal – it means the trading
activity is weakening. This is also confirmed by the candlestick
analysis - red candlesticks have shorter bodies with each subsequent
candlestick. Close the trade when you see the first green candle.

The profit was about 90 points at 4-digit quotes.

### Using ADX to Detect Sideways Movement

The main index line is great for identifying sideways movement. If you
don’t want the dotted lines to bother you, you can turn them off in the
settings in the Styles tab.

The indicator line on a 1-minute interval was below the 25% level for 5
hours. The price chart shows a clear narrow flat of fewer than 10 points
wide at 4-digit quotes. Considering the spread on such a range, only
[scalping strategies][6] will be effective.

### Looking for Trends Using ADX

 _A practical example of opening a trade. Now, I will describe how the
chart analysis works and open a trade. And while it’s in the market, I
will continue the explanation. In the end, I will tell you about its
results._

Trading in a flat only interests the scalpers who open trades with a
target profit of several points. The biggest profits are only obtained
by using trend trading. The faster the price changes, the stronger the
trend and the more profitable and faster the transaction will be.

ADX has two strengths:

  * It doesn’t allow you to get stuck in a flat since it gives you warning of when it’s starting and ending.
  * It shows the trend strength - the rate of the price increase.

The lag is its disadvantage. On the other hand, when you open a trade on
a long timeframe expecting a long trend using a lagging signal, it’s
considered a perfect conservative, low-risk strategy.

Now I will try to open a trade based on the information given in this
review. I will find the beginning of a trend using ADX and enter the
market.

 **1\. Preliminary analysis.**

The situation indicated in point 1 was explained at the beginning of
this section. The index left the 0-20 zone after the +DI and -DI
crossover, the red dotted -DI went up, indicating a downtrend.

After September 23, the trend began to fade - the main line began to
decline and the dotted lines began to converge. This signals that the
downtrend has exhausted itself. At 12:00 on September 25, all three
lines converged at one point below the 20% level. It was a sign of a
flat and, after that, it’s possible to see a change in the trend
direction.

At point 2, the dotted lines cross and swap – this is the first signal
of a growing movement. The second signal occurs when the green candles
break out of the resistance level built on the significant downtrend
extremes. ADX is still below 20%.

 **2\. Opening a trade.**

One of the effective technical analysis techniques is assessing the
market situation on a higher timeframe and opening a trade on a lower
timeframe. The analysis was done on the H1 interval (previous
screenshot). Here is what I saw:

  * Breakdown of the resistance level
  * A row of rising candles
  * Divergence of + DI and -DI towards a growing trend
  * ADX reversal upwards in the lower zone

Then, I am switching to M30. This isn’t recommended, but you need to
work intuitively and improvise in trading. Here, I notice the same
conditions, but the ADX indicator has already crossed the 20% mark. With
a delay of 1 candle, I still open a 1-lot trade. While observing the
open trade, I simultaneously monitor the situation on an hourly
interval. After 30 minutes, the oscillator rose above 20% on an hourly
interval. All the signs of a trend change are evident.

The H4 interval also showcases an interesting situation. Here, there is
also a crossover of the dotted lines with the signal of a trend change,
but ADX has already bounced off the level 40 and is gradually going
down. This may indicate that you should close a trade that has been
opened on a 30-minute interval within the day.

 **3\. Closing the trade.**

On the hourly interval, the indicator line turned downwards, signifying
the convergence of the dotted lines. I could’ve closed the position on
this candlestick. And if I did that, my profit would be just over $30.
It's not bad for a low-risk strategy.

But I decided to take my chances for the following reasons:

  * The chart analysis shows that the overall downtrend is likely over. Therefore, a large downward candlestick is only a temporary occurrence.
  * The oscillator on the H4 interval shows + DI and -DI continue to diverge with the growth of the index line.

You will find out at the end of the review whether my search for a new
trend succeeded or if the price continued to move in a downtrend. And
while ADX trading is in full swing, I will continue explaining the
theoretical framework.

You can look for trends on stock charts ADX using stock screeners. For
example, go to Investing.com and select Tools / Stock Filter from the
top menu. On the page, select the Technical Indicators tab / ADX, and
set its value in the 20-25 range. In the top menu, set the country and
other parameters. From the drop-down list, select the stocks of the
companies that are included in the LiteForex cabinet, and analyze the
chart in more detail. We have another review – on the [relative strength
index RSI][7] – that describes [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) work with screeners with
screenshots and practical examples.

In detail, with screenshots and practical examples, work with screeners
is discussed in the review of another indicator - the relative strength
index RSI. The analysis is similar.

The ADX indicator has interesting modifications that can be installed in
MT4. The formula remained almost the same, but there are useful
additions to simplify the process of searching for signals:

  * ADX Crossing shows the candles where +DI and -DI cross. The exact moment can be accompanied by a sound alert.
  * ADX Crossover shows when the main index line crosses the set level with an arrow. For example, 20%.
  * ADX Cobra is an independent trading system based on a modified version of the indicator.

Comment below if you need templates for these indicators or if you don't
know [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) download ADX in a modified version.

## Best ADX Trading Strategy

The index can be used in any strategies that involve opening trades on
hourly timeframes and higher. With ADX, you can conduct a preliminary
analysis of whether there is sideways movement in the market and receive
signal confirmation in trend [trading strategies](https://www.fintechee.com/forex-trading-strategies/). It works equally well
on currency pairs, stock, and commodity assets. But it’s not suitable
for “pip” strategies.

One of the most common questions is: "What is the best intraday ADX
strategy?" It is searching for a flat period in the first third of the
day, receiving a signal based on patterns and trend indicators, and
opening a trade when the price exits the flat. In this strategy, ADX
helps differentiate between the start of a strong trend and a false
breakout.

 **How to build your own trading system with ADX:**

1\. Select a strategy type. Due to timeframe restrictions, scalping and
swing trading aren’t suitable. Long-term strategies will result in swap
losses. Intraday strategies are a good option.

2\. Select tools. ADX is an auxiliary indicator so:

  * Choose the main indicator for the strategy. You can find some of them and their descriptions in the Trading Indicators tab. Below, I will give a few examples of successful strategies with the Alligator and RSI but don’t feel limited to use only them.
  * Add the support and resistance levels to the strategy, see whether any patterns form. Patterns and breakout/bounce of levels are additional signals.
  * Analyze the market on higher timeframes and open trades on lower ones.

3\. Remember the fundamental factors. They can drastically affect the
price; meanwhile, the indicators can show lagging data. You’re not
advised to open trades during major [news](https://www.letsplayfx.com/blog/forex-news-website/) on the economic [calendar](https://www.fintechee.com/web-trader/), or at
least increase stops on open trades. If your deposit and collateral can
sustain it. Or close trades.

What is the best ADX strategy depends entirely on you. Above all, you
should be comfortable using it. Therefore, figure out the optimal set of
indicators and their combinations using a demo account. Use the [MT4
tester][8] to check the strategy’s effectiveness.

### Trading Strategy Using ADX and Alligator

The Alligator is a versatile basic indicator with a simple yet effective
calculation formula. Trade theory suggests adding trend tools to the
oscillator - for example, a moving average or a combination of ADX and
EMA. The Alligator is not just a moving average. It is a set of MAs with
different periods that show four stages of a trend - beginning, active
phase, weakening trend, and flat. You can read more about the Alligator
in the review ["Three Most Effective Forex Indicators."][9] One of the
strategies with the Alligator and Anti Alligator is examined in the
review ["Forex strategies for intraday trading."][10]

 **Conditions of the strategy with ADX and Alligator are:**

  * Currency pair - EUR/USD
  * Timeframe - H4
  * ADX (14, 14)
  * Alligator (13.8, 8.5, 5.3)

 **Conditions for opening a long position:**

  * The market is flat. All three moving averages are intertwined and move horizontally. The main oscillator line is below 20-25% and moves horizontally.
  * The moving averages begin to diverge while moving upwards. The oscillator confirms the signal: the index is rising above 20%, the dotted lines diverge, and blue +DI is at the top.

Open a trade on the next candle after all the conditions are met. Stop
loss is set at the previous candle low. Close the trade based on ADX -
when all three lines turn downward.

As you can see from the screenshot, a flat occurs at the divergence of
moving averages t. As soon as the Alligator lines begin to diverge, we
check the oscillator signals and open a trade on the candle indicated by
the red arrow. Close the trade on the candlestick marked with a yellow
arrow, as all three lines of the oscillator turned downward.

 **Conditions for opening a short position:**

  * Again, the market is flat.
  * The moving averages begin to diverge while moving upward. ADX confirms the signal: the index is rising above 20%, the dotted lines diverge, and blue +DI is at the top.

The guidelines for opening and closing a trade are similar.

On a separate period, you can usually see a flat: the oscillator moves
horizontally. As soon as the Alligator's moving averages start diverging
and the oscillator goes up, open a trade. Exit conditions depend on the
situation. There are no perfect signals, so traders sometimes need to be
flexible and use non-standard approaches.

 **Comments on the strategy:**

  * The Alligator is more convenient for opening a trade, ADX, or patterns - for closing. The Alligator can be late with close signals, the oscillator – vice versa.
  * Divergence of two out of three Alligator lines is enough if the signal is confirmed by the oscillator. For example, for a long position, when the green MA crosses the blue one from bottom to top, short - from top to bottom, it’s a signal.
  * A flat before the MA divergence is recommended but not necessary.

Don't be afraid to improvise. The conditions for the strategy are
described in general [terms](https://www.fintechee.com/terms/) and may change depending on the market
situation.

### ADX and RSI Trading Strategy

Another great combination is ADX and RSI. The two oscillators complement
each other perfectly and compensate for each other’s weak points. For
those who aren’t familiar with the [Relative Strength Index](https://www.algotradesoft.org/custom-indicator/relative-strength-index.html), I recommend
reading the RSI review, which goes into detail about what it is, how it
works, the formula, and examples of strategies.

This trading system involves searching for signals based on RSI and
assessing the trend strength by the index. The profits are made from
impulse movements. When RSI enters overbought and oversold zones, it’s
usually interpreted as a potential reversal. This is true only if the
trend is weak. If the ADX shows a strong trend after entering these
zones, the impulse movement will continue for some time. We are
interested exactly in that.

 **Starting point:**

  * Currency pair - [EURUSD][1]
  * Timeframe - H1, H4
  * RSI (14)
  * ADX (14, 14)

 **Conditions for opening a long position:**

  * ADX rises above the 30% level.
  * RSI enters the overbought zone, meaning it rises above the 70% level.

 **Conditions for opening a short position:**

  * ADX rises above the 30% level.
  * RSI enters the oversold zone, meaning it plummets below the 30% level.

The stop length is 20-25 points. Exit the market based on patterns or
the trailing stop.

 **Comments on the strategy:**

  * If the RSI, while being in the overbought and oversold zones, went back a few candles and returned, it’s not considered a repeating signal.
  * Don’t open a trade if RSI enters the overbought or oversold zones and if the ADX is above 40% while moving horizontally or turning downward.
  * Don’t use indicators to exit the market.

 **Example 1.**

 ****

Yellow arrows show points for opening long and short positions.

  * Point 1. ADX - 29.9%, RSI has risen above the 70 level. All conditions are met, the trade would’ve been profitable. A small correction after opening a stop at 20 points didn’t affect it.
  * Point 2. False signal. Despite all the conditions being met, a trade would’ve been closed with a stop. It's not the end of the world; losses would be recouped through other transactions.
  * Point 3. The situation matches all conditions; open a short position.
  * Point 4. Don’t open a trade as instructed in the comments above the screen.

 **Example 2.**

 ****

  * Point 1. The best option for opening a long position. RSI is above 70%; ADX is rising above 30%.
  * Point 2. Don’t open a trade as described in the first paragraph in the comments.
  * Point 3. All signals match the conditions. Open a deal or increase the trade volume following the trend.
  * Point 4. Don’t open a trade as described in the comments.
  * Point 5. All signals match. You can open a trade here.

There can be false signals, but the idea is good enough and follows
solid logic. The target profit for each position is 50-70 points at
4-digit quotes. Stop is at least 20-25 points.

 **So, what happened to the trade I opened earlier?**

As I was writing this review, the trade was already at over $450 in
profit. I didn’t rush to close it at the first falling candle. Also, I
didn’t fully rely on ADX on the 30-minute interval. But I saw that the
trend strength was only increasing on the H4 timeframe, which meant it
was too early to close.

The red arrow on the chart indicates the point of opening the trade.

 **Exiting a trade:**

  * Analyze several timeframes.
  * The indicator is lagging.
  * There are two [options](https://www.fixpro.org/post/options-liquidity/) for closing trades. The conservative option is based on the first signal, as shown in the example, or by a 10-15 point stop. The high-risk one is based on setting stops at a 30-point distance (at least) and holding the trade for more than one day.

The second option turned out to be more effective, since I wasn’t
completely guided by the oscillator data but also levels and Price
Action. ADX assists you, but it can’t be considered the main indicator.

Don't be afraid to take risks if they are justified. Rules are all good
in theory, but only practice allows you to understand what is worth
following and what can be disregarded. Come up with your own trading
systems and be confident in your abilities. You will succeed!

Here is a [link][11] to a demo account that doesn’t require signing up.

## Conclusion

 **ADX advantages:**

  *  **Easy to interpret.** You need to analyze where the main oscillator line is located and the +DI and -DI lines relative to each other.
  *  **Low-effort settings.** Period and smoothing.
  *  **Versatility.** It can be used for any currency pair. It shows both the trend’s strength and direction, works well when the price exits a flat, and allows you to differentiate between the beginning of a trend and a local correction.

 **ADX disadvantages:**

  *  **Lagging.** Don’t expect that any breakout from the 20-25% zone is guaranteed to indicate the beginning of a trend. While the indicator goes upward, the price can reverse.

There are more advantages than disadvantages. I'd like to add that ADX
is one of my favorite basic indicators, along with [stochastic
modifications][12], [moving averages, and RSI][3]. Try to apply the
strategies described in this review using a demo account. And if you
still have questions or want to share your opinion, join the discussion
by leaving a comment!

Good luck!

* * *

P.S. Did you like my article? Share it in social networks: it will be
the best “thank you" :)

Ask me questions and comment below. I’ll be glad to answer your
questions and give necessary explanations.

 **Useful links:**

  * I recommend trying to trade with a reliable broker [here][13]. The system allows you to trade by yourself or copy successful traders from all across the globe.
  * Use my promo-code BLOG for getting deposit bonus 50% on LiteForex platform. Just enter this code in the appropriate field while [depositing][14] your trading account.
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

   1. my.liteforex.com/trading/chart?symbol=EURUSD
   2. www.liteforex.com/[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/trading-indicators/indikator-atr-average-true-range/
   3. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/best-technical-indicators/moving-averages-ema-indicator/
   4. drive.google.com/file/d/1q0-j3IDUsi9a6YxsIKGTqMdzJUUawFX7/view
   5. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/price-action-forex-strategies/
   6. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/forex-scalping-strategy/
   7. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/best-technical-indicators/rsi-relative-strength-index/
   8. www.liteforex.com/blog/for-professionals/metatrader-4-strategy-tester/
   9. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/three-most-effective-trading-indicators-for-forex-traders/
   10. www.liteforex.com/blog/for-professionals/day-trading-forex-strategies/
   11. my.liteforex.com/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=forex_from_the_begining
   12. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/best-technical-indicators/stochastic-oscillator/
   13. my.liteforex.com/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=best-technical-indicators&slug2=adx-indicator-average-directional-index&openPopup=%2Fregistration%2Fpopup&utm_source=blog&utm_medium=article&utm_campaign=bonus
   14. my.liteforex.com/deposit/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=best-technical-indicators&slug2=adx-indicator-average-directional-index&promo_code=BLOG&utm_source=blog&utm_medium=article&utm_campaign=bonus