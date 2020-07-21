+++
categories = ["Cryptocurrency", "Blockchain", "SmartContract"]
date = "2020-07-21"
description = "grid strategies and grid advisors"
tags = ["Cryptocurrency", "Blockchain", "SmartContract"]
title = "grid strategies and grid advisors"
type = "post"
+++

{{<iframe id="large-banner" src="https://www.bounty.group/#slide=18.0" width="100%" height="600" scrolling="no" style="border: 0px solid rgb(216, 221, 230); border-radius: 3px;">}}

July 21, 2020

July 21, 2020

Grid Trading: a complete overview of Forex grid trading methodMikhail
Hypov

Dear friends!

As promised in the last lesson, this time we will look at an interesting
technique for making profit in the sideways market. Many novice traders
get confused when prices move sideways and try to avoid entering the
market at such times. However, this strategy limits the opportunities
for making a profit. So if you want to trade with maximum efficiency
even during price consolidation, Forex grid might be for you!

## What is Forex grid trading?

The grid trading system is a trading method aimed at making profit by
placing long and short orders below or above the base price. Placing
orders at specific intervals creates a trading grid. In addition to the
obvious possibility of making a profit from the sideways price movement,
the grid trading method does not require predicting the direction of the
market movement. Therefore, grid trading is suitable for [beginners](https://www.playgroundfx.com/blog/forex-for-beginners/) and
also easily [automated](https://www.fintechee.com/features/automated-forex-trading/), which I will discuss below.

There are two ways to implement the **grid trading method:**

  *  **Trading with the trend** is used when the price is expected to move in a certain direction. In this case, buy orders are located above the base price, and sell orders - below it.
  *  **Trading against the trend** is effective when sideways price movement is expected. Pending sell orders are located above the base price, and buy orders are placed below it.

It is also important to set take profit and stop loss levels for each
trade. Otherwise profitable trades may turn against you over time as a
result of a market reversal. Or you will have to keep an eye on the
market in order to close them on time manually.

### Grid trading with stop loss and take profit

Let's look at the simplest grid trading with stop loss using the
[EURUSD][1] pair as an example.

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][2]



Let's choose 1.08950 (purple line on the chart) as the base price. We
will place a pending order on both sides at a distance of 0.00850 from
it.

Since it looks like a sideways price movement is forming, we will grid
trade against the trend. We will place a pending Sell Limit positions
above the base price, and a Buy Limit below it.

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][3]

We mark the Sell Limit position at the level 1.08950 + 0.00850 =
1.09800. Stop loss is placed above the position at the level 1.10300
(red line)

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][4]

Why this particular level? Because if it is reached, the price will
leave the trading range (the chart above shows that its border does not
go beyond 1.10200). If the price overcomes this trading range, a trend
movement will likely begin. At the same time, it makes sense to place
Take Profit around the lower border of the range (below the base price).
For our example, I will set take profit at 1.08050 (green line in the
chart). Since this level is below the base price, but within the trading
range, it is quite likely to be reached.

If the chart moves upward from the base price, the pending sell order
will be executed. Then, continuing to move in the trading range, it
crosses the green Take profit line and we take the profit. Of course, we
can do this trade without Stop loss and Take profit levels and close
positions manually. However, this approach creates the danger of
increasing your losses and even losing your deposit. But in a positive
you risk missing the impulse and not taking the profit on favorable
levels. So I  strongly recommend automatic take profit and stop loss
when using this strategy.

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][5]

Now let's place a pending Buy Limit order.

After calculating the distance, we place a buy order at the level
1.08950 - 0.00850 = 1.08100 (orange line in the chart above). Set the
stop loss lower - at 1.07600 (red line at the bottom of the chart), and
take profit - around the Sell Limit position - at 1.09800. Continuing
the logic of the pending sell order, I will set the take profit for the
buy order at the top of the trading range at 1.08850 (see the green line
at the top of the chart).

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][6]

 **A trading grid with a stop loss** is too complicated for visual
perception. So for clarity, I removed the automatic profit and loss
levels for each of the two orders.

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][7]

