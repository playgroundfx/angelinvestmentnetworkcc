+++
categories = ["Cryptocurrency", "Blockchain", "SmartContract"]
date = "2020-07-27"
description = "Forex quotes and their providers. Accuracy of quotes"
tags = ["Cryptocurrency", "Blockchain", "SmartContract"]
title = "Forex quotes and their providers. Accuracy of quotes"
type = "post"
+++

{{<iframe id="large-banner" src="https://www.bounty.group/#slide=9.0" width="100%" height="600" scrolling="no" style="border: 0px solid rgb(216, 221, 230); border-radius: 3px;">}}

July 27, 2020

July 27, 2020

Forex QuotesOleg Tkachenko

## Forex currency quotes and their providers. Accuracy of Forex quotes

Unlike bank rates, Forex currency quotes are dynamic. They are formed as
the ratio of supply and demand and change every second. Someone makes
money and someone loses on slippage. An error in the accuracy of the
quotes in MT4 can lead to a disruption of the strategy testing results.
In this review you will learn what Forex quotes are and [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) find the
most profitable rates, what the accuracy of quotes is and why this
information is important for a trader, [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) download quotes in MT4 and
[how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) make money on Forex on the difference in rates. Stick around!

How to read Forex quotes and work with them

You have surely seen currency quotes in banks and exchange offices. Have
you noticed that not only buy and sell rates are different at each bank,
but also the size of the margin? It’s the same on Forex: each broker has
its own quotes and spread size, and the trader needs to choose the most
profitable rate.

