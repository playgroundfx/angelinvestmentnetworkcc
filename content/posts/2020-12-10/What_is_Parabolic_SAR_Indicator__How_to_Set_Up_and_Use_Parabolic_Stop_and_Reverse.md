+++
categories = ["Cryptocurrency", "Blockchain", "SmartContract"]
date = "2020-12-10"
description = "What is Parabolic SAR Indicator: How to Set Up and Use Parabolic Stop and Reverse"
tags = ["Cryptocurrency", "Blockchain", "SmartContract"]
title = "What is Parabolic SAR Indicator: How to Set Up and Use Parabolic Stop and Reverse"
type = "post"
+++

{{<iframe id="large-banner" src="https://www.bounty.group/#slide=28.0" width="100%" height="600" scrolling="no" style="border: 0px solid rgb(216, 221, 230); border-radius: 3px;">}}

2020-12-10

2020-12-10

[Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) Indicator and the best way to use it while tradingMikhail
Hypov

Dear friends! In this article, we will talk about the [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html)
indicator. Unlike the previously discussed [Stochastic][1] and [MACD][2]
oscillators, it is designed to accurately determine the direction of the
trend and the point of reversal with an accuracy of one bar.

The article covers the following subjects:

Today I will tell you about this indicator, its advantages and
disadvantages, signals, peculiarities of trading with it on the Forex
market and many other secrets of this tool. I will separately consider
five [trading strategies](https://www.fintechee.com/forex-trading-strategies/) that work with the SAR. I will also analyze
examples on the real market.

## What is Parabolic Sar?

PSAR is for Parabolic Stop And Reverse. It is a trend indicator with a
minimal lag that can be used on almost any timeframe. This and the good
forecasting accuracy are the reason for the great popularity of
Parabolic on Forex. The SAR is a trend indicator. It shows who is
stronger on the market - bulls or bears, and allows you to identify the
conditions for a trend change.

In the chart the indicator looks like dots, each of which corresponds to
its own candlestick. In an uptrend, the dots are located below the bars,
and in a downtrend, above them. The formation of a correction or
reversal is accompanied by a “jump” of the dot to the opposite side.

Continuing the description of the PSAR indicator, I should note that it
can also be used as a stop loss and trailing stop. When the price
crosses the current dot of the indicator, the trader receives a signal
of the trend correction or reversal.

## The parabolic stop and reverse indicator

The SAR was created by J. Welles Wilder Jr. In addition to this
indicator, he is known as the inventor of the [RSI][3] and DMI - two
other classic instruments that are available in most trading platforms.

Let's return to the description of the [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) indicator. Wilder
was looking for a system that would maximize profits from trend
movements. The resulting Parabolic indicator allows you to calculate
both the beginning of a new trend and its end.

At the same time, PSAR does not try to guess the peak of the movement.
It follows the trend, making it possible to maximize profits by
gradually shifting the take profit level.

The indicator can be applied to any trading instruments with prevailing
trend movements. At the same time, the developer does not recommend
trading on timeframes below one hour. Also, the indicator is not
recommended for use in case of price fluctuations in a flat. In a
sideways movement, Parabolic gives a large percentage of false signals.

For safe use, do not trade with it in a flat. You can use [the Bollinger
Bands][4], which I talked about in previous articles. Then, using the
Parabolic, confirm the trend acceleration. Acceleration will occur as
long as the indicator dots maintain their position below or above the
price chart, depending on its movement vector. When the [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html)
reverses, this is a signal for a trend reversal.

In the [EURUSD][5] chart, yellow areas mark the moments of PSAR
reversals. Such situations indicate a trend reversal. And the rest of
the time, when the dots are consistently above or below the candles,
directional movement occurs.

## How [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) is calculated

The [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) calculation is done using an algorithm with two
[Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) formulas. The first one is used for long positions
(uptrend):

 **PSAR(i) = (HIGH(i-1) - PSAR(i-1)) * AF+PSAR(i-1)**

The second is for short positions (downtrend):

 **PSAR(i) = (LOW(i-1) - PSAR(i-1)) * AF+PSAR(i-1)**

Where:

  *  **PSAR** is the Parabolic value. With index (i) it’s the current value, and with (i – 1) it’s the value preceding the calculated one.
  *  **HIGH** is the price high.
  *  **LOW** is the price low.
  *  **AF** is the acceleration factor. Its value grows with a step set for each period when new extreme price values ​​are reached. Wilder recommends using an initial factor of 0.02, which increases by 0.02 with each new bar until it reaches a maximum value of 0.2.

AF formula:

 **АF = 0,02 + ix*K**

Where:

  *  **ix** is the number of periods accumulated since the beginning of counting;
  *  **K** is the step of price change, which by default is 0.02.

>  **Important!** AF limit value can be changed in the [LiteForex web
terminal][6] and MT4. However, the author himself and his closest
followers stick to the standard value of 0.2 when trading.

## How to use the [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) and read its signals

Let's look at the operation of [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) and its signals in detail:

  * Identifying the trend. If the curve is above the price, the market is in a bearish trend. If it’s below – a bullish trend.
  * Change of trend. If the current dot appears on the opposite side (the price crosses the curve), then a reversal or at least a major correction should be expected. A [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) buy signal occurs when the parabola is above the price in a downtrend. And after that the first dot is formed below the bar. Accordingly, a signal to sell will be the opposite situation, when the lower dots change to the upper points.

>  **Important!** In case of a sideways trend, these signals do not
work. Avoid using PSAR in a flat.

Let's consider how the indicator works through the example of
**Ethereum**.

The last lower dot is marked with a blue circle in the [ETHUSD][7]
chart. The dot that forms after it is located above the corresponding
bar (purple circle). After this signal appears, a trend reversal occurs.
Then, during the downward movement, we observe an increase in the
distance between the points (red area) signaling the development of the
trend.

I also recommend taking into account the following factors:

  * The probability of a reversal increases as the distance between the dots of the parabola decreases.
  * We can talk about a stable movement in the desired direction after the appearance of 3-4 consecutive dots in a row on the same side.

## How to Trade with the [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html)

Let's look at real Parabolic trading using the [S&P500][8] CFD as an
example.

The first step is to determine the moment when a new trend begins to
form in order to maximize profit from the trade. The ideal signal is a
break in the curve. The blue circle marks the last upper dot. It is
followed by a gap and the first lower dot is formed.

We enter the market at the close of the candle (blue line). Set stop
loss at the level of the [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) indicator (red line). With each
step we will move it to the level of a new dot.

Eventually, one of the stop orders is triggered (red circle in the chart
above). A reverse of the indicator has formed in the chart indicating
the end of the upward movement (green circle).

In the chart above, the flat shows a good example of the PSAR not
working in a sideways movement. We can see that all 100% of the signals
are false. The dot reverses, which indicates a trend reversal. However,
the price movement vector is not directed towards the indicator
movement, but against it.

## [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) Indicator in MetaTrader 4

Now let's figure out [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) use [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) with the MetaTrader 4
platform as an example. The indicator is already available in the
terminal, so you don't need to download and install it.

To add it to the chart, you need to find "Indicators" in the "Insert"
tab or in the "Navigator" menu, select "Trend Indicators" and click on
the "[Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html)".

You can also download the Parabolic Sar 24 with custom modifications. A
popular version of this indicator is [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) MTF (Multi Time
Frame). You can download it [here][9].

The installation procedure in MT4 is standard. See the example in the
article ["Forex [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) Indicator"][4].

Unlike the regular version, [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) MTF is capable of showing
curves from several timeframes at once. For example, the chart above
shows the weekly and [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) PSAR for [BTCUSD][10]. It is convenient for
tracking market dynamics at different levels and for doing end-to-end
analysis of several timeframes in one window.

To set up the desired timeframe, you need to specify the required number
of minutes in the data entry tab for the TimeFrame parameter. Use this
table:

Value| Timeframe  
---|---  
1| M1  
5| M5  
15| M15  
30| M30  
60| H1  
240| H4  
1440| D1  
10080| W1  
43200| MN1  
  
Another interesting type of this indicator is the [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) Color
Alert. It allows you to customize the colors of the dots for an uptrend
and a downtrend separately. The indicator also has sound alerts for
every trend change.

The download link for the [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) Color Alert indicator is
[here][11].

Advisors based on Parabolic are useful too. One of these tools is the
MQLTA [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) Trailing Stop. Its function is to pull up the stop
loss level to the indicator dots. This way the user does not need to
move the level manually.

You can download the script from [this page][12].

## Pros and Cons of the PSAR

After using the Parabolic for a while I have highlighted the following
advantages of this tool:

  * The indicator allows you to keep a position within the trend. As long as the continuous curve continues to form, you can be confident that directional movement is developing. In addition, the current strength of the trend can be indirectly measured by the distance between the dots. When it shrinks, you should be preparing for a reversal.
  * [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) takes into account not only the dynamics of the trend development, but also its duration.
  * Few false signals and small delays during directional movement on the market.
  * The indicator shows where to place your stop loss.
  * Following the signals, PSAR is insured against trading against the trend.

And now to the disadvantages:

  * Parabolic is not intended for flat trading. Only use it in trend phases of the market.
  * On small timeframes, the indicator demonstrates high sensitivity to market noise. Wilder himself recommends using it on H1 and up. I am inclined to believe that trading on smaller timeframes is possible. But only with non-standard settings and in conjunction with other technical analysis tools that filter out market noise.

## The SAR Indicator Settings

The best settings are the standard Parabolic parameters.

The initial factor is 0.02, the price step is also 0.02, and the maximum
AF is 0.2. Most traders use these settings for the Parabolic. Wilder
also used them. These parameters allow you to trade on most common
timeframes above H1 and get high-quality buy and sell signals.

Moreover, the lower the acceleration factor, the less it will follow the
price. On the other hand, the higher the acceleration factor, the closer
to the price it will move. Therefore, increasing the factor increases
the sensitivity of PSAR, while lowering it decreases it. We will use
this feature to determine the optimal settings for different timeframes.

### Best [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) settings for intraday

The standard [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) settings are quite applicable for classic
intraday trading. In rare cases, when it comes to the timeframes M5 and
M15 and the indicator needs higher sensitivity, you can use the 0.021
step.

###

### [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) settings for 5 minute chart

For the M5 timeframe, I would stick to Wilder’s classic teachings and
also use the [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) setting with a step of 0.021. It is quite
sensitive to fluctuations in five-minute charts. But the strategy using
two Parabolics in a five-minute chart suggests adjusting one of the
indicators in 0.04 increments.

### Best [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) settings for scalping

Scalping in the classic version, especially when it comes to trading on
minute timeframes, requires the settings that are most sensitive to
price changes. So it is best to set the largest value recommended by
Wilder at 0.022.

There are also [trading strategies](https://www.fintechee.com/forex-trading-strategies/) with Parabolic settings beyond the
values recommended by the creator with a step of 0.05 and even more.

## [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) strategy

The high accuracy and easy use of PSAR have become the reason that this
indicator is used in many successful trading systems. Strategies using
Parabolic can include several versions of this tool. In this case, the
authors of trading systems strive to reduce the disadvantages of using
one indicator by using different timeframes and settings.

The second option is the combined [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) strategies. In addition
to Parabolic, they include other signals and indicators, for example
MACD or moving average crossovers.

Below I will tell you about five working Parabolic strategies that are
popular among many traders.

### Double parabolic SAR strategy

This trading system is designed to trade currency pairs, indices,
metals, and commodities in a five-minute chart (intraday).

 **[Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) indicator setup and trading strategy:**

  * Parabola 1 - initial factor 0.02, step 0.02, limit 0.2;
  * Parabola 2 - initial factor 0.02, step 0.04, limit 0.2.

Conditions for entering a buy position:

  * Two points jump from the upper to the lower position.
  * The stop loss is set just below the low of the opening bar.

Conditions for entering a sell position:

  * Two points jump from the lower to the upper position.
  * The stop loss is set just above the high of the opening bar.

Exit the position in one of the following three ways:

  * when the fast Parabolic breaks;
  * when a local support or resistance level is reached;
  * by take profit equal to 2-3 stop losses.

Let's consider this Parabolic indicator strategy in the [bitcoin](https://www.letsplayfx.com/blog/forex-for-bitcoin/) chart.

In the [BTCUSD][10] chart, a blue circle marks two dots of the fast and
slow Parabolic when they moved from a position above the price to a
position below the price. After receiving a signal, open a long position
at the blue line level. Set a stop loss below the low of the opening
candle. I’ve marked it with a red line.

Then wait for the signal to exit the market. The fast parabola breaks in
the area marked with the green circle. At this moment, close the
position with a small profit (green line).

### EMA crossover and [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) strategy

 **This [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) trade strategy allows you to trade on longer
timeframes from H1 to H4. It’s suitable for any asset, but it
demonstrates the best performance on classic Forex currency pairs,
indices, and gold.**

Indicator settings:

  * Parabolic - 0.02, 0.02, 0.2;
  * EMA 10 - 10 bars;
  * EMA 25 - 25 bars;
  * EMA 50 - 50 bars.

Conditions for entering a buy position:

  * EMA 10 crosses EMA 25 and EMA 50 from the bottom up.
  * PSAR reverses from top to bottom. Moreover, if this is the first lower dot, some traders open an order at the next one after it and thus receive additional signal confirmation.

Conditions for entering a sell position:

  * EMA 10 crosses EMA 25 and EMA 50 from the top down.
  * PSAR reverses from bottom to top. If this is the first upper dot, wait for the next one as confirmation.

Set stop loss at the point opposite the opening bar. Afterwards you can
leave it there or move it along with the parabola.

You can close the position in two ways:

  * After the formation of a break in the SAR curve.
  * When the EMA 10 crosses the two lines, the EMA 25 and the EMA 50. This method itself results in a loss of profit due to a delay in the response of the moving averages. Therefore, it is better to use it together with a trailing stop.

Let's try trading with this strategy using the [EURJPY][13] currency
pair as an example.

The blue oval marks the moment when the fast blue EMA 10 crosses the
slow green EMA 25. Before that, the fast moving average crossed the EMA
25. I marked the first lower dot after a series of dots located above
the price bars with a yellow circle. After getting a signal, open a long
position at the blue line. After that, set a stop loss near the parabola
dot (red line).

As a trend develops, a gap forms in the indicator curve. The first dot
above the price bars is marked with a green circle. Here we take profit
at the green line.

Note that the EMA was not crossed because the short-term bearish move
was a correction. After it, the main trend continued. This means that
the second signal option to close a position allows you to reduce the
influence of minor price fluctuations. However, it should be used in
conjunction with a trailing stop.

### [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) and MACD strategy

 **This Parabolic strategy uses the[[MACD indicator](https://www.algotradesoft.org/custom-indicator/macd.html)][2], which I’ve
described earlier in my article. It is easy to learn, includes only
standard technical analysis tools and shows good results in any markets.
The minimum time period is M15, and the optimal one is M30 and above.**

Indicator settings:

  * Parabolic - 0.02, 0.02, 0.2;
  * MACD - 12, 26, 9.

Conditions for entering a buy position:

  * The Parabolic curve forms below the price after the break, confirming the development of a bullish trend.
  * The MACD histogram crosses the zero line from the bottom up during the first three lower dots of the [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html).

Conditions for entering a sell position:

  * The curve forms above the price after the break.
  * The MACD histogram crosses the zero line from the top down during the first three dots of the SAR.

You can set stop losses and take profits in two ways:

  * By the nearest local extremum. In this case, close by take profit of 1.5–2 stop orders.
  * By the PSAR dots. Close using the Parabolic signal if the stop loss remains stationary or by trailing stop, which moves in the direction of the trend along with the PSAR points.

Let's look at how this strategy works through the example of [gold][14].

The blue circle in the MACD chart marks the moment when the histogram
crosses the zero line. The blue circle in the price chart marks the
first PSAR low after the gap. Note that in some cases the histogram
crosses the zero line before the reversal signal from the Parabolic.
Such situations are also considered a signal to enter the market.

After receiving all the necessary confirmation of the development of an
uptrend, open a position at the blue line level. Set a fixed stop loss
at the level of the parabola dot. Next, wait for a signal to close the
order. A gap appears in the area marked with a green circle. On this
bar, fix the profit at the level of the green line.

### [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) scalping strategy

 **The [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) scalping strategy shows high efficiency on classic
currency pairs like the[EURUSD][5], [GBPUSD][6], [AUDUSD][15]. The
optimal timeframes will be M5 and M15.**

We will use three instruments at once:

  * Parabolic with standard settings (0.02, 0.02, 0.2);
  * [Commodity Channel Index](https://www.algotradesoft.org/custom-indicator/commodity-channel-index.html) (CCI) with a period of 45 bars;
  * EMA with a length of 50 for M1 charts and a period of 21 for M5.

Rules for opening a long position:

  * The Parabolic dot is located above the moving average;
  * CCI is above the “+100” level.

Rules for opening a short position:

  * The SAR dot is below the moving average;
  * CCI is below the “-100” level.

Set stop loss at the nearest extreme point within 3-5 bars. You can
close by take profit of 1-2 stop orders. Also, to select the optimal
time for closing a position, you can use the signal of the CCI curve
crossing the level +100 or –100.

The blue oval in the CCI chart marks the moment when the indicator curve
reaches the oversold zone and the subsequent rebound in the opposite
direction. In the [EURUSD][5] one-minute price chart, at this moment,
the Parabolic dot is below the moving average.

After getting a signal to sell, open a position at the end of the
candlestick located opposite the Parabolic dot marked with a blue circle
(blue line). Set stop loss at the level of the nearest high (red line).

After some time, we see the CCI crossing the mark -100 (green circle).
On the candlestick where this event took place, we take the profit at
the level of the green line.

### ADX + [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) strategy

The combination of PSAR and ADX indicators is very popular in trading
strategies. Here we will look at one of the most simple but effective
trading systems.

You will need:

  * [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) with standard settings - 0.02 and 0.2.
  * ADX with a period of 14

This trading strategy is popular with Forex traders. However, in my
personal experience, the PSAR and ADX bundle work well together both in
the cryptocurrency market and in stocks as well.

The ADX indicator itself deserves a separate mention. If you have never
worked with this tool, read the article ["ADX Indicator: Average
Directional Index"][16]

In short, the ADX, like the Parabolic, is also a trend indicator. Its
ability to reflect the strength of directional movement allows it to
filter out sideways movements in the market, which are detrimental when
dealing with PSAR signals.

 **Let’s look at the entry points when using this strategy:**

For a long position:

  1. PSAR dots start their count below the price chart
  2. +Di crosses -Di and is on top
  3. ADX curve is greater than 13 with an upward slope

For a short position:

  1. PSAR dots start their count above the price chart
  2. +Di crosses -Di from the top down
  3. ADX curve is greater than 13 with an upward slope

To exit the position, one of the following conditions must be met:

  * Reverse crossing of the lines +Di and -Di
  * The transition of the Parabolic dot in the direction opposite to the price chart
  * Closing by the set stop loss or take profit.

The strategy itself does not have separate conditions for determining
stop loss and take profit levels. Reverse signals are used as the SL and
TP – the PSAR reversal and reverse crossing of the ADX indicator signal
lines.

If trailing Take Profit and Stop Loss are not allowed by your risk
management system, the recommended indent for take profit is 2.5x the
stop loss size. In this case, the stop loss level itself is set with an
indent of several points from the local extremum.

Also, remember to follow the basic rules of risk management and move
your stop loss to breakeven and protect profitable positions from
drawdowns.

The chart above shows an example of this strategy. All three conditions
for opening a long position are met. After the signal candle closes, we
enter the market at the blue line.

Then we get the first reverse signal from the PSAR - the indicator dot
appeared above the price chart (green circle). When the candle opens, we
take the profit. I also marked the reverse crossing of the ADX signal
lines with a red circle. You can see that the last signal was a little
late. In practice, opposite scenarios can also occur, when the first
signal is the crossing of +Di and -Di. Therefore, it is important to
notice which signal appeared first.

Let's discuss the most frequently asked questions

## Conclusion

Beginners are often reluctant to use built-in indicators believing that
effective tools cannot be available to everyone. The [Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html) is a
striking example of the opposite. The indicator's ability to predict
trend reversals and update support levels can be a good addition to any
trending strategy or as a risk management tool.

The only Achilles' heel of this indicator is the sideways movement of
the market. The PSAR is not capable of filtering this alone, so it is
imperative to use additional technical analysis tools indicating the
absence of a trend.

If you doubt the effectiveness of Parabolic, try it out on the
[Liteforex demo account][17]. To start trading, you don't even need to
register. And the time spent on learning and testing will pay off with
stable profits!

Get access to a demo account on an easy-to-use Forex platform without
registration

[ Go to Demo Account ][18]

## Price chart of EURUSD in real time mode

The content of this article reflects the author’s opinion and does not
necessarily reflect the official position of LiteForex. The material
published on this page is provided for informational purposes only and
should not be considered as the provision of investment advice for the
purposes of Directive 2004/39/EC.

Rate this article:

{{value}}

( {{count}} {{title}} )

   1. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/best-technical-indicators/stochastic-oscillator/
   2. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/best-technical-indicators/macd-indicator-forex-trading/
   3. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/best-technical-indicators/rsi-relative-strength-index/
   4. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/best-technical-indicators/bollinger-bands/
   5. my.liteforex.com/trading/chart?symbol=EURUSD
   6. my.liteforex.com/trading/chart?symbol=GBPUSD
   7. my.liteforex.com/trading/chart?symbol=ETHUSD
   8. my.liteforex.com/trading/chart?symbol=SPX
   9. www.best-metatrader-indicators.com/parabolic-sar-mtf-multi-time-frame/
   10. my.liteforex.com/trading/chart?symbol=BTCUSD
   11. www.best-metatrader-indicators.com/parabolic-sar-color-with-alert/
   12. www.mql5.com/en/market/product/26362
   13. my.liteforex.com/trading/chart?symbol=EURJPY
   14. my.liteforex.com/trading/chart?symbol=XAUUSD
   15. my.liteforex.com/trading/chart?symbol=AUDUSD
   16. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/best-technical-indicators/adx-indicator-average-directional-index/
   17. my.liteforex.com/trading
   18. my.liteforex.com/trading/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=best-technical-indicators&slug2=parabolic-sar-indicator&type=currency