+++
categories = ["Cryptocurrency", "Blockchain", "SmartContract"]
date = "2021-10-08"
description = "What types of forex brokers exist? What is the difference between A-Book and B-Book brokers?"
tags = ["Cryptocurrency", "Blockchain", "SmartContract"]
title = "What types of forex brokers exist? What is the difference between A-Book and B-Book brokers?"
type = "post"
+++

{{<iframe id="large-banner" src="https://www.bounty.group/#slide=21.0" width="100%" height="600" scrolling="no" style="border: 0px solid rgb(216, 221, 230); border-radius: 3px;">}}

2021-10-08

2021-10-08

Forex Broker Types. A-Book and B-BookOleg Tkachenko

It is essential to understand the difference between different types of
Forex brokers to succeed in trading.

Many brokers present themselves as ECN brokers (the A-Book model), but
it is clear from their trading conditions that they are not connected
with Electronic Communication Network.

Other brokers present themselves as STP, being in fact common Dealing
Desks or kitchens. After all, a B-Book kitchen scheme does not always
mean a scam, so do not hurry to put labels.

This article deals with different types of order processing models. I
will explain A-Book and B-Book models, the difference between them, and
why the B-Book is not always bad. You will also learn the difference
between DD and NDD brokers and get acquainted with NDD order processing
sub- types – STP, ECN, DMA, and MTF. I hope it will help you choose a
reliable broker.

The article covers the following subjects:

## What types of Forex brokers and order execution models exist?

Have you ever thought about how Forex trades are executed? From the
trader's point of view, it looks quite simple. You only need to click on
the button to open an order, and a confirmation of the transaction
appears on the screen.

But who is the counterparty for this trade? Is trade carried out at all?
What determines the transaction execution speed?

There are two types of broker operation mode, A-Book and B-Book models.
These models transfer the client orders to the interbank forex market in
entirely different ways.

Moreover, the A-Book and B-Book models utilize different technologies of
order execution, depending on the sub-type, MM, NDD, STP, ECN, DMA, MTF.

They also have different operation technologies: ECN-systems and MTF-
systems.

Let us explore all these complicated abbreviations. It won’t be easy,
but it will be very informative!

### A-Book and B-Book models of managing client’s orders