You can often encounter the term accuracy of quotes on traders' forums.
Sometimes there are explosive disputes around it: according to some
traders, the inaccuracy of quotes is the reason for their losses.
Although this is a rather controversial issue, the quotes of currency
pairs differ with different brokers. There is even a strategy called
[arbitrage](https://www.playgroundfx.com/blog/arbitrage-bot-bitcoin/) trading, where you make money on the difference in Forex
currency rates of different brokers in the short term.

In this article, you will learn the following:

  * What are Forex quotes and why a trader needs this information?
  * Who are Forex currency rate providers and how does ECN systems work?
  * Why is the accuracy of quotes important and where to find the most profitable rate?
  * How to upload and download quotes in MT4?
  * What is [arbitrage](https://www.playgroundfx.com/blog/arbitrage-bot-bitcoin/) on Forex?

### What are currency quotes on Forex and what types are there?

Quote is the value of an underlying asset (instrument) expressed in
units of another (quoted) asset (instrument). On Forex, a currency rate
is the value of one currency expressed in units of another currency.
Currency pair quotes are represented by two values: the Bid price - the
price at which the trader can sell it, and the Ask price - the price at
which the trader can buy the base currency for the quoted one. The Bid
price is always lower than the Ask price.

![LiteForex: Forex quotes and their providers. Accuracy of quotes][1]

 **Example.** The screenshot shows the quotes of the EUR/USD currency
pair in MT4. They mean the following:

  * Ask (Buy) price - 1.10039. It means that a trader can buy 100,000 euros for 110,039 US dollars.
  * Bid (Sell) price - 1,10016. It means that when selling 100,000 euros, the trader gets 110,016 US dollars.
  * Spread = 1.10039 - 1.10016.

 _ **Important! Look at the colors. Please note that the buy price of
the EUR for the USD (the one that is higher) is located above the Buy by
Market button in blue. You press this button if you want to buy Euro by
opening a long position. The red Sell by Market button opens a short
position (selling euros). You already know that the Buy price is always
higher than the Sell price. But then why is the higher price red in the
left chart? Answer: Ignore the color of the lines in the chart. This is
an MT4 bug that the developers stubbornly refuse to fix. We don’t know
why, but this can be confusing for novice traders.**_

Quotes can be direct and inverse. For example, if the quote EUR/USD = 2
is direct (you can buy 1 euro for 2 US dollars), then the reverse quote
will be USD/EUR = 0.5 (you can buy 1 US dollar for 50 euro cents). The
base currency in the first place is always equal to one, and the value
of the quoted currency is how much you can buy this very base unit for.

Other things you need to know about quotes:

  * In most cases, quotes are expressed in 4 digits after the decimal point and the last digit is called a point. So the price change from 1.2500 to 1.2501 is equal to one point. Some brokers have five-digit quotes, and you can encounter the term "pip". This is where the confusion begins. According to one version, points and pips are the same thing. According to another version, the 5th digit in quotes is pips, and the 4th is points. This is most confusing on trading forums, where someone writes that they earned 500 points, while in fact they earned only 50 points (which is the [daily](https://www.fintecher.org/2020/03/03/forex-trading-daily-strategy/) volatility of the pair). What do you do? Read the broker's offer, account specification and study the [terms](https://www.fintechee.com/terms/) carefully.
  * Pip is the 4th digit after the decimal point (0.0001) for all currency pairs except for the Japanese yen – there it’s the 2nd digit after the decimal point (0.01).
  * Currency pairs with the USD are called major pairs. Pairs without the USD are called a cross rates.
  * Quotes can be dealing or indicative. Dealing quotes are real quotes from [news](https://www.letsplayfx.com/blog/forex-news-website/) agencies and are used on live accounts. Indicative quotes are approximate quotes that do not have high accuracy and update speed. They can be used on demo accounts.

### Who are quotes providers

The currency exchange rate on Forex is formed as the ratio of supply and
demand. This means that all traders' orders should be gathered by
brokers into a single system, where they will be processed, sorted and
transferred back to traders as the best proposed [options](https://www.fixpro.org/post/options-liquidity/). These order
processing systems are also called liquidity [aggregator](https://www.fintechee.com/features/price-aggregator/)s or quote
providers. The counterparties who execute orders of traders and who are
also participants in these systems “on the other side of the barricades”
are [liquidity provider](https://www.fintechee.com/services/liquidity-provider/)s.

Simply put, [liquidity provider](https://www.fintechee.com/services/liquidity-provider/)s are providers of information on order
volumes and desired rates. Liquidity [aggregator](https://www.fintechee.com/features/price-aggregator/)s are platforms where
quotes are mixed and sorted and trades are managed.

How ECN (Electronic Communication Network) liquidity [aggregator](https://www.fintechee.com/features/price-aggregator/) works:

  * All traders' orders to buy and sell currencies are gathered in the so-called order book (depth of market). They are divided into two groups - buy and sell - and are sorted by price in ascending or descending order.
  * If there are suitable orders from different clients inside the order book (the same buy and sell prices), these trades overlap.
  * A request is made to [liquidity provider](https://www.fintechee.com/services/liquidity-provider/)s (such as large banks, brokers) with a price closest to the next order.
  * If the [liquidity provider](https://www.fintechee.com/services/liquidity-provider/) approves it, the trader's order is executed. If there is no approval, the order is forwarded to the next supplier.
  * If none of the [liquidity provider](https://www.fintechee.com/services/liquidity-provider/)s is ready to satisfy the trader's request at the price set by them, the trader gets a new quote.

Client orders are merged using the FIX (Financial Information Exchange)
protocol, which allows two [options](https://www.fixpro.org/post/options-liquidity/) for order execution:

  * FOK (fill or kill) - full execution of the order if there is a suitable price and volume offer from the [liquidity provider](https://www.fintechee.com/services/liquidity-provider/). There is no other option.
  * IOC (immediate or cancel) - full or partial order execution. The trader's order can be partially executed at the price specified in the order, the remaining volume is executed at a different price.

 **For example,** the trader wants to buy 100 euros at a price of
1.2000. In the first case, if the [liquidity provider](https://www.fintechee.com/services/liquidity-provider/) is ready to satisfy
the order in full, the trade is executed, if not - the order is not
executed. In the second case, if the [liquidity provider](https://www.fintechee.com/services/liquidity-provider/) is ready to
satisfy the request for 70 euros at this price, the order is executed,
the trader buys the remaining 30 euros at a higher price.

The most famous [liquidity provider](https://www.fintechee.com/services/liquidity-provider/)s are Barclays, Citibank, Credit
Suisse, and Saxo Bank. The most famous ECN systems (liquidity
[aggregator](https://www.fintechee.com/features/price-aggregator/)s) that unite [liquidity provider](https://www.fintechee.com/services/liquidity-provider/)s, brokers and act as the
final link in the trader chain are Integral, Currenex, and LMAX. LMAX is
referred to as an MTF [aggregator](https://www.fintechee.com/features/price-aggregator/), but I see no reason to go into the
details of differences between ECN and MTF systems. For novice traders,
the difference in how they process orders and deliver quotes is
irrelevant.

 **A few useful points:**

  * Small brokers often do not have the technical capacities of direct access to Integral and Currenex networks. They use the services of other large brokers that provide sub-brokers with access to [liquidity provider](https://www.fintechee.com/services/liquidity-provider/)s and the necessary software. But the more intermediaries there are in the network, the longer the delay in quotes updating.
  * The more access a broker has to [liquidity provider](https://www.fintechee.com/services/liquidity-provider/)s, the less slippage in order execution.
  * Honest brokers do not hide their quotes and [liquidity provider](https://www.fintechee.com/services/liquidity-provider/)s.

### Frequently asked questions about quotes

 **1.** Is there a difference between quotes on live and demo accounts?
Yes, there is, although some brokers swear to potential clients that
there is no difference. Some broker [website](https://www.playgroundfx.com/blog/website-for-forex-trading/)s have a warning that the
demo account is intended for perfecting the use of technical tools and
the platform, because the quotes are not the same as the rates (quotes)
of the Forex currencies in the real market. In order not to overload the
servers, brokers deliberately reduce the rate of quotes updating on demo
accounts.

Other brokers assure that live and demo accounts are completely
identical.

  * How to check for discrepancies in quotes. You open two platforms at the same time with a real and demo account. At the time of placing an order, compare quotes for several currency pairs. To avoid wasting money on experiments, use cent accounts with a deposit of several dollars. Please note that the placed orders will also have to be executed in the same way (slippage may occur on a live account).

Differences in quotations are often caused by dishonest brokers
deliberately manipulating the rates. The results of many strategies
depends on a few millimeters of price movement (for example, the price
is two steps away from a stop loss or stop out). It is beneficial for a
broker to create the appearance of success by adjusting rates. While in
the real market the trade would have been closed by stop order, on the
demo account the price reverses to the delight of the trader.

 **2\. Which providers of quotes are the fastest?** Opinions differ:
Integral, Currenex, LMAX. The question of the fastest supplier has been
repeatedly discussed on trading forums and there is no right answer due
to several factors:

  * Proximity to server and exchange. The closer the trader is to the quotes distribution server, the faster they get the quotes.
  * Protocol for overlapping orders: FOK (fill or kill) or IOC (immediate or cancel), which in turn affects the execution queue and slippage, determining the rate of change of quotes.
  * Technical capabilities of the broker’s and trader’s software.

 **3\. What is the importance of the accuracy of the broker's quotes and
[how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) check it?** The accuracy of quotes affects the trading results.
For example, the price is in the channel for some time, suddenly breaks
through the channel boundaries, touches the stop loss and returns to the
previous level. Question: was everything ok with the quotes?

Another example: to test a strategy, you upload the [history](https://www.fixpro.org/post/chargeless-historical-data-api-backtesting/) of defective
quotes - the quotes with gaps for certain periods of time. Tell me,
would you trust the results of such testing without knowing how the
price behaved within the missed period? I wouldn’t.

How to check the accuracy of quotes:

  * Compare Forex quotes of several brokers online by opening terminals or their web versions. However, the result is not guaranteed since differences in rates may be of a local (temporary) nature.
  * Download quotes of several brokers from their terminals in Excel (more about [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) do it below). Find discrepancies using basic formulas. Advantages of this method: you will immediately see the discrepancies for the past periods, when these discrepancies appeared and how large they were. The only problem is in choosing the standard of quotations (what you compare them to).
  * Test the trading system with the same parameters by loading quotes from different sources.
  * Download an archive of quotes or compare current quotes directly with [liquidity provider](https://www.fintechee.com/services/liquidity-provider/)s in the ECN system. For example, on the [website](https://www.playgroundfx.com/blog/website-for-forex-trading/) of Bloomberg agency, Dukascopy bank, etc. Avoid using informers, investment [website](https://www.playgroundfx.com/blog/website-for-forex-trading/)s, etc. - they advertise in order to increase traffic and the accuracy of their quotes is questionable.

Problems with the accuracy of quotes can occur in two cases: a delay in
the rate update or manipulation by a broker. The broker will not bother
with a trader with a small deposit - this is not worth the reputation.
The discrepancies in quotes for a trader with a large deposit can be
explained by a technical failure. If you ahve are doubts - look for the
archive of quotes, compare online Forex quotes and draw conclusions.

### How to download Forex quotes in MT4 or export them to Excel

 **1\. Downloading quotes in MT4.** In MT4, click "Service - Quotes
Archive". Select the desired currency pair and timeframe, click
"Download". The data is automatically downloaded from the [website](https://www.playgroundfx.com/blog/website-for-forex-trading/) of MT4
developer MetaQuotes.

 **![LiteForex: Forex quotes and their providers. Accuracy of
quotes][2]**

The period is specified in the "Service - Options - Charts" menu, where
you need to set the number of [history](https://www.fixpro.org/post/chargeless-historical-data-api-backtesting/) bars.

 **2\. Import the quotes archive downloaded from other resources to
MT4.** Download only minute quotes because they are the most detailed
and accurate.

Where to find the most accurate quotes? Many forums recommend
www.truefx.com. According to them, they deliver quotes that are directly
formed in the ECN-system Integral.

 **3\. Upload quotes from MT4 to Excel.** In the previous screenshot,
there is an "Export" button. We unload the data, open it in a
spreadsheet editor. In Excel all seven columns are uploaded in one cell.
We do the following:

  * In Excel, click "Data", then in the top menu on the left find the "From Text" tab, import the file unloaded from MT4.
  * Select "With delimiters", select a character as a delimiter (comma).
  * Choosing a column format. That's it, the file is ready.

Now we transfer quotes from other sources to the same format, and move
the data into the main file by date through the VLOOKUP function. By
subtracting the cells, we find the divergence in quotes.

### What is [arbitrage](https://www.playgroundfx.com/blog/arbitrage-bot-bitcoin/) trading on Forex? Learning to make money on the
difference in quotes

Imagine you have $110. You come to the exchange office and buy 100 euros
at the EUR/USD sell rate = 1.1000. While walking back home, in another
exchange office you see the buy rate (Important! It’s the buy rate, it’s
always lower) [EUR/USD][3] = 1.110. You sell your €100 and get $111.
Your profit was $1. Now you can return to the first exchange office for
another 100 euros. Congratulations, you've made an [arbitrage](https://www.playgroundfx.com/blog/arbitrage-bot-bitcoin/) trade.

Alas, in reality you cannot earn by walking between exchange offices,
otherwise everyone would be able to make money on such a simple
speculation. None of the exchange rates quoted by exchangers will ever
be higher than the selling rates of another exchanger. Forex is a
different matter:

  * Here trading is carried out on exchanges around the world, on a much larger scale.
  * Here quotes are formed by the ratio of supply and demand and change every fraction of a second. For comparison, banking rates for the population are often set every day (they can change several times during the day, but not every second).
  * Many intermediaries are involved in the data transmission system. Before the information flow reaches the trader and is converted into numbers in MT4, it is sent from [liquidity provider](https://www.fintechee.com/services/liquidity-provider/)s through a series of servers, including the broker's servers. It takes time.

Some things are possible on Forex that do not happen in the system of
bank quotations. Competition dictates brokers to set tight spreads. Some
of the brokers (and therefore traders) get information earlier, some
later because of the technical and software capabilities. This is why
sometimes for a few seconds, the sell price of one broker is higher than
the buy price of another broker. Forex does not have a single center -
the difference in quotes for the same currency pair can even be on
different exchanges. And you can use this!

 **Classic [arbitrage](https://www.playgroundfx.com/blog/arbitrage-bot-bitcoin/) trading looks like this:**

  * At 13:05, quotes on 2 exchanges for one currency pair were the same. The trader discovers that at 13:06 on one exchange the quotes for a currency pair rose, for example, to 1.2565, on the other – to 1.2555. The difference is 10 points.
  * A trader opens a buy trade at a lower price, and a sell trade at a higher price. The difference between quotes must be greater than the spread of both brokers (i.e. double spread). The volume of both trades is equal.
  * As soon as the prices arrive at the same value, the trader closes both positions.

Opening two opposite trades with the same volume is called locking.
There are two open positions for the following reason: in theory, the
lagging price should go up, but the second option is also possible - the
leading quotes will return to the lagging ones. In the case of two
opposite trades, the trader loses only on the additional spread, but in
any case earns on the leveling of prices.

There is another type of [arbitrage](https://www.playgroundfx.com/blog/arbitrage-bot-bitcoin/) trading - cross-platform trading. You
need to find two brokers whose quotes are lagging relative to each
other. There will be one leading broker and the second lagging broker.
Trades are opened on different platforms according to the principle
described above, using software that will automatically track price
differences. You only need to find honest brokers.

The advantage of trading on differences in currency rates is that there
is no risk - the trader knows in advance where the lagging price will
go. Another advantage is that you need neither fundamental nor technical
analysis, although the greatest discrepancies in quotes happen precisely
at the moments of sharp surges in trading activity ([news](https://www.letsplayfx.com/blog/forex-news-website/) release).

 **Disadvantages of trading with an [arbitrage](https://www.playgroundfx.com/blog/arbitrage-bot-bitcoin/) strategy:**

  * Relatively low income. The difference between currency rates in Forex is small, but this is not even the problem. To compensate for the costs (brokerage, transaction and withdrawal fees), a trader needs to do several dozen or even hundreds of trades. Is it worth it? It’s up to you to decide.
  * Emotional load. The trader is forced to constantly look for divergence of rates to make money on them. Do you want to sit at the monitor for days and not just watch the chart, but actively search through dozens of quotes?
  * Arbitrage cases last a few seconds and during this time you need to detect the discrepancy and also make a trade. You can always use a script or a [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/), but will they be effective?
  * The characteristics of servers, platforms and other technical tools are improving every day. The speed of information transfer is already so high that discrepancies in quotations happen less frequently.
  * Brokers are familiar with the [arbitrage](https://www.playgroundfx.com/blog/arbitrage-bot-bitcoin/) technology and not all of them like it, so they set restrictions: they include the conditions of the minimum trade time in the offer, increase the spread, etc.

My opinion: [arbitrage](https://www.playgroundfx.com/blog/arbitrage-bot-bitcoin/) trading is not worth the effort and time. But it
exists and there are those who make money with it. Whether you should
use it is up to you, but I hope the information was useful to you.

 **Conclusion.** For some reason, beginner traders neglect the
importance of the accuracy of quotes, although their comparison can tell
a lot about the honesty of the broker. Also, the accuracy of quotes is
important in the formation of a trading system: where you set a stop
loss or take profit, where the key resistance and support levels are,
etc. No less important is the accuracy of Forex currency quotes when
testing strategies and indicators. I hope this review was helpful to
you. Do you have questions or tips? Let’s discuss in the comments!

* * *

P.S. Did you like my article? Share it in social networks: it will be
the best “thank you" :)

Ask me questions and comment below. I’ll be glad to answer your
questions and give necessary explanations.

 **Useful links:**

  * I recommend trying to trade with a reliable broker [here][4]. The system allows you to trade by yourself or copy successful traders from all across the globe.
  * Use my promo-code BLOG for getting deposit bonus 50% on LiteForex platform. Just enter this code in the appropriate field while [depositing][5] your trading account.
  * Telegram channel with high-quality analytics, Forex reviews, training articles, and other useful things for traders <t.me/liteforex>

![Forex Quotes][6]

The content of this article reflects the author’s opinion and does not
necessarily reflect the official position of LiteForex. The material
published on this page is provided for informational purposes only and
should not be considered as the provision of investment advice for the
purposes of Directive 2004/39/EC.

Rate this article:

{{value}}

( {{count}} {{title}} )

   1. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Forex-Quotes/Quote-en-1.jpg?w=30&s=f9db306696040cc090379fe043a2b823
   2. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Forex-Quotes/Quote-en-2.jpg?w=30&s=3244bc12bacea7cdefe1ac60fdeb4e1d
   3. my.liteforex.com/trading/chart?symbol=EURUSD
   4. my.liteforex.com/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=forex-quotes&openPopup=%2Fregistration%2Fpopup&utm_source=blog&utm_medium=article&utm_campaign=bonus
   5. my.liteforex.com/deposit/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=forex-quotes&promo_code=BLOG&utm_source=blog&utm_medium=article&utm_campaign=bonus
   6. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/Forex-Quotes/Forex-Quotes.jpg?q=75&w=1000&s=ec8255733b8c4d604a1e5e5044dccee7