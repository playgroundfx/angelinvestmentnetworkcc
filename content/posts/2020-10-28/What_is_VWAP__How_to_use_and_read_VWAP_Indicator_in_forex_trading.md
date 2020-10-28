+++
categories = ["Cryptocurrency", "Blockchain", "SmartContract"]
date = "2020-10-28"
description = "What is VWAP? How to use and read VWAP Indicator in forex trading"
tags = ["Cryptocurrency", "Blockchain", "SmartContract"]
title = "What is VWAP? How to use and read VWAP Indicator in forex trading"
type = "post"
+++

{{<iframe id="large-banner" src="https://www.bounty.group/#slide=25.0" width="100%" height="600" scrolling="no" style="border: 0px solid rgb(216, 221, 230); border-radius: 3px;">}}

2020-10-28

2020-10-28

VWAP Indicator: what is VWAP in trading and [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) use itOleg Tkachenko

VWAP indicator is a great alternative to the moving averages. Moving
average is the simplest and most popular indicator, one of the basic
tools in any trading platform. Dozens of basic and combined indicators
are built on their basis.

For example, classic [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) are, in fact, the very same moving
averages with a standard deviation in the formula, which are located on
both sides of the price and form a channel. And yet, like any other
indicators, the moving averages are not without drawbacks: they
calculate the average price based on the prices of separate time frames
but do not take into account trading volumes in them. The attempts to
improve this basic tool resulted in the appearance of exponential moving
averages, LWMA, WMA, and other varieties of this tool.

The article covers the following subjects:

## What is VWAP?

VWAP (Volume Weighted Average Price) is one of moving averages derived
indicators that takes trading volumes into account when averaging
prices. VWAP is the abbreviation of the volume-weighted average price.
Let’s look at this indicator in more detail.

First, let me remind you what the [moving average][1] is:

SMA (simple moving average) is the average value of a certain type of
price for a fixed number of periods. For example, in accordance with the
settings in this screenshot, the value of the simple moving average will
be based on the closing prices (Close) of the last nine one-minute
intervals - the chart has one-minute timeframe and the period of 9.

This approach to calculating the average price does not reflect the real
picture at all. I will give an example:

  * Suppose we have a box with 100 apples, each of which costs $2. We put there an apple of another variety worth $1. The average price of an apple will be (1 + 2) / 2 = $1.5. It doesn’t matter how many apples of two varieties there are in the box – 100 or 1,000 - the average price will remain unchanged while there are two varieties in the box. But if this value is calculated for a box with 101 apples, then the total price will be 100 * 2 + 1 = $201, and the average price of an apple will be 201/101 = $1.99. You will agree that the difference between 1.5 and 1.99 dollars is significant, the second figure reflects the real situation much better. This average value is called the weighted average price, that is, it’s the price taking into account the amount of goods (101 apples) in the calculation.

The same applies to Forex. The SMA from the example above takes into
account only the price that was recorded at the end of the time frame,
but does not take into account the fact that in one-time interval the
trading volume could be $1 million, and in the other - 10 thousand. This
was taken into account in the VWAP indicator.

### VWAP Indicator Description

 **Volume Weighted Average Price (VWAP)** is an indicator used to
determine the average value of a price weighted by volume. The VWAP
indicator takes into account the trading volume for each timeframe. And
the larger this volume, the greater the weight of the timeframe price in
the final result.

## VWAP calculation: formula & algorithm

The formula for the VWAP calculation is as follows:

Let's look at each value and action in the formula step by step:

  * Let's start with Price. The average price value for the VWAP calculation may be based on different datasets. In some versions of the indicator, the type of price can be changed. For example, using only average market closing prices, low and high; or the average value of the opening and closing prices of the market, the highest and lowest prices of the day.

When setting up average prices, you can see the following values ​​in
the indicator:

 _Median price - calculated as follows: (High + Low) / 2_

 _Typical price - calculated as follows: (High + Low + Close) / 3_

 _Weighted price - calculated as follows: (High + Low + Open + Close) /
