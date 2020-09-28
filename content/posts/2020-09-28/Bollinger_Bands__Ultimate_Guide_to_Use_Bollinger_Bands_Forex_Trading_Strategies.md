+++
categories = ["Cryptocurrency", "Blockchain", "SmartContract"]
date = "2020-09-28"
description = "Bollinger Bands: Ultimate Guide to Use Bollinger Bands Forex Trading Strategies"
tags = ["Cryptocurrency", "Blockchain", "SmartContract"]
title = "Bollinger Bands: Ultimate Guide to Use Bollinger Bands Forex Trading Strategies"
type = "post"
+++

{{<iframe id="large-banner" src="https://www.bounty.group/#slide=13.0" width="100%" height="600" scrolling="no" style="border: 0px solid rgb(216, 221, 230); border-radius: 3px;">}}

2020-09-28

2020-09-28

[Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) Indicator in Forex ExplainedMikhail Hypov

Dear friends!

In this article, we will take a detailed look at [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html), a
classic indicator that traders have been using for many years.

I will tell you what are [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html), what this tool does, how it
works, how are [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) calculated, [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) use [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html)
Forex strategies, and give you lots of other interesting information
with examples.

The article covers the following subjects:

Let's get started with bollinger bands [tutorial](https://www.fintechee.com/tutorial-for-forex-trading/)!

## What [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) are: Definition and History

Let's dive into the [history](https://www.fixpro.org/post/chargeless-historical-data-api-backtesting/) of the indicator. The very first mention of
a tool similar to [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) dates back to 1960.

The well-known trading analyst Wilfrid LeDoux used a trading channel
based on two moving averages in his trading system. The first band was
built based on the highs, and the second - on the lows. The signals in
the LeDoux’s trading system were both the expansion and contraction of
the channel itself and the price movement shapes within it.

 _John Bollinger_

Funnily enough, at first John Bollinger did not even think about
trading. He thought his future work would be on television. But while
working as an operator at one of the Hollywood companies, he encountered
some financial analysts and became interested in this occupation. Later,
the future trader’s mother asked her son to help organize her investment
portfolio.

Starting then, Bollinger finally decided to be part of the world of
stock trading. Combining his work as an operator at Financial News with
training from experienced financiers, he quickly mastered trading and
moved on to the position of financial analyst on the same channel. He
did not become a TV star, but he gained fame thanks to successful
trading ideas based on simple envelopes.

 _The envelope is one of the oldest technical analysis indicators. It
was built on the basis of a simple moving average and two bands located
at an equal distance from this center line._

Between 1984 and 1991, John worked on his own trading system based on
the LeDoux strategy and the envelope indicator. John's brainchild was
named after its creator – the [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html). The instrument is based
on a moving average with so-called bands plotted above and below.
However, unlike envelopes, the offset is not by a certain number of
points, but by a percentage.

The [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) are shown in the EURUSD chart.

The red lines are the upper and lower boundaries of the channels. They
are plotted based on the percentage offset from the blue moving average.
The main purpose of BB indicator is to determine a sharp deviation from
the average direction of the current trend.

> Next, we will analyze the techniques for using the Bollinger indicator
in detail. In order to study the material as efficiently as possible, I
advise you to go to the LiteForex [demo account][1] right now (you do
not need to register), open any trading instrument and apply the
Bollinger bands to the chart. Skim the Bollinger Band chart and see how
it reacts to price changes. If you encounter any difficulties, we will
do it together below.

The [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) indicator became widely known after the mention in
the book The New Commodity Trading Systems and Methods by Perry Kaufman
published in 1987.

The author of the indicator spoke about his brainchild and Bollinger
Bands strategies only in 2001, in the book Bollinger on [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html).
The article that you are now reading is written on the basis of
materials from these two books. I have extracted from them the most
relevant and useful information adapted for modern markets. Enjoy the
article!

## [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) Formula & Calculations

Today, in order to draw [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) in a chart, you just need to
select the required indicator from the list. Before, a trader had to
gather it piece by piece. The process is as follows: take the moving
average (hereinafter the MA) and build two bands: one above the center
line by some percentage distance and one below it. The main issue was
selecting the optimal interval for the MA and the deviation of these
bands (Bollinger levels) from it.

The author of the indicator looked for an effective way to select the
interval for a long time.

 _Marc Chaikin_

For some time he followed Marc Chaikin’s principles. Chaikin used a
21-day moving average for his bands offset up and down so that the
resulting zone contains about 85% of last year's data. However, he later
realized that the key to success in establishing the width of trading
bands is the degree of market volatility.

To determine the offset of the waves from the moving average, John used
the formula for the root-mean-square or standard deviation. This
variable is usually denoted as σ (sigma). To calculate the standard
deviation, the average closing price is calculated for a specified
period. The resulting value is subtracted from each point of this
closing price dataset. As a result, you will have a list of deviations
from the average price. Some of these values will have positive values,
others will be negative. The general principle is that the range of
deviations is in direct proportion to the degree of variability of the
series. Simply put, in a volatile market, Bollinger bands expand, and in
case of consolidation, they narrow.

At the next stage, we add up the list of data we have obtained. If we
add negative and positive values, we end up with 0. To get a non-zero
result, we need to get rid of negative values ​​by squaring them. As a
result, after adding up, we get the average absolute deviation. This
amount is divided by the period for which the data was collected, and
then we extract the root of the resulting value.

We get the following formula for calculating the square deviation:

σ – standard deviation;

x – closing price;

i – order number of the bar;

μ – moving average;

N – total number of points (period).