In the chart above, we see the following designations:

  * Purple line is the base price,
  * Blue line is the Sell Limit,
  * Orange line is the Buy Limit.

As you can see, grid trading is a variety of trading channel strategies.
The main common feature of this approach is effective trading in a flat
market and maximizing profits from trading in the channel. That is why
this strategy is especially effective on Forex currency pairs, which
mainly trade in price channels. As you understand, in such conditions,
the strategy will generate income until there is movement in the
channel. Because regardless of the market moving up or down, we will
take the profit on the rebound. Here I have presented the simplest
trading grid scheme. A more complex Forex grid system may contain
several consecutive pending Buy and Sell orders placed in the zones
where the price should reverse. We will talk about such systems below.

### Example of a classic grid system

Classic Grid systems are often used for protection against price risks.
We will consider using the Grid system as hedging on Forex in more
detail in this section. We will follow all actions step by step,
summarize and calculate the possible profit. As an example, let's take a
similar situation of sideways movement in the [EURUSD][1] pair.

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][8]

In the chart above, the purple oval marks our current position. Let's
say we expect the EUR to grow against USD, but we cannot estimate the
horizon of this event. To compensate for possible losses from a fall in
the Euro rate, we take our current position 1.10150 as the base price
(purple line in the chart above) and build a trading grid from it.

There is no single method for determining the intervals for building a
grid.

Main approaches to determining the intervals for placing orders:

  1. Fixed value calculated as the channel width divided by the maximum number of orders placed plus one.
  2. Based on the Pivot indicator, Fibonacci levels and other tools to determine support and resistance levels
  3. Based on the distance to the nearest extreme.

I personally prefer to calculate intervals based on extrema. Below we
will analyze this case in more detail.

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][9]

To do this, let's look at the [history](https://www.fixpro.org/post/chargeless-historical-data-api-backtesting/) of the chart and determine the
distance from the current level to the nearest extreme. Since we are
determining the interval for the first pending orders, they need to be
executed within the development of the side channel. Sofrom this extreme
we go to the candlestick body or the high value (in the case of a Sell
order) of the previous candlestick and round to whole numbers (they act
as a magnet for major players). We get Sell Limit order at the level of
1.10650 points, and the interval between the base price and the order is
500 points.

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][10]

We will move the stop loss by another 500 points, setting it at the
level of 1.11150. Take profit is set approximately at a double interval,
at the level of 1.09600.

 ![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][11]

As a result, in the chart, the first part of our grid looks like this:

  * Sell ​​Limit - light blue line,
  * stop loss - red line,
  * take profit - green line,
  * base price - dark blue.

Now let's place a pending Buy limit order.

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][12]

To do this, we measure 500 points down from the base price. The level
for opening an order = 1.10150 - 0.00500 = 1.09650. Let's move the stop
loss down another 500 points and set it at the level of 1.09150. Set the
take profit at 1.10700, next to ​​the pending sell order.

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][13]

As a result, in the chart above, we see the **classic Grid system** with
Sell (blue line) and Buy (orange) pending orders and automatic take
profit (green lines) and stop loss levels (red lines).

As we can see, first the price hits is the Sell Limit order (blue oval
in the chart). After its opening, the price immediately moves down.

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][14]

After some time, the price reaches 1.09650, hitting the pending Buy
order (orange oval). A little later, at the level of 1.09600, the take
profit of the Sell order is triggered, which was executed earlier.
Immediately after the order has been executed by take profit, we place
exactly the same order with the same settings as the previous one. Our
net profit without the spread was already 1,050 points.

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][15]

Then, the price goes up rapidly and crosses the take profit at the level
1.10700. The Buy order is automatically closed, and our profit doubles
up to 2,100 points. The Sell order is activated and a pending Buy order
is placed. As you can see, the price almost reaches the stop loss level
of the Sell order and comes back down.

However, what would happen if the price reached the Stop Loss level?

The answer is simple - in this case, we would update the base price
based on the result of the last formed candlestick, do a new calculation
of the interval and re-place pending orders taking into account the new
input data.