4_

  * Then, according to the formula, the obtained value of the average price is multiplied by the volume.
  * The numerator is calculated: this is the aggregate indicator of the product of the average price and the volume over the entire period. The entire period means the number of candles specified in the indicator settings (VWAP period).
  * The denominator is calculated: total volume for the entire period.
  * The ratio of the numerator to the denominator is calculated

The weighted average price is calculated for the specified period. You
can calculate it for various timeframes. The VWAP indicator calculates
data from the beginning of the period specified in the settings (for
example, hour, day, week) to the end moment in cumulative mode. The data
is not averaged. In the indicator settings, it is also important to set
up the correct time, which must be the same as the time of your broker.
Also, the trader needs to indicate the desired number of periods that
should be taken into account when calculating VWAP. VWAP results will be
presented in the chart as a line.

The indicator does not show individual large positions in one direction
or another. It displays the price level with a relatively high or low
level of volume, which is a sign of high or low liquidity.

VWAP is a trend indicator that is somewhat similar to the classic moving
averages, which also average the price. The fundamental difference is
the calculation basis. In MA, the calculation is based on the price that
comes to the terminal from the quote provider (this is a simplified
description). VWAP “pulls up” volume data from Globex, the trading floor
of the Chicago Mercantile Exchange. This is the reason the indicator is
fee-based. In free versions, VWAP uses tick data of an individual
broker, and since each broker has different data, the result will be
different.

