+++
categories = ["Cryptocurrency", "Blockchain", "SmartContract"]
date = "2020-09-25"
description = "What is RSI indicator? How to Use & Read Relative Strength Index"
tags = ["Cryptocurrency", "Blockchain", "SmartContract"]
title = "What is RSI indicator? How to Use & Read Relative Strength Index"
type = "post"
+++

{{<iframe id="large-banner" src="https://www.bounty.group/#slide=19.0" width="100%" height="600" scrolling="no" style="border: 0px solid rgb(216, 221, 230); border-radius: 3px;">}}

2020-09-25

2020-09-25

[Relative Strength Index](https://www.algotradesoft.org/custom-indicator/relative-strength-index.html) - RSI IndicatorOleg Tkachenko

The relative strength index is an oscillator widely employed in
technical analysis. Many Forex [trading strategies](https://www.fintechee.com/forex-trading-strategies/) for [beginners](https://www.playgroundfx.com/blog/forex-for-beginners/) use it
as a tool to confirm signals to buy or sell. It works like a stochastic
oscillator, MACD, and CCI. There also used the modifications, such as
Silent RSI, RSI Divergence, and others.

The article covers the following subjects:

The article is going to be useful, engaging, and to the point!

## What is the RSI in Stocks: Definition & History

The [Relative Strength Index](https://www.algotradesoft.org/custom-indicator/relative-strength-index.html) (RSI) was developed by J. Welles Wilder, the
author of another standard indicator for МТ4 and МТ5, the ATR indicator.

Wilder first published the description of the RSI indicator in
Commodities magazine in 1978. A few years later, his book New Concepts
in Technical Trading Systems was published, where he described the
technical tool in more detail, using practical examples.

 **What does relative strength index mean? According to the RSI
definition, it is a momentum oscillator that measures the velocity and
magnitude of price movements. It is a dynamic line moving in the scale
from 0 to 100. The indicator compares the closing prices of the current
and the previous candlesticks, indicating the trend strength. How to
read the RSI indicator?**

The relative strength index charts work as follows:

  * The stronger is the relative price movement up, the greater is the total value of rising candlesticks, and the stronger is the uptrend. The oscillator line is close to value 100. 

  * The stronger is the relative price movement down, the greater is the total value of descending candlesticks. So, the stronger is the downtrend, the closer the oscillator line to 0.  

The oscillator is displayed in a separate window under the trading
chart.

Horizontal dotted lines are signal lines, whose parameters are specified
in the settings. The values of 30 and 70 are by default; the levels
scale is on the right of the chart.

  * The overbought zone is between levels 70 and 100.
  * The oversold zone is between the levels of 30 and 0.

These zones are strong as the trend and the oscillator are the most
likely to reverse.

If the trend is clear, the levels of the borders of the range can be
moved to 20 and 80. Levels 30 and 70 are used if the trend is weak, or
the market is trading flat. The longer is the distance between the
signal levels, the less frequent are signals. One the other hand, the
signals are more accurate in this case.

You can employ the indicator in any market. It is equally efficient in
the Forex trading charts, in the securities or stock markets.

## RSI Indicator Calculation & Formula

What does the RSI indicate? By the RSI meaning, the indicator compares
the size of candlesticks (i.e. the trend strength. The longer is the
candlestick, the stronger is the trend) within a particular period
specified in the settings. In general, that is what the rsi indicator
buy and sell signals are based on.

 **RSI formula:**

 **Step 1.** The relative strength index calculates the range of the
positive (U) and the negative (D) change in the price. I will explain
the relative strength index formula below.

  * The period closes up, being a rising (positive) period if the current close is higher than the closing price of the previous period.

U = Price(i) - Price(i-1)

D = 0, where

Price(i) is the close price of the current period (i.e. current
candlestick), Price(i-1) is the close of the previous period.

  * The period closes down, it is a falling (negative) period if the current close price is lower than the previous close.

U = 0

D = Price(i-1) - Price(i)

If both closing prices are equal, then U = 0, D = 0.

 **Step 2.** Calculation of the relative strength.

RS = SMA(N) of U / SMA(N) of D

The formula means that the values of U and D are smoothed with a Simple
Moving Average (SMA) with the N period. One of the sources gives a
simplified formula: RS (Relative strength) is the ratio of the average
gain to the average loss.

 **Step 3.** Calculation of the RSI indicator

RSI = 100 - ( _100 /(_ _1 +_ _RS))_

This is one of the most common calculation formulas, but not the only
one. For example, in adapted versions of the RSI indicator formula, the
price change is smoothed using [Exponential Moving Average](https://www.algotradesoft.org/custom-indicator/exponential-moving-average.html)s. The author
himself suggested using a Modified Simple Moving SMMA.

 **Note 1:** If you use an SMA in the formula. If the trend is steadily
rising, without a single down candlestick for the period written in the
indicator settings, the D value in the RS denominator will be 0. Since
you cannot divide by 0, the oscillator value is considered to be 100.

 **Note 2:** The above formula describes the general principle of the
index calculation, it is not a constant. According to it, when the
period is 2 for an uptrend, the index value must be 100. The actual
value in the screenshot below is 89.

If you want to explore the formula and understand in more detail, and
you know the MGL programming language, you can open the code. In the MT4
menu, enter the File/Open data folder. In the window that opens, go to
the directory “MQL4/Indicators”, find there an mql4 file, and run it. It
will open in Word.

### RSI Calculation Excel Sheet

I have prepared the relative strength Calculator template for technical
analysis. The Excel file includes an algorithm for calculating the
[Relative Strength Index](https://www.algotradesoft.org/custom-indicator/relative-strength-index.html), you can also draw diagrams using the RSI values
you enter.

You can download the RSI calculation excel [Sheet here.][1]

## Set up and custom RSI

You don’t have to set up the standard version; the oscillator is in
almost all trading platforms. It is a little more difficult with the
modifications. You have to set them up onto the trading platform
yourself. Moreover, the indicator code must be compatible with the
trading terminal code. For example, for the MT4 platform, it should be
the MQL4 programming language. If the trading platform doesn’t suggest
adding indicators, you can’t trade with the RSI’s combined versions. If
you want to download a modified version, let me know in the comments
section. I will write to you where you can get working templates.

### Using the RSI indicator in the trading terminal

 **Install the [Relative Strength Index](https://www.algotradesoft.org/custom-indicator/relative-strength-index.html) in the LiteForex trading
terminal:**

1\. In your profile, open the trading chart of any currency pair. For
example, [AUD/CAD][2]. Click on the trade TRADE on the left menu, go to
the Currencies section, and click on the currency pair you need.

2\. At the top of the chart, click on the Indicators tab, and choose the
**RSI Indicator.**

It will appear under the price chart. To see the custom window, click on
the corresponding icon (marked with the arrow on the screenshot below).

RSI settings:

1. Parameters:

  * Length (period). It is the number of candlesticks, which the oscillator analyzes to indicate the average value. The default period is 14. It means that the price change for the last 14 is considered. If the period is 25, the oscillator analyzes the last 25 candlesticks.
  * Source is the type of price that is considered in the formula. By default, it is the close price. You can also set the open price, the high or the low. There are three variants of median prices.
  * Accuracy. The levels value the value of the levels with precision to the fourth decimal place. If the parameter 0 is set, the value of the levels is 30, 70, etc. If the parameter is1, levels are 30.0, 70.0, etc.

2\. Style:

  * RSI line (lines color). You can choose the thickness and the color of the lines, levels, and the fill color between the levels.
  * The **RSI values** of levels (upper limit/lower limit). The default limits in the LiteForex trading terminal are 30 and 70. You can change them according to your trading strategy.
  * Enable/Disable indicator lines, levels, fill.

The LiteForex terminal’s advantage is that you will immediately see any
change on the chart next to the settings window. You need to click "OK"
or "Apply" to activate other trading platforms’ changes. On the
LiteForex platform, you see the customs’ adjustments immediately without
unnecessary keystrokes and the need to call the settings window again.

### RSI for MT4

In MT4, you install and configure the [Relative Strength Index](https://www.algotradesoft.org/custom-indicator/relative-strength-index.html) in a
slightly different way from the same procedure for the LiteForex trading
terminal, but the general principle is similar.

1\. In MT4, you install and configure the indicator in a way that is a
little different from the same procedure for the LiteForex trading
terminal, but the general principle is similar.

2\. Open the custom window:

2.1. Parameters:

  * Period is the same as the Length parameter in the LiteForex terminal. It stands for the number of candlesticks analyzed. The most recent candlesticks are analyzed.
  * Apply to – is the price type. Unlike that in the LiteForex terminal, there are more [options](https://www.fixpro.org/post/options-liquidity/). Previous Indicator’s Data and First Indicator’s Data. MT4 allows one to apply indicators not only to the price chart but also to other indicators. If you want to know what this function is for, how you can use it and what the advantages of superimposing one indicator on another are, write in the comments,, and I will explore this matter in a different overview.
  * Style includes the thickness and color of the lines.
  * Fixed minimum/Fixed maximum. This option sets the chart window in the level range you enter. For example, if you enter the RSI values of 40/60, the indicator window will display only the content between the levels of 40 and 60.

2.2. Levels:

You can set the parameters of the level in this tab: the RSI values, the
color, and the style of the lines. A good option is setting additional
levels using the Add button.

2.3. Visualization:

 This tab allows you to set the indicator visualization on all
timeframes or some of them.

 **Drawbacks of the MT4 compared to the LiteForex terminal:**

  * To apply the settings, you need to click on the OK button, then call the parameters window again by clicking the right mouse button and entering the "List of Indicators - Properties" menu. Everything is more straightforward in the [LiteForex][3] terminal. First, all changes to the settings are displayed right there (no need to click OK, which I mentioned above). Second, to open the settings window, just click on the corresponding gear icon next to the chart’s indicator name.
  * There is no color fill between the levels.
  * You can’t set the levels with the accuracy of a few decimals.

### RSI for MT5

In MT5, the [Relative Strength Index](https://www.algotradesoft.org/custom-indicator/relative-strength-index.html) is set in the same way as in MT4.
You go to the Insert menu and open the Indicators tab. The properties
window has a few differences:

  * The [options](https://www.fixpro.org/post/options-liquidity/) of Fixed maximum value/Foxed minimum value is moved from the Parameters tab to the new Scale tab.
  * The Levels tab is the same as in the MT4.
  * There are two new [options](https://www.fixpro.org/post/options-liquidity/) in the Scale tab: Inherit scale and Scale by line.
  * The Visualization tab hasn’t changed. The developers have changed only the visualization of timeframes and added new periods. 

To sum up, there are hardly any differences between the MT4 and MT5
platforms concerning the installation and customization of the
oscillator.

## RSI Trading Strategies

The most popular RSI [trading strategies](https://www.fintechee.com/forex-trading-strategies/):

  1.  **Building horizontal and diagonal levels and entering trades on the breakout.** You draw the level according to the oscillator reference points, which helps you build a similar price chart level. As the indicator sends early signals, you can see the breakout point in advance.
  2.  **Overbought - Oversold (OBOS) Levels.** This RSI indicator strategy suggests spotting the trend pivot points. The trend reverses when the market is overheated, and there is an imbalance in the volumes of buy or sell orders. 

At these moments, the index is in the overbought or oversold zones. If
the indicator line goes higher than level 70, you shouldn’t buy the
asset.

The strategy implies that you should wait until the index line reverses
in the overbought zone and enter a short trade, according to some
additional signals. The same is relevant for entering a long trade when
the indicator turns in the oversold zone.

  3.  **Divergence.** It occurs when the indicator line goes in the opposite direction to the price chart. It means a soon trend reversal.
  4.  **Failure swing.** It occurs when the oscillator draws an M or a W pattern. You open a position on the trend correction after the pattern forms,, and the signal level is broken out.
  5.  **Cardwell’s trend confirmations.** The strategy employs levels shifted in the price trend direction. It suggests entering trades when the indicator reverses and rebounds from the strong levels. The levels for an uptrend are 40 and 80, for a downtrend – 20 and 60.
  6.  **Cardwell’s positive and negative reversals.** It is the same as the inverse divergence.

Next, I will explain all the above Forex RSI strategies and the signals
to buy and sell. I will also give you real-life examples.

 **Important:** The [Relative Strength Index](https://www.algotradesoft.org/custom-indicator/relative-strength-index.html) indicator features common
flaws. The signals are lagging, and the indicator repaints. So, the tool
mostly serves as an additional confirming tool to supplement trend
indicators, technical patterns, etc. Do not enter trades based only on
the oscillator signals.

### Potential Buy & Sell Signals

The RSI indicator well combines with the classical graphical analysis

It is clear from the screenshot that the price lows coincide with the
reference points of the price relative strength at the level of 28. Note
that the line breaks through the resistance level earlier than the price
actually reverses, signaling the breakout in advance. A sell signal is
sent when the oscillator breaks out the level built according to the
reference points; it is level 28 in our example.

Another example, taken from the MT4. The MT4 chart is sometimes more
convenient to study [historical](https://www.fintechee.com/services/historical-data-for-forex/) data.

The thin red ovals mark the reference points of the indicator coinciding
with level 30. When the indicator breaks through level 30, there is a
trading signal. It is an early signal. According to graphical analysis,
the entry would be at the point marked with the green circle.

 **Notes on the strategy:**

  * Trade in the short-term timeframes, М15-М30
  * The period is less than 14. I used the period of 9 for the EUR/USD.
  * Zoom out the chart using the scroll or the minus sign. This way, you will extend the period of the chart display without changing the time frame.

###  Overbought - Oversold (OBOS) Levels

The relative strength index overbought oversold levels are the signal
levels, whose default parameters are 30 and 70. When the index line goes
beyond these levels, it means that the market is overbought or oversold.
When the indicator line reverses in these zones, it could signal the
change in the trend direction or a deep correction. However, the trend
may go sideways, as in the figures below.

Look for entry points when the lines go back to the range:

  *  **Early signal.** The oscillator turns up in the oversold zone or down in the overbought zone.
  *  **Primary signal.** When the oscillator breaks out level 70 downside, enter a buy trade. If it breaks level 30 upside, enter a sell trade.

With the input parameters (14) for the [EUR/USD][3] pair and the M15
timeframe, four signals appeared.

The first turned out to be weak, although ultimately, the pullback would
not have triggered the stop,, and the trade would have yielded a profit.
The second one is a perfect trade signal. The third is false. The fourth
is true but weak.

Do not strictly follow the default levels parameters of 30 and 70. Use
the 5% rule. Find in the [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) timeframe the sections where the
oscillator’s extreme values for the past three months haven’t lasted
more than 5% of the time. Move this level to your trading chart
timeframe, revise the level values every 5-10 bars.

Example:

Over the past three months, the indicator hasn’t entered the oversold
zone. So, we refer to only the overbought level 76 suits.

We set 76 in the customs and go to the working timeframe. The trades are
entered according to the same principle.

The indicator should break through the strong level when it goes outside
the overbought oversold zones.

 **Notes on the strategy:**

  * When the indicator line crosses the signal level, you enter trades when the price goes in the same direction as the indicator. If the indicator goes against the trend, ignore the signal.
  * Do not strictly follow the 5% rule; it is general. Visually estimate the extreme levels, and identify the levels for each instrument separately.
  * Be flexible. The 5% rule reduces the number of signals, but they are more accurate as you enter trades earlier. Find out your optimal combination of the period, levels, and the frequency of signals. 

### RSI Divergences

Divergence occurs when the indicator and the price chart go in opposite
directions due to lagging. The [Relative Strength Index](https://www.algotradesoft.org/custom-indicator/relative-strength-index.html) is a leading
indicator, so the price chart is usually lagging. If the price chart
continues the trend, and the signal line has reversed, it is divergence.
Divergence signals the trend reversal.

 **Types of divergence:**

  * Bullish. Price lows are getting lower; indicator lows are rising.
  * Bearish. The price highs are going higher; the indicator highs are going down.

You can learn more about the divergence in this [overview][4].
Divergence looks like this in the chart:

The signal is the strongest when the divergence occurs while the
indicator line is in the overbought/oversold zone. A weaker, but still
relevant movement is when at least one of the divergence high/low is
above level 70 or below level 30.

The above figure displays the bullish divergence. The levels are drawn
across two lows; the indicator line hits one of the lows below level 30.
The trend reversed up after the divergence.

 **Notes on the strategy:**

  * You can spot divergence in any timeframe.
  * Highs/Lows on the price and indicator charts should visually coincide.

You enter a trade after the price turns in the direction of the
indicator line. The entry point in the screenshot is at the bar that is
marked by the arrow.

### RSI Failure Swing: Bullish & Bearish

RSI indicator perfectly combines with the Price Action trading
strategies. One of the Price Action patterns is a Failure Swing. It is
based on the false breakout of a significant High or Low of the previous
swing.

  *  _Note. The swing strategy suggests entering trades on the local correction and pullbacks at the moment of the primary price rebound. You can learn more in this[overview][5]._

When the index is in the overbought/oversold zones, the oscillator line
tries to break through the previous high/low. Next, it turns back to the
median level. For the RSI overbought zone, the pattern looks like M; it
is a W-shaped for the oversold zone.

There is an M-shaped pattern. The indicator line draws the first top in
the RSI overbought zone, turns down, and breaks out level 70. Next, it
again tries to test the top, but the second high is lower and is not
explicit.

Buyers can’t repeat the first high. It is clear not only from the
movement of the oscillator line but also from the trend character. The
candlesticks’ bodies are getting smaller as the price approaches the
peak, drawing a[ Pin Bar pattern][6]. All signals indicate that you can
enter a trade at the moment of the trend reversal.

I’ll explain how this method relates to swing trading. I zoom in the
chart.

The uptrend’s local high (depicted in the previous figure) is one of the
corrections of the price downtrend. The oscillator helps pick up the
moments when the price reverses in the direction of the corrections’s
primary trend.

 **Notes on the strategy:**

  * You need additional indicators to confirm signals.
  * If the second top (bottom) is farther than the first, you enter a trade when the signal level is broken out.
  * Signal levels are 30 and 70. You should not change the values.
  * Change the chart scale to identify the local trend relative to the global direction.

### Cardwell’s trend confirmations

Andrew Cardwell suggested an rsi trading strategy, different from the
approach defined by Wilder. For example, instead of the normal signal
levels 30 and 70, he offered to consider the values of 40 and 80 for an
uptrend, 20 and 60 for a downtrend separately. He claims that a strong
uptrend won’t retrace to the RSI overbought zone, as well as a strong
downtrend won’t reach the RSI oversold zone. So, the indicator line
should be moving between levels 40 and 60, which serve as support and
resistance levels. Cardwell’s trend confirmation is when the price
rebounds from these levels.

 **Trading in the bullish and bearish trend:**

  * In a bullish trend, the indicator line is most of the time between levels 40 and 80. Level 40 is a strong support level. When the price rebounds up from level 40, it is the right time to open a long position.
  * In a bearish trend, the indicator line is most of the time between levels 20 and 60. Level 60 is a strong resistance level. When the price rebounds down from level 60, it is the right time to enter a short trade.

As you see from the above figure, the trend is up. The indicator line is
most of the time between levels 40 and 80. Both signals at the moment of
touching level 40 are strong and true. Note that you should not consider
the price rebound from level 80 as a signal to enter a trade in the
uptrend.

The market situation displayed in the above screenshot is not that
clear. The trend is down, but the price rebounded from level 65 in the
second case.

 **Notes on the strategy:**

  * In the bullish trend, you’d better trade in the timeframe starting from M30 and longer with a period of not less than 14. If the period is 9, the indicator often falls to level 30 and turns down from the median level of 50. If you reduce the period, there will be more than 50% of false signals.
  * You shouldn’t stick to only the levels suggested by Cardwell. He gave a general idea, and you should adjust it to each particular timeframe and currency pair.

### Positive & Negative Reversals

Positive and negative reversals is another trading approach offered by
Cardwell. He noted that the rule of direct divergence is not often
observed. For example, a positive reversal occurs when the next low is
higher than the low of the previous correction down in the uptrend.

Simultaneously, the next low of the oscillator forms lower than the low
of the previous correction. Despite the divergence between the price and
the oscillator movements, the price continues running up after a small
decline. This situation is called inverse divergence.

For the negative reversal, the situation is the opposite. If the
indicator forms a higher high, and the price makes a lower high, the
market will continue declining.

 **Trading the opposite direction:**

  * If the price goes up, and the oscillator line runs down, the price will jump up.
  * If the price goes down, and the oscillator line moves up, the price will fall.

In the above figure, red lines mark the bearish divergence spotted based
on the highs. Green lines mark Cardwell’s positive reversal levels. The
divergence drawn across the highs should have signaled a bearish
divergence and a soon price reversal down. However, the price continued
rising.

 **Notes on the strategy:**

  * Cardwell’s ideas are different from the trading theory suggested by Wilder. This proves that there are universal rules in technical analysis.

## RSI Stock Screener

It is related to the stock RSI meaning. The oscillator is used not only
to analyze the Forex market and the [Forex trading](https://www.fintechee.com/forex-trading-strategies/) signals. One can also
employ stocks [Relative Strength Index](https://www.algotradesoft.org/custom-indicator/relative-strength-index.html) in the stock market to spot
separate securities for short-term investments.

There are thousands of equities traded in the global stock market. One
of the ways to select stock for investment is the stock screener.

The stock screener is an analytical platform that provides information
on securities. The advantage of screeners is that they offer dozens of
filters to sort and group the shares based on any parameter. A screener
could be both a [website](https://www.playgroundfx.com/blog/website-for-forex-trading/) and a part of an analytical information portal.

Read a detailed overview of screeners [here][7].

What does RSI mean in stocks? One of the filter parameters is the data
of technical indicators, for example, the RSI stock indicator. Investors
should find securities that are currently overbought or oversold and
carry out a deeper analysis. You will know if it will be profitable to
buy or sell a particular paper.

 **Examples of screeners:**

1. [Investing][8]. It is an analytical portal that has a built-in
screener.

  * In the main menu, enter the tabs Instruments -Stock Screener.
  * In the window that opens, custom the information parameters: country, exchanges, sector, and so on.
  * In the criteria window, select Technical analysis, and click on the needed tool (RSI). Set the values for the RSI overbought zone.

There are [amazon][9] shares in the below list. I open the LiteForex
trading terminal:

Everything is correct. Thanks to the screener, I didn't have to revise
all the charts of the securities. You can also filter shares by other
indicators and criteria.

The disadvantage of Investing is that you can select securities only by
the RS index with a period of 14 in the 1D timeframe.

2. [Finviz][10] is another financial analytical portal. It offers more
filter parameters. However, the screener analyzes only the US stock
market.

## Example of successful RSI trading strategy

Using RSI in Forex trading. As an example, I will take the [EUR/ZAR][11]
currency pair in the M5 timeframe. I want to demonstrate to you [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/)
enter a profitable trade, rather than make the maximum profit.

 **Analyzing the above chart, I see the following:**

  * The downtrend has broken out the strong resistance level. Zooming in the chart, we see that the price hasn’t fallen so deep for more than ten days.
  * The [Relative Strength Index](https://www.algotradesoft.org/custom-indicator/relative-strength-index.html) with a period of 14 and signal levels of 30 and 70 suits to trade this pair.
  * There starts forming a W-shaped failure swing pattern.

The price is likely to reverse soon, considering several signals. The
resistance level is broken out, the indicator line enters the overbought
zone, and there is forming a pattern. We expect the trend reversal and
enter a trade when the indicator line breaks out level 30 from below.

Now, the matter is when we should close the position. We could have
waited until the index goes up to level 50. We could have also presumed
that there is the beginning of the new strong uptrend.

According to Cardwell’s RSI meaning in stocks, the price rise could be a
local correction within the ongoing downtrend. So, I do not risk and
exit the trade at the first sign of the trend reversal.

I am correct. The trend, following the local correction, has resumed
running down. Furthermore, I made a profit on the local correction
(marked with the arrow in the screenshot).

RSI trading has yielded a small profit in a short time. This is an
example of a scalping strategy.

You can combine the RS oscillator not only with the trend, channel
indicators, or graphical analysis but with other oscillators as well.
For example, there is the rsi trading strategy Triple confirmation.

It is based on the combination of the RSI, CCI, and stochastic. One
enters a trade when the signals of all the three tools coincide. Signals
are rare, but the accuracy is more than 80%.

## [Relative Strength Index](https://www.algotradesoft.org/custom-indicator/relative-strength-index.html) (RSI) FAQ

## Summary of the RSI Forex [trading strategies](https://www.fintechee.com/forex-trading-strategies/)

I will sum up in a few paragraphs:

1\. [Relative Strength Index](https://www.algotradesoft.org/custom-indicator/relative-strength-index.html) is a leading indicator measuring the trend
strength. It is used to confirm entry signals.

2\. The index value changes in the range from 0 to 100. The default
signal levels are 30 and 70. The price range between levels 30 and 0 is
the overbought zone. The range between 70 and 100 is the RSI oversold
zone.

3\. The indicator works in any timeframe. The default period is 14. For
minute timeframes, you can set a period of 5, 7, 9. For the [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/)
timeframe, the period is 25.

4\. The significant signals delivered by the RS index.

  * The reversal in the overbought zone and crossing the level from above is a signal to enter a long position. The reversal in the RSI oversold zone and crossing level 30 from below signals a short entry.
  * Divergence. The indicator line and the price chart go in opposite directions. It signals a soon trend reversal.

5\. The values of the signal levels adjusted to each currency pair and
timeframe. The settings are:

  * Levels 40 and 80 are for a bullish trend. Levels 20 and 60 are for a bearish trend.
  * 5% rule. You set such a level on the [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) timeframe, above/below which the indicator line has been no longer than 5% of the time for the last three months.

6\. **** You exit trades according to the market situation. You close
the position in the following cases:

  * When the indicator line abruptly reverses in the range between 30 and 70.
  * When the indicator reaches the median level 50 (conservative strategy).
  * When level 50 is reached, you close half of the position. The rest of the position is protected by the stop at the breakeven and is closed when the oscillator reaches the opposite signal level (aggressive trading).
  * There appears a reversal pattern.
  * The price reaches the take profit level.

You can read a detailed overview of [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) use your personal profile
[here][12]. I’d like to remind you that you still can take part in the
[LiteForex dream draw][13]. Register with LiteForex, enter trades, be
confident in yourself, and you will succeed. If you still have
questions, write them in the comments and I will be glad to answer!

I wish you successful trading!

* * *

P.S. Did you like my article? Share it in social networks: it will be
the best “thank you" :)

Ask me questions and comment below. I’ll be glad to answer your
questions and give necessary explanations.

 **Useful links:**

  * I recommend trying to trade with a reliable broker [here][14]. The system allows you to trade by yourself or copy successful traders from all across the globe.
  * Use my promo-code BLOG for getting deposit bonus 50% on LiteForex platform. Just enter this code in the appropriate field while [depositing][15] your trading account.
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

   1. drive.google.com/file/d/1Cx49mNcqX7JrFzbXdZ6DZRDvKtWGHxRn/view?usp=sharing
   2. my.liteforex.com/trading/chart?symbol=AUDCAD
   3. my.liteforex.com/trading/chart?symbol=EURUSD
   4. www.liteforex.com/blog/for-professionals/what-is-divergence-on-forex/
   5. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/swing-trading-strategies/
   6. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/pin-bar-how-to-identify-a-liar/
   7. www.liteforex.com/blog/for-[investor](https://www.fintechee.com/tutorial-for-forex-trading/investor-mode/)s/screener-stocks-guide/
   8. www.investing.com/
   9. my.liteforex.com/trading/chart?symbol=%23AMZN
   10. finviz.com/
   11. my.liteforex.com/trading/chart?symbol=EURZAR
   12. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/lets-look-into-liteforexs-new-client-space/
   13. lite.forex/contests/dream-draw/
   14. my.liteforex.com/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=best-technical-indicators&slug2=rsi-relative-strength-index&openPopup=%2Fregistration%2Fpopup&utm_source=blog&utm_medium=article&utm_campaign=bonus
   15. my.liteforex.com/deposit/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=best-technical-indicators&slug2=rsi-relative-strength-index&promo_code=BLOG&utm_source=blog&utm_medium=article&utm_campaign=bonus