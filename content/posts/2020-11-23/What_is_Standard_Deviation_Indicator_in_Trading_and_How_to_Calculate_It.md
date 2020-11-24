+++
categories = ["Cryptocurrency", "Blockchain", "SmartContract"]
date = "2020-11-23"
description = "What is Standard Deviation Indicator in Trading and How to Calculate It"
tags = ["Cryptocurrency", "Blockchain", "SmartContract"]
title = "What is Standard Deviation Indicator in Trading and How to Calculate It"
type = "post"
+++

{{<iframe id="large-banner" src="https://www.bounty.group/#slide=4.0" width="100%" height="600" scrolling="no" style="border: 0px solid rgb(216, 221, 230); border-radius: 3px;">}}

2020-11-24

2020-11-23

Standard deviation indicatorOleg Tkachenko

How do we determine current volatility and trend strength? At which
distance from the price mean value and market entry point should we
place a stop loss? Is the market flat at the moment? The Standard
deviation indicator can answer all those questions. Read on to find out
how it works and how it is used in trend strategies combined with other
indicators.

The article covers the following subjects:

## What Is a Standard Deviation Indicator

Trading borrowed the idea of standard deviation from descriptive
statistics, which is a branch of mathematical analysis. The standard
deviation is an indicator of the data average deviation value compared
with their mean value over a chosen period. In statistics, it's denoted
by the Greek letter (σ), or sigma.

Before examining the Standard deviation indicator, let's recall why a
trader should consider volatility and what [SMA][1] means.

### Volatility

Volatility means a price change range over a certain time period. In
trading, it is used in the following ways:

  * For trend identification. If there is no volatility, there is no trading. If the price doesn't deviate from its average value, it's impossible to open a trade. The growth of volatility means that a big price move emerged.
  * For identifying a trend’s end and an eventual reversal. If volatility reaches its peak, the trend is about to end. The extremums are visually compared with similar extremums over the previous periods.
  * For placing stop orders. If market volatility is moving in both ways, at which distance from an open trade should we place a stop loss so that the price line doesn't touch it? - According to larger time frames’ mean volatility. Take Profit orders can be placed in the same way.

There are different ways of measuring volatility. For example, 1-day
volatility on a [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) time frame is the distance between High and Low
prices expressed in points. These values can be found in the calculator
on the [site of Investing][2], for example.

Volatility can also be measured relative to the moving average: the
higher the price, the higher volatility.

Another method suggests comparing the current price change in % with the
previous period's closing price. If the change range doesn't exceed 3%,
volatility is low. If the price changes by 10%, volatility is high.
These values are relative and depend on a currency pair.

### Simple moving average

The SMA is a technical analysis indicator calculated as the average of
chosen prices. Its disadvantage is that it doesn't consider price
volatility inside a price range. Let's take two numerical sequences as
an example:

  * 8, 7, 12, 2, 6.
  * -30, 66, 7, 12, -20.

Can we say they are identical as the SMAs are equal to 7 in both cases?
No, we can't. The price ranges are different even if their averages are
the same. This variation of prices is called "volatility".

### What Is Standard Deviation

In trading, the arithmetical mean is a [simple moving average][2]. The
price can deviate from it. The more the price deviates from its average
value, the higher the volatility. Volatility is measured by the Standard
Deviation (StdDev) indicator.

The Standard Deviation is a trend indicator: it serves to identify the
moments of trend strengthening. The higher volatility, the stronger the
trend is. Since it measures price deviations from the average value in
both directions, this tool is also used in channel indicators. If the
indicator's value is relatively small, the market is bored and a price
spike should be expected. Inversely, when the indicator's value is too
high or even extreme, traders' activity will slow down soon.

