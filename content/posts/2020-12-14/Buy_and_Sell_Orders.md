+++
categories = ["Cryptocurrency", "Blockchain", "SmartContract"]
date = "2020-12-14"
description = "Buy and Sell Orders"
tags = ["Cryptocurrency", "Blockchain", "SmartContract"]
title = "Buy and Sell Orders"
type = "post"
+++

{{<iframe id="large-banner" src="https://www.bounty.group/#slide=23.0" width="100%" height="600" scrolling="no" style="border: 0px solid rgb(216, 221, 230); border-radius: 3px;">}}

2020-12-14

2020-12-14

Orders: Market, Limit, and Stop, Buy and SellMikhail Hypov

Beginner traders don’t tend to think about whether the current market
price is optimal. This often results in increased risk and lower
profits. This is why experienced traders use pending orders. In this
article, I will go into detail about this instrument. We will analyze
the features of different types of order execution and when they should
be used.

The article covers the following subjects:

## Types of Orders

For those just starting out in stock trading, I will first explain what
an order on the stock exchange is. This is important to understand
before we go on further. An order - a market, limit, or stop order - is
an instruction to buy or sell an asset.

In stock trading, there are several types:

Type of order| Description  
---|---  
Market| Orders for opening a trade at the current price. (Buy market and
Sell market)  
Limit| Fulfilled under predetermined conditions. For example, it opens a
buy position when the asset reaches a certain price (Buy limit, Sell
limit, Buy stop, Sell stop, Stop limit)  
Stop| Closes a position when the asset reaches a certain price (Stop
loss, Take profit, Trailing stop)  
  
Market orders are used to instantly open a position at the current
price. They are also often used in high-frequency trading. Pending
orders, such as a Sell limit or Stop limit, are for more experienced
traders. Such orders allow you to enter the market at the most
convenient prices, with no need to be behind the computer all the time.

The chart above shows all possibilities for pending orders and how they
are applied. We will talk more about each type below.

And finally, we will look at stop orders:

  * Stop loss (also known as SL or Stop) is set to limit losses if the price moves against the trader's position.
  * Take profit (TP or simply Take) will automatically close the position after it reaches the trader's set target.

## Market Orders

To properly use orders, you need to learn what a Forex order is once and
for all. In short, it is an order to execute a specified action - buying
or selling an asset. Depending on the order type, it can be executed
immediately or when the trader’s conditions are met.

### Buy and Sell Orders

Let's look at the simplest orders. What are Sell and Buy? An order to
buy at the current price (Buy market) is placed when a trader
anticipates the asset’s further growth. It is instantly executed at the
current market price, plus the spread.

The yellow line on the line shows the [EURUSD][1] market price. The buy
order itself is placed slightly above due to the spread (blue line). The
green arrow shows the expected price direction. A market order is placed
when there is a possibility of getting a decent profit and seizing the
opportunity to open a position immediately based on the current market
conditions.

A sell order is similar. The red arrow shows the expected price movement
after entering the market.

## Pending Orders

A pending order is a market order that is filled when the market meets
certain conditions. For example, a trader doesn’t want to waste time
manually opening a Buy position. Instead, they can place a pending
order, which will be automatically triggered at the desired price. The
difference between market and pending orders is how they are executed.
The former are executed immediately, while the latter - under certain
conditions.

Types of pending orders:

  * Limit order
  * Stop order
  * Stop limit order

The chart above shows when pending Limit and Stop orders should be used.

Let's take a closer look at real examples of using pending orders in
Metatrader 4.

### Buy Stop Order

What is Buy stop, and how do you use it? This order involves buying at a
higher price in a bullish trend.

On the chart, the yellow line shows the [EURUSD][1] market value. During
market consolidation, it is unclear whether the price will continue to
grow. We believe that if the market reaches the blue line, there will be
a bullish signal, so we set a Buy stop order to open a long position
here.

### Buy Limit Order

A Buy limit order is triggered after a drop in value, a local bottom
breakout, and an upward reversal. We enter the market after the set
level is crossed.

