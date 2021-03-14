+++
categories = ["Cryptocurrency", "Blockchain", "SmartContract"]
date = "2021-03-14"
description = "Average True Range - ATR Indicator"
tags = ["Cryptocurrency", "Blockchain", "SmartContract"]
title = "Average True Range - ATR Indicator"
type = "post"
+++

{{<iframe id="large-banner" src="https://www.bounty.group/#slide=9.0" width="100%" height="600" scrolling="no" style="border: 0px solid rgb(216, 221, 230); border-radius: 3px;">}}

2021-03-12

2021-03-14

[Average True Range](https://www.algotradesoft.org/custom-indicator/average-true-range.html) Indicator: improve your trading with volatility
measureOleg Tkachenko

The ATR ([Average True Range](https://www.algotradesoft.org/custom-indicator/average-true-range.html)) indicator is a tool for measuring relative
volatility levels.

The ATR meaning tells us how much the price has changed in a current
period compared with previous periods. It is used in trend strategies to
assess a trend reversal probability and determine the moment when the
market starts trending. It also serves to place Stop Loss and Take
Profit orders and is used for estimating the range's width when trading
based on channel strategies.

The indicator is included by default in many trading platforms and
applied as an auxiliary indicator combined with Price Action and
oscillators.

The article covers the following subjects:

## What is ATR: average true range full definition

Technical analysis indicators can be divided into three groups:

  * Trend indicators that show a trend's strength and direction

  * Oscillators that indicate a potential reversal and form overbought/oversold areas

  * Forecast indicators that predict price movements based on previous regularities

The ATR forex indicator is often considered to be an oscillator as it
helps us define trend reversal points. If the indicator covers over 75%
of its average distance in a fixed time period, there can be a reversal.
Unlike oscillators, it hasn't got the "0" and "100" limits that define
overbought and oversold territories. Thus, the ATR indicator is a
specific technical analysis indicator that combines the three groups'
features.

The [Average True Range](https://www.algotradesoft.org/custom-indicator/average-true-range.html) was first introduced by J. Welles Wilder in 1978.

J. Welles Wilder also developed such popular tools as [[Parabolic SAR](https://www.algotradesoft.org/custom-indicator/parabolic-sar.html)][1]
and [RSI][2]. The indicator was first meant for futures markets, which
are much more volatile than stock markets. Then it grew so popular that
it was included in trading platforms as a basic one.

J. Welles Wilder created the ATR indicator for one purpose: determining
market volatility.

Average true range trading is rarely applied to manual strategies, but
it is often used for forming trading [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s' automatic risk management
systems. This indicator doesn't measure a trend's strength and cannot
forecast price movements. It only estimates market volatility.

That said, the average true range is the indispensable tool for setting
target profit levels, placing stop orders, and determining the width of
price channels in channel and range strategies (strategies used for
trading retracements and breakouts).

The ATR indicator is NOT used for

  * determining a price direction

  * searching for a divergence

  * it can sometimes indicate reversal points

  * it is used for measuring price ranges and the nature of their changes.

The indicator's main signal is the following: when the indicator grows,
an asset's volatility grows. The classic error is to link the
indicator's growth to price growth. The ATR indicator doesn't show the
price's direction either. When it grows, the price line may rise or
fall. It’s the price volatility range that increases.

### What is [Average True Range](https://www.algotradesoft.org/custom-indicator/average-true-range.html)?

This volatility indicator measures price volatility over a certain
period. It compares

  * the current candle's highs and lows
  * the current candle's highs and lows, and the previous candle's close.

 Then it takes the greatest of those values and averages them out based
on the arithmetic mean.

The indicator's relatively low value can be read as follows:

  * the market is flat. The price moves in the same range, and the average difference between highs and lows doesn't change. However, we cannot estimate the range’s width using the ATR indicator;

  * the market trend is slow. The price grows or falls, but the difference between neighboring candles isn't significant.

The indicator's leading signal is a sharp increase in its readings that
indicates a rising difference in candlestick extremums. The candles'
bodies and shadows are growing, and the price's angle of ascent relative
to the horizontal axis becomes bigger. At the same time, the price range
may remain the same. Volatility growth means that the price covers the
same distance faster.

Example of using the ATR:

There's a small downtrend in the market; the ATR value is small.

Then, there's a sharp volatility splash: the price range is growing
sharply over a short time period. The [Average True Range](https://www.algotradesoft.org/custom-indicator/average-true-range.html) is rising
steeply. Next, a slow uptrend begins. Although the distance between the
trend's start and top is many times bigger than the volatile segment's
range, the ATR is reducing because the trend has been developing over a
certain time period.

## ATR indicator formula

There are three formulas [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) calculate atr:

  * The difference between a current candle's extremums (high and low). The current candle's high less low.

  * Absolute value of the current Max (High) less the previous close. |High — (Close-1)|

  * Absolute value of the current Min (Low) less the previous close. |Low — (Close-1)|

Then we take the greatest value of those and calculate the ATR
indicator's readings. Here's the formula:

ATR = Moving Average (TR, m)

where TR is the greatest value out of the three differences and m is an
averaging period. Moving average is the arithmetic mean of a given set
of values.

### [Average True Range](https://www.algotradesoft.org/custom-indicator/average-true-range.html) calculation

Now let's find out [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) calculate the ATR value to better understand
its work principle. I remind you that the [Average True Range](https://www.algotradesoft.org/custom-indicator/average-true-range.html) is the
greatest value of the following: current high minus current low;
absolute value of current high minus previous close; absolute value of
current low minus previous close. The indicator compares those three
values for two neighboring candles. The period is the number of candles
considered.

For example, if the period's value is 1, the ATR indicator will compute
the difference of prices for the latest candle. It will compare its
High/Low, and the difference between the candle's High/Low and the
previous candle's close. So, with period "1", two candles are
considered. For example:

The difference between high and low: 1.2121 — 1.2117 = 0.0004, or four
points for 4-digit quotes. That is the greatest value of the three
possible remainders.

The print screen shows that the value is identical to ATR calculation.
"0.0004" means that the average true range is four points for one candle
period.

If we take period 2, the three latest candles will be considered. The
two values for the ultimate and the penultimate candles are averaged:
they are summed and divided by two, according to the arithmetic mean.

The longer the period, the more candles are considered, and the smoother
the indicator's line gets. However, remember that ATR reacts slower to
price movements when the period gets longer.

## How can volatility indicator help while trading?

The indicator identifies the moment when the price range starts
enlarging sharply. This feature can be used for the following purposes:

  * To form short-term strategies. A sharp volatility surge is a perfect moment for scalping. You can check my article [Forex scalping][3] to learn more about this type of strategy.

  * To decide in which direction a trade should be opened. If the [Average True Range](https://www.algotradesoft.org/custom-indicator/average-true-range.html) covered half its mean range, it's probably too late to open a trade in the direction of the trend, and you'd better wait for a reversal.

  * To determine price targets. Take Profit is placed at the volatility range limit or within the range. If the [Average True Range](https://www.algotradesoft.org/custom-indicator/average-true-range.html) is 60 points, Take Profit can be set at 45-50 points relative to the opening price.

  * To determine Stop Loss levels. Stop Loss is placed outside the price volatility range and linked to the ATR correction multiplier. ATR correction multipliers are calculated separately for each specific asset.

## What Does ATR Indicator Tell You?

The ATR indicator has got just one signal: it rises or falls. The higher
the ATR value is, the more volatile the market is, and the faster the
trend line moves from one range limit to the other.

  * In segment 1, the indicator is moving horizontally. It means the market is flat: the amplitude of price fluctuations and candlesticks' size are small.

  * In segment 2, the ATR value is surging, and the indicator starts growing. It means volatility is increasing, and we should look for an entry point. As the ATR doesn't indicate a price direction, we shall determine it ourselves. For example, draw support and resistance levels through the flat range's extremums and open a trade in a breakout direction.

  * In segment 3, there remains high volatility, but the trend is changing direction. A trader's task is to catch the price line reversal on time and reverse the trade when volatility is still high.

  * In segment 4, the indicator is returning to its lowest values in a flat range. It means volatility is declining; the pace of price changes is slowing down; the amplitude of price moves is decreasing; the candles' bodies are becoming shorter than the candles in segments 2 and 3. That can indicate a flat market or a trend slowdown. In our case, we have a slow downtrend. It's a signal for swing-traders and scalpers to exit the market.

Here's how we can use the ATR's signal about a rise in volatility:

  1.  A new trend's start is a signal to open a short-term trade to catch the fastest price movement in either direction over a short period. It’s one of the [options](https://www.fixpro.org/post/options-liquidity/) for scalpers.

  2. A sharp increase in the price movement amplitude is a signal to exit the market or increase stop orders' value. Suppose we have a medium- or long-term trade, and the stop order value was calculated based on the maximum possible drawdown, according to our risk management rules. We see that the volatility is growing sharply. We have two [options](https://www.fixpro.org/post/options-liquidity/): to close the trade earlier before the price reaches the stop level or top up our account, increase the stop value, and wait for a temporary drawdown to end.

This volatility indicator doesn't point to overbought/oversold areas, so
its readings are estimated compared to the readings over previous
periods by zooming out the chart. Volatility levels don't depend on a
price direction. The indicator's line can be rising, while the price can
be moving up or down.

## Day trading ATR

Large time frames are usually used for preliminary analysis. The main
time frame can be H1, and the time frame analyzed can be D1.

Example: let’s determine average [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) volatility for the USDCAD on the
[daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) time frame.

With period 14, the value is 0.0077. It means that the price's average
true range is 77 points over the last 14 trading days. Switch to the H1
time frame and check how far the price moved since 00:00 up to this
moment:

The [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) range's open price at 00:00 is 1.26799 (rounded to 1.2680);
the current price is 1.2661. There's a powerful downtrend that other
indicators can confirm too. The price moved down by almost 20 points,
with average volatility being 77 points. Theoretically, if the price
line has not covered 50% of the average true range, we can open a trade
in the trend direction. The market entry point for a short position is
the current candle.

If the price has covered over 50% of the ATR, wait for a while. Think
about opening a trade in the opposite direction of the trend if the
price covers 70%-80% of the [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) ATR. This method isn't flawless, but
it can be one of the [options](https://www.fixpro.org/post/options-liquidity/) when determining market entry points and
the price direction.

## The ATR Indicator in MT4

The [Average True Range](https://www.algotradesoft.org/custom-indicator/average-true-range.html) indicator is one of the basic ones in MetaTrader
4 and MetaTrader 5. You can find it in the "Indicators/Oscillators"
menu.

 **ATR settings for MT4**

The main parameter is Period. Using the same window, you can set Maximum
and Minimum levels. That's convenient for visually comparing previous
periods' volatility with a current period's one. Memorizing values isn't
convenient: it's easier to set the levels and check deviations from a
current value by scrolling the chart. The chart will display only the
time limits specified in the settings.

You can fix the value of the level in the "Levels" tab, and it will be
displayed as a horizontal line in the chart. For example, as the red
line in the print screen below.

One of the drawbacks of displaying the indicator in МТ4 is that only the
current value is shown next to its name (the blue rectangle), and it
won't change when you're scrolling. You can put the cursor on a point
and wait for a pop-up window or activate the "Data Window" (Ctrl+D).
Both [options](https://www.fixpro.org/post/options-liquidity/) aren't convenient to me.

The Visualization tab shows how the indicator will be displayed on a
selected time frame. For example, you're analyzing the chart on several
time frames, and you need ATR on the [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) time frame. You tick D1, and
the indicator will disappear when you switch to other time frames.

There are various modifications of the indicator on the Internet. You
can [download ATR Ratio][4] on the MQL5 site (Short-term ATR / Long-term
ATR ratio).

The template can be added to the platform. Please let me know if you
want to learn more about those modifications and work strategies based
on them.

## ATR settings on LiteForex's online platform

How to set the ATR indicator on LiteForex's platform:

  1. Go to "For Beginners/Open a demo account" in the homepage's upper menu. You will be automatically redirected to a free demo account on LiteForex's online platform. Registration isn't necessary.

  2. Click "Trade" in the left menu. Choose your trading instrument. Let's say [the EUR/USD pair][5] in the "Currencies" tab.

  3. On the price chart that appears, click on "Indicators" and select "[Average True Range](https://www.algotradesoft.org/custom-indicator/average-true-range.html)."

###

 **ATR settings on LiteForex's online platform**

There are a few of them:

1\. Depth (period)

The default value is 14, which means the indicator uses the last 14
candlesticks. For short periods up to M15, it is recommended to increase
that period. For time frames longer than H4 - decrease that period. For
example, traders prefer period 7 for the D1 time frame.

An asset's peculiarities should also be considered: some pairs are more
volatile than others. So, it would be wise to shorten the period for low
volatility assets to increase the indicator's sensitivity to price
changes.

2\. Smoothing

It's about the type of MA that the indicators are based on. There are
four [options](https://www.fixpro.org/post/options-liquidity/). This parameter doesn't influence the indicator line's
plotting significantly, but the value can vary, and that can be a
decisive moment for high-precision strategies.

3\. Accuracy

The parameter varies from 0 to 8 and sets the number of digits after the
decimal point.

You can change the line color in the "Style" tab.

In contrast to MT4, you can see the indicator's value by placing a mouse
pointer to it.

## How to use ATR indicator

Average True range is most often used in the following cases:

  1. To determine Stop Loss levels. Volatility levels outline the range of price movements. The limits of that range can be a reference point.

  2. To determine flat periods. If the ATR value is low when compared with average volatility, the market is flat.

  3. To identify the end of a trend. The farther the price line goes beyond the ATR limits, the likelier it is to stop.

### Placing Stop Loss orders

Stop orders are usually placed in the area of local extremums with a
slight indent. The question is [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) correctly identify local extremums
and not let price noise trigger stop orders.

To place stop orders using ATR, we need to do the following:

  * Draw support and resistance levels through the most evident extremums on a short time frame (М5-М15).

  * Add/subtract 2*ATR to/from the price value of the candle's ultimate extremum. The value you get is a Stop Loss level. The multiplier "2" should be adjusted to each specific pair. At least 1.5 ATR is recommended. The best ATR Stop Loss multiplier for time frames starting from H1 is "3".

There's a different method: place a stop order at the level when opening
a trade. Subtract or add a few points from that value for filtering. To
place Take Profit, switch to a bigger time frame and check the
instrument's level there.

This method works the best on short time frames with price noise — the
price line's chaotic, unpredictable movements in either direction. Using
the indicator allows us to place stop orders at a safe level, providing
for price noise.

Example

During a downtrend, draw a resistance level to open a trade after its
breakout, confirmed by the pattern. Open a long position on a pullback.
Minimum price — 1.19588, ATR — 0.0005 or five points. Multiply 0.0005 by
two and subtract the value from the minimum price. You'll get the Stop
Loss level of 1.19488. As the print screen shows, the price line didn't
get to that level. It tested the level of 1.19516 and then reversed
upwards.

### Flat filter

You earn from a trending currency pair with medium [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) volatility of
80 points. I got this number using a volatility calculator. If current
volatility is less than 50% of that range, the market can be considered
flat. So, if the value is less than 40 points, we don’t search for entry
points using trend strategies as any direction of quotes will hardly
last for a long time.

It's hard to say if it's reasonable to follow that scheme. First, the
value of 50% is conventional and should be readjusted to each particular
pair. Second, the market can be trending on smaller time frames.

The instrument's drawbacks are lags, which is true of all moving
averages. The longer the period, the less sensitive the instrument is to
current price changes. For example, if you set the period at 50, the
indicator will consider 50 last candlesticks. If the price changes
sharply on the two or three last candles, such changes will be absorbed
by the previous candles' values. On the other hand, a short time frame
can produce a lot of false signals. So, all the minuses of moving
averages are typical here too.

Example:

The EURUSD's average volatility over the past week was 44.25 points.

The ATR current value on 4-digit quotes was 61 points on the [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/)
chart. As the current volatility is higher than average, the market
isn't flat, and the current trend is a bit stronger than the weekly one.

### Determining potential trend reversal points

The bigger the indicator wave's amplitude is relative to its previous
values, the likelier the price line is to reverse.

Example

A relatively low ATR value couldn't say if there was a trend on the
[daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) chart. There was an uptrend, but its pace was so slow that the
[Average True Range](https://www.algotradesoft.org/custom-indicator/average-true-range.html) couldn't identify it.

The indicator's steep growth indicates that market volatility is rising:
the price's angle of ascent is increasing, and the price is changing
faster. The trader only needs to predict the trend's direction.

ATR reaching the maximum and reversing means that volatility has started
to fall. Note that the trend changed its direction while the indicator
line was growing. Let me remind you that the [Average True Range](https://www.algotradesoft.org/custom-indicator/average-true-range.html) doesn't
indicate price directions; it only shows a relative price change speed.
The indicator's return to its current lows means that the price change
speed is declining: the market is becoming flat or trending slower.

There's another way to identify pivot points. The average true range
value is compared with the distance that the price has covered from the
beginning of a time frame to the present moment. A shorter time frame is
used for comparison.

Example. Let's take as 100% the H1 ATR value, which shows a price
movement’s average true range over the past hour. Then switch to the
one-minute time frame and find where the current H1 time frame begins.
Estimate the price distance covered up to the present moment.

  * If the price line went farther than 70%, a reversal is highly likely to happen. Think about opening an opposite position.

  *  If the price line covered less than 30% of the distance, think about opening a trade in the trend direction.

  * If the distance varies from 30% to 70% of the range, take your time.

Those values are just a reference point. They are specific to each
particular asset.

## ATR [trading strategies](https://www.fintechee.com/forex-trading-strategies/)

Trading on several time frames using levels and ATR. Most strategies
have already been described above. I'll show you [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) use them in
practice.

### Step 1. Daily time frame analysis

Open the [GBPUSD][6]'s [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) chart and check the trend.

The chart shows a strong, steady trend that started after a dramatic
drawdown. Note a sharp ATR surge during the downtrend: one could profit
from short positions there. A smooth uptrend continues; there are
several consecutive growing candles with small bodies. The ATR indicates
there's no strong volatility. That means the price is expected to
continue rising smoothly. The ATR value is 92 points.

### Step 2. Short-term time frame analysis

Then switch to the M15 chart and check how many points the price has
covered since the [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) opening.

The opening price was 1.38988 at 00:00. By the morning, the price gained
almost 55 points and then came back. ATR indicates high volatility. As
the [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) range is 92 points and the price isn't far from the start, we
can presume that the uptrend will continue.

### Step 3. Opening of a trade

Let's sum up: we decided to open a long position because

  * There's a slow uptrend with low volatility on the [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) time frame.

  * The M15 time frame is showing a resistance level from which the price has just pulled back upwards.

  * The price has covered nearly 50% of its [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) volatility and partly corrected back to the [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) range’s start point.

So, I open a trade at 1.39236 (almost 25% of the [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) range equal to 92
points). Stop Loss: current ATR*2, which equals 14 points. A multiplier
of 3 would probably be better: Stop Loss would be located a bit below
the opening price of 1.38988. Take Profit: 75% of [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) ATR.

The volume of a position should be determined individually and depends
on your goals and deposit.

Close the trade based on Take Profit or when a clear reversal pattern
appears. I don't think it will appear before the [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) ATR reaches 50%,
though. The target profit is 5 USD.

### Step 4. Closing a trade

#### 4.1. Conservative scenario

Everyone has their own profit targets, but I'd recommend that beginner
traders shouldn't wait for Take Profit to trigger and should fix current
profits at the first reversal.

If you see that the price cannot decide its direction during a high
volatility period, like in this situation, close the trade. Closing
price: 1.39385. Profits in 2.5 hours: around 15 points minus spreads.

#### 4.2. Aggressive scenario

The target is to make the most profits based on the ATR theory. I'm not
in a hurry to close a trade, and I hold it. As a result, it closed at
Stop Loss at minus 1.51 USD. The market analysis revealed a mistake. The
market volatility is still high, but there was a clear trend shift. The
arrow in the print screen below marks the opening point.

The [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) candlestick is downward. So, I open a counter trade using the
same principle: the opening price at 00:00 (1.38988) marks the beginning
of the volatility range, but the trend is downward now. The volume can
be doubled.

It took me 30 minutes to claw back the loss from the previous trade and
earn 0.5 USD. I fixed the profit from the second trade for psychological
reasons: to cover the previous loss.

### Key points:

  * The ATR indicator shows current volatility shifts. However, the examples proved that the price could change its direction within a few hours. That can be used in [Swing [trading strategies](https://www.fintechee.com/forex-trading-strategies/)][7].

  * To calculate Stop Loss for a short time frame, we'd better use multipliers equal to or less than 2. I'm open to further discussions regarding the issue, though.

  * There are two market exit strategies. The first one suggests exiting at the first trend reversal. The other one implies using Take Profit calculated based on ATR. If a trade hasn't closed by the end of the day, close it manually. If a trade is closed at Stop Loss, try to open a counter position.

You can use hedging or Trailing Stop.

## ATR Trailing Stop Loss

Trailing Stop Loss is a Stop Loss order that follows the price in the
direction of a trade and stays at the taken level if the price reverses.

Volatility is measured only by the price range over a fixed time frame.
The price can move in any direction. If we open a trade and place a
regular Stop Loss order when the price went outside a flat range, we can
have the following scenario: the price reaches fast the opposite limit
of the volatility range and gets back. Here's an example in the print
screen below.

[Average True Range](https://www.algotradesoft.org/custom-indicator/average-true-range.html) starts growing, and we can open a long position in
point 1. If a trader is eyeing the chart all the time, he/she will close
the trade based on patterns in point 2. If he/she misses that moment,
he/she will lose profits and make losses in point 3. The price will have
gone through the entire volatility range and backward within a few
hours.

Using ATR Trailing Stop allows us to fix at least some parts of profit
and avoid closing a trade at loss during high volatility. Theoretically,
the Trailing stop's value is ATR*k, where "k" is a volatility multiplier
set manually. Most often, it's "2", "2.5" or "3": the higher the time
frame, the bigger the multiplier.

The same example: a long position is opened at 1.26776 in point 1 and
secured with Trailing Stop set at 2*0.0006, i.e., 12 points, which
equals the ATR value registered at the trade's opening. If the trade is
secured with Trailing Stop, it will be automatically closed in point 2.
If we deduct spreads, the profit will be around 15-17 points on 4-digit
quotes in two hours. Without Trailing Stop, the trade would have been
closed at 12-point loss plus spreads.

How to set Trailing Stop on LiteForex's platform:

  * Set the size of a trade and open it in one click.

  * Open the "Portfolio" menu in the lower part of your platform and click "Edit".

  * Set Trailing Stop in the window that opens.

## ATR stock trading/ atr stock

The instrument's application to the stock market is the same. Average
True Range estimates trading activity and [investor](https://www.fintechee.com/tutorial-for-forex-trading/investor-mode/)s' interest in a
stock. If the indicator's value is growing, volatility and trade volumes
are growing too. If the value is low, the market is flat. In addition to
ATR, you can use the volume indicator or the depth of market (DOM) in
MT5 to check powerful support and resistance levels.

The indicator is even more useful when financial reports, press
releases, or other stats are published. It helps us to see:

  * Market reaction - how fast and violently the market reacts to the [news](https://www.letsplayfx.com/blog/forex-news-website/).

  * Market volatility levels concerning specific [news](https://www.letsplayfx.com/blog/forex-news-website/)worthy occurrences; what type of [news](https://www.letsplayfx.com/blog/forex-news-website/) provokes a stronger market reaction.

  * Volatility degree: how long a high volatility period lasts after statistics are released.

  * Correlation: which releases are interrelated? For example, will Apple's financial reports affect other technological companies' quotes?

Another important aid will be [the Economic [calendar](https://www.fintechee.com/web-trader/)][8] and financial
[calendar](https://www.fintechee.com/web-trader/). Have a try and use ATR on the [Tesla (TSLA)][9] chart, for
example.

## Downsides of ATR

The [Average True Range](https://www.algotradesoft.org/custom-indicator/average-true-range.html) has got some downsides too:

  * Limited area of application. It doesn't show price directions or provide forecasts. It only estimates general volatility levels compared with previous periods.

  * Lags. Specific average true range formula. Volatility can start growing, but the indicator's value will still be low. Lagging can last across 1-2 candlesticks.

Though ATR belongs to the oscillators group, it's best applied in
combination with Stochastic, MACD, and other oscillators. Also, short
periods will work better: the period of 12-14 is optimum on the H1 time
frame.

## Key points

The volatility indicator is necessary for professional trading. It isn't
informative enough for beginner traders to appreciate it more than other
tools. Nevertheless, it's worth mentioning as some may need it for
developing their [trading strategies](https://www.fintechee.com/forex-trading-strategies/).

Would you like to download the ATR indicator free? Don't hustle. It's a
basic indicator on MT4 and MT5 platforms, and you can get used to it on
a demo account. If ATR isn't there for some reason, you can reinstall
the platform or copy the setup file from the MQL/Indicators folder from
the platform installed on another computer. You can also find ATR on
LiteForex's platform integrated into the Client Area. You don't need to
install it.

I hope this article has been useful for you. If you've got any questions
left, ask them in the comments section. Good luck in trading!

* * *

P.S. Did you like my article? Share it in social networks: it will be
the best “thank you" :)

Ask me questions and comment below. I’ll be glad to answer your
questions and give necessary explanations.

 **Useful links:**

  * I recommend trying to trade with a reliable broker [here][10]. The system allows you to trade by yourself or copy successful traders from all across the globe.
  * Use my promo-code BLOG for getting deposit bonus 50% on LiteForex platform. Just enter this code in the appropriate field while [depositing][11] your trading account.
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

   1. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/best-technical-indicators/parabolic-sar-indicator/
   2. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/best-technical-indicators/rsi-relative-strength-index/
   3. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/trading-strategies/scalping-forex/
   4. www.mql5.com/code/495
   5. my.liteforex.com/trading/chart?symbol=EURUSD&returnUrl=true
   6. my.liteforex.com/trading/chart?symbol=GBPUSD&returnUrl=true
   7. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/swing-trading-strategies/
   8. www.liteforex.com/trading/[calendar](https://www.fintechee.com/web-trader/)/
   9. my.liteforex.com/trading/chart?symbol=#TSLA&returnUrl=true
   10. my.liteforex.com/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=best-technical-indicators&slug2=atr-indicator&openPopup=%2Fregistration%2Fpopup&utm_source=blog&utm_medium=article&utm_campaign=bonus
   11. my.liteforex.com/deposit/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=best-technical-indicators&slug2=atr-indicator&promo_code=BLOG&utm_source=blog&utm_medium=article&utm_campaign=bonus