However, since there are no signs of the end of the sideways movement or
its shift up or down, we continue to use the **Forex grid system**
without changes.

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][16]

After some upward movement, the price goes down in steps and reaches the
lower Buy Limit order (green oval). Then it crosses the take profit
level of the Sell position, taking the current profit at 0.01050 points.
The total profit of the three closed positions now is 3,150 points
without spreads.

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][17]



Then the price chart crosses the automatic stop loss level of the active
Buy order (see the red circle). Therefore, we subtract from the total
profit the loss of 500 points and it is now equal to 2,650 points.

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][18]



As I said above, the grid strategy allows you to hedge risks on the
Forex market. The remaining profit of 2,650 points would be enough to
cover the losses in the main buy position in EURUSD in a comparable
amount up to 1.06500. The chart shows that until the moment of a strong
upward impulse, we did not see the crossing of this level (marked with a
green ray). And given that the work of the grid strategy does not stop
there and the profit will constantly expand the break-even range for the
main position, we can talk about the grid system being effective as a
hedging instrument.

I highly recommend testing this strategy in manual mode with small lots
or even on a demo account. This will help you work out the mechanics of
the strategy and understand [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) work with it. All the necessary tools
are available from [LiteForex][1]. After you gain experience trading
with this strategy, the next big step for you is to use a quality Forex
Grid master or Forex Grid trader. In other words, this is a trading
[robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/) / [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/) that will automatically set the grid. This will save a
lot of time, as well as rid your trading system of the notorious human
error. I will talk about this later in this article.

### Forex grid strategy

As I said above, high volatility markets are considered difficult for
most traders to profit from. On the one hand, the limited range of price
fluctuations does not provide any significant profit. On the other hand,
the frequent change in the direction of price movement complicates the
analysis, increasing the risks many times over. But this is only true
for classic trading methods.

The Forex grid strategy is their exact opposite. Even its simplest
version presented above demonstrates high accuracy. It therefore allows
you to consistently profit from recurring price fluctuations. But at the
same time, even the best Forex grid strategy demonstrates low efficiency
in the case of a stable unidirectional trend movement.

Absolutely any grid hedge strategy is based on placing "mirror"
(opposite) orders. In most cases, positions are placed against the
trend, because during the back-and-forth development of the market,
price movement in one direction inevitably leads to a quick reversal.
Thanks to this, we can simplify the market analysis, since we don’t need
to forecast the upcoming price movement in any direction. The usual
number of orders placed on each side of the base price is 3-4. In this
case, the setting interval can be either fixed or dynamic, and tied to
the support and resistance levels of the Pivot indicator or any other
instrument that allows you to identify the traded levels.

In principle, Forex hedging with a grid trading strategy is suitable for
trend following. However, its effectiveness will be low. In this case,
orders with a higher price are placed to buy, and orders with a lower
one - to sell.