To fully understand the Buy limit and Buy stop, you need to see the
difference between them. A Buy stop order is opened with an assumption
that the trend is going to continue. A limit order is used if you expect
a rapid trend reversal.

The figure above shows how the pending Buy limit order works. When the
order is created, the price is at the yellow line. Meanwhile, the trader
assumes that the downward movement is going to turn into an upward trend
soon. To enter a long position at a reasonable price, they set the Buy
limit at the blue line. But there is a risk of the market not reversing
at the expected level but continuing to fall. The chart above shows that
this level wasn’t the best for buying, and the [EURUSD][1] price dropped
even lower before rising.

Let's examine this. A trader wants to buy [Apple][2] shares at $115 per
share. However, the asset is now at $120.70. What orders should be
placed: Limit order, Market order, Take profit, or Stop limit? Or will
the simplest Buy market suffice?

The right solution would be to set a Buy limit order. For this order to
be executed, the price needs to drop to $115 or lower. The price must go
above the position opening level for the trade to be profitable.

### Buy Stop Limit

Let's consider another situation.

The [EURUSD][1] pair in Forex: the yellow line shows where the trader is
at the moment. They assume the price won’t go above the green line, and
there will be a pullback to the blue line. This is where they’d open a
long position. What kind of order is more suitable? As you can guess,
it’s the Buy Stop limit. This order combines stop and limit positions.
It consists of two prices: stop (trigger) and limit prices. A limit
order is created when the price reaches the trigger level. As soon as
the chart reaches the limit, a long position will be opened
automatically.

When you know what a Stop Limit is, trading becomes much easier. After
all, a Buy stop limit can be used for a rollback scenario as well as to
break through key levels. The trader only needs to set a limit order at
the level lower than the stop price.

### Sell Stop Order

Buy/Sell stops follow the same concept. But with the Sell, the current
market position is above the key level, with an expectation of a
downward breakdown.

The image above illustrates when a trader expects a bearish trend. But
because of a flat at the yellow line, they follow the scenario of a key
level breakout at the blue line instead of entering the market. The
trader believes that since the market has reached this value, it will
continue to fall.

### Sell Limit Order

Now, you can probably tell what order scenario is shown on the chart
above. Judging from the trader's expectations to enter a short position
at higher levels, it’s the Sell limit.

The differences between Sell limit / Sell stop and Buy limit / Buy stop
are obvious. They follow the same concept but work in different
directions. The first two are used for a falling market, and the other
ones are for the growing ones.

### Sell Stop Limit

We’ve covered the Buy stop limit. A Sell stop limit follows the same
logic in any market. But this order serves to enter a short position.
The chart above shows a common scenario. The trader is trading
[BTCUSD][3] at the yellow line level and expects the price to stay below
10,000 USD and experience a pullback from that level. They place a Stop
order at 10,000 USD (green line), and when it’s crossed, a pending Sell
order will be placed at the blue line.

Why wouldn’t they go short at 10,000 USD using a simple Sell limit
order? It’s the risks. There is a risk of the price continuing to rise
after they enter a short position. The Sell stop limit eliminates the
risk because market entry takes place after the rollback.

To be fair, the examples for Sell and Buy Stop limit orders are just a
few of the many variations. The Stop order position can be placed
anywhere - both above and below the market and pending orders. Stop
level is only an additional condition for placing pending buy or sell
orders.

### Buy Limit vs. Buy Stop Comparison - What's the Difference?

Now, it's time to examine how the Buy stop and Buy limit differ. The
difference between Buy stop and Buy limit revolves around the price
movement. Knowing what a Buy stop is, we build a scenario where:

  * The current market position is below the key level;
  * We expect an upward movement with a breakout of this level.

A Buy limit order is used when we expect a bullish rebound or a reversal
of a bearish trend.

Based on how these orders work, a Buy limit is placed below the market,
and a Buy stop -  above.

Here is a simple example. Let's say [Google][4] shares are trading at
$1,800. The trader expects a bearish correction from the current levels
but sees potential in the security and starts looking for good levels to
maximize profits.