If we translate all of the above from the math language into trading
language, the obtained value of σ determines the area in which all
candles close with a probability of 68.2% (if the indicator is based on
closing levels) for the selected period. When the price breaks out of
this area, it is outside the root-mean-square distribution - it becomes
an anomaly in [terms](https://www.fintechee.com/terms/) of mathematical statistics. What does this mean for
the trader? We'll find out it out a bit later.

As for the choice of the optimal moving average period, the classic
version of the Bollinger indicator uses a 20-period MA. This range is
approximately equal to the number of trading days in a month. If for
some reason the period has to be shortened, in order to obtain the
optimal width of the band, you need to cut the number of standard
deviations. If the period is lengthened, the number of standard
deviations must be increased.

The need to adjust the calculation of the [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) width may
arise because of the peculiarities of the formula. After analyzing the
largest markets, the author has derived the most convenient ratios for
frequently used periods:

Periods| Multiplier  
---|---  
10| 1,9  
20| 2  
50| 2,1  
  
Let me explain why you need these ratios. In most markets, when using 20
periods and 2 standard deviations, you can get coverage of 88-89%. As
the period is shortened or lengthened, the coverage changes, which
affects the analysis efficiency. To maintain coverage at 88-89%,
[Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) should be plotted using a 1.9 ratio for a 10-bar period.
This means you cut the band width from 2.0 to 1.9. With a period of 50
bars, respectively, you need to increase the width from 2.0 to 2.1.

After selecting the multiplier and the period, you can calculate the
Bollinger bands themselves.

The formula for the top band is as follows:

 _UB_ _=_ _μ_ _\+ (_ _m_ _*_ _σ_ _),_

For the bottom band:

LB = μ - (m * σ),

UB – upper band;

LB – lower band;

μ - moving average value

σ – standard deviation value

m - factor

As an example, let's calculate the value of one point of the upper
Bollinger band. To simplify the calculations, let's take a period of 10
bars.

Candles entering the period are marked with a blue rectangle in the
chart.

First, let's identify the closing levels of these candles in points,
starting with the most recent. For convenience, I have rounded ten
thousandths to 0:

1,18700;

1,17700;

1,16500;

1,14200;

1,13000;

1,12400;

1,12100;

1,11700;

1,12500;

1,12900.

Therefore, the moving average is:

 = (1,18700 + 1,17700 + 1,16500 + 1,14200 + 1,13000 + 1,12400 + 1,12100
+ 1,11700 + 1,12500 + 1,12900)/10 = 1,14200

We can now move on to calculating the standard deviation:

Now we know the value of the standard deviation and can calculate the
point of the upper Bollinger band above the last bar (take the
multiplier 1.9 from the table above):

 1,14200 + 1,9 * 0,02404 = 1,18768.

Knowing the standard deviation, we can calculate other points and draw
the top line along them. The points of the lower line are calculated
similarly. As you can see, manual calculations are too cumbersome. To
simplify the Bollinger Band calculation, you can use an Excel
spreadsheet, which I will discuss below.

Now let's talk about the allowed parameters. From my own experience, I
can say that it makes no sense to use the Bollinger indicator with a
period of less than 10 and more than 50. If such a need arises, you need
to change the timeframe, for example, switch from a [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) to a four-hour
chart or vice versa. In the initial stages, I recommend limiting
yourself to a period of 20-30 bars. The author himself believes that his
indicator works best in this range.

In addition to the classic setting of [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html), combined [options](https://www.fixpro.org/post/options-liquidity/)
are possible as well. For example, a chart might contain two band
indicators plotted using the same calculation period but with different
ratios. In his book, the analyst gives an example of a chart with two
bands in 20 periods that differ in width by 1 and 2 standard deviations.

You can see this tool in the picture above. Visually, these two
indicators coincide at the moving average line but have different
widths. A narrower channel is built with a factor of 1.0, and a wider
one – with a factor of 2.0.

The second popular option for setting up the indicator is to plot BB of
two different types. For example, one channel can be formed based on a
moving average with a period of 20 bars and a width of 2 standard
deviations. The second one has a period of 50 bars and a ratio of 2.1.
If you think you already know [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) use [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html), you are wrong.
All the fun is yet to come. Get a cup of tea and let's move on.

### [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) Excel Sheet

[Here you can find the [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) Excel Sheet][2]. It is designed
to accurately calculate [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) at a specific point in time.
This tool can also be used to experiment with inputs to calculate the MA
or the multiplier.

In order to use the table, you need to make a copy of it or download the
[Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) calculator directly to your computer. The screenshot
above shows the path: File / Make a copy or Download.

The table is very simple. In column A, you fill in the purple cells. The
formulas work for 50 cells, but there is no need to enter numbers in
each one. Input values ​​can be any numbers. For example:

  * closing levels
  * opening levels
  * bar highs
  * bar lows
  * weighted averages of each bar
  * or any other numbers for your experiments

The number of values ​​corresponds to the calculated period. If 10 cells
are filled in, the calculation will correspond to a moving average with
a period of 10.

In column B, indicate the multiplier in the purple cell. The default
ratio is 2, but you can enter any other number instead.

Columns C, D and E contain the final result and a caption for the values
​:

  * standard deviation - σ
  * upper band - UB
  * moving average - μ
  * lower band - LB

 **Important!** All calculations are done automatically. You do not need
to enter data manually in the blue cells in column E.

## How [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) Indicator Works

We already know that the [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) indicator consists of three
lines: a moving average, upper and lower bands. The latter are formed
with an offset ranging from 1.9 to 2.1 standard deviations.

Setting up [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) is pretty straightforward even for [beginners](https://www.playgroundfx.com/blog/forex-for-beginners/).
There are only two relevant columns in the Parameters tab: "Length" or
the period for which calculations will be made, and the "Multiplier"
factor. It only makes sense to change other settings within the classic
[Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) if you want to experiment. For example, changing the
source from the closing price to the opening price changes the
traditional approach to building the indicator, but it may show an
unexpectedly interesting result on certain trading instruments.

In the second "Style" tab, you can set the color of the Bollinger bands,
the moving average, and the chart area between them.

John suggests using two indicators in the trading process:

  * %b allows you to determine exactly where the price is in relation to the [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html). This tool will be useful when developing a trading system that uses the relationship between price behavior and the behavior of the bands.
  * BandWidth analyzes the current offset width. This metric is very useful for finding the start and end points of a trend, and BandWidth is an integral part of the squeeze technique. I will talk about it in detail a bit later.

First, let's take a closer look at %b. This tool is calculated by the
formula:

%b = (Last price - LB) / (UB - LB).

  * UB - upper band
  * LB - lower band

If you look closely at this formula, you will understand that if the
last price is located on the upper band, the calculation result will be
1. If it is located on the moving average, the %b value will be 0.5. And
if the price stops at the lower band, the result of the above formula
will be 0.

In this case, negative %b is possible if the price breaks out of the
lower Bollinger bands. This signal can be interpreted both as a sign
that the asset is oversold and as a sign of a trend reversal.

A value greater than 1 is possible if the price goes above the upper
band. In this case, it will be a signal either about an overbought
asset, or about a change from a bearish to a bullish trend.

In order to read these signals correctly, you need to use additional
indicators as filters.

The Alligator indicator is often used for this purpose.

In the chart above, we can see that the price has gone above the upper
band, i.e. %b must be greater than 1 (highlighted in the graph with a
green oval). At the same time, Alligator does not show any crossings
between its lines (in a blue circle), which indicates an early sign of
an overbought asset and a possible trend change.

In the next chart, the green oval marks an area where several candles in
a row close below the lower band, which means %b will be less than 0.
This can be both an oversold signal and a trend reversal signal. A
little later, the Alligator lines cross, which confirms the trend change
and lets us open a short position. We see that Alligator helps us
correctly interpret the Bollinger signal.

 %b can also be used to identify shapes. We will talk about this later.

Now let's move on to BandWidth, which analyzes – you guessed it – the
current band width. It is determined by calculating the difference
between the upper and lower bands and dividing the result by the moving
average value. The formula looks like this:

BandWidth = (UB – LB)/μ

  * UB - upper band
  * LB - lower band
  * μ - moving average

This signal is useful for detecting squeeze. In other words, it
describes a situation when market volatility has decreased to an
abnormally low level.

> This situation can be described as the calm before the storm. __

Bollinger noticed that most trends are born when BandWidth is at its
lowest. Like the calm before bad weather, market volatility is very low.
The emergence of a sharp expansion of Bollinger bands and a strong price
movement in such a situation indicates the possible formation of a new
trend.

In the chart, the green oval marks the moment when the [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html)
narrow, i.e. the market volatility decreases to a local minimum. As you
can see, a sharp upside breakout occurs after this, which is the start
of a bullish trend.

BandWidth will also be very useful in determining the end points of
strong trends. Heavy movements provoke a significant increase in
volatility. Because of this, the level of dispersion increases and the
[Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) expand. In the case of a bullish trend, after the
channel narrowing, we will see a strong fall of the lower Bollinger band
downwards against the main trend. This phenomenon is an early signal of
a bullish trend reversal.

The EURUSD chart shows [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) at the time of the trend
development. The green rectangle marks the area when the lower line
begins to move down during the formation of an upward trend. After that,
in the area marked with a blue rectangle, the lower band reverses and
begins to move up. A signal about the end of the trend appears. And
indeed, after a while there is a transition from a bullish trend to a
bearish one.

## [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) Signals

Earlier, we have already discussed the main signals of the Bollinger
Bands. Their weak point is the need to filter and identify entry and
exit points. The simplest solution to the first problem is a Bollinger
filter.

To solve the second problem - identifying the entry and exit points - in
most cases finding shapes is the solution. A shape is a pattern formed
by a market price movement or a sequence of such movements. They are
fairly easy to recognize in the chart. At the same time, for a better
understanding, [beginners](https://www.playgroundfx.com/blog/forex-for-beginners/) are recommended to use [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html). They
smooth out minor market fluctuations, making it possible to focus only
on significant price reversals. Often, shapes precede a reversal or are
themselves part of a trend reversal. I will tell you about the two most
common shapes - W and M.

Before we move on to examining the features of the shapes, have a look
at their types.

####  _W-bottoms_

####  _M-tops_



The image above will help you understand what types of patterns we are
talking about.

The meaning of each of the presented shapes is unique. You can read more
about this in the book MW Waves by Arthur A. Merrill. Here we will just
take a quick look at these patterns and discuss [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) work with them.

All shapes can be grouped by to the signal the trader receives. Let's
take a look [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) read bollinger bands signals:

  * М15, М16, W14, W16 signal the formation of an uptrend.
  *  M1, MZ, W1, W2 indicate the formation of a downtrend.
  * W6, W7, W9, W11, W13, W15, M2, M4, M6, M8, M10, M11 are reversal formations. These patterns indicate a trend reversal.
  * М13, W4 - in classical technical analysis these figures are called triangles. The direction of movement is determined by the side of the exit from the figure.
  * M5, W12 - in classic technical analysis, these are expanding triangles - the trend is determined after the breakout.
  * W6, W7, W9, W11, W13, W15 are most often part of the head and shoulders reversal formation.
  * M2, M4, M6, M8, M10, M11 are often components of the inverted head and shoulders pattern
  * For the rest of the figures - M7, M9, M12, M14, W1, W3, W5, W8, W10 - signals are generated based on the general rules described below for W and M shapes.

### W-Bottoms (Double Downs)

W-bottom is the most common pattern of transition to the bullish market.
It is rarely seen in its pure form and often has a variety of deviations
from the ideal shape.

Bollinger developed a system for the psychological assessment of market
sentiment based on the following pattern features:

  * Longer right side suggests that there is a sentiment of disappointment in the market. Many [investor](https://www.fintechee.com/tutorial-for-forex-trading/investor-mode/)s expect another retest of the lows, abandoning their positions and are extremely disappointed after the price soars up.
  * Equality of the lows on the left and right sides indicates a calm market. Investors make purchases after a repeat testing without much stress and soon get the expected profit.
  * If the low on the right side is lower than the low on the left, this situation is accompanied by fear and discomfort on the part of the masses of ordinary traders. Many of them went long at the previous low and ended up being kicked out of the market. Few of them will want to buy again, and the inflow of new money is limited to the formation of a new low point. The technical analyst Richard Wyckoff once called this phenomenon a spring, and this term is still used in the trading circles to this day.

As for the interaction of the W-bottom with the BB, in most cases the
left side of the pattern will touch the lower line or cross it. The
growth following the local low will again return the candles to the
inner zone of the bands. In this case, the crossing of the moving
average of the indicator should occur.

The next move will be a second touch inside the lower Bollinger Band. It
is important to pay attention here that the low in the considered
strategy is determined by the lower band. If the first point crossed the
band, and the second is formed within the channel, then the second low
will be considered higher even if it is located lower in absolute [terms](https://www.fintechee.com/terms/).

The retest price must be greater than or equal to the price of the first
low. This is one of the most important requirements. To check whether it
is met, you can use the previously discussed %b indicator, which allows
you to accurately measure the position of candles relative to Bollinger
bands.

Another feature of W-bottoms is the presence of some smaller formations
in their structure. A closer look at smaller timeframes reveals reversal
signals. They form the beginning or end of the compound segments of a
large figure.

A W-bottom gives a clear signal of base formation. Therefore, these
formations are often used to predict trend reversals and open positions.

The chart depicts a growing W-bottom. This is a formation in which
retesting occurs at a higher level. This is true only when analyzing the
absolute location of the lows, i.e. the location relative to the
coordinates of the chart. As for the [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html), both low points
cross the lower line at approximately the same distance. We can talk
about the equality of the lows of the left and right sides and
equilibrium in the market.

After finding the W-bottom, you need to answer the question: "When and
what positions should I open?" Experts recommend buying “strong” - wait
for the moment when a bar with a volume and range above average is
formed. This will be the signal to open a long position.

The stop order should be set below the last low point (below the right
side of the formation). Later it should be moved up. You can do this by
eye or according to your own rules. For [beginners](https://www.playgroundfx.com/blog/forex-for-beginners/), I recommend starting
with stop losses set off from local lows.

### M-Tops

While the most common base shape is a W-bottom, the tops can be double
or triple in an M-top.

The most common case of a triple top is the head and shoulders pattern,
which is well known in technical analysis. It shows rapid growth and
small rollbacks. This rollback forms the left shoulder. It is followed
by another period of growth, which forms a new high, which ends with an
even larger rollback. Quite often, this rollback completes near the
previous local low. It forms the so-called head.

Following the head, the right shoulder is formed. It represents a failed
growth with an amplitude less than the previous one (ideally ends around
the peak of the left shoulder) and a subsequent fall in price setting a
new low. The right shoulder may be followed by another minor growth,
bringing prices back to the vicinity of the lows of the left and right
shoulder. Traders often refer to these lows as the neckline. It is
usually followed by a complete fall.

The chart depicts a head and shoulders formation. For clarity, I marked
its outlines with green lines, and its components with numbers:

  1. left shoulder;
  2. head;
  3. right shoulder;
  4. backward movement before final decline.

This example clearly shows that in practice the head and shoulders are
rarely formed as a perfect structure. Deviation of one or more
parameters is considered acceptable.

When analyzing a figure, I also recommend paying attention to volume. On
the left side of the figure, especially in the head area, it is
characterized by high values. At this point, [news](https://www.letsplayfx.com/blog/forex-news-website/) is published preceded
by rumors and expectations. After passing the peak of the head, activity
decreases. A small surge of optimism can be observed on the right
shoulder or the last jump up.

In the chart, we see that at the moment of the formation of the right
shoulder, traders are confused. Most of them argue that a reversal is
inevitable. Therefore, the increase in volume occurs at the stage of the
lowering of the right shoulder. In the first part of the last spike, the
high volume can be explained by the struggle between bulls still hoping
for growth and bears confident of the fall. After passing the peak,
massive sales continue at the expense of traders, who at the last moment
realized that further growth is impossible.

Analysis of the formation using Bollinger signals is even more
interesting. In the ideal version, the left shoulder goes beyond the
upper line. The right one misses it by a little. The neckline in the
right shoulder often stops at the moving average, and the first decline
is in the vicinity of the lower Bollinger band.

In our graph above, only one condition is met strictly. Upon reaching
its peak, the first shoulder is crossed by the Bollinger Wave indicator
(blue arrow). The neckline is bounded by the lower band rather than the
moving average. You can also say that the first decline stops at the
lower line (red arrow). However, upon closer inspection, a slight
overlap is noticeable. This once again confirms the fact that in real
trading you will rarely come across perfect shapes.

The first part of the head and shoulders formation is ideally an M-top
consisting of a left shoulder and a head. Most often it is expressed in
the form of an M15 or M16 shape. The next part is also an M and it
includes the head and right shoulder (possible shapes are M3, M4, M7 and
M8). The last phase (right shoulder and reverse growth before the final
decline) can be formed in the form of an M1 or M3 shape.

M-tops are useful for identifying the tops of sustainable trends. In the
process of their formation, there is a reversal of the price movement,
which opens up opportunities for effective entry into the market. Even
more useful is the analysis of the interaction of the head and shoulders
with the BB. It allows you to recognize the pattern before it is fully
formed, which means opening a position at one of the high points and
increasing the final profit from the trade.

At the same time, starting from the right dip after the head, the
structure has a downward slope. This means it can be analyzed using W
shapes. Reverse growth often forms as W1 or W2 shapes.

As you analyze, you can get deep into the details by identifying each
component of the M and W at the following levels. There should be five
of them in total. But with traditional analysis, there is no need to
analyze all the constituent figures. It is enough to find a few of them.
In addition, the formation is easy to read visually, as well as in [terms](https://www.fintechee.com/terms/)
of its interaction with [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) and the impact on trading
volumes.

### Three pushes to high

In addition to the classic head and shoulders, you will often see a
variation of this pattern, which Bollinger calls the three pushes to a
high. It usually completes larger shapes. When analyzing this structure
using [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html), you can see the following patterns:

  * The first push goes beyond the upper band.
  * The second push creates a new high and touches the upper level.
  * The third push may or may not form a new high. If a new extreme point is created, it will not be much higher than the previous one. In this case, the third push does not touch the upper Bollinger band.

The highest volumes ​​are observed at the first stage of the development
of the three pushes to a high. Then the activity gradually decreases and
in the final stage reaches a low. Let's take a look at an example.

In the EURUSD chart, I marked the direction of price movement with green
lines. The peaks of the three pushes to a high are labeled with numbers.
We will use them as serial numbers. The first push naturally crosses the
upper Bollinger band. The second creates a new top. However, it is only
slightly higher than the previous one. Because of this and as a result
of the previous rapid upward movement, the second pattern is not
realized.

The third spike is also not much stronger than the previous ones. Its
high touches the Bollinger band, but the end point of the candlestick is
below it. A gradual decrease in volumes from the beginning of the
formation to its end confirms an early reversal. I marked this
phenomenon in the chart with a blue line.

## [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) Strategies

In this section, I have collected the most popular [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html)
strategies. We will look at various methods within the day, in the
lowest timeframes, learn [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) squeeze the bands and use their signals
in conjunction with other indicators. I will separately talk about the
[Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) strategies, which involve trend following in the
presence of a breakout of important levels and additional reversal
signals.

### Daily Trading with DBBs (Double [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html))

 _Kathy Lien_

This method appeared as a result of the efforts of the exchange analyst
Kathy Lien. In her book, The Little Book of Currency Trading. How to
Make Big Profits in the World of Forex, she described an unusual
technique involving the use of two [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) of the same type in
the same chart.

To understand what this is about, let's add them to the chart. The first
indicator will be with a period of 20 candles and two standard
deviations.

For the second indicator, we use slightly different Bollinger Band
settings: a 20-bar period and one standard deviation.

I also recommend assigning its own color scheme for each indicator, so
that it’s easier to compare their readings in the chart.

The final Bollinger indicator consists of five lines:

  * top (red) line with two standard deviations;
  * top (green) line with one deviation;
  * moving average (blue);
  * bottom (green) line with one deviation;
  * bottom (red) line with two deviations.

All bands, except the moving average, form trading zones that we will
use to open trades:

  * buy zone - between the upper red Bollinger band and the upper green line;
  * neutral zone - between the upper green and lower green line;
  * sell area is between the lower green and lower red line.

The price being in the buy zone indicates the strength of the current
trend. This means that there is a high probability that the price will
go up for some time. For trend trading, Ketty recommends opening long
positions when the close of the candlestick hits the upper quarter of
the double Bollinger indicator. In this case, the two bars preceding it
should close in the neutral half. Keep a long position as long as the
candles close within it.

On the other hand, if the price is in the sell zone, it indicates the
strength of the bearish trend. By analogy, here you should open short
positions (provided the closing points of the two previous bars are in
the neutral half) and keep them until the candle closes return to the
neutral zone.

For an uptrend, stop orders should be set at the lowest price of the
first bar that broke the upper line of the neutral zone. For a
downtrend, the stop order position is determined by the high of the
first bar that breaks the lower line of the neutral zone. The initial
target is set at a distance of two stop losses. When the distance of one
stop loss is passed, Kathy recommends moving it to breakeven. Then it
should be gradually moved along with the potential target following the
price and closed manually when the last candlestick closes in the
neutral zone.

After the price has entered the neutral zone, we can consider two
possible scenarios:

  1. The price will move to one of the trading quarters - usually this happens when a trend reverses.
  2. The price will consolidate in the neutral zone - there will be a “calm before the storm”. You can prepare for a strong movement in either direction.

The price being in the neutral zone demonstrates uncertainty. You should
refrain from entering the market and wait for the price to close in one
of the quarters. Alternatively, you can go to a lower timeframe or trade
short-term trades within the channel. In the latter case, the [Grid
trading strategy][3], which I talked about in one of the previous
materials, may come in handy.

Now let's look at the classic strategy Double [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) through an
example.

In the chart, the bar marked with a blue oval closes in the upper
quarter. A buy signal appears. Open a long position at the close of the
candlestick at 1.17873 points (blue line in the chart). Set the stop
loss at the low of the candle that has broken through the first upper
line. It is marked with a red line in the chart. I’ve marked the target
with a green line, it’s located at two stop loss lengths.

In the future, you can stop at the target level. But it is much better
when the price grows to move the stop loss to the breakeven level, leave
it at this position and wait for the signal to close the order or move
it dynamically with the target.

As long as the price remains in the upper quarter, we leave the position
open. In the chart above, the borders of this period are between the
blue and orange ovals. Then a downtrend bar forms - see inside the
orange oval. It closes in the neutral zone, which is a signal to take
profit. The closing price is marked with a black line and is 1.18755
points. The resulting profit will be equal to 1.18755 - 1.17873 =
0.00882 points excluding spread.

If we had stuck with the option of moving the stop loss and target, the
close would have occurred automatically at the 1.18877 level marked with
a red line. In this case, net profit excluding spread would be 0.00886
points.

It is recommended to use the strategy of double Bollinger bands on trend
instruments. You can use almost any timeframe - from M15 to D1.

Here's what experienced traders think of the strategy:

### [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) Scalping

This strategy works on any exchange instruments. The recommended chart
timeframe is M1 to M15.

We will receive the main signals from [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html). We will use them
to identify opportunities for opening and closing positions.

The picture above shows [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) set up the [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html). The
parameters are standard - the period of the moving average of 20 bars
and two standard deviations.

The RSI indicator is used as a signal filter.

I recommend using the 8 bar period for it. Go to the indicator settings,
open the "Parameters" tab and set 8 under the "Length".

We leave the upper and lower limits as is - 30 and 70.

To open a long position, the following conditions must be met:

  1. the price candlestick touches or breaks the lower Bollinger band;
  2. RSI level is below 30;
  3. one of the following candles will close within the channel.

The stop loss is set just below the low level of the breakout candle.
The gap should not be less than 10 points. The optimal ratio of take
profit to stop loss when using this strategy is 0.6. Therefore, the
minimum target should be at least 6 pips above the buy price.

To open a short position, the following conditions must be met:

  1. the candle touches or breaks the upper band;
  2. RSI level is above 70;
  3. enter when one of the following candles closes within the channel.

Set stop losses and take profits similarly as with long positions.

Let's consider the application of the strategy using an example.

In the five-minute [EURUSD][1] chart, a blue circle marks the area where
one of the candles touches the lower band. At the same time, the RSI is
below 30%, confirming a buy signal. We open a long position immediately
after the close of the next upward candlestick within the channel. The
opening price is 1.18805 points (green line). The stop loss is set below
the low of the touch candle. Since there are several such bars in a row,
we take the smallest low and set the stop loss just below it. Set the
take profit slightly above the buy price so that it is about 60% of the
stop loss.

The take profit is crossed on the next candlestick after the opening.
Thus, the long position is automatically closed at the price of 1.18868
points. The profit from the trade is 1.18868 - 1.18805 = 0.00063 points.

### Bollinger Band and Stochastic Strategy

Bollinger trading with the Stochastic indicator is similar to the
previous strategy using the RSI. We will use the bands to detect
potential entry points, and the oscillator readings to filter signals.
Unlike the previous one, this trading method is more like a channel
strategy, with the only difference that the Bollinger channel will be
used for trading. Therefore, it is very important to pay special
attention to setting the indicator bands. As an example, we will use
standard parameters - a 20-bar moving average and a multiplier with a
factor of 2. Your input data may be different. Depending on the trading
instrument, timeframe and market peculiarities, select the period and
multiplier in such a way that the moving average of the indicator shows
the correct trend direction. At the same time, the price should not be
outside the channel for longer than several candles.

To add a Stochastic, click on the "Indicators" button in the upper part
of the online terminal window. Select "[Stochastic Oscillator](https://www.algotradesoft.org/custom-indicator/stochastic-oscillator.html)" from the
dropdown list.

We will use the following default parameters for the Stochastic: periods
5 for line K and 3 for line D, length 3. You can change the colors of
the K and D lines, as well as the upper and lower limits in the "Style"
tab. By default, K is orange and D is blue.

Conditions for opening a buy order:

  * the candlestick crosses or at least touches the lower band;
  * the oscillator shows oversold (less than 20%);
  * line K crosses D from bottom to top;
  * buy after the close of the signal candle.

Conditions for opening a sell order:

  * the candlestick crosses or at least touches the upper Bollinger band;
  * the oscillator shows overbought (more than 80%);
  * line K crosses D from top to bottom;
  * Sell when the signal candle closes.

Stop loss is set with an offset of at least 10–20 points from the low of
the breakout candle in the case of a long position and the high in the
case of a sell position. Set take profit on the opposite Bollinger band.
When buying, take profit will be located on the upper band, and when
selling - on the lower one.

Let's consider the application of the strategy using an example.

In the area of ​​the chart marked with a blue oval, the candlestick
crosses the lower band. Here line K crosses D, and the Stochastic itself
shows oversold below the 20% level.

At the opening of the next candle, we enter the market with a buy
position at 1.08752 points (green line). Set the stop order a little
lower (red line).

Place the take profit on the upper band. It is marked with a blue line
in the chart. After a while, one of the candles reaches it and the order
is automatically closed at a price of 1.09100 points. Thus, the profit
from the trade is 1.09100 - 1.08752 = 0.00348 points.

If you are going to use this strategy on small timeframes, I recommend
to monitor more stable trends additionally. This way you will avoid
entering the market against powerful trends.

### Using EMA and WMA instead of [Simple Moving Average](https://www.algotradesoft.org/custom-indicator/simple-moving-average.html)

Traders often ask: "Can I use a weighted average or exponential instead
of a moving average?" In theory, any average is suitable for plotting
BB. When trying to answer this question, John Bollinger himself did a
comparative analysis of various averages and came to the conclusion that
the classical moving average is the simplest and most accurate tool for
constructing reference points.

Let's compare the indications of moving averages using an example.

In the chart, the blue channel represents standard bands based on a
20-period moving average. The orange channel, in turn, was built on the
basis of the 20-period EMA. As you can see, in times of high volatility,
these methods give different results.

And in this chart, the red channel marks the bands plotted by the WMA,
and the blue one - by the moving average. As you can see, in this case
the differences are noticeable, especially at the extreme points.

Both examples show that using WMA and EMA instead of a moving average
can give very unexpected results. Therefore, these averages are not
recommended for Bollinger trading.

### Bollinger Band Squeeze

[Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) are driven by volatility. Because of it, the stripes
expand and contract.

To determine the degree of compression, John created the BandWidth
indicator. It determines volatility as a function of the average and
works great on any time frame. BandWidth is calculated by the formula:

BandWidth = (UB – LB) / μ

UB - upper Bollinger line;

LB - lower Bollinger line;

μ - moving average value

You can download [Bollinger Bandwidth for MetaTrader 4 here][4].

Let's look at the process of installing and setting up the indicator:

Download the archive from the link above and unpack it. We need the
dinapoli-BandsBandwidth.mq4 file.

Open the File tab in the MetaTrader4 top menu. Next, select the item
"Open Data Folder".

File explorer will open with the target folder. In it, select the "MQL4"
folder.

Then select the "Indicators" folder. Copy the unarchived
BandsBandwidth.mq4 file to this directory. Restart the terminal. Open
the chart to which you want to add the indicator. In our case, it will
be [EURUSD][1].

At the top of the terminal, open the "Insert" tab, then go to the
"Indicators" item. Click on the "Custom" item and select the name of the
newly installed indicator. In our case, it’s BandWidth.

After that, the indicator window will appear. By clicking on the OK
button, you launch the indicator with default settings.

You can also change the indicator settings. Best bollinger band setting
is:

  * Common – these are the technical settings for the indicator. They are best left as default.
  * Inputs - here you can set the period and the number of standard deviations. For most timeframes, it is best to use the default settings.
  * Colors - here you can set up the color, thickness and look of the indicator lines.
  * Levels – this item allows you to set levels. For example, the level, upon crossing which you need to buy, etc.

Let's look at the indicator's application using an example.

The Bollinger indicator is shown in the chart with red lines. At the
bottom, the blue line shows BandWidth. The principle is simple: the
higher the line, the greater the expansion; the lower the line the
stronger the narrowing. With blue arrows, I marked the narrowing areas,
which correspond to the minimum values in the BandWidth chart.

The [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) Squeeze strategy shows good results during narrowing
and expansion. It is a channel trading method. The idea is to open
positions on a rebound from one of the levels. The strategy works well
on any exchange instruments with a timeframe of M30 and higher.

We need:

  1. [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) indicator with the following settings: 20 periods and two standard deviations.
  2. BandWidth indicator.

To add the [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) indicator to the chart, open the "Insert" tab
in the main menu, then "Indicators", "Trend" and in the submenu that
opens, select [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html).

This will open the settings window. In it, we will set the period equal
to 20 bars and two standard deviations.

As John Bollinger argued, periods of low market activity are cyclically
replaced by periods of high volatility. This statement is the essence of
the Bollinger Squeeze strategy.

The signal for an early entry into the market is the narrowing of the
BB. We will identify it using BandWidth, which demonstrates its lowest
values ​​during this period.

In the EURUSD chart, the blue arrows indicate a narrowing. Please note
that the BandWidth is at its lowest during this period.

The next goal is to identify when the narrowing ends. The beginning of
the movement is evidenced by the breakout of one of the Bollinger bands.
For a bearish trend, this will be the crossing of the lower level, and
for a bullish trend, it will be the crossing of the upper level.

In the chart, I have marked the moment of the breakout of the lower
level with a red arrow. This signal indicates the beginning of a bearish
trend.

You can set the stop order, as in previous trading methods, at the high
or low point of the breakout candle. The initial take profit must be at
least twice the stop loss length. Since we are talking about trend
trading, it makes sense to use the trailing stop and wait for the signal
of the trend end. This signal can be one of the patterns described in
the analyst's book or another narrowing of the channel.

The next narrowing of the channel is marked by green arrows in the
chart. It signals a reversal, which means it's time to close the short
position.

 **Important!** During the squeeze, one unusual phenomenon often happens
that confuses most [beginners](https://www.playgroundfx.com/blog/forex-for-beginners/). This is a false breakout that occurs in
anticipation of the end of the squeeze. At this moment, the chart makes
an intense but short-term movement. After that, it also reverses sharply
and starts to move in the direction of the emerging trend. This
phenomenon can also be used as a signal for the end of market
consolidation.

In order not to be fooled by a false breakout, don’t jump to
conclusions. Wait a bit until the movement develops so that there is no
doubt that a new trend is forming. Experienced traders often derive
additional profits from false breakouts. To do this, they open a
position at the very beginning of the movement. After that, a trailing
stop is set in such a way that it falls into the breakeven zone as soon
as possible. Further moving of the stop order in the direction of the
candlestick formation will give profit when triggered.

### Bollinger Bounce

This strategy is suitable for trading on timeframes from M30 to H4. It
is based on two popular tools: the [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) indicator and the
RSI. The essence of the trading system boils down to finding a price
bounce, which is formed during the development of a trend.

First, let's add [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) and RSI to the EURUSD chart of
[LiteForex online terminal][5]. To do this, click on the "Indicators"
button at the top of the chart. Then, in the menu that opens, click on
the "[Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) (BB)" and "RSI" links.

Now let's move on to setting up the tools.

For [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html), we will use standard parameters: 20 bar period and
2 standard deviations.

For RSI, we will also leave the default settings:

  * length - 14;
  * limits - 30 and 70.

Let's modify the RSI a little by adding a horizontal line at the 50
level.

The Bollinger Bounce strategy involves trading on developing trends. The
direction of price movement does not matter. In an uptrend, we will look
for the moment when the price rolls back down, touches or almost touches
the lower band. In a downtrend, on the contrary, we need a moment when
several candles go up and stop at the border of the upper band.

Next comes the RSI. We will use it to understand how the instrument is
strengthening or weakening in its value. In an upward trend and downward
rollback, the signal is confirmed when the indicator line is within
30-50. Ideally, it goes up. Accordingly, in a downtrend and an upward
rollback, the RSI should be between 50 and 70 and going down.

If the main trend is upward, we enter the market at the close of the
subsequent bullish (white) candlestick. If the trend is downward, enter
after the close of the bearish bar. If the movement is too strong and
you are afraid to miss a significant part of the movement, you can move
to the next smaller timeframe and wait for the bar to close on it.

Place stop loss a little behind the touch point of the Bollinger Band
indicator. It is recommended to place take profit at the level of the
opposite band.

Let's see how the strategy works though an example.

The [EURUSD][1] chart shows an uptrend. In the place of the supposed
bounce, one of the bars touches the lower band (green oval area). In
this area, the RSI moves in the direction of the trend and is located in
the optimal range from 30 to 50 percent. Therefore, we can talk about a
signal for the upcoming bounce.

Following the touch candle, a bullish bar is formed, signaling the start
of a bounce. At its final point, open a long position at 1.09042 points
(green horizontal line). Set the stop loss (red line) slightly behind.
Take profit is placed at the level of the upper band (blue line).

The position closes by take profit (blue line) upon reaching the level
of 1.10031 points. The profit from the trade was 1.10031 - 1.09042 =
0.00989 points.

### Bollinger Band Breakout Strategy

Many experts agree that strategies based on breakout signals are the
most effective. The [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) indicator is among the best
indicators for tracking and predicting future impulses. This is noted by
D. Rooney, technical analyst and trader with ten years of experience,
winner of an award in writing trading systems.

One such trading system is the Bollinger Band breakout strategy. It is
equally effective on both 5-minute and weekly timeframes. This strategy
is the complete opposite of the [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) bounce strategy. The
founder of breakout trading is Bruce Babcock, the author of the
intuitive trading theory. John Bollinger liked his approach to trading
volatility breakouts and decided to adapt it to his indicator.

The key to success is the correct choice of timing to enter the market,
namely, the moments of lowest volatility. To determine the narrowing, we
will use the already familiar BandWidth indicator. I’ve talked in detail
about this tool, its installation and setting up in the section on
narrowing.

If the BandWidth narrows, the trader should be prepared to see a
breakout of one of the [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html). We enter the market as soon as
one of the candles closes above or below the line. The direction of the
position coincides with the direction of the breakout. This means, if
the upper band is crossed, we open a long position, and if the lower one
is crossed - a short position.

Stop orders are placed just below the breakout candle. Then, at regular
intervals, the stop loss is pulled up by the price movement distance.
Such intervals will be different for each of the timeframes. In [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/)
charts, the optimal nudge time would be the opening of trades at the
beginning of the day. You can also use the trailing stop, which changes
the stop loss value at the close of each candle.

Breakout Strategy is almost identical to Bollinger Squeeze. But there is
also a significant difference. It’s in an alternative parabolic way of
exiting the market. In this case, the stop loss is set in the breakeven
zone during the growth process. We exit the market when the opposite
band is touched: for the bullish movement - the lower band, and for the
bearish - the upper band. Let’s look at this option through an example.

For the breakout strategy, I took the same chart that was used to
demonstrate squeeze trading. The blue arrows indicate the narrowing
area, the red one shows the candlestick crossing the lower level. When
it closes, we enter a short position. With the blue line, I marked the
entry price of 1.00002 points. And the red line is the initial stop
loss.

During the development of a bearish trend, we move the stop loss to the
opening price (in reality you need to move it a little lower to
compensate for the spread). The new stop loss is marked with a red line.
I also left the original one intact for clarity. It is now marked with a
semi-transparent red line.

The position is closed when the candlestick touches the upper Bollinger
band. This event is marked with a red cross in the chart. The closing
price is marked with a green line and is 1.09410. This trade should have
brought us a profit of 1.09410 - 1.00002 = 0.09408 points.

### Trend Trading Indicator Strategy

The essence of this approach boils down to predicting the birth of
trends using price strength analysis. The analyst considers the ability
of the chart to approach the upper band during an upward movement and
the lower one during a downward movement as a sign of strength.
Additionally, the strength is confirmed by the MFI readings.

To measure how close the price is to one of the bands, we will use the
[Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) %b indicator. I talked about it in detail in the section
"How the Bollinger Wave Indicator Works".

Let's look at the process of installing and setting up the indicator:

1\. Download the [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) %b indicator from the link
[www.mql5.com/ru/code/7165][6]

2\. Open the "File" tab in the top menu of MetaTrader4, select the "Open
Data Folder" item.

3. File explorer will open with the target folder. In it, select the
"MQL4" folder.

4. Select the "Indicators" folder. Copy the unarchived
Bollinger_Bands_3b.mq4 file to this directory and restart the terminal.
Open the chart to which you want to add the indicator. In our case, it
will be [EURUSD][1].

5. At the top of the terminal, open the "Insert" tab, then go to the
"Indicators" item. Next, click on the "Custom" item and select the name
of the newly installed indicator - Bollinger_Bands_3b.

6\. The indicator window will appear. By clicking on the OK button, you
will launch the indicator with default settings.

The editable parameters of the tool are in the following tabs:

  * Common - technical settings for the indicator. They are best left as default.
  * Inputs - here you can set the period and the number of standard deviations. For most timeframes, it is best to use the default settings.
  * Colors - here you can set up the color, thickness and look of the indicator line. By default, it is bright yellow, so it is better to immediately change it to a more vivid color.
  * Levels – this item allows you to set levels. For example, a level, at the crossing of which you need to buy, etc. In the case of our strategy, it makes sense to add levels 0.8 and 0.2.
  * Visualization - here you can select the timeframes on which the indicator will be displayed.

You can download MFI from the link below:

<www.mql5.com/ru/code/8025>

The installation principle for this instrument is the same as for
[Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) %b. Most of the settings are the same as well.

The only difference is in the "Inputs" tab, where you can only change
the period. For trend trading with MFI, it is recommended to set a
period that is half the period of [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) %b, which for us is 10
bars.

The tool itself is designed to measure the intensity with which funds
are invested in a security or withdrawn from it. Its full name reads as
the Money Flow Index. Within the described trading system, we will only
be interested in levels above 80 and below 20 signaling a potential
market top and bottom.

We also need classic [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) with standard settings: 20 period
and 2 standard deviations.

Conditions for opening a long position:

  * [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) %b is in the range from 0.8 to 1.
  * The MFI chart is above 80.

We enter after the completion of the growing bar. Stop orders are set at
the low price with a two candlestick offset, counting from the bar with
an open position.

Conditions for opening a short position:

  * [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) %b is in the range from 0 to 0.2.
  * The MFI chart is below 20.

We enter after the completion of the descending bar. Stop orders are set
at the high of the candlestick with an offset of two bars from where the
position was opened.

In the process of the market movement along the trend, the stop order
should be moved to a break-even position. We take profit when one of the
bars crosses the Bollinger Band opposite to the trend direction. For an
upward movement this will be the lower band, and for a downward movement
it will be the upper one.

Let's look at an example.

The EURUSD chart shows a downward trend movement. The blue arrows mark
the candlestick in which the [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) %b ranges from 0 to 0.2,
and the MFI chart is just below 20. Both conditions for opening a short
position are met.

Enter the market at the close of this bar at 1.09731 points (blue line).
Stop-loss is placed at the candlestick low with a two-bar offset from
where the position was opened (red line).

When the trend develops, we move the stop loss to a breakeven position
(red line). For clarity, I marked the initial stop level with a
transparent red line.

Then the price touches the upper band opposite the green cross. At this
moment, we close the order at 1.09402 (green line). The total profit is
1.09731 - 1.09402 = 0.00329 points.

Some traders prefer to use an alternate version of the trending strategy
that uses MACD instead of MFI. This indicator shows really good results
on some instruments. So if you want to find the ideal trading method for
several of the most commonly used currency pairs, it makes sense to test
the strategy with both MFI and MACD.

### [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) Reversal Strategy

This strategy aims to predict trend reversals by comparing the touch of
the [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) with the behavior of indicators.

First of all, we need a Bollinger indicator with standard settings. I’ve
described earlier [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) add it to the MT4/MT5 chart.

We also need the MACD oscillator. It is available in MetaTrader by
default.

To add this instrument to the chart, click on the "Insert" button, then
"Oscillators" and select MACD in the drop-down list.

A new window with the settings will appear. The period of the fast EMA
should be set at 21 bars, the slow one at 100 candles, and the signal
line - at 9. You can do this in the "Parameters" tab.

In the "Colors" tab, you can change the colors of the histogram and
signal line.

For convenience, in the "Levels" tab, add a new value "0". The third
indicator will be the [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) %b, which is already familiar to
us from the previous strategy. I have already described its installation
and setting up. It is standard.

In the trading process, we will need to determine the levels 0.95 and
0.05. So let's add them to the indicator chart.

Open a long position when the following conditions are met:

  1. The candlestick touches the lower Bollinger band;
  2. [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) %b ranges from 0 to 0.05;
  3. MACD is above zero.

Open a short position if the following conditions are met:

  1. The candle touches the top band,
  2. [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) %b ranges from 0.95 to 1,
  3. MACD is less than 0.

Place the stop loss at the extreme reversal point, and in the process of
the new trend development, move it to the breakeven zone. A signal to
close can be a narrowing, the appearance of conditions for the next
reversal, or touching of the Bollinger Band opposite to the direction of
the main movement.

Let's look at the strategy using an example.

In the chart, blue arrows mark the moment when one of the candles
touches the upper band, [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) %b is in the range from 0.95 to
1, and MACD is less than 0. This is a clear signal to enter the market.

At the close of the bar, open a short position at a price of 1.10447
points (green line). Wait for the appearance of the high price values
​​at the reversal in the vicinity of the candlestick and set a stop loss
(red line) at this level.

Move the stop order to the breakeven zone (red line). I’ve marked the
previous stop loss value with a semi-transparent red line.

The development of the downtrend ends. The candlestick marked with a red
cross crosses the upper border of the channel. After detecting the
signal, close the position at a price of 1.09831 points (green line).
The profit from the trade is 1.10447 - 1.09831 = 0.00616 points.

## [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) Screener

For effective profitable trading, it is important to always be on alert
and monitor the market situation. While accessing the market is easy now
even from a smartphone, novice traders often have problems with the
choice of an instrument for trading.

Screeners help you solve this problem – these are services for tracking
trading instruments according to user-specified criteria. With their
help, you can not only save time on market analysis, but also choose the
best moments for entry and exit.

One of the best quality screeners is offered by tradingview.com.

Here you can set up filters by technical and fundamental parameters.

For your convenience, in the upper part of the window there is a search
bar for parameters by name. All filters are divided into three
categories:

  * common;
  * fundamental;
  * technical.

As part of Bollinger trading, we are interested in technical filters.

In particular, here you can select assets whose price is located near a
certain level of the upper or lower Bollinger band. In this case, you
can set both standard parameters (higher or lower) and more complex
ones: for example, higher or equal, crosses up and down. You can even
configure the Bollinger indicator so that it will work with an alert and
send signals if a specified condition is met.

You can refine your search using other tools that we used in the
described strategies. For example, you can use the RSI readings to
select trading instruments for which you should enter the market right
now.

## [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) Tips & Rules

Whichever strategy you use, certain basic rules should always be
followed when working with [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html). They were deduced by the
author of the indicator John Bollinger and listed in his book. I chose
the most relevant ones and put them in a simpler language:

  * [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) should be used in conjunction with other technical analysis tools.
  * You can use a variety of indicators with [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) that determine momentum, market sentiment, activity, intermarket data, etc. The indicators used should not be connected to each other. For example, trend and volatility are used in the calculation of the bands. Their use for additional confirmation of price behavior is meaningless.
  * The default indicator parameters are applicable for most instruments, timeframes and trading methods. But this does not mean that you cannot use other settings. It is important that the moving average always describes the medium-term trend well. If it lengthens or shortens, the number of standard deviations should also be increased or decreased. For example, for fifty periods it is better to use a ratio of 2.1, and for 10 periods - 1.9.
  * [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) are good for confirming chart patterns such as triangles, double and triple tops and bottoms, head and shoulders, and other W-shaped bottoms and M-shaped tops.
  * With a directional price movement, it can often move along the upper line and in the case of a bearish trend - along the lower one.
  * Bars closing outside the bands are statistically more likely to indicate the continuation of the trend, rather than its end.
  * The price touching the band does not in itself signal a buy or sell. Therefore, it should be considered only in conjunction with the readings of other indicators.
  * The Moving Average in [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) is not a substitute for strategies that involve SMA, EMA and other types of averages.
  * The [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) %b indicator will help determine the position of the price relative to the [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html).
  * The BandWidth indicator is recommended to be used together with [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html). It helps identify the “calm before the storm” and signs of trend changes.
  * [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) work on any timeframe and any market. An important requirement for the correct use of the indicator is sufficient price activity and ca[Libra](https://www.playgroundfx.com/blog/libra-creator/)tion of the parameter settings based on the [history](https://www.fixpro.org/post/chargeless-historical-data-api-backtesting/) of its movement.
  * [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) do not provide clear recommendations on their own. This indicator should improve your chances of avoiding bad trades.

Remember these rules and always stick to them if you use [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html)
in your trading method.

## Conclusions on Bollinger Trading

[Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html), like most other indicators, are best not applied alone.
However, they can become an integral part of your trading strategy and
give a good result in combination with other signals. At first, you can
use the above trading methods. If you are just starting out as a trader,
it is best to first master the [Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) trending strategy on a
large timeframe. You can get invaluable experience in trading the
[Bollinger Bands](https://www.algotradesoft.org/custom-indicator/bollinger-bands.html) strategies mentioned in this article on a Liteforex demo
account completely free of charge and without registering.

The Bollinger Band indicator can be compared to a seasoning. Eating it
with a spoon will not bring great results, but it will make any dish
tastier. When you gain experience and intuitively understand the
indicator signals, try additional tools and different combinations of
settings and indicators to maximize your profitability. The Bollinger
Band indicator is perfect for almost any strategy!

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

   1. my.liteforex.com/ru/trading/chart?symbol=EURUSD
   2. docs.google.com/spreadsheets/d/1TfiWC5q9gVd_6T69ypexUwYNLgD1mWeF5xsR6tKnALY/edit?usp=sharing
   3. ru.liteforex.com/blog/for-professionals/grid-torgovla-foreks/
   4. www.mql5.com/en/market/product/4768
   5. my.liteforex.com/
   6. www.mql5.com/ru/code/7165
   7. my.liteforex.com/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=best-technical-indicators&slug2=bollinger-bands&openPopup=%2Fregistration%2Fpopup&utm_source=blog&utm_medium=article&utm_campaign=bonus
   8. my.liteforex.com/deposit/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=best-technical-indicators&slug2=bollinger-bands&promo_code=BLOG&utm_source=blog&utm_medium=article&utm_campaign=bonus