### Specifics of Standard Deviation Indicator:

  * The Standard Deviation Forex Indicator is efficient when applied to high and medium volatility tools.
  * It is used in trend strategies to determine when the price leaves a flat range and starts trending. It isn't suitable for scalping due to lags.
  * You’d better use it for currency pairs than for stocks or commodities. The currency market is characterized by frequent trend changes and deep corrections during which we can search for entry points. The stock market is more stable.
  * The optimal time frame starts at M30. On shorter time frames, such as M1-M5, there can be chaotic price moves that interfere with the indicator's construction logics.
  * The Standard Deviation Forex Indicator often moves horizontally in lower points and rarely indicates a horizontal plateau at extremums. After growth begins, movements are most often wavy.

One of efficient strategies is looking for growing volatility on a
longer time frame and using this move 1-2 time frames lower.

#### Advantages of Standard Deviation Indicator:

  * Simple reading. The higher the indicator's value, the higher price volatility.

#### Disadvantages of Standard Deviation Indicator:

  *  **Lags.** The price blue line may have already left the flat zone while the indicator says volatility is low.
  *  **It doesn't show a trend direction.** When the standard deviation line starts growing, the price deviates from its average value more and more, but the deviation can be upward or downward.

Trades aren't usually opened based on a volatility level alone, so
Standard Deviation reading is rarely used in independent trading
systems. It can be combined with trend indicators as a tool for signal
confirmation. I'll analyse some interesting strategies based on a
combination of Standard Deviation with another volatility indicator,
ATR, and Fibonacci levels.

## How to calculate standard deviation

Standard Deviation is a mean-square deviation. It's a mathematical term
that measures the degree of dispersion of random variables. Its
calculation formula is

