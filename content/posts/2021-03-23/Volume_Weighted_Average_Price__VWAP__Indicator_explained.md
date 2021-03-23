+++
categories = ["Cryptocurrency", "Blockchain", "SmartContract"]
date = "2021-03-23"
description = "Volume Weighted Average Price (VWAP) Indicator explained"
tags = ["Cryptocurrency", "Blockchain", "SmartContract"]
title = "Volume Weighted Average Price (VWAP) Indicator explained"
type = "post"
+++

{{<iframe id="large-banner" src="https://www.bounty.group/#slide=17.0" width="100%" height="600" scrolling="no" style="border: 0px solid rgb(216, 221, 230); border-radius: 3px;">}}

2021-03-23

2021-03-23

VWAP Indicator: what is VWAP in trading and [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) use itOleg Tkachenko

VWAP indicator is an excellent alternative to the Moving Averages.
Moving Averages are the simplest and most popular indicator, one of the
basic tools in any trading platform. Dozens of basic and combined
indicators are based on the MA principle.

For example, classic [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) are, in fact, the very same moving
averages with a standard deviation in the formula, which are located on
both sides of the price and form a channel. And yet, like any other
indicators, the moving averages are not without drawbacks: they
calculate the average price based on the prices of separate time frames
but do not take into account trading volumes in them. The attempts to
improve this basic tool resulted in the appearance of Exponential Moving
Averages, LWMA, WMA, and other MA variations.

The article covers the following subjects:

## What is the Volume Weighted Average Price (VWAP)