Let's discuss [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) implement a successful grid trading strategy,
regardless of which of the methods below you will use:

  * Choose the instruments on which the Forex grid hedge strategy works best. You should choose instruments that you can make money on both in a bullish and a bearish market. They include Forex currency pairs, futures, and cryptocurrencies. The latter are characterized by high volatility and most of them are ideal instruments for grid trading. But stocks, with rare exceptions, are not what we’re looking for. Some of them cannot be traded short or have high commissions. By the way, with [LiteForex][1] you can short any stocks. However, the main problem with stocks is that trend movement dominates there, and hedging with a grid strategy will not work effectively. As for timeframes, this is purely individual. If you intend to place orders manually, then it is better to select large timeframes. Otherwise you may simply not have time to place new pending orders, take profit and stop loss. Any timeframes with cyclical price movement and channel tracing are suitable for trading with [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s.
  * Almost any Forex hedging grid strategy involves opening a large number of orders. So you need a broker that does not charge a commission for opening orders or charges minimal commissions. Again, [LiteForex][1] is an excellent alternative to most other brokers in this matter. A backup option is a sufficiently large deposit, which will significantly expand the trading grid to a large number of pending orders on both sides of the base price. However, in this case, the efficiency of grid trading will drop sharply.
  * In the process of placing pending orders, you need to clearly define the step of positions, as well as the intervals for setting take profit and stop loss.

### Forex grid hedge strategy

The Forex grid hedge strategy is classic grid hedging. The essence of
the method is to place pending orders opposite in direction, with stop-
loss and take-profit orders for each of them. I talked about placing
such orders above.

After the pending positions are set, there are three possible scenarios,
two of which are favorable:

  1. If the price starts moving in one specific direction, having previously triggered an order in the same direction, then it will liquidate all trades placed against the main movement and collect Stop Losses for these positions. The result of this scenario will be neutral - with the correct placement of positions, the resulting profit should compensate for losses from liquidated positions.
  2. Consolidation is observed in the market, and all positions are opened and take profit levels intersect on each side of the base price.
  3. The price opens a position in one direction only, does not cross the take profit, and then starts moving in the opposite direction. In this case, the only open position will be unprofitable.

The last unfavorable option is one of the drawbacks of the Forex hedging
grid strategy, which does not allow you to rely on this method entirely
and get 100% profit.

### Forex Double Grid Strategy

This strategy is neutral - it does not require the trader to predict the
likely price movement. At the same time, it has high requirements for
the setting and execution of stop losses and take profits.

One of the key differences in the Forex Double Grid Strategy is the
double trading grid. Suppose the EURUSD currency pair is currently
trading at 1.1000. To create a grid, we need to do the following (I
indicated the prices in the tables without taking spread into account).

Buy:

 **Order type**|  **Price**  
---|---  
  
 **Buy Stop**

|

 **1,1060**  
  
 **Buy Stop**

|

 **1,1045**  
  
 **Buy Stop**

|

 **1,1030**  
  
 **Buy Stop**

|

 **1,1015**  
  
 **Buy**|

 **1,1000**  
  
 **Buy Limit**

|

 **1,0985**  
  
 **Buy Limit**

|

 **1,0970**  
  
 **Buy Limit**

|

 **1,0955**  
  
 **Buy Limit**

|

 **1,0940**  
  


Sell:

 **Order type**|  **Price**  
---|---  
  
 **Sell Limit**

|

 **1,1060**  
  
 **Sell Limit**

|

 **1,1045**  
  
 **Sell Limit**

|

 **1,1030**  
  
 **Sell Limit**

|

 **1,1015**  
  
 **Sell**|

 **1,1000**  
  
 **Sell Stop**

|

 **1,0985**  
  
 **Sell Stop**

|

 **1,0970**  
  
 **Sell Stop**

|

 **1,0955**  
  
 **Sell Stop**

|

 **1,0940**  
  
The grids in these tables are mirrored. It means when one group of
positions is in profit, the other will be unprofitable and vice versa.
The number of positions in each grid can be completely different: from
two (excluding market orders) to 5, 10 or more. It is important that
both grids contain the same number of positions of the same volume.
Grids consisting of a small number of positions are easy to use, but
they do not always allow flexible risk management.

There are several ways to trade the **double grid system**. The first
way involves managing the two grids as separate systems. Each side has
its own take profit and stop loss.

The second option resembles a swing strategy: it involves separate
management of trading pairs. It is effective when the market is
experiencing sideways volatility requiring take profit and stops for
each currency pair. This option is suitable for large timeframes and a
small number of positions in each of the grids.

The key to getting the most out of your strategy is active
experimenting. The intervals for setting take profit and stops will
differ depending on the instrument traded.

Now let's take a close look at the principle of trading with a double
grid strategy:

  * Stop orders to buy and sell are opened in the direction of the trend when a predetermined level is crossed
  * Buy limit orders are executed if the market falls below the current level and stopped when the market rises.
  * Sell ​​limit orders are executed when the market rises above the current level and stopped when the market falls.

Now let's talk about risk control. Each of the two trading grids must
have clear boundaries for profit and loss. Take profits and stop losses
are placed according to the same principle that I showed in the examples
above. It makes sense to place stop losses at the level when the profit
received from the open trades in one grid will exceed the loss from
positions in another grid that is mirrored to it.

When the stop loss density is too high, “market noise” can cause some
trades to close before they can generate a profit. Therefore, the
minimum possible placement of stops is considered to be slightly higher
or lower than the level of the hedging position, depending on the
direction. So the hedging trade must be opened before the stop loss is
triggered.

### Pros of the double grid strategy

  * You can get profit without predicting which direction of the market.
  * The strategy works great in volatile markets without a pronounced trend.
  * With a thoughtful positioning, you can get a big profit using the full potential of rapid price fluctuations along the trading grid.
  * The amplitude of fluctuations is easily calculated by analyzing the previous cycles.
  * The strategy contains many repetitive actions that are easily [automated](https://www.fintechee.com/features/automated-forex-trading/).

### Cons of the double grid strategy

Frst of all, like other methods of grid trading, this strategy is not
particularly effective during the formation of strong trends. If we
compare it with the classic Forex grid hedge strategy, the double grid
is more complex in [terms](https://www.fintechee.com/terms/) of management. Because of this, [beginners](https://www.playgroundfx.com/blog/forex-for-beginners/) often
place orders at sub-optimal prices, make mistakes with take profit and
stops, and deprive themselves of the opportunity to get high profits
over and over again.

### Forex grid trading ea review

As I said above, the grid system is easily [automated](https://www.fintechee.com/features/automated-forex-trading/). Next I will do a
Forex grid trading ea **review of the Forex VR Smart Grid** , a
multifunctional [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/) that allows you to trade using order grids. It
can show positive results not only during the sideways movement of the
market, but also in trend movements.

The grid trading [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/) is designed to work with any timeframes and
financial instruments: currency pairs, futures, CFDs, cryptocurrencies,
or metals. To start trading, it uses a simple algorithm based on the
signals of the CCI indicator. When the indicator is in the oversold
zone, the [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/) opens a long position, and when in the overbought zone -
a short one. When entering the breakeven zone by stop loss, the [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/)
will add new positions, thereby increasing potential profit.

The grid of orders against the trend is closed by hedging them. The grid
trend multiplier can hedge all positions, or the last two, or the
lowest, and the highest. There is also a Smart Hedging option available,
when the [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/) chooses the most optimal method from the ones described
above.

Positions are closed with a minimum profit set in the settings. In
addition, positions with the highest risk can be closed using
accumulated profit, taking into account broker commissions and swap
costs.

Grid trend trading ea download: you can download VR Smart Grid
[here][19]. In addition to the standard version, a demo version is
available on the page. I will use it to show the principles of trading
with an [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/).

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][20]

To install **VR Smart Grid ea MT4** , first of all, you need to launch
the terminal, select the "File" tab in the top menu, and "Open data
directory".

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][21]

This will open an explorer window. In it, go to the "MQL" folder, then
to the "Experts" directory and copy the downloaded [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/) file into it.

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][22]

To complete the installation, restart Metatrader. To check if the
installation was correct, open the "Navigator" menu, choose the
"Advisors" tab and check for the name **"VR Smart Grid"** in the list.

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][23]