Not wanting to waste time, they set a Buy limit order at $1,720. This is
where the trader expects the correction to end.

The chart shows that over time, the price reached this level, and the
buy order was executed.

## Take Profit

For some reason, [beginners](https://www.playgroundfx.com/blog/forex-for-beginners/) often confuse Take profit with Stop limit. In
fact, they are applied completely differently and serve different
purposes. So, now we will take a closer look at Take profit.

This order locks the profit when the price reaches a specified level.
How does it work? The golden rule of trading is to always set targets
for each trade. Take profit helps you catch the highly anticipated
moment when the price reaches that target. This order's execution
involves placing an opposite order - long position for a short one and
vice versa. As a result, the remaining position goes to zero, and the
trader fixes the difference between the buy and sell prices on their
balance sheet as profit.

Take profit has two sides. On the one hand, it limits profits. On the
other hand, it reduces the risk of losses during a trend reversal. Let's
see how Take Profit works on the Bitcoin chart.

Expecting a further rise of [BTCUSD][3], we enter the market at the blue
line.

We believe that the price will rise steadily to 16,350 points. We set
Take profit at this level (shown as the green line).

As soon as the price reaches the green line, the position will be closed
automatically.

## Stop Loss

A stop order is one of the basic trading orders. It limits losses if the
market moves in the opposite direction from what was expected. In fact,
it’s the opposite of Take profit. TP sets limits for profits, and SL -
for losses. Similar to Take profit, when the price reaches a specified
level, the order is triggered, automatically closing the position.

This order can be used for an open and pending position. Moreover, SL
can be set for both short and long positions.

Let's illustrate this with an example.

Suppose we expect the asset growth to continue and open a short position
at the blue line.

To limit losses if the situation unravels differently, we set Stop loss
at the red line.

The initial downward ended quickly, and a profitable position turned
into a losing one. Then there was an upward reversal (green arrow),
which led to the crossing of the Stop loss, position buyback, and fixed
losses.

This example shows the importance of correctly determining SL andTP
levels. Even one mistake can turn a successful trade into a losing one.
At the same time, it’s also not recommended to neglect them. If you do,
you can quickly lose control over risk and deplete your deposit.

## Specifics of Order Execution

Buy market and Sell market, Stop loss and Stop limit, and the other
orders described, are based on one simple idea. Imagine yourself
purchasing goods in a store using one of two ways:

  * At the seller's price
  * Bargaining for a more reasonable price

In the first case, you will definitely receive the goods at a fixed
price. In the second case, you can purchase at the desired price or
better, but it might not take place. Exchange orders work similarly.
Here, pending orders act as a trading instrument.

The order book is an important concept. All orders - buy and sell - are
collected here. Like in the market, there are sellers of the same
product at different prices. Let's say you've sent a 50-lot order to a
[liquidity provider](https://www.fintechee.com/services/liquidity-provider/). However, there are only 20 lots available for
selling. Therefore, the remaining 30 lots will be executed at a lower
price. In this case, the trader will experience slippage, and their
position will be opened at the average cost.

In addition to pending orders, there are orders for immediate fill. If a
broker agrees to the specified price, a position will be opened
successfully. If it’s impossible to execute the order, the broker
rejects it, and it offers a requote - the current asset price with
guaranteed execution.

What else causes slippage? Imagine you’ve set a Sell stop at 308 pips.
When the price reaches the target level, the broker will send a sell
request to the supplier, which usually takes a split second. But even in
such a short time, the asset value can change, e.g., reaching 310
points. Thus, the actual execution price will be 310, the price stated -
308, meaning the slippage will be 2 pips.

## How to Place Stop and Limit Orders on MT4 / MT5

Creating pending orders in MT4 and MT5 is very easy. I will give you
step-by-step instructions.

Click New order and the settings window will appear. Select In Pending
order in the Type tab.

Then, select the type of pending order. Choose a Buy Stop order and
specify the price for order execution. And, if necessary, set the goals
and the level of acceptable losses.

## When to Use Each Order Type: Strategy

I will give you another example to illustrate the difference between
Stop and Limit orders in real trading.

The purple oval shows where I am on the [EURUSD][1] chart. I see another
correction wave after an unstable growth with no signs of a bullish
movement.

At the same time, I see that, [historical](https://www.fintechee.com/services/historical-data-for-forex/)ly, there is a strong support
level at 1.1600, and if the asset falls, it is likely to rebound from
that level.

To catch this moment and avoid wasting time sitting in front of the
terminal, I set the Buy limit at a price slightly higher than the
previous minimum of 1.16250 - the blue line. Stop loss (red line) is
placed below the support level, around 1.1590. I decided to set Take
profit (green line) at 1.18250, based on the previous tops and trading
channels (green ovals).

To avoid waiting for the reversal, I placed a Limit order by selecting
Pending order - Buy Limit in the order settings window. I also made sure
to set the lot size, SL, TP, and the price for order execution.

I counted on a rebound from the 1.16250 level and an increase to at
least 1.18250.

Meanwhile, I only risk losing 350 pips with a profit of 2000 pips.

In addition to real risks, professionals also take into account
alternative risks. In my case, it’s a situation where the market doesn’t
reach the pending Buy limit order, makes a reversal earlier, and
continues to grow.

The benefit of pending orders is that there can be an unlimited number
of them. To hedge against an unexpected market move, such as early
reversal, I placed a pending Buy stop order slightly above the market
price. This is shown in the chart above.

We now have a simple two-order trading strategy. Real pros use four
orders or more. For [beginners](https://www.playgroundfx.com/blog/forex-for-beginners/), there is a risk of getting confused and
canceling orders when there is no need for it.

In the chart above, you can see that the market followed the first
scenario. The second Buy stop order serves no purpose and should be
closed on time.

## Conclusion

Having examined Limit orders, Stop loss, Take profit, and Stop limit in
simple [terms](https://www.fintechee.com/terms/), we draw the unequivocal conclusion that pending orders are
essential for successful trading. When used correctly, they save a lot
of time. They allow you to control the risks of losses and fully manage
your funds on the balance sheet.

The main difficulty is choosing the right order type and gaining
experience in working with several orders at the same time. There isn’t
much room for advice, except [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) practice the skill of using
different orders in real market conditions. You can do this risk-free in
a [LiteForex demo account][1].

* * *

P.S. Did you like my article? Share it in social networks: it will be
the best “thank you" :)

Ask me questions and comment below. I’ll be glad to answer your
questions and give necessary explanations.

 **Useful links:**

  * I recommend trying to trade with a reliable broker [here][5]. The system allows you to trade by yourself or copy successful traders from all across the globe.
  * Use my promo-code BLOG for getting deposit bonus 50% on LiteForex platform. Just enter this code in the appropriate field while [depositing][6] your trading account.
  * Telegram chat for traders: <t.me/liteforexengchat>. We are sharing the signals and trading experience
  * Telegram channel with high-quality analytics, Forex reviews, training articles, and other useful things for traders <t.me/liteforex>

## Price chart of EURUSD in real time mode

The content of this article reflects the author’s opinion and does not
necessarily reflect the official position of LiteForex. The material
published on this page is provided for informational purposes only and
should not be considered as the provision of investment advice for the
purposes of Directive 2004/39/EC.

Rate this article:

{{value}}

( {{count}} {{title}} )

   1. my.liteforex.com/trading/chart?symbol=EURUSD
   2. my.liteforex.com/trading/chart?symbol=%23AAPL
   3. my.liteforex.com/trading/chart?symbol=BTCUSD
   4. my.liteforex.com/trading/chart?symbol=%23GOOG
   5. my.liteforex.com/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=orders-market-limit-and-stop-buy-and-sell&openPopup=%2Fregistration%2Fpopup&utm_source=blog&utm_medium=article&utm_campaign=bonus
   6. my.liteforex.com/deposit/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=orders-market-limit-and-stop-buy-and-sell&promo_code=BLOG&utm_source=blog&utm_medium=article&utm_campaign=bonus