This flaw explains why traders still prefer moving averages.
Professionals use paid packages, including VWAP with advanced settings
(for example, packages from [Volfix][2]). Beginners and medium-level
traders prefer to save. And since the free version of the indicator is
very reduced in [terms](https://www.fintechee.com/terms/) of settings and VWAP readings are different on the
terminals of different brokers, traders choose moving averages.

In the stock market, this VWAP coefficient is used more often than in
the currency market. At high speeds, the VWAP value is a sort of
estimated indicator that allows you to see the difference in the
execution price of your order in comparison with the average market
price. If the order is closed at a price close to the indicator value,
then the execution price is definitely “no worse” than that of other
market participants. Ideally, the order execution price should be better
than the VWAP value.

## Where to download VWAP for MT4

VWAP has several versions, but most of them are fee-based. A simplified
version of VWAP indicator MT4 with a minimum of settings can be
[downloaded here][3]. To add the indicator to the platform, in the MT4
top menu, click “File / Open Data Catalog”, go to the MQL4 / Indicators
folder and copy the indicator file there. Restart MT4, the indicator
will appear in the "Insert / Indicator / Custom" submenu.

This is the simplest way to install mql4 VWAP indicator.

## Forex VWAP Indicator Signals

 **1.** If the price has been above the indicator for a long time, then
the trend is upward. If the price moves is below VWAP, this is a sign of
a downtrend. We are talking about a long period, which is usually
analyzed for a general assessment of the market before opening a
position.

The green line is the price line, the white one is VWAP. The yellow
rectangle is the zone of the growing trend, the blue is the declining
one. Please note that in both zones at the end of the trend there is a
reversal, which could not be predicted by the VWAP. That is why the
indicator is used as only confirming in certain areas.

 **2.** If the VWAP is located above the price, this indicates that a
long position (purchase) will be opened at a lower price than the
average market quotes. One of the high-risk strategies is based on
opening buy positions when the price is below the VWAP but reverses up.
In accordance with conservative strategies, a long position is opened
when the price crosses the indicator from bottom to top, and a short
position  - from top to bottom.

 **3.** If the indicator crosses the price chart several times, the
market is flat.

 **4.** If the VWAP starts to decline steadily, this indicates that
trading volumes are declining and interest in the asset is falling. Such
a signal may be a harbinger of a flat.

There is no single recommendation for building strategies for the VWAP
indicator, and you could follow the same tactics as when trading with
moving averages. The most common use of the indicator is to build the
main VWAP line and 3 deviation lines that form the channels.

The principle here is similar to trading on channel indicators: we look
at the VWAP center line and its position relative to the price and open
positions at the moment of the price rebounding from the extreme channel
lines (VWAP with the largest deviation parameter). Yellow arrows show
examples of such signals. The blue arrow is an example of when the price
continued a strong uptrend after touching the channel line. So it makes
sense to add trend indicators to the strategy.

I will not describe the VWAP strategies in detail. Since the purpose of
this review is to introduce you to the essence of VWAP trading and
encourage you to experiment. If you need a detailed review of the VWAP
strategy, please leave a comment. You can download the VWAP indicator
template [here][4] with deviation parameters for [MT5][5].

## VWAP trading strategy

This strategy, one of the simplest strategies out there, is based
exclusively on the VWAP indicator, although this is somewhat contrary to
the logic of technical analysis. Nevertheless, the signals turn out to
be quite accurate. The only drawback is that these signals are quite
rare: they occur once a month on average, so this strategy is an
additional one to your main strategies.

The goal of the strategy is to combine two timeframes: a large one - for
preliminary analysis, and an intraday one - for opening/closing trades
within the day in order to save on swaps. Currency pair here:
[EUR/USD][6]. The VWAP inputs: period 11, shift 0.

Conditions that should be met to open a long/short trade:

  * D1 time frame: the current candlestick closes above/below the VWAP line after trend reversal. If it closes above, it is a preliminary signal to open a long trade, if below, open a short one.
  * Н1 time frame: the current candlestick closes above/below the VWAP indicator line after changing the trend direction.

Open trades only once a day. If another signal appears within the day,
it is ignored.

The stop-loss length is no more than 30 points for 4-digit quotes or
close to the level of the local extremum. Open a trade on the H1
timeframe at the next candlestick after the signal one. The target
profit level is 20-30 points, after which the stop-loss is set to the
breakeven level, 50% of the profit is then fixed, the rest of the trade
is protected by a trailing stop loss (there is a risk of being
disconnected from the Internet, during which time trailing does not work
- use the [VPS rental service][7] instead).

There are false signals in this strategy but they are mostly caused by
fundamental factors.

 **Example 1.**

On the [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) time frame, there is the following picture. VWAP indicator
was below the price for a long time - this indicates an uptrend. Then
the price changed direction, but the white falling candlestick only
touched the VWAP (green arrow), this is not a signal for two reasons:

  * The falling candle did not close below the VWAP. The way it touched the indicator line is a weak signal.
  * The next candlestick is growing and closes above the VWAP. The direction of the trend has not changed.

The candlestick indicated by the yellow arrow is falling and when the
trend reversed, it closed below the VWAP line. This event took place on
16 June 2020. Let’s go to the H1 chart and look for a signal to open a
short position on the next day - 17 June 2020.

A signal candlestick that crosses the VWAP and closes below the
indicator line appeared at 10 am. One could open a short position at the
next candlestick, marked with a yellow arrow. The opening price would be
1.12666, the closing price of the trade with a 20-point trailing stop
loss would be 1.12447, and the profit would be 22 points.

 **Example 2.**

The previous example appeared on the [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) timeframe in June. Let's go
back in [history](https://www.fixpro.org/post/chargeless-historical-data-api-backtesting/) a month back to May where two opposite signals are
visible. In the first case, an uptrend is visible, highlighted by a blue
rectangle, after that the trend reverses and the signal candle (yellow
arrow) closes below the VWAP line. The candlestick appeared on 5 May
2020, therefore, one would look for a signal to open a trade on the
hourly timeframe of 6 May 2020. In the second case (green arrow), the
rising candlestick closes after a trend reversal on 18 May 2020.

Opening a trade on the hourly time frame for the first case:

A trade can be opened on any candlestick within the range indicated by
the blue rectangle. The signal candle is the one that closed exactly at
midnight, so a trade could be opened right on the next candle. You could
wait for several falling candles in a row for it to be a more reliable
signal. If you open a trade on the candle the arrow points to (a
conservative strategy) and set a 20-point trailing stop loss, the profit
would be 20 points. A strategy with a higher level of risk involves
opening a trade earlier.

Opening a trade on the hourly time frame for the second case:

Here the signal candlestick in the direction of price growth closed at
the same level as the VWAP indicator. In theory, this is a weak signal
and it would be worth waiting for the next candle closing above the VWAP
line (yellow arrow), but trading is always a risk, which sometimes turns
out to be justified.

Despite the fact that VWAP indicator is more sensitive to price in
comparison with moving averages, its disadvantage, like the MA, is
delay. Like moving averages, VWAP is more of an auxiliary trend
confirmation signal. It is rarely used independently and is not
predictive. The tool is used exclusively in intraday strategies. And
although no one forbids you to use the VWAP on long timeframes, its
signals will lose their accuracy.

Interested in free versions of the indicator? Test it on a demo account.
If you don’t have one yet, you can do it in 2 minutes. Click on the
“Register” button in the upper right corner on the broker's [website](https://www.playgroundfx.com/blog/website-for-forex-trading/) (on
any page).

Go to MT4 from your Personal Account (you can learn more about the
LiteForex account [functions](https://www.fintechee.com/tutorial-for-forex-trading/basic-functions/) [here][8]), download, install the template
in accordance with the instructions from the review, test the indicator
and be sure to share your opinion about it in the comments!

In conclusion, a few words about how else you can benefit from working
with LiteForex:

  * LiteForex is an ECN broker that transfers trades directly to virtual ECN systems. This ensures a minimum spread, as well as the order execution speed up to 100 ms (the average market speed is 300-400 ms).
  * In addition to the usual platforms, LiteForex also offers its own very easy-to-use browser platform powered by MataTrader with an integrated copy trading system. Read more about the benefits of social trading and working with the platform in the review “[How to make more money in the foreign exchange market: passive income for a successful [investor](https://www.fintechee.com/tutorial-for-forex-trading/investor-mode/)][9]”.
  * Psss! Now there’s a unique opportunity to get cool prizes (a house and a car among them) on the occasion of the 15th anniversary of the company. Read more about participating in the draw [here][10].

## Conclusions

VWAP is a useful signal confirmation tool, which is very similar to
moving averages. But unlike them, it provides more reliable data on
market volumes and the average market price. It complements trend
indicators and oscillators quite well and is more sensitive to price /
volume changes than moving averages. It will be an excellent assistant
in deciding whether to enter or exit the market. If you still have
questions or ideas on optimizing VWAP [trading strategies](https://www.fintechee.com/forex-trading-strategies/), leave a
comment!

* * *

P.S. Did you like my article? Share it in social networks: it will be
the best “thank you" :)

Ask me questions and comment below. I’ll be glad to answer your
questions and give necessary explanations.

 **Useful links:**

  * I recommend trying to trade with a reliable broker [here][11]. The system allows you to trade by yourself or copy successful traders from all across the globe.
  * Use my promo-code BLOG for getting deposit bonus 50% on LiteForex platform. Just enter this code in the appropriate field while [depositing][12] your trading account.
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
   2. volfix.net/
   3. drive.google.com/file/d/1JRZdhkmI_uN9jagFE3eJ_zTko39VZDNR/view
   4. drive.google.com/file/d/1l1K8vmbRfjrcDvhQljdJCJ6iMrEW05WW/view
   5. lite.forex/downloads/mt5/
   6. my.liteforex.com/trading/chart?symbol=EURUSD&returnUrl=true
   7. www.liteforex.com/trading/additional-services/vps-services/
   8. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/lets-look-into-liteforexs-new-client-space/
   9. www.liteforex.com/blog/for-professionals/combined-strategies-to-make-money-on-forex/
   10. lite.forex/contests/dream-draw/
   11. my.liteforex.com/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=best-technical-indicators&slug2=vwap-indicator-what-is-vwap-in-trading-and-how-to-use-it&openPopup=%2Fregistration%2Fpopup&utm_source=blog&utm_medium=article&utm_campaign=bonus
   12. my.liteforex.com/deposit/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=best-technical-indicators&slug2=vwap-indicator-what-is-vwap-in-trading-and-how-to-use-it&promo_code=BLOG&utm_source=blog&utm_medium=article&utm_campaign=bonus