Now, let us explore what is the vwap. VWAP (Volume Weighted Average
Price) is one of the moving averages derived indicators that takes
trading volumes into account when averaging prices. VWAP is the
abbreviation of the volume-weighted average price. In simple [terms](https://www.fintechee.com/terms/), the
Volume Weighted Average price is the cumulative average price with
respect to the volume.

First, let me remind you what the [moving average][1] is:

SMA (simple moving average) is the average value of a certain type of
price for a fixed number of periods. For example, in accordance with the
settings in this screenshot, the value of the simple moving average will
be based on the closing prices (Close) of the last nine one-minute
intervals - the chart has the one-minute timeframe and the period of 9.

This approach to calculating the average price does not reflect the real
picture at all. I will give an example:

  * Suppose we have a box with 100 apples, each of which costs $2. We put there an apple of another variety worth $1. The average price of an apple will be (1 + 2) / 2 = $1.5. It doesn’t matter how many apples of two varieties there are in the box – 100 or 1,000 - the average price will remain unchanged while there are two varieties in the box. 



But if this value is calculated for a box with 101 apples, then the
total price will be 100 * 2 + 1 = $201, and the average price of an
apple will be 201/101 = $1.99. You will agree that the difference
between 1.5 and 1.99 dollars is significant; the second figure reflects
the real situation much better. This average value is called the
weighted average price; that is, it’s the price taking into account the
number of goods (101 apples) in the calculation.

The same applies to Forex. The SMA from the example above considers only
the price recorded at the end of the time frame but does not take into
account that the trading volume could be $1 million in the one time
interval, and in the other - 10 thousand. This was taken into account in
the VWAP indicator.

### VWAP Indicator Definition

Volume Weighted Average Price (VWAP) is an indicator used to determine
the average value of a price weighted by volume. The VWAP indicator
takes into account the trading volume for each timeframe. And the larger
this volume, the greater the weight of the timeframe price in the final
result.

## WAP calculation: formula & algorithm

The formula for the VWAP calculation is as follows:

Let's look at each value and action in the vwap formula step by step:

  * Let's start with Price. The average price value for the VWAP calculation may be based on different datasets. In some versions of the indicator, the type of price can be changed. For example, using only average market closing prices, low and high; or the average value of the market’s opening and closing prices, the highest and lowest prices of the day.

  * When setting up average prices, you can see the following values ​​in the indicator:

Median price - calculated as follows: (High + Low) / 2

Typical price - calculated as follows: (High + Low + Close) / 3

Weighted price - calculated as follows: (High + Low + Open + Close) / 4

  * Then, according to the formula, the obtained value of the average price is multiplied by the volume.

  * The numerator is calculated: this is the aggregate indicator of the average price’s product and the cumulative volume over the entire period. The entire period means the number of candles specified in the indicator settings (VWAP period).

  * The denominator is calculated: total volume for the entire period.

  * The vwap ratio of the numerator to the denominator is calculated.

The weighted average price is calculated for the specified period. You
can calculate it for various timeframes. The VWAP indicator calculates
data from the beginning of the period specified in the settings (for
example, hour, day, week) to the end moment in cumulative mode.

The data are not averaged. In the indicator settings, it is also
important to set up the correct time, which must be the same as the time
of your broker. Also, the trader needs to indicate the desired number of
periods that should be taken into account when calculating VWAP. VWAP
results will be presented in the chart as a line

The indicator does not show individual large positions in one direction
or another. It displays the price level with a relatively high or low
level of volume, which is a trading benchmark showing high or low
liquidity.

VWAP is a trend indicator that is somewhat similar to the classic moving
averages, which also average the price. The fundamental difference is
the calculation basis. In MA, the calculation is based on the price that
comes to the terminal from the quote provider (this is a simplified
description). VWAP “pulls up” volume data from Globex, the trading floor
of the Chicago Mercantile Exchange.

This is the reason the indicator is fee-based. In free versions, VWAP
uses tick data of an individual broker, and since each broker has
different data, the result will be different.

This flaw explains why traders still prefer moving averages.
Professional traders use paid packages, including VWAP with advanced
settings (for example, packages from[ Volfix][2]). Beginners and medium-
level traders prefer to save money. And since the free version of the
indicator is very reduced in [terms](https://www.fintechee.com/terms/) of settings and VWAP readings are
different on the terminals of different brokers, traders choose moving
averages.

In the stock market, this VWAP coefficient is used more often than in
the currency market. With big trade volumes, the VWAP stock value is a
sort of estimated indicator that allows you to see the difference in the
execution price of your order in comparison with the average market
price.

If the order is closed at a price close to the indicator value, then the
execution of the price of the stock definitely “no worse” than that of
other market participants. Ideally, the order execution price should be
better than the stock VWAP value.

 **Important!** Above, there is a general calculation principle. But
there are significant differences between the free VWAP MT4 version and
the paid MT4 versions of the indicator, Thinkorswim, QUIK, and stock
market platforms. For example, the settings are different:

1\. Settings of the VWAP indicator for MT4:

In this version of VWAP in MT4, this is an analog of moving averages
with one difference. When weighing the price, the indicator takes into
account the trading volumes of each candlestick. There are two variables
in the settings, period and shift.

2\. Settings of ClusterDelta VWAP indicator:

  * Instrument — the asset ticket.

  * Update in sec — the period of the WVAP chart updates. Too frequent updates may result in incorrect chart data; you’d better set the value of one minute or longer.

  * The new calculation starts each Monday. Europe means the count starts at the beginning of each new European session. Likewise for other sessions, as well as exchange sessions - CME, NYSE.

  * Amount – the number of charts analyzed.

  * MetaTrader GMT — the time zone of the platform operation. It is set manually if the market is closed.

  * VWAP_Period — the period, based on which, the chart is drawn. For example, for the specified value ‘Daily’, the report starts from the beginning of trading. If the VWAP period is weekly, the analysis goes on from Monday till Friday inclusive. 

There are also the settings for square standard deviations ‘numDev1 —
numDev6’. In the chart, it is displayed like this: Central main line of
the indicator and 6 lines, 3 on each side, forming channels. You can see
something like this in the [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) indicator. You can read more
in the article devoted to [[Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) Indicator in Forex
Explained][3].

This VWAP version has more settings and is differently displayed in the
chart. You can add to the main line a series of Volume Weighted Average
Price indicators of different timeframes – weekly, [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) series in the
same chart. The indicator calculation base has also been changed.

The weekly VWAP is calculated from Monday to Friday; [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) VWAP
considers 24 hours after the opening of the trading session, etc. Data
are calculated per minute from the beginning of the period to the
current moment in the cumulative mode without averaging.

Next, I will deal with the free VWAP indicator for MT4 and MT5, which is
a simplified version available on the Internet.

### How to calculate vwap on excel Sheet

The VWAP calculation in Excel is needed to check the correctness of
indicator data in the chart. For example, you downloaded a VWAP version
from an unknown source and don't understand the cypher. How to check if
this is the same indicator or some other algorithm called VWAP? Create a
table in Excel and compare the obtained values with the data provided by
the indicator.

Step 1. Export the quotes from MT4. In the MT4, click on the Tools menu
and enter the History Center tab. Next, select the needed currency pair
and timeframe.

Click on the Export button and save the file in the csv. format.

Step 2. Open the Excel file and edit it. The exported data are arranged
in one column of digits, separated with a comma. Each line corresponds
to the date.

For the calculation, I will use the Median Price, so I only need two
types of prices, Open/Close and volumes. For example, the last 30
values. Volumes are the last six digits. The prices I want are at the
beginning; they are after the date and before the volumes.

I will extract the data using the LEFT() and RIGHT() [functions](https://www.fintechee.com/tutorial-for-forex-trading/basic-functions/). If you
do not know [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) apply these [functions](https://www.fintechee.com/tutorial-for-forex-trading/basic-functions/), write in the comments, and I
will explain in more detail. If you know an easier way to export the
data into Excel in a convenient format, share it in the comments,
please!

Remember to convert the data to a number if a green triangle appears in
the corner of the cells. Also, replace the dot separator with a comma.

Step 3. Calculate the numerator of the fraction in column F. The average
open and close prices are multiplied by volume. Stretch the cells.

F2: =(C2+D2)/2*E2

Step 4. Calculate the VWAP with period 12:

G13=F13/E13

Period 12 means that the data are calculated based on the last twelve
candlesticks, that is, the last twelve cells. So, you enter the formula
only in the twelfth line, G13.

 You can download the template via [this link][4].

## Where to download VWAP for MT4

VWAP has several versions, but most of them are fee-based. A simplified
version of VWAP indicator MT4 with a minimum of settings can be
[downloaded here][5]. After you download the VWAP, you should add the
indicator to the platform. In the MT4 top menu, click on “File / Open
Data Catalog,” go to the MQL4 / Indicators folder, and past the
indicator file there.

Restart MT4, the indicator will appear in the "Insert / Indicator /
Custom" submenu. You can download the VWAP indicator template [here][6];
the template has the parameters suitable for the [MT5][7].

  *  **Important!** The MT4 archive offered for download is a simplified version of the indicator without additional square deviation lines. Archive of the VWAP for MT5 is a free extended version with square deviations, but it is not complete either. You get the VWAP full version after you have a paid subscription with the developers.

## Forex VWAP Indicator Signals

1\. If the price has been above the indicator for a long time, then the
trend is upward. If the price is below the VWAP line, this is a sign of
a downtrend. We are talking about a long period, which is usually
analyzed for the market general assessment before opening a position.

The green line is the price line; the white one is the Volume Weighted
Average Price line. The yellow rectangle is the zone of the growing
trend; the blue is the declining one. Please note that in both zones at
the end of the trend, there is a reversal, which could not be predicted
by the VWAP. That is why the indicator is used only to confirm signals
in certain areas.

2\. If the VWAP is located above the price, this indicates that a long
position (purchase) will be opened at a lower price than the average
market quotes. One of the high-risk strategies is based on opening buy
positions when the price is below the VWAP but reverses up. In
accordance with conservative strategies, a long position is opened when
the price crosses the indicator from bottom to top, and a short position
is opened when the price crosses the indicator from top to bottom.

3\. If the vwap crosses the price chart several times, the market is
flat.

4\. If the VWAP starts to decline steadily, this indicates that trading
volumes are declining and interest in the asset is falling. Such a
signal may be a harbinger of a flat.

There is no single recommendation for building volume weighted average
price trading strategy, and you could follow the same tactics as when
trading with moving averages. The most common use of the indicator is to
build the main VWAP line and three deviation lines that form the
channels.

## VWAP Trading Strategies

VWAP [trading strategies](https://www.fintechee.com/forex-trading-strategies/) depend on the indicator version you are going to
employ. You can use the version for the MT5, the closest to the full
one, for channel [trading strategies](https://www.fintechee.com/forex-trading-strategies/). The channel's borders will be the
average square deviation. You can employ a simplified VWAP version for
the MT4 similar to the MAs.

You install two VWAP indicators with different periods, look for signals
at the time of their crossing, and confirm the trading vwap ideas to buy
or sell with other technical tools. I will cover several Volume Weighted
Average Price [trading strategies](https://www.fintechee.com/forex-trading-strategies/) below.

### VWAP Pullback for five-minute timeframe

This trading strategy is based on the Moving Averages and the VWAP with
the same period.

Input parameters:

If you use other MA modifications instead of the SMA, you can face
lagging signals. But you can test other types of MAs on other currency
pairs. Perhaps, the application of EMAs, for example, on less volatile
assets, could be justified.

Entry conditions:

  * Long position. After the indicators cross, the candlestick body should close higher than both lines. The red line of the faster SMA should cross the white slower VWAP line from bottom to top.

  * Short position. After the indicators cross, the candlestick body should close lower than both lines. The red line of the faster SMA should cross the white slower VWAP line from top to bottom.

Two important moments:

  * The candlestick must be completely above or below the lines of both indicators. The moment the price crosses the indicator lines is only an early signal.

  * The primary signal is when the price crosses the lines of both indicators, the crossing of the VWAP and SMA is a confirming signal.

Example:

The SMA and the VWAP usually move along with almost the same trajectory;
therefore, the moment of their crossing is an amplifying signal.

  * At point ‘1’, a falling candlestick breaks through both indicators. Although VWAP and SMA do not cross, both indicators are directed downward. At the next candlestick, we open a short position and insure it with a trailing stop.

  * At point ‘2’, indicators cross, but as the price has been below the VWAP for a long time. It signals a downtrend, which could end soon. There is no entry signal.

  * At point ‘3’, the price closes higher than both indicators; the red line crosses the white line from bottom to top. We open a long position.

  * At point ‘4’, the price closes below the indicators; the closed candlestick has very little body and shadows compared to the previous ones. Most likely, the bear trend is exhausting, and it makes to expect the upward price movement to continue. 

  * There are no signals at points ‘5’ and ‘6’, as the price has been for a long time above the indicators.

  * At point ‘7’, the trend could reverse. But the signal is weak, as both indicators have a slight slope. We can take a risk and enter a trade now or wait until a few following candlesticks form.

  * We exit the trade at point ‘8’ or ‘9’. At the eighth point, there is a candlestick with a small body, which signals a likely reversal. At the ninth point, there is an upward engulfing candlestick. 

### VWAP Price Action

The Price Action strategy suggests a search for a complex pattern
composed of five or more candlesticks. Volume Weighted Average Price is
employed here as a supplementary tool to confirm the trading signals. By
and large, a Price Action trading strategy looks like this. You draw the
support/resistance levels, Fibonacci retracements, look for price chart
patterns, such as a Triangle, for example, and others.

Next, you spot the level breakouts. As the level breakout could be a
correction, you receive an additional confirmation signal from the VWAP.
The VWAP signal is sent when, at the moment of the level breakout, the
price move should also break out the indicator line, or the candlestick
should close below/above the indicator, depending on the trade
direction. VWAP confirms that trading volumes are increasing, and the
price movement will continue after the level breakout.

Example. Input parameters:

There is a sideways trend in the hourly chart. The price movement is
getting flat; the candlestick bodies are getting shorter, the price
movement almost coincides with the VWAP. Along with some extreme points,
marked with the red arrows, we can draw a Triangle pattern. The breakout
of the Triangle borders could mean the beginning of a new trend.

The rising candlestick breaks out the Triangle upside and closes higher.
This candlestick also closes above the white VWAP line, which was broken
out by the preceding candlestick. The VWAP sideways movement turns into
a rise, and we can enter a long trade at the next candlestick (blue
arrow) or after it.

The exit conditions depend on your trading style. I would refer to the
patterns in this case. Following four candlesticks after the trade was
entered, there appears a Doji candlestick, where I would close the
position. The trade would yield a profit of about 25-30 pips, depending
on the entry and exit points of the trade.

### Channel trading strategy with VWAP Deviation lines for MT5

The VWAP settings for MT5, whose template you can upload via the link
above, provide an opportunity to draw the square deviation lines, which
make up a channel. You specify the coefficient in the setting. The
recommended settings are as follows:

The problem with channel indicators is that they follow the price and
then repaint. A candlestick touching the channel boundaries does not
mean that the price will turn to the middle of the channel, it can go
further, and the channel will widen following the price movements.

The strategy offered here eliminates the ambiguity. The trades are
entered when the price exits the consolidation zone. The signal is sent
when the price sharply exceeds the channel boundaries. You can apply the
trading system in the five-minute timeframe, 10-minute chart, or M15
interval.

Input parameters:

  * Currency pair — any.

  * TImeframe — М5-М15.

  * Indicator VWAP for МТ5.

Entry signals. The market is trading flat, and the channel is getting
narrower.

In a perfect situation, if the channel is horizontal and it is clearly
visible compared to the previous price movement. When the channel is
narrowing, it indicates a potential signal; but the narrowing should
last during at least three-five candlesticks. The entry signal appears
when the channel sharply broadens. In the chart, it looks like this:

  * There appears a relatively long candlestick, compared to the previous ones, in a certain direction.

  * The extreme line of the channel, towards which the candlestick went, sharply changes the slope angle. 

You open the position at the next candlestick after the signal
candlestick touches the last channel line in the direction of the
emerging trend.

Example 1.

There is a clear visible narrowing of the horizontal channel. At point
‘1’, the price breaks the extreme channel line, which sharply changes
the slope down. At the next candlestick, we can enter a trade.
Candlesticks 2 and 3 confirm that the trading decision is correct.

Example 2.

In both situations (red boxes), following the channel narrowing, the
price sharply swings beyond the channel borders, and the channel widens.
Both signals are accurate.

Pay attention to the zone of the blue box. There is also a narrowing of
the channel, a breakout of the border by candlestick downside, and a
change in the slope of the Volume Weighted Average Price indicator line.
But the narrowing of the channel lasted less than 3 candles - this
suggests that the market quickly left the zone of uncertainty. With such
a signal, I would not recommend entering a trade for conservative
traders.

The disadvantage of the channel strategy is that signals are rare, and
you have to expect the consolidation zone. Therefore, the recommended
timeframes are M5-M15, the frequency is one signal per 1-3 days. The
idea of the strategy is simple; therefore, I recommend also paying
attention to patterns or adding oscillators. If you manage to develop
this idea into a full-fledged trading system, share your experience in
the comments.

## Support and Resistance with the VWAP

In a trending market, the Volume Weighted Average Price indicator line
could serve as a support or resistance level. If the current price is
higher than the average price over the chosen period, the trader
overpays for the asset.

If the current market price is lower than the average one, the trader
buys an asset at a more beneficial price. If the price is close to the
VWAP line, the current price is balanced. This is a key level where the
trend is likely to continue or reverse.

Following a downtrend, the price is trading flat for some time, several
times breaking through the white line of the Volume Weighted Average
Price, indicating bearishness. Next, a bullish starts, and the indicator
line becomes a support level, from which the price rebound and goes up.

At the first box, there is again uncertainty. Bears are trying to press
the price down, but the price again rebounds from the VWAP line in the
chart in the main trend direction. Close to the second box in the chart,
there is uncertainty. After that, the VWAP turns into a resistance
level.

## How to use VWAP: example

This strategy, one of the simplest strategies out there, is based
exclusively on the VWAP indicator, although this is somewhat contrary to
the logic of technical analysis. Nevertheless, the signals turn out to
be quite accurate. The only drawback is that these signals are quite
rare: they occur once a month on average, so this strategy is an
additional one to your main strategies.

The vwap intraday strategy is based on the combination of two time
frames: a longer one serves for preliminary analysis, and an intraday
price timeframe is for entering/exiting trades within the day in order
not to pay swaps. Currency pair here: [EURUSD][8]. The VWAP inputs:
period 11, shift 0.

### Entry conditions for a long/short trade:

  * D1 time frame: the current candlestick closes above/below the VWAP line after trend reversal. If it closes above, it is a preliminary signal to open a long trade; if it is below, open a short one.

  * Н1 time frame: the current candlestick closes above/below the VWAP indicator line after changing the trend direction.

You enter trades only once a day. If another signal appears within the
day, it is ignored.

The stop-loss length is no more than 30 pips for 4-digit quotes or close
to the level of the local extremum. Open a trade on the H1 timeframe at
the next candlestick after the signal one.

The profit target level is 20-30 pips, after which the stop-loss is set
to the breakeven level, 50% of the profit is then fixed, the rest of the
trade is protected by a trailing stop loss (there is a risk of being
disconnected from the Internet, during which time trailing does not work
- use the [VPS rental service][9] instead).

There are false signals in this strategy but they are mostly caused by
fundamental factors.

Example 1.

In the [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) chart, there is the following picture. VWAP indicator was
below the price for a long time - this indicates an uptrend. Then the
price changed direction, but the white falling candlestick only touched
the VWAP (green arrow); this is not a signal for two reasons:

The candlestick indicated by the yellow arrow is falling and when the
trend reversed, it closed below the VWAP line. This event took place on
16 June 2020. Let’s switch to the H1 chart and look for a signal to open
a short position on the next day - 17 June 2020.

A signal candlestick that crosses the VWAP and closes below the
indicator line appears at 10 am. One could open a short position at the
next candlestick, marked with a yellow arrow. The opening price would be
1.12666, the closing price of the trade with a 20-pip trailing stop loss
would be 1.12447, and the profit would be 22 pips.

Example 2.

The previous example appeared on the [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) timeframe in June. Let's go
back in [history](https://www.fixpro.org/post/chargeless-historical-data-api-backtesting/) a month back to May where two opposite signals are
visible. In the first case, an uptrend is visible, highlighted by a blue
rectangle; after that, the trend reverses, and the signal candle (yellow
arrow) closes below the VWAP line.

The candlestick appeared on 5 May 2020. Therefore, one would look for a
signal to open a trade on the hourly timeframe of 6 May 2020. In the
second case (green arrow), the rising candlestick closes after a trend
reversal on 18 May 2020.

Entering a trade in the hourly time frame for the first case:

A position can be opened on any candlestick within the range indicated
by the blue rectangle. The signal candle is the one that closed exactly
at midnight, so a trade could be entered right on the next candle. You
could wait for several successive falling candles for it to be a more
reliable signal.

If you open a trade on the candle the arrow points to (a conservative
strategy) and set a 20-pip trailing stop loss, the profit would be 20
pips. A vwap strategy with a higher level of risk involves opening a
trade earlier.

Entering a trade in the hourly time frame for the second case:

Here the signal candlestick in the direction of price growth closed at
the same level as the VWAP indicator. In theory, this is a weak signal
and it would be worth waiting for the next candle closing above the VWAP
line (yellow arrow), but trading is always a risk, which sometimes turns
out to be justified.

Despite the fact that the VWAP indicator is more sensitive to price in
comparison with moving averages, its disadvantage, like the MA, is a
delay.

Like moving averages, VWAP is more of an auxiliary trend confirmation
signal. It is rarely used independently and is not predictive. The tool
is used exclusively in intraday analysis strategies. And although no one
forbids you to use the VWAP on long timeframes, its signals will lose
their accuracy.

Are you interested in free versions of the indicator? Test it on a demo
account. If you don’t have one yet, you can do it in 2 minutes. Click on
the “Register” button in the upper right corner of the broker's [website](https://www.playgroundfx.com/blog/website-for-forex-trading/)
(on any page).

Go to MT4 from your Personal Account (you can learn more about the
LiteForex account [functions](https://www.fintechee.com/tutorial-for-forex-trading/basic-functions/) [here][10]), download, install the template
in accordance with the instructions from the review, test the indicator
and be sure to share your opinion about it in the comments!

## VWAP vs. MVWAP

According to the VWAP definition, it is the volume-weighted average
price. The MVWAP or Moving VWAP is the moving volume weight average
price. The difference is in the averaging method.

There is no averaging in VWAP - the numerator is the price weighted by
volume, and the denominator is the cumulative volume. The MVWAP is the
average VWAP value. For example, if MVWAP has a period of 10, then the
current indicator value will correspond to the arithmetic average of
VWAP values for the last 10 candlesticks.

Some sources describe the difference between these indicators as
follows. VWAP calculates the value for a fixed period - for a day, a
week. This is indicated in the period settings: Daily, Weekly, etc.

For example, for a [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) period, the indicator shows the weighted
average price for the current day. And the next day, the Volume Weighted
Average Price calculation will start over.

The MVWAP has a standard option for specifying the period in the
settings. It is not tied to days or weeks and calculates the average
over a specified number of candles, accumulating data over a specified
period.

In theory, VWAP works better in intraday [trading strategies](https://www.fintechee.com/forex-trading-strategies/) in short
time frames. MVWAP performs better in the timeframes starting from H4
and longer. In practice, everything depends solely on the trader's
experience, intuition, and ability to spot signals. Both MVWAP and VWAP
can be adjusted to any timeframe.

One of the [trading strategies](https://www.fintechee.com/forex-trading-strategies/) involves the simultaneous use of VWAP and
MVWAP. Signals can be intersections of both indicators with each other
and/or price, the same direction of VWAP and MVWAP along with the price,
signaling a trend, etc.

## Anchored VWAP

The AVWAP or Anchored VWAP was developed by Brian Shannon, who described
this tool in one of his books. Using the Anchored VWAP, you can
calculate the indicator value for any period from the point which you
click on with the mouse. From this point indicated on the chart, the
average price value will be calculated, taking into account the volumes.

The key differences between VWAP and AVWAP (a simplified, free VWAP
version is described):

  * The VWAP indicator calculates a weighted price value taking into account volumes for the period specified in the settings. For example, the period is 10, the indicator calculates the data for the last 10 candlesticks. Accordingly, after 10 candles from the moment the indicator was installed, the data is calculated based on the fully updated interval. The calculation period remains unchanged - the last 10 candles.

  * The AVWAP indicator calculates the weighted price value from the moment it is installed in the chart by clicking the mouse. With each new candlestick, the analyzed period increases.

  * AVWAP allows you to analyze the price trend from the moment of any fundamental event or strong market surge. In a trending market, it is not always possible to draw clear support or resistance levels since the price extremes are not located on the same line, and it is not clear which of them should be taken as the main points.

If you need to find the average price line taking into account the [news](https://www.letsplayfx.com/blog/forex-news-website/)
factor, set AVWAP to a candlestick at the time of the [news](https://www.letsplayfx.com/blog/forex-news-website/) release and
get the needed value.

Example. We need to analyze the price [history](https://www.fixpro.org/post/chargeless-historical-data-api-backtesting/) since the Nonfarm payrolls
report to see how long the market works out the [news](https://www.letsplayfx.com/blog/forex-news-website/) and how sharply the
price chart changes. Let's say that the event happened 10 candlesticks
ago. The timeframe is not important in this case. The largest number of
trades and the most significant volumes are during the first few
candlesticks.

If we use the VWAP indicator with a fixed period, then, as new bars
appear, the oldest candlesticks with the maximum volumes will be
excluded from the calculation. After a few bars, we will receive data
without taking into account the largest volumes at the time of the [news](https://www.letsplayfx.com/blog/forex-news-website/)
release.

One of the ways out is to increase the Volume Weighted Average Price
indicator period every few candlesticks so that trading volumes at the
time of [news](https://www.letsplayfx.com/blog/forex-news-website/) release continue to be included in the calculation.
Alternatively, you can use Anchored VWAP, which is tied to a specific
reference point.

## Limitations of Using VWAP

VWAP is not a price prediction indicator, as its values are based on
price data from previous periods. Therefore, the indicator is used to
confirm the already existing signal received from other tools. The
limitations on trading with the VWAP are as follows:

  * You can't use the VWAP to predict the trend direction. The indicator doesn’t search for the regularities in the previous periods.

  * The VWAP indicator performs well in the short- and medium-term timeframes, M5-H1.

  * The VWAP is a trend indicator for the medium-volatile markets. You’d better not enter a trade with this tool at the moment of [news](https://www.letsplayfx.com/blog/forex-news-website/) releases.

One of the significant problems with VWAP is the different versions of
the indicator. If we compare the code, then different versions have only
one similarity - the price of each bar is weighted, that is, multiplied
by its volume. In all other respects, the indicator versions diverge.

In one case, the value is calculated for the period specified in the
settings, taking into account the cumulative data. In another, the
calculation takes place for the specified period (day/week), and with
each new period, a new calculation starts. Accordingly, the data of
these versions of indicators will differ.

Some of the solutions are:

  * Find out which version of VWAP you have installed. Understand how it works and what each setting parameter means. You can also buy a paid subscription to the developer for the entire package of indicators, including Volume Weighted Average Price, and get a detailed description for it.

  * Test the indicator without being tied to any specific strategy. For example, this overview describes strategies for the indicator, the link to the template of which is given at the beginning.

  * Consider the general principles of VWAP and develop your own vwap trading system based on them. Test it in the MT4 / MT5 tester.

## Pros and Cons

I will sum up and describe the VWAP pros and cons in the table below:

Advantages

|

Drawbacks  
  
---|---  
  
1\. It takes into account the transactions weighted back volume for each
period of the interval. Therefore, it gives more accurate averaged price
data at the current moment.

|

1\. It takes into account the volumes provided by the broker. But the
broker does not always have the aggregated volume data for the entire
market; therefore, its volumes may differ from real ones.  
  
2\. It is hardly affected by price noise, so you can use it in short-
term timeframes, such as М1-М5-М15.

|

2\. The VWAP could be lagging. That is why it is used to analyze the
previous period to confirm a trading signal.  
  
3\. It can be used to develop a high-frequency trading system based on
prices and volumes.

|

3\. The indicator sensitivity to the recent periods is lower due to the
large volume of the accumulated data.  
  
4\. It draws the boundaries of price channels more accurately in
comparison with [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) and some other channel indicators.
Therefore, it is better suited for intraday channel [trading strategies](https://www.fintechee.com/forex-trading-strategies/).
It refers only to the full version of VWAP, where the standard square
deviation lines are provided in the settings (Deviation).

|

4\. The full VWAP version is paid. The basic free VWAP forex version is
a single line of weighted price. The full VWAP version consists of
several lines according to timeframes.  
  
## VWAP trading indicator. Conclusions

VWAP is a useful signal confirmation tool, which is very similar to
moving averages. But unlike MAs, it provides more reliable data on
market volumes and the average market price. It complements trend
indicators and oscillators quite well and is more sensitive to
price/volume changes than moving averages.

The VWAP  will be an excellent assistant in deciding whether to enter or
exit the market. If you still have questions or ideas on optimizing VWAP
[trading strategies](https://www.fintechee.com/forex-trading-strategies/), write in the comments!

In conclusion, I would like to write a few words about how else you can
benefit from working with LiteForex:

  * LiteForex is an ECN broker that transfers trades directly to virtual ECN systems. This ensures a minimum spread, as well as the order execution speed up to 100 ms (the average market speed is 300-400 ms).

  * In addition to the usual platforms, LiteForex also offers its own very easy-to-use browser platform powered by MetaTrader with an integrated copy trading system. Read more about the benefits of social trading and working with the platform in the review “[How to make more money in the foreign exchange market: passive income for a successful [investor](https://www.fintechee.com/tutorial-for-forex-trading/investor-mode/)][11].”

  * Psss! Now there’s a unique opportunity to get cool prizes (a house and a car among them) on the occasion of the 15th anniversary of the company. Read more about participating in the draw [here][12].

## VWAP FAQ

How to set up VWAP on Thinkorswim?

Thinkorswim by TD Ameritrade is the result of a merger between the
developers of a US stock trading platform and an American brokerage
company. To configure the indicator, you need:

  * Enter your TOS profile. Click on the Studies / Edit Studies in the right corner of the menu.
  * Enter the indicator name, WVAP, in the search bar.
  * Specify the window in which the indicator will be installed - Price, Volume, Lower.
  * Specify the parameters Input, Day in the settings window. 

Since this platform is designed to trade in the US stock market, you
should pay attention to the VWAP for МТ4 and QUIK. You install the
indicator on both platforms similarly. You need to add the indicator
running file into the platform, specify the values of the time interval
volume that will be taken into account in the formula, the period of
chart update in seconds, shift in the settings.

How to read the vwap?

There are several ways to read the VWAP signals:

  * If the price has been above the VWAP line for a long time, it indicates bullishness, and the trend is up. If the price is clearly below the indicator line, the trend is down. However, this can also signal a soon trend reversal. One of the [trading strategies](https://www.fintechee.com/forex-trading-strategies/) suggests you open, for example, a short position when the price is above the VWAP and turning down, starting a bearish trend.
  * Volume Weighted Average Price is going down along with the price - this indicates that trading volumes are decreasing. Investors are not interested in the trading asset, it is uninspiring to oversell. So, the price could start trading flat soon. A decline in prices with consistently high transaction volumes may indicate a strong downtrend.
  * The steeper the slope of the indicator, the stronger the trend.
  * The price crosses VWAP several times in a short period of time, which means the average price corresponds to the current one. This is a sign of equality in the volumes of purchases and sales, which corresponds to a sideways trend.

Analyze the VWAP signals together with other technical indicators, price
action patterns, or Ichimoku cloud.

How to calculate vwap on excel?

Upload the quotes from МТ4/МТ5 into Excel, having chosen the needed
symbol and timeframe.

  * Change the formatting of the uploaded data using formulas to get prices and volumes in separate columns.
  * Calculate the average price. Use several [options](https://www.fixpro.org/post/options-liquidity/) Typical, Median, Weighted.
  * Calculate the numerator of the fraction: multiply the average price by volume and stretch the cells.
  * Calculate VWAP for the required period: Add the calculated numerator and denominator for the period. Divide the resulting sum of the numerator by the resulting sum of the denominator.

You can download the template of the Excel spreadsheet

[via this link][4]

.

It is a trading strategy based on the VWAP indicator developed to
[optimize](https://www.fintecher.org/2020/03/17/added-genetic-algorithm-for-trading/) the risks and maximize profit. The trading system can be based
on the channel's construction using the Volume Weighted Average Price
with different periods or deviation parameters.

Or the VWAP trading strategy means that you estimate the direction of
the VWAP line movement and the location of the indicator above/below the
price. In the first case, you can use intraday [trading strategies](https://www.fintechee.com/forex-trading-strategies/) based
on price movement within the channel. In the second case, enter trades
based on additional signals—for example, chart patterns and oscillators
to define the overbought or oversold state.

The content of this article reflects the author’s opinion and does not
necessarily reflect the official position of LiteForex. The material
published on this page is provided for informational purposes only and
should not be considered as the provision of investment advice for the
purposes of Directive 2004/39/EC.

Rate this article:

{{value}}

( {{count}} {{title}} )

   1. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/best-technical-indicators/moving-averages-ema-indicator/
   2. volfix.net/
   3. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/best-technical-indicators/bollinger-bands/
   4. drive.google.com/file/d/1zl93Ber3ROh4ZJSgrq4kwq4ibku6WGzF/view?usp=sharing
   5. drive.google.com/file/d/1JRZdhkmI_uN9jagFE3eJ_zTko39VZDNR/view
   6. drive.google.com/open?id=1l1K8vmbRfjrcDvhQljdJCJ6iMrEW05WW
   7. www.liteforex.com/downloads/mt5/
   8. my.liteforex.com/trading/chart?symbol=EURUSD
   9. www.liteforex.com/trading/additional-services/vps-services/
   10. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/lets-look-into-liteforexs-new-client-space/
   11. www.liteforex.com/blog/for-professionals/combined-strategies-to-make-money-on-forex/
   12. www.liteforex.com/contests/dream-draw/