, where

  * N - means number of price values in a set specified in the indicator's settings.
  *  _Хi_ \- i-th member in the set. By default, it is each candlestick’s closing price over the chosen time period.
  *  _Xavg_ \- X is the arithmetic mean of all price values in the set. In technical analysis [terms](https://www.fintechee.com/terms/), it's a simple moving average (SMA).

Here's step-by-step calculation of the indicator's value:

  1. Calculate the arithmetic mean value over the chosen period. For example, if the period is set at 20, the price arithmetic mean is calculated for the last 20 candlesticks. Closing prices are used by default.
  2. Subtract the result from each price's value.
  3. Square the values and sum them up.
  4. The final value is divided by the number of values in the series, i.e. the number indicated in standard settings as the period.
  5. Extract the square root of the result. This is the standard deviation.

An example of standard deviation calculation in Excel:

Calculation stages:

 **1.** Enter the price values in column B. You can take these values
from MT4 or ask your broker. The number of lines corresponds to the
indicator's period. By default, the table has 20 lines.

 **2.** Enter the formula

 **=AVERAGE(B2:B21)**

in cell С21.This is the arithmetic mean, called "simple moving average"
in technical analysis.

 **3.** Calculate the difference of the price's each value and the
arithmetic mean. Enter

 **=B2-$C$21**

in cell D1. Apply the formula to all the cells.

 **4.** Calculate the square of values. Enter the formula =D2^2 in cell
E2. Apply the formula to all the cells.

 **=D2^2**

 **5.** Sum all the previous column values in cell F21 and divide the
result by 20 in cell G21.

 **6.** Calculate the standard deviation in cell Н21 using the formula

 **=G21^(1/2)**

You can find the table’s template [here][3]. You can also find standard
deviation calculators on the internet, but copying quotes into them
isn't convenient whereas they can be easily uploaded to Excel.

## Using the Standard Deviation in trading

Standard Deviation Forex indicator is used in trend trading. If the
indicator is at its peak or is growing most of the time, it's too late
to open a trade. Wait for a flat period or a trend reversal. A signal to
open a trade is the indicator's line growing from its lows.

 **1\. Strategy of Trading flat breakouts**

It's a conservative strategy. The price doesn't deviate too much from
its mean value in a flat range, and the indicator is located at the
bottom. A signal to open a trade is produced when StdDev starts growing
and goes outside the flat range. Once the candlestick breaks out the
flat range, open a trade on the next candlestick following the trend.
Close the trade once the indicator starts reversing.

 **Example**

StdDev's penultimate wave was trending down and then switched to a
sideways trend. The indicator's maximum value in a horizontal range was
0.0009. In point 1, the price line broke out the resistance level, and
the green candlestick closed almost at the previous local peak's level.
StdDev started growing simultaneously, reaching the value of 0.0011. A
trade was opened.

In point 2, on the red candlestick that could predetermine a reversal,
StdDev started to reverse too. The trade was closed. The profit could be
at least 300 points in 5-digit quotes.

 **2\. Strategy of identifying an early trend reversal**

It's an aggressive strategy that implies an early opening of trades
based on Standard Deviation waves. Its advantage is that it allows
solving the issue of lags. Signals are produced more often as we don't
need to wait for a flat range, but they are often produced falsely
compared with the previous strategy.

Conditions for opening trades:

  * Draw a support level for StdDev through its lows. Take a period of 2-3 weeks for the H1 time frame.
  * Open a trade once the indicator has crossed the support level and continued growing.
  * The trade's direction is identified as follows: if the previous wave's half was trending downwards, open a long position. If the previous wave's half was trending upwards, open a short position.

If a flat range preceded the previous wave's half, follow the previous
strategy. If the wave has two and more tops, divide it by half. If the
wave can't be clearly identified, is asymmetrical, or its beginning and
end can't be clearly identified, ignore the signal.

 **Example**

The indicator touches the level in 4 points. The wave's half located
before point 1 was trending up, so we open a short position in that
point. The same is true of point 2. In point 3, there's a double-top
wave, so we calculate its half from the bottom. The trend is upward, so
we open a short position in that point. The chart’s flat in point 4. We
don't open a trade until candlesticks point to a trend direction.

We'd better ignore the signal or search for its confirmation as such
signals are indecisive in such situations. We can't clearly identify the
wave in the first case, and the wave is asymmetrical in the second case.

### High standard deviation

There's a numerical sequence of the last five candlesticks' closing
prices: 4, 5, 3, 4, 6. The dispersion is relatively small. The
arithmetic mean is 4.4. The minimum and maximum prices will be 3 and 6,
which is 31.8% and 36.4%, respectively. Let's say such deviations are a
normal situation corresponding to a flat range for that tool over that
time period.

The price starts gradually growing. There's another sequence three
candlesticks later: 4, 6, 10, 14, 13. The average price is now 9.4. The
minimum and maximum values are now 4 and 14, which is 57.45% and 48.93%.
In the first case, the price deviated from its arithmetic mean by one
third on average; now the price has deviated by 50% on average.

Volatility is growing. Now let's check the deviation readings. In the
first case, they are

In the second case, they are

The standard deviation increased by more than 3 times amid the growth of
price and volatility. A high standard deviation means that the price
changes in either direction. The Standard deviation growing with every
candlestick means the market is trending, and the price deviates more
and more from its average value in either direction. Once the Standard
Deviation reaches its peak, the following scenarios are possible:

  * The price moves into a flat range. The price range will look like this three candlesticks later: 14, 13, 15, 14, 12. The arithmetic mean will grow and the SMA will move higher in the chart than in the first situation. However, the standard deviation will return to the value of 0.5099 again. The indicator's chart will display a wave with flat values of 0.5099 and a peak value of 1.9391.

  * The price will reverse. The price range will look like this three candlesticks later: 14, 13, 8, 5, 7. The SMA's value will equal 9.4 and the Standard Deviation Indicator's value will be 1.7493, which is practically the same level despite the trend direction change.

It looks like the following:

The question is what should be called "a high standard deviation". To
understand how long a market trend will last, we need to compare the
current Standard Deviation value with other visual extremums.

The dotted line in the screen above is at the Standard Deviation's
average level. Most often, the indicator was below that level or crossed
it for a short time. Thus, the values located much higher than that
level can be considered high.

  * The local extremum is in point 1. The flat range starts when the indicator's line is reversing. The flat areas are marked as red rectangles in the screen shot.
  * StdDev continues growing in point 2 located at the same level as point 1. It means the trend is uninterrupted, but may end soon. The indicator's line reverses in point 3, and a flat range begins.
  * In point 4, with StdDev's peak value, there's a trend reversal. Since the reverse ascending movement isn't as powerful as the previous descending one, the indicator goes down.
  * Flat range emerges in points 5 and 6 when the indicator is reversing.

 **Conclusion.** A high standard deviation may mean that an uptrend or a
downtrend continues, but it's already too late to enter the market. The
standard deviation's peak value and subsequent reversal mean the trend
will reverse or turn into a flat range.

### Low standard deviation

A low standard deviation means that the price holds on to its average
value calculated over a certain time period. It can mean the following:

 **1\. The market is flat.** The volumes of bulls' and bears' orders are
almost the same, or trade volumes aren't big enough. The price holds on
to its average value

 **Example:**

The 20 EMA, corresponding to StdDev's period of 20, is added into the
chart. The standard deviation line is moving at the bottom, close to the
level of 0.0009. A low standard deviation corresponds to a flat area,
where prices move in a narrow range. Once the price breaks the range's
lower limit, the standard deviation starts growing and the price starts
deviating fast from the SMA.

 **2\. The current price movement is smooth.** The price changes step by
step with a small deviation from its previous value.

 **Example:**

StdDev's value can be called low compared with peak values and waves in
the shaded area. Still, that segment is trending smoothly down.

 **Conclusion.** A low standard deviation can indicate a flat area or a
smooth ascending or descending trend.

>  **Attention:** the time period set in the Standard Deviation Forex
indicator's settings is essential here. For example, the standard
deviation in the numerical sequence of 5, 6, 30 for period 3 will be
relatively low (4.4759). In contrast, the standard deviation in the
numerical sequence of 4, 3, 6, 5, 7, 5, 6, 5, 6, 30 for period 10 will
be relatively high (5.3108.) The longer a stable price range and the
sharper a price change on the last candlestick, the higher the standard
deviation.

## How to set the Standard Deviation Indicator

Many basic trading platforms include this indicator. As for LiteForex's
platform, you can install it in the following way:

 **1.** Open the platform. Click on "For [beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)" - "Open a demo
account" in the top menu bar on LiteForex's site. Registration isn't
required: you go straight to the embedded trading platform.

 **2.** Choose your trading instrument, click "Trade" on the left panel
and open the chosen currency pair's chart.

 **3.** Pick Standard Deviation on the list of indicators.

It will appear under the price chart. Click on the gear sign to see the
settings.

The default settings are:

 **1.** Length, or the period, - the number of candlesticks that will be
considered for calculation. The default set is twenty last candlesticks.

  * The bigger the period, the faster and sharper the indicator reacts to price changes.
  * The smaller the period, the less sharp the indicator’s moves are.

That is one of StdDev's essential differences from other indicators. For
example, the SMA slows down when a period increases: the longer the set,
the less weighty the last price is. With StdDev, everything is the other
way round.

 **2.** Source: the price that is included into calculation.

  * Close - candlestick's closing price.
  * Open - candlestick's opening price.
  * High - the peak value of a price in a set, the upper-extreme of a shadow.
  * Low - the lowest value of a price in a set, the lower-extreme of a shadow.
  * Median: price = (High + Low)/2.
  * Median HLC: price = (High + Low + Close)/3.
  * Median HLOC: price = (High + Low + Open + Close)/4.

 **3.** Accuracy/precision - a number of digits after the decimal point
in the indicator's value displayed on the right on the scale.

The "Style" tab allows choosing the indicator line's color or width, or
changing it into a dotted line.

The indicator is placed under the chart line in the form of a line
moving upwards and downwards relative to zero in an unlimited range. The
higher the indicator's value, the higher market volatility is.

The price type can be left as Close by default. Below there's a StdDev
chart featuring various price types. There's almost no difference in
line drawing, except that the indicator built through Close prices is
1-2 candlesticks ahead of the others.

### Standard Deviation for MT4

StdDev settings in Mt4 are slightly different from those in LiteForex's
profile. Still, the indicator is included as a basic one in MT4. You can
find it here: "Insert"/"Indicators"/"Trend".

 **Settings:**

The main difference is that you can change a MA type. The basic version
uses the SMA (simple moving average), but you can pick the SMMA
([Smoothed Moving Average](https://www.algotradesoft.org/custom-indicator/smoothed-moving-average.html)) or the LWMA (linearly weighted moving
average).

The choice of the MA is critical as the line's smoothness and
amplitude's size will be different. There doesn't exist the best option.
Advice: choose your parameters based on a market situation and an asset
you are trading.

Modifications and other indicators based on Volume Standard Deviation
Indicator:

  * Juicenew, the indicator based on StdDev. It's visually convenient. There is a histogram with 2 columns colored in different colors in place of a line that can be interpreted differently. Signals can be interpreted unambiguously, without disputable moments: if there's a signal, there's a signal. You can download this MT4 [indicator here][4].
  * [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html), a standard channel indicator included in many trading platforms. It consists of three lines: the central line is a regular moving average. The lines marking the channels' borders are moving averages shifted by a certain number of standard deviations (StdDev).

## Trading strategies combined with Standard Deviation Indicator

Here are two strategies which exemplify the use of StdDev. The first one
combines StdDev with ATR, another volatility indicator. The second one
implies trading Fibonacci levels and using StdDev as an auxiliary
indicator.

### Standard Deviation and ATR

ATR is used to measure market volatility. You can read about it in the
article "ATR indicator: volatility under trader's control"[1] .

 **Input data:**

  * Currency pair: GBPUSD.
  * Time frame: H1.
  * Settings: StdDev (20), ADX (20). The periods of both indicators must be the same.

The strategy consists in opening a trade when the trend grows stronger,
confirmed by both indicators' readings.

 **Conditions for opening a trade:**

  * ATR crosses its support level from below or pulls back from it in an ascending direction and continues growing.
  * StdDev crosses its support level from below or pulls back from it in an ascending direction and continues growing.

On the candlestick following the concurrence of both conditions, open a
trade in the trend's direction. Place a stop loss past the local
extremum.

 **Market exit [options](https://www.fixpro.org/post/options-liquidity/):**

  * When a reversal pattern, for example, a [pin bar][5], is forming.
  * When one of the indicators starts reversing.

 **Don't open a trade if**

  * one of the indicators has just pulled back from the support level and the other has already covered a 50% distance to the resistance level.
  * highly important [economic [news](https://www.letsplayfx.com/blog/forex-news-website/)][6] is expected.

 **Example**

The first step is drawing resistance levels for both indicators. To do
that, we need to scale down the chart as much as possible and draw a
horizontal line through the levels at which the indicators were
reversing most often. Then, reset the scaling and extend the levels'
lines as the price moves further.

Both conditions are observed in point 1. StdDev is the first to break
its support level and go up. Wait for confirmation from ATR. Once you
get it, open a short position. Falling candlesticks confirm the
direction. A stop loss is placed past the nearest local maximum, 2-3
points away from the shadow's end. Close the trade when ATR is
reversing. The pin bar formed by the green candlestick confirms that the
decision is right.

Both conditions are also observed in point 2, but the question is when
to close the trade. Following ATR, the trade could be closed ahead of
time. Unfortunately, there's no common recommendation concerning market
exits, so let the situation guide you. The same is true of point 4.

Point 3. A long position could have been opened if the indicators'
signals had coincided, but both indicators reversed immediately. The
signal is false, so don't wait for the stop loss to work out and close
the trade.

### Standard Deviation and Fibonacci correction levels. Practical
example.

The strategy is called "Fibonacci levels and StdDev scalping". Scalping
correction levels means catching the main trend, waiting for a local
retracement to Fibo levels and opening a trade in the trend's direction
with a take profit placed at the next level. You can check the article
[What is Fibonacci retracement?][7] for more information on Fibonacci
levels and their derivative tools.

Identifying the market entry point can be problematic for a few reasons:

  * The signal is the price's pullback in the main trend's direction from the level of 0.382. However, the price won't probably reach it, having reversed inside the range's green shaded area. Shall we then open a trade? Or is it a correction inside a correction?
  * After having retraced from level 0.382, will the price continue moving in the trend's direction once level 0.236 has been reached? Or will this level be a consolidation area?

The Standard Deviation indicator will answer these questions.

 **Step 1 Preliminary analysis.**

Scale down the M15 time frame chart of the GBPUSD currency pair and draw
a 20-period support level for StdDev. The level is drawn through visual
minimums. Place the Fibonacci grid onto the uptrend. Just in case, place
the SMA (25) into the chart too.

 **Step 2 Analysis of current situation, search for prospective opening
points.**

Having reached the maximum, the price goes flat: the price line is
moving down to the first correction level and touches it twice. However,
the correction is weak: StdDev is moving horizontally along its support
level close to zero.

Two scenarios are possible here:

  * The price will break out the correction level of 0.236 and move down. The correction's ending at level 0.382 will be a signal to open a trade.
  * The price will pull back from level 0.236 and move upwards to set a new maximum.

The standard deviation forex indicator will hint at the trend's start
point.

 **Step 3 Opening of a trade.**

The situation then develops as follows: the correction does break out
the key level of 0.236 and goes down. StdDev then starts growing, but it
would be false to open a short position based on that signal because

  * StdDev doesn't show a trend direction. Traders' activity growth only means that the price went outside the flat range, but it can reverse at any moment.
  * Fibonacci correction levels are the key indicator, and its signals are the main ones.

The correction ends before level 0.382 and the price reverses upwards.
StdDev grows. A trade is opened.

According to a conservative scenario, a trade is closed when a price has
reached the closest Fibonacci level. In our case, it's level 0.236. The
profit is over 7 dollars in just 30 minutes.

* * *

## Resumé. FAQ on standard deviation

* * *

P.S. Did you like my article? Share it in social networks: it will be
the best “thank you" :)

Ask me questions and comment below. I’ll be glad to answer your
questions and give necessary explanations.

 **Useful links:**

  * I recommend trying to trade with a reliable broker [here][8]. The system allows you to trade by yourself or copy successful traders from all across the globe.
  * Use my promo-code BLOG for getting deposit bonus 50% on LiteForex platform. Just enter this code in the appropriate field while [depositing][9] your trading account.
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

   1. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/best-technical-indicators/moving-averages-ema-indicator/
   2. uk.investing.com/tools/forex-volatility-calculator
   3. docs.google.com/spreadsheets/d/1RJWmzRgLUfvesDd_DkoGTuMa1iLS_s2y/edit#gid=317182742
   4. drive.google.com/file/d/1Bl5riLQWcv81-fp-b_EvTpioNgGsMLxr/view
   5. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/pin-bar-how-to-identify-a-liar/
   6. liteforex.com/trading/[calendar](https://www.fintechee.com/web-trader/)/
   7. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/best-technical-indicators/fibonacci-retracement/
   8. my.liteforex.com/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=best-technical-indicators&slug2=standard-deviation-indicator&openPopup=%2Fregistration%2Fpopup&utm_source=blog&utm_medium=article&utm_campaign=bonus
   9. my.liteforex.com/deposit/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=best-technical-indicators&slug2=standard-deviation-indicator&promo_code=BLOG&utm_source=blog&utm_medium=article&utm_campaign=bonus