I also recommend making sure that the platform settings are activated,
which are necessary for the [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/) to work correctly. To do this, in the
top menu select the "Service" tab, then in the drop-down menu select
"Settings".

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][24]

In the window that opens, open the "Expert Advisors" tab. The items
"Allow automatic trading", "Disable automatic trading when changing
account", "Disable automatic trading when changing profile", "Allow DLL
imports" and "Allow WebRequest for the following URLs" must be checked.

### Setting up VR Smart Grid Expert Advisor for MT4 (Magic Number)

The VR Smart Grid settings window opens immediately after dragging the
Expert Advisor from the Navigator window onto the chart.

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][25]

In the "Common" tab, you can configure the type of positions that will
be used by the trading [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/), allow or prohibit the EA to trade, and add
or exclude import permissions.

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][26]

Trading strategy settings are in the "Input parameters" tab:

  *  **Take Profit (in pips)** \- sets the take profit level.
  *  **Start lot** \- sets the size of the initial lot.
  *  **Maximal Lots** \- sets the maximum lot size.
  *  **Type close orders** \- method for closing orders. Here you can select one of two parameters: Average and Part close.
  *  **Point order step (in pips)** \- this parameter sets the step between the order grid.
  *  **Minimal profit for close grid (in pips)** \- minimum profit required for the [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/) to close the grid.
  *  **Magic Number** \- the identifier used by the Expert Advisor to identify the orders it has opened. Such identifiers are required when launching multiple [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/)s. If you leave the field at zero, the [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/) will be able to close any position, and if you assign it a number, it will only close only positions with this number.
  *  **Slippage (in pips)** \- the difference in pips between the planned price and its actual value, at which the trading [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/) will not open positions.