To execute a transaction, there must be a counterparty in the foreign
exchange. If someone buys an asset, then someone must sell it. A-Book
and B-Books models differ in [terms](https://www.fintechee.com/terms/) of the counterparty and its source:

  * A-Book brokers forward the trading orders to the [liquidity provider](https://www.fintechee.com/services/liquidity-provider/), which then redirects them to the interbank market. The broker's earnings are commissions for a fixed volume of transactions (as a rule, for 1 lot) or a markup on a spread. The broker in this scheme is only an intermediary; the final counterparty to the transaction is also a trader, whose opposite trades are in the interbank market or a [liquidity provider](https://www.fintechee.com/services/liquidity-provider/). 

  * B-Book brokers process their clients’ orders in house and act as market makers. There is no external liquidity pool, as the broker executes trades internally. The B-Book model is also called a kitchen, but everything is not that simple.

There is no conflict of interest in the A-Book model. The broker is just
an intermediary in providing financial services. Such a broker will
benefit if the trader increases trading volume and turnover, as the
commission charged by the broker will also increase.

The B-Books model is often associated with a scam, as the broker acts as
the counterparty to fill the trader’s order. Obviously, there arises a
conflict of interests; the broker is not only an intermediary but also a
counterparty. Therefore, the company could set non-market quotes in the
terminal, see the client stop-loss orders through the MT4 added
software, and trigger stops with the plugins in the server part of the
platform. Thus, such a broker could do everything to make the trader
lose the money.

However, many brokers use the B-Books and do not even hide it. The
matter is that to bring client orders to the external market, brokers
need to make contracts with a [liquidity provider](https://www.fintechee.com/services/liquidity-provider/) (and, as a rule, not
just one), obtain licenses, provide technological support. All these are
costs that the A-Book broker compensates at the expense of high mark-up
to the spread.

That is, the A-Book broker can’t compete with the B-Book one in [terms](https://www.fintechee.com/terms/) of
costs. Traders, in turn, do not really understand all these models,
preferring more favorable conditions, thereby encouraging the activity
of such kitchens.

> Important! If a broker utilizes the B-Book model, it doesn't
necessarily mean that it is a kitchen (although such a probability is
high). This may indicate that the broker fills small transactions within
its platform. In contrast, large transactions, individually or in a
pool, can be transferred to the [liquidity provider](https://www.fintechee.com/services/liquidity-provider/) and then to the
interbank market Forex. This is the so-called the hybrid of A-Book and
B-Book models. An example of such a model is a combination of cent
(B-Book) and ECN (A-Book) accounts. There is no conflict of interest in
this model since the broker does not act as a counterparty to
transactions.

Pure B-Book brokers are far less reliable. Compared with the volumes of
interbank transactions, the internal volumes on the broker's platform
are too small.

If a large client places a large order within the system, the broker
will have to either act as a counterparty or allow slippage. Both
variants are the features of a kitchen, which do not promise anything
good to a trader. That is why you’d better avoid pure B-Book brokers.

You can learn more about Forex trades processing mechanisms, types of
order execution, such as Market Execution and Instant Execution, as well
as the A-Book and B-Book models[ in this article][1]. I will deal in
more detail with the principles of transactions transfer to the
interbank market based on the A-Book model and the hybrid scheme.

## How do A-Book and B-Book brokers work?

### 1\. B-Book brokers: DD (Dealing Desk) and MM (Market Maker) models

The counterparty to the trade is a market maker, which tries to find a
matching order from its other clients (if the trader wants to buy 1 lot,
the broker looks for someone who will sell 1 lot). If there is no such
an order, the market maker acts as a counterparty, thereby arising a
conflict of interests. In this case, the trade’s loss becomes the market
maker’s profit. If the trader makes a profit, the market maker can
redirect the order to the liquidity [aggregator](https://www.fintechee.com/features/price-aggregator/), also referred to as the
[liquidity provider](https://www.fintechee.com/services/liquidity-provider/).

DD brokers, market makers, Dealing Desk brokers – all these mean the
same counterparty, which takes the other side of the client’s trade,
executing almost all the trades with its internal system. Dealing Desk
brokers create a market for the client, serving as market makers. A
Dealing Desk can change the leverage, spread, affect the accuracy of the
quotes, artificially increase slippage, manipulate client’s orders. A
pure Dealing Desk is a kitchen.

### 2\. A-Book: NDD (No Dealing Desk) model

A-Books brokers pass the client’s orders to the interbank market. An NDD
broker does not take the other side of their clients’ trade; they serve
as an intermediary, linking two parties. The broker charges a commission
or puts a markup, slightly increasing the spread. Differently put:

  * If the broker doesn’t pass trades to the interbank market, it is a Dealing Desk which can be equated to a kitchen. Here is an important moment – even if such a broker has a license. A B-Book license grants the broker the right to fill the orders of their clients within the system. Of course, a license means the broker is controlled by a regulatory body.

  * If the broker passes the client’s trades to the interbank market, it is an NDD broker, serving as an intermediary and applying the A-Book model. If a broker has an A-Book license, it means the regulator monitors that all transactions are passed through the software into the interbank market. 

Traders in the interbank market are conventionally divided into two
groups: Price Giver and Price Taker. The Price Giver is the one who
creates a market offer, that is, places an order (for example, a large
institutional [investor](https://www.fintechee.com/tutorial-for-forex-trading/investor-mode/)).

The Price Taker is the one who fills the Price Giver’s order.
Differently put, a Price Giver places an order in the interbank market
indicating the purchase volume in lots and the price at which it is
ready to buy/sell the asset. The order enters the Depth of Market, Price
Taker accepts the most suitable order for it (at the best price and
sufficient volume), entering into a deal with Price Giver.

There are several types of order execution in the market.

### 2.1. Order processing model NDD + STP  (Straight Through Processing)

Brokers using this model route their clients’ orders directly to their
[liquidity provider](https://www.fintechee.com/services/liquidity-provider/)s who have access to the interbank market. The Price
Giver is the [liquidity provider](https://www.fintechee.com/services/liquidity-provider/) (any [investor](https://www.fintechee.com/tutorial-for-forex-trading/investor-mode/) working with a large
capital: banks, funds, and so on), which sends the orders to the
interbank market. Traders see the [liquidity provider](https://www.fintechee.com/services/liquidity-provider/)’s prices in the
Depth of Market, send their opposite orders through the broker, and the
orders are instantly executed provided all conditions match.

 Order execution process:

  * The trader (Price Taker) sees in the trading platform the current price, formed in the interbank market (broker obtains it through the quotes provider), and places an order.

  * The broker passes the trader’s order to the liquidity [aggregator](https://www.fintechee.com/features/price-aggregator/), which picks up (accumulates) the orders of all Price Takers and routes them to the [liquidity provider](https://www.fintechee.com/services/liquidity-provider/).

  * A counterparty fills the orders. 

In this model, traders are one party to the transaction. Large
[aggregator](https://www.fintechee.com/features/price-aggregator/)s (usually banks) are the other one, a broker is an
intermediary for traders, an [aggregator](https://www.fintechee.com/features/price-aggregator/) is a participant that collects
orders from brokers.

Each broker can work with an unlimited number of [aggregator](https://www.fintechee.com/features/price-aggregator/)s and
[liquidity provider](https://www.fintechee.com/services/liquidity-provider/)s. The [terms](https://www.fintechee.com/terms/) of the partnership will depend on the
order execution speed, spread, and commission. There are several flaws
in this scheme, which are easier to show with examples.

1.  A broker has two counterparties ([liquidity provider](https://www.fintechee.com/services/liquidity-provider/)s). One offers a
3-pip spread with a commission of $15 per lot. Another liquidity
provider offers a 5-pip spread and charges a commission of $10. The
broker system sorts traders’ offers automatically at the best prices for
financial instruments. So, the broker first pays the commission, and
there arises a problem. Most of the turnover goes to the liquidity
provider with a narrower spread, which is why the broker loses $5. To
solve this problem, the broker adds 2-pip markup to the spread of the
first [liquidity provider](https://www.fintechee.com/services/liquidity-provider/), thereby distributing the trades between the
counterparties equally.

On the one hand, such a model encourages competition between liquidity
providers, thus narrowing the spread and reducing the commission fees.
On the other hand, traders do not receive the best price because of the
mark-up added to the spread. Another problem is that the quality of the
services offered by [liquidity provider](https://www.fintechee.com/services/liquidity-provider/)s is deteriorating over time. The
order execution quality lowers, there emerge slippages.

The trader, of course, blames the broker for everything. Therefore, the
broker is forced to use software to track such tricks of the provider.
According to representatives of a large brokerage company, this practice
occurs even at the "highest Forex levels”. Sometimes it is enough to
inform the provider about the breach of contract. Sometimes brokers have
to look for a new provider.

2\. A vivid example is the case of the British subsidiary of a well-
known broker that employed the STP model, and due to which it became
bankrupt in one day. The agent's work scheme was as follows: a trader
opens a position in the MT, the broker opens the same position with a
[liquidity provider](https://www.fintechee.com/services/liquidity-provider/) ([aggregator](https://www.fintechee.com/features/price-aggregator/)). That is, instead of being an
independent technical intermediary, the broker acted as a participant in
the transaction. And then, at one point, the Swiss Central Bank unpegged
the franc. In just one day, the traders’ long positions on the
[EUR/CHF][2] pair went into negative territory. Accordingly, the
positions of the broker itself yielded losses, forming a cash gap. Due
to segregated accounts, traders received about 80% of their funds back,
and the broker was forced to declare bankruptcy.

There were numerous cases of bankruptcy after the SNB unpegged the franc
from the euro. Therefore, today the pure STP model is rare, although
some brokers continue to focus on it.

### 2.2. NDD + ECN (Electronic Community Network)

The [ECN][3] model provides equal rights for all traders and liquidity
providers. In the STP model, the conditions were largely imposed to the
trader by a particular provider. The ECN is a kind of platform where
everyone places Bid/Ask orders that affect the market liquidity.

The ECN differs from the STP in the way trades are filled. In the ECN
model, traders can trade with each other. Conversely, in the EST model,
the trader has to match the offer of a particular [liquidity provider](https://www.fintechee.com/services/liquidity-provider/)
(only the one with which the broker has an agreement).

In the ECN model, each [individual trader](https://www.fintechee.com/services/individual-trader/) acts both as a Price Giver and
a Price Taker. In the STP model, a trader sees only market makers’
orders in the Depth of Market, while in the ECN model, there are all
existing orders with prices and volumes.

> Reference. The Depth of Market is a tool reflecting the information on
orders placed by sellers and buyers at the current time. The trader sees
prices and volumes of orders, which suggest a kind of market sentiment.
The Depth of Market of level 1 displays the data on the best prices. The
Depth of Market of level 2 provides complete information on all orders
placed.

If there is no DOM of level 2, which can be used to assess supply/demand
and the further direction of the price, you do not deal with an ECN
broker. At best, it is an STP, at worst - a DD (B-Book).

ECN order execution model:

  * A trader in the platform sees the current price generated in the interbank market and opens a position (creates an order).

  * The broker passes the order to the ECN system (the ECN platform) to the DOM, where the trader could monitor the order, and other traders’ orders with volumes. 

  * The platform automatically sorts out the orders according to the price.

  * Due to the liquidity within the network (the platform unites all [liquidity provider](https://www.fintechee.com/services/liquidity-provider/)s and their traders, which is not the case in the STP model), matching orders are executed instantly. The order execution speed can be 40-100 milliseconds (500 ms is the average speed in the ECN market).

The advantage of the ECN model compared to the STP is the number of
participants (both traders and [liquidity provider](https://www.fintechee.com/services/liquidity-provider/)s). The more
participants, the more liquidity (trade volumes) and the narrower is the
spread. Each participant tries to offer the best price, and all traders
get the best current Bid/Ask price. At the moments of the [EURUSD][4]
highest liquidity, the spread could be around zero level, however, there
can’t be literally zero spread.

The ECN system is another market participant, intermediary providing the
technological ability to process orders. The broker can create its own
ECN system, but then it becomes senseless, as there will be a relatively
small number of participants.

### 2.3. NDD + ECN + STP hybrid execution model

The A-Book hybrid [Forex broker](https://www.playgroundfx.com/blog/best-forex-broker-for-beginners/) model is one of the most common ways of
technological support for trades execution employed by large brokerage
companies. ECN/STP brokers are the brokers that combine both models
without prioritization, focusing on the speed of finding a matching
trade.

But ECN/STP brokers cannot be called pure ECN brokers, since they do not
give the trader information about the Depth of Market (its liquidity).
To understand which broker you are working with, you need to place a
Limit order and it should be displayed in the Depth of Market. A pure
ECN broker should have it visible.

### 2.4. DMA (Direct market access) model

DMA, or Direct Market Access, is a type of trade execution where brokers
offer direct access to the interbank, enabling them to place trading
orders with [liquidity provider](https://www.fintechee.com/services/liquidity-provider/)s with the Depth of Market formation. This
execution model combines the benefits of the ECN and STP models.

The transaction processing technology:

  * Trader in the platform sees the current price, generated in the interbank market, and puts an order.

  * A broker passes the order to the [liquidity provider](https://www.fintechee.com/services/liquidity-provider/) offering the best conditions. If it is a Buy/Sell order, it is executed instantly. If it is pending order, it is displayed in the Depth of Market exposed to the trader. 

The difference be is that the ECN is a virtual network where orders of
all market participants are aggregated, sorted and executed. DMA is
similar to STP, where traders' orders are distributed among liquidity
providers.

An intermediate comparative analysis for three major NDD models (I will
not include DD and B-Book models without passing orders to the external
market) is presented in the table below.

Parameter| STP| ECN| DMA  
---|---|---|---  
Type of order execution| Instant Execution, Market Execution| Market
Execution| Market Execution  
Type of spread| Fixed/Variable| Variable| Variable  
Commission| No| High| Moderate  
Counterparty| Individual [liquidity provider](https://www.fintechee.com/services/liquidity-provider/)s| Network participants|
Individual [liquidity provider](https://www.fintechee.com/services/liquidity-provider/)s  
Depth of Market| Missing| Present| Sometimes present  
Entry threshold (minimum deposit)| low| high| medium  
Spread| High/Middle| Low| Middle/Low  
  
## How to distinguish between A-Book and B-Book brokers

Features of A-Book broker for STP, STP, DMA models:

  * Order execution type - Market Execution.

  * Spread is variable. A fixed spread may mean that the broker or the [liquidity provider](https://www.fintechee.com/services/liquidity-provider/) add a commission to the best price.

  * There are no re-quotes (they can rarely be observed only with the STP brokers).

  * Slippages are both in the negative and positive directions.

  * There are no limits to [trading strategies](https://www.fintechee.com/forex-trading-strategies/) employed. ECN brokers encourage high-frequency [trading strategies](https://www.fintechee.com/forex-trading-strategies/) and can provide their server capacities for algo trading. 

### 2.5. MTF (Multilateral Trading Facility)

Multilateral Trading Facility is the most up-to-date system of order
processing and execution, which has a lot in common with the ECN model.
Typical features of an MTF platform:

  * MTF are not counterparties in the order execution chain. Like the ECNs, the MTFs only link market participants irrespective of their status (an [individual trader](https://www.fintechee.com/services/individual-trader/) or a market maker).

  * MTF platforms, unlike the ECNs, do not work with the quotes providers (Reuters, Bloomberg), forming real time quotes based on the supply/demand.

There are discussions on the forums regarding the fundamental difference
between MTF and ECN. If ECN platforms have existed since the 90s, then
the MTF system is often associated with the LMAX platform, which
appeared in 2010. It presents itself either as a Currenex-style platform
or a broker. It seems that LMAX just slightly modified the ECN
technology and called it MTF. Anyway, the ECN model is still the most
widespread and popular in professional trading.

And finally, the most important question. Why do you need to know all
the above? The trader’s profit depends on the spread (its size or type –
fixed or variable), order execution speed and the reliability of the
broker. The quotes in the interbank market change in milliseconds the
price at which the order will be executed depends on how quickly the
trade is transferred to the market.

  * The ECN model has the highest order execution speed. There is a relatively narrow spread here, since there is no margin from the broker, but there is a commission for each traded lot. The technology is considered expensive and difficult to implement. Therefore, this model will be of interest primarily to professionals who value the speed and have volume of trades sufficient to cover the commission.

  * The DMA and STP models will suit forex traders who have just started their career and are gaining the experience. The ECN model provides the confidentiality of the transactions, so large banks are unwilling to offer the best quotes. In DMA and STP models, where the brokers have contracts with specific providers, competition forces the [liquidity provider](https://www.fintechee.com/services/liquidity-provider/)s to offer better [terms](https://www.fintechee.com/terms/). Therefore, in theory, the DMA model should have better spreads compared to ECN. In practice, due to the commission charged, the trading costs in ECN and DMA are relatively the same.

  * The ECN model provides a full market depth. 

I can’t say that the ECN is a perfect model. I wouldn’t say that the STP
or the DMA are the best [Forex broker](https://www.playgroundfx.com/blog/best-forex-broker-for-beginners/) models. Every model has its pros
and cons, in [terms](https://www.fintechee.com/terms/) of order execution speed, trading costs and
slippages. I would recommend trying both models and choosing the one
most suitable for your trading style and trading system.

I personally work with LiteForex. It is a licensed, regulated broker
working on the A-Book hybrid model. Traders have a choice between
classic trading accounts (Classic, STP model) and professional ECN
accounts.

You can learn more about trading conditions provided for both types of
trading accounts [here][3]. ECN specification is [here][5], Classic
account specification is [here][6].

I hope you have at least a general understanding of order execution
models now. If you still have questions, write in the comments, I will
be glad to answer. I wish you success in trading!

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

   1. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/principle-of-orders-execution-at-forex/
   2. my.liteforex.com/trading/chart?symbol=EURCHF
   3. www.liteforex.com/trading/account-types/
   4. my.liteforex.com/trading/chart?symbol=EURUSD&returnUrl=true
   5. www.liteforex.com/trading/account-types/ecn/
   6. www.liteforex.com/trading/account-types/classic/
   7. my.liteforex.com/?category=for-professionals&slug=forex-broker-types-a-book-and-b-book&openPopup=%2Fregistration%2Fpopup&utm_source=blog&utm_medium=article&utm_campaign=bonus
   8. my.liteforex.com/deposit/?category=for-professionals&slug=forex-broker-types-a-book-and-b-book&promo_code=BLOG&utm_source=blog&utm_medium=article&utm_campaign=bonus