The settings may differ for each trading instrument. The author of this
[advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/) herself recommends testing the [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/) on a demo account or a test
live account with a small amount for 2-4 weeks.

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][27]

The chart shows the VR Smart Grid Expert Advisor. The algorithm draws
arrows in the chart for open positions and dashes for take profit
levels. The trading [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/) is based on the principle of opening the
maximum number of trades in both directions. Long and short positions
are initially controlled separately from each other. They are combined
into a single system only when the [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/) detects the possibility of
hedging one of the sides due to the excess total profit on the other
side.

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][28]

In the chart such combinations of orders look like a bundle of dotted
lines, which converge at one point.

 **VR Smart Grid Expert Advisor** is an excellent example of grid
strategy automation. Although it is not the Grail, in skilled hands with
due diligence, risk management rules and continuous testing, it can
bring positive results. I also recommend looking at the Grid Trend
Multiplier trading [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/).

Not all brokers allow the use of such tools. Many are openly against
such trading automation tools. Don’t waste your time on searching, try
this [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/) with LiteForex. LiteForex clients can also rent VPS servers
directly from their personal account. Thanks to this, you don’t have to
set up the server, you can start trading and setting up [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/)s
immediately. Trading quotes and server capacities are supplied by a
single provider, thus ensuring reliable and fast operation of [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s
around the clock.

## Crypto grid trading: an example of using on the cryptocurrency market

Cryptocurrency markets are highly volatile and therefore are great for
applying grid strategies. At the same time, **cryptocurrency trading**
is no different from trading with conventional currency pairs. Let's
look at the simplest grid through the example of [BTCUSD][29].

 **Crypto grid trading begins with the formation of a price grid.** In
the classic version, you use the current price and place pending orders
at regular intervals from it. This time we will use another grid trading
crypto method - we will calculate the arithmetic mean of the local high
and low and take it as the base price. In your trading you can either
use the proposed method for calculating the base price or the classical
method.

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][30]

The local high marked with a green circle is 9,540 points, and the local
low (red circle) is 9,080 points. Thus, the optimal base price, from
which we will count the levels of pending orders, is 9,310 points
(purple horizontal line).

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][31]

Now we form a trading grid by progressively opening positions. There
will be two pending Sell Stop orders and two Buy Stop orders in total.

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][32]

In this strategy, we will calculate the interval taking into account the
channel width and the maximum number of orders. Taking into account that
the width of the trading channel is approximately 500, the optimal step
for pending orders is 100 points. That’s because in this case the price
amplitude will presumably cover the entire grid based on the maximum
number of orders: 4 orders + 1 base price. As for the intervals for stop
losses and take profits, they are 200 points. I made them a little
smaller in the chart for clarity, so that the stops do not overlap with
positions. Sell ​​Limit is marked with blue lines, Buy Limit with orange
lines. I depicted stop losses with red lines, and take profits with
green lines. Since there are two orders in this example on each side,
the base price will be recalculated after crossing the extreme second
level of automatic stop loss. If only one stop loss out of two is
triggered in one direction, a new pending order will be placed in the
stead of the liquidated position.

![LiteForex: Forex grid trading: grid strategies and grid [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s][33]

When using the grid strategy for trading [Bitcoin][29], we saw the
following picture:

  1. A position is opened for the first pending Buy order.
  2. A position is opened for the second pending Buy order.
  3. The stop loss of the first Buy order is triggered. The final result is a loss of 200 USD. The order for the Buy Stop is reopened in place of the first one with identical parameters.
  4. An order to open the first pending Buy order is executed. The take profit level of the second Buy order is triggered. A position is opened for the first pending Sell order. The final result is 0 USD.
  5. The take profit level of the first Sell order is triggered. A new limit order for a Sell order is placed in the stead of the executed order. The final result is a profit of 200 USD.
  6. The stop loss of the first Buy order is triggered. The order for the Buy Limit is reopened in the place of the first one with identical parameters. The final result is 0 USD.
  7. The take profit level of the second Buy order is triggered. A new limit order for a Buy order is placed in the stead of the executed order. The final result is a profit of 200 USD.
  8. The take profit level of the first Sell order is triggered. A new limit order for a Sell order is placed in the stead of the executed order. The final result is a profit of 400 USD.

As this experiment has shown, the Grid strategy is capable of generating
profit in the [cryptocurrency markets][34]. When placing orders and
calculating intervals, you need to make allowances for the extremely
high volatility of this trading instrument and possible losses due to
slippage of stop losses. To avoid this, it is recommended to use this
strategy exclusively for highly liquid cryptocurrency pairs.

## Conclusions on the use of the grid system in trading

The grid system differs from most trading methods in that it is more
suitable for trading in volatile markets, mainly sideways movement. It’s
easy to learn and algorithmize, and it does not require special
analytical skills. The disadvantage of this strategy is that you always
have to be in the market. Having no open positions is rare when using
this strategy, so requires constant monitoring of the market situation
and attention. Many traders use Expert Advisors that set the price grid
and take profits automatically. The most important parameters for the
Grid strategy are as follows:

  * As many open positions as possible. On the one hand, you need to be sure that you have enough resources to cover them and not catch margin call at the extreme point of the channel. On the other hand, you need to understand that the fewer orders, the lower the effectiveness of this strategy.
  * The base price level is an important factor that impacts the effectiveness of the grid strategy. We analyzed two approaches to determining the base price. They are the arithmetic mean between the last two extreme points, or the current level of the last closed candle.
  * The interval between orders, just like the base price level, is critical for the effective operation of the entire strategy.

Based on my own experience and the given practical examples, the most
effective trading grid system should be one that allows a flexible
approach to revaluation of the channel width, intervals, base price and
the maximum number of orders. Adherence to your own risk and money
management rules is critical when using this strategy. I strongly
recommend to immediately practice the new knowledge. You can try
everything I have described today in the convenient [LiteForex][34]
trading terminal, which I used when writing this article.

Good luck everyone!

Respectfully,

Mikhail@Hyipov

 _Just in case, I should remind you that all the information is
presented as an example solely for educational purposes. This is not
financial advice and I do not give any guarantees of profit. You make
all trading decisions yourself at your own risk._

* * *

P.S. Did you like my article? Share it in social networks: it will be
the best “thank you" :)

Ask me questions and comment below. I’ll be glad to answer your
questions and give necessary explanations.

 **Useful links:**

  * I recommend trying to trade with a reliable broker [here][35]. The system allows you to trade by yourself or copy successful traders from all across the globe.
  * Use my promo-code BLOG for getting deposit bonus 50% on LiteForex platform. Just enter this code in the appropriate field while [depositing][36] your trading account.
  * Telegram channel with high-quality analytics, Forex reviews, training articles, and other useful things for traders <t.me/liteforex>

![Grid Trading: a complete overview of Forex grid trading method][37]

The content of this article reflects the author’s opinion and does not
necessarily reflect the official position of LiteForex. The material
published on this page is provided for informational purposes only and
should not be considered as the provision of investment advice for the
purposes of Directive 2004/39/EC.

Rate this article:

{{value}}

( {{count}} {{title}} )

   1. my.liteforex.com/trading/chart?symbol=EURUSD
   2. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Grid_EURUSD_1.jpg?w=30&s=a7908cb96691417cbda92ddb97a5963e
   3. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Grid_sell_order_2.jpg?w=30&s=81b65ceeec099e650a5d62f5ef96a6fd
   4. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Grid_EURUSD_3.jpg?w=30&s=46055d29c061f53adf1470395ecd4777
   5. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Grid_buy_order_4.jpg?w=30&s=7acfe447e7448bb62170c74095227727
   6. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Grid_EURUSD_5.jpg?w=30&s=ec50397ec3e6c1e0640d2525d88654d1
   7. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Grid_EURUSD_6.jpg?w=30&s=a28e63a4ff1d49ba0816d3e5468b9beb
   8. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Grid_EURUSD_7.jpg?w=30&s=844bc33741ad2424650ac5649bce21d2
   9. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Grid_EURUSD_8.jpg?w=30&s=0ae532cda53217bf90b14c20c3285ad6
   10. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Grid_sell_order_9.jpg?w=30&s=d57c0cb6087f63df23c1cb0111f66a60
   11. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Grid_EURUSD_10.jpg?w=30&s=438143a3c84bbd80c5d980cc861ca6db
   12. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Grid_buy_order_11.jpg?w=30&s=c8969ca71d88df9561d0dd901653a6cd
   13. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Grid_EURUSD_12.jpg?w=30&s=5b1be38cb6e1d91b7f1cbf33a17c16e6
   14. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Grid_EURUSD_13.jpg?w=30&s=43307f502880a34a1453b114c4a4b938
   15. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Grid_EURUSD_14.jpg?w=30&s=ba0e348c35fd86c68dbe34084e903b00
   16. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Grid_EURUSD_15.jpg?w=30&s=d0e8a23d93b50e7bc0c42695832fb273
   17. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Grid_EURUSD_16.jpg?w=30&s=89b4cda58cb235ec5ee8d275a5475e71
   18. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Grid_EURUSD_17.jpg?w=30&s=0227c77f9e74cedc710176a4b023b28f
   19. www.mql5.com/en/market/product/28140
   20. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Smart_Grid_18.jpg?w=30&s=9c2b1290ecbac0140f93863f4ecb52b2
   21. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Smart_Grid_19.jpg?w=30&s=7b8c42d7462771af8505420261bac552
   22. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Smart_Grid_20.jpg?w=30&s=54ebe79c32481b44df9ce67e977f6a27
   23. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Smart_Grid_21.jpg?w=30&s=027ddab07372440a59e503e0f7bac6dd
   24. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Smart_Grid_22.jpg?w=30&s=a7d8221a819fc0a52836385ca6785a7d
   25. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Smart_Grid_23.jpg?w=30&s=69e43dd5c79b1820164f6af16f05382c
   26. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Smart_Grid_24.jpg?w=30&s=a31c26c78b78bb075bc52c176345b8fc
   27. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Smart_Grid_25.jpg?w=30&s=5eaa9163552107fe1396d5be9fe58594
   28. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Smart_Grid_26.jpg?w=30&s=d602f3394afcd034cbddf2c03a86e34e
   29. my.liteforex.com/trading/chart?symbol=BTCUSD
   30. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Grid_BTCUSD_27.jpg?w=30&s=31c6ed12b3d486b2860834e3970fb308
   31. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Grid_sell_order_28.jpg?w=30&s=3a8239a609f5c50054430bce207a2b6e
   32. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Grid_BTCUSD_29.jpg?w=30&s=57e1d18a0f23a4eca56b15768aa3c54d
   33. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Grid_BTCUSD_30.jpg?w=30&s=c6ccd7b24dd3f6289f00bad166d033f4
   34. my.liteforex.com/trading?type=crypto
   35. my.liteforex.com/?category=for-professionals&slug=grid-trading-a-complete-overview-of-forex-grid-trading-method&openPopup=%2Fregistration%2Fpopup&utm_source=blog&utm_medium=article&utm_campaign=bonus
   36. my.liteforex.com/deposit/?category=for-professionals&slug=grid-trading-a-complete-overview-of-forex-grid-trading-method&promo_code=BLOG&utm_source=blog&utm_medium=article&utm_campaign=bonus
   37. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Grid-trading/Grid_strategy_hypov_logo.jpg?q=75&w=1000&s=76003d14eb03e573505070e4579b1bad