+++
categories = ["Cryptocurrency", "Blockchain", "SmartContract"]
date = "2020-06-11"
description = "Quantitative Trading"
tags = ["Cryptocurrency", "Blockchain", "SmartContract"]
title = "Quantitative Trading"
type = "post"
+++

{{<iframe id="large-banner" src="https://www.bounty.group/#slide=26.0" width="100%" height="600" scrolling="no" style="border: 0px solid rgb(216, 221, 230); border-radius: 3px;">}}

June 11, 2020

June 11, 2020

Quantitative TradingOleg Tkachenko

## How to use quantitative [trading strategies](https://www.fintechee.com/forex-trading-strategies/)

Classic trading uses fundamental and technical analysis. Quantitative
[trading strategies](https://www.fintechee.com/forex-trading-strategies/) are a radically different approach that has much in
common with algorithmic trading and [neural network](https://www.fintecher.org/2020/03/17/added-genetic-algorithm-for-trading/)s, some of them have
direct correlation to high-frequency trading. Quant [trading strategies](https://www.fintechee.com/forex-trading-strategies/)
rely on mathematical modeling using software [algorithms](https://www.fintechee.com/algorithms-for-trading/) and statistical
methods. In other words, quant-based [trading strategies](https://www.fintechee.com/forex-trading-strategies/) are [automated](https://www.fintechee.com/features/automated-forex-trading/)
systems written in classical programming languages ​​(C ++, Python,
etc.) using computer programming software such as EViews or MATLAB. Are
they accessible for private traders? This is a rhetorical question. But
you need to know about their existence if only because quant based
[trading strategies](https://www.fintechee.com/forex-trading-strategies/) are used by market makers (hedge funds or investment
banks).

### Quant-based [trading strategies](https://www.fintechee.com/forex-trading-strategies/) as an alternative to technical and
fundamental analysis

Which strategies are more profitable: ones based on technical or
fundamental analysis? Manual strategies or ones that use trading
[advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s? The example of the world's leading investment funds shows that
neither fundamental nor technical analysis meets expectations. However,
there is another trading method - quantitative strategies. In this
review, I will try to outline the essence of this method and show the
main differences from the usual [trading strategies](https://www.fintechee.com/forex-trading-strategies/) based on fundamental
and technical indicators.

>  **Note. Quantitative trading is built on mathematical methods and
statistical analysis using programming. Therefore, the purpose of this
review is to only inform of the existence of such a method. If you have
knowledge of higher mathematics and programming languages ​​(we are not
talking about MQL), try to dig deeper and be sure to share your
experience in the comments!**

### Quantitative trading strategy for a private [investor](https://www.fintechee.com/tutorial-for-forex-trading/investor-mode/): what it is and
[how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) model it

The trader’s job is to determine the direction of the trend and possible
reversal points. It does not matter what tools, strategies or type of
analysis are used for this, as long as it does the trick. You only need
to find reversal points, determine the strength of the trend and enter
the market at its beginning.

  * In fundamental analysis, the trader tries to predict the direction of movement after the [news](https://www.letsplayfx.com/blog/forex-news-website/) or based on wave-like movement of the global economy. The strategy is based on the fact that the market will somehow respond to information, stimulating the growth of demand or supply.

  * In technical analysis, fundamental factors are excluded. The trader analyzes the [history](https://www.fixpro.org/post/chargeless-historical-data-api-backtesting/) and finds patterns. Force majeure and other fundamental factors are automatically taken into account in the general trend.

But there is another trading method that does not involve either
technical or fundamental analysis. For it, predicting the direction of
the trend is a secondary issue, and the releases of the Central Banks
are irrelevant. Currency quotes here are just a set of basic input
market data on which the network machine algorithm is built. This method
is called quantitative trading strategy or quant based trading strategy.

The point of quants [trading strategies](https://www.fintechee.com/forex-trading-strategies/) is not to predict the direction
of the trend, but to find the optimal strategy and the best set of
trading tools by selecting a mathematical set of parameters that will
ultimately allow you to get a stable profit.

### ![LiteForex: Quant trading and Quantitative Trading Strategies][1]

### A bit of [history](https://www.fixpro.org/post/chargeless-historical-data-api-backtesting/) of Quant trading

Despite seeming somewhat pointless, algorithmic trading and quantitative
strategies have been known for more than half a century and actively
used by investment hedge funds.

One of the first companies to apply quant based [trading strategies](https://www.fintechee.com/forex-trading-strategies/) was
the George Soros Foundation. Soros was able to prove in practice that
fundamental and technical analysis are inferior in comparison with the
strength of capital. By having access to insider information and
artificially shaping people’s opinion with the help of the media, he
changed the direction of the trend at his discretion with large volumes,
bringing down the policies of the Central Banks. This is why his fund
was one of the first to give up assessing the monetary [policy](https://www.fintechee.com/policy/) of the
Central Bank and searching for technical patterns in favor of
mathematical modeling and programming.

In 1973, Fischer Black and Myron Scholes first published the option
pricing model formula. The key point in determining the value of the
option was the expected volatility of the underlying asset, the level of
which can be calculated mathematically. Without going into details, the
formula includes the cumulative distribution function of the standard
normal distribution, the risk-free interest rate (we see something
similar in the [Sharpe ratio][2]), spot and strike prices, and
volatility. To characterize the sensitivity of the option price to
changes in certain values, coefficients called greeks (based on the
letters of the Greek alphabet) are used.

In 1997, the Black-Scholes model won the Nobel Prize in economics,
radically changing the approach to developing [trading strategies](https://www.fintechee.com/forex-trading-strategies/). The
yield of 75-80% of transactions based on mathematical analysis has
become a proof of the effectiveness of this technique and was adopted by
market makers and investment banks. Today's real examples of using
quantitative trading models are:

  * Two Sigma Investments - the fund was founded in 2001. Its [trading strategies](https://www.fintechee.com/forex-trading-strategies/) are based on methods using artificial intelligence, machine learning (an analogue of [neural network](https://www.fintecher.org/2020/03/17/added-genetic-algorithm-for-trading/)s), and distributed computing.

  * DE Shaw&Co - the fund was founded in 1988. The company is known for its development of sophisticated modeling systems and programs that track market anomalies.

  * Renaissance Technologies LLC - the company was founded in 1982. It specializes in trading in quantitative models developed on the basis of mathematical and statistical analysis.

There is practically no human involvement in their trading methods.

There is practically no human involvement in their trading methods.

## What is quantitative trading and how it works?

Quantitative trading is based on the principle "the more the better".
The mathematical apparatus allows you to sort through many strategies
for all trading assets, choosing the optimal result of the risk/profit
ratio. In general [terms](https://www.fintechee.com/terms/), the algorithm uses the analysis of a certain
time section, where the values ​​of price quotes are fixed (for example,
closing price). The data obtained are interpreted as follows:

  * As a function. The job of the programmer writing the model code is to find this very function (to build an equation) that would describe the distribution of quotes in a time series.

  * As a time series that is analyzed by statistical methods. The accuracy of forecasting by statistical regularity is tested on other time intervals (forward testing).

The quantitative trader can get some extreme points from the function
and time series that describe the price movement chart. By adding an
additional mathematical apparatus (approximation, entropy), you can
calculate the areas of trend slowdown, flat, or calculate the predicted
stop order points. And only later a quantitative trader may try the
strategy in real time, applying the risk management required.

Another method of econometric analysis on which quantitative trading
strategy is based is to break the time section into separate clusters
(areas where you can see a clear price movement according to a certain
pattern). For example, a section 10 years long, is divided into segments
of different lengths (1 day, 1 week - they do not have to be the same),
on which the pattern is visible. Moreover, the sections can intersect
and overlap each other - a [neural network](https://www.fintecher.org/2020/03/17/added-genetic-algorithm-for-trading/) with algorithmic program code
finds all these sets of patterns. The current market conditions are
compared with similar patterns of price behavior in the past, based on
which a further forecast is made.

## Mandatory conditions for using the quantitative trading strategy:

  * High liquidity. Only highly liquid instruments are selected for quantitative [trading strategies](https://www.fintechee.com/forex-trading-strategies/), therefore this method is more common on [stock markets][3] than on Forex.

  * Diversification. Quant [trading strategies](https://www.fintechee.com/forex-trading-strategies/) involves launching mathematical [algorithms](https://www.fintechee.com/algorithms-for-trading/) for a large number of instruments. It will not work on one currency pair. In this case, the correlation coefficient between instruments should be as low as possible.

  * Quantitative analysis works for the largest possible number of [algorithms](https://www.fintechee.com/algorithms-for-trading/) (three variants of such [algorithms](https://www.fintechee.com/algorithms-for-trading/) - function search, distribution of number series and template trading - are described above).

The model of quantitative strategies has something in common with the
algorithmic [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/) trading. The formula of moving averages attempts to
search for patterns of price movement. And over time, technical analysis
enthusiasts added a series of coefficients to the formula, which became
EMA, LMA, etc. However, the problem remained the same - there are no
ideal tools that would bring 100% income.

Still, forex quantitative trading is not the Grail, but just another
trading method. There are companies involved in the development of such
[algorithms](https://www.fintechee.com/algorithms-for-trading/) and selling the product to [individual trader](https://www.fintechee.com/services/individual-trader/)s. In my opinion,
given the complexity of the product, the need for software support and
the cost, the idea of ​​using quantitative trading systems in private
trading seems unreasonable.

### Conclusion

Quant [trading strategies](https://www.fintechee.com/forex-trading-strategies/) are another attempt to get closer to the Grail
using the methods of mathematical and statistical analysis and
programming. There are a lot of quant traders convinced that this model
works in financial markets much better than technical and fundamental
analysis. But I did not find open information about the profitability of
such strategies.

Quant based [trading strategies](https://www.fintechee.com/forex-trading-strategies/) should only be used for stock market
instruments. Therefore, quantitative [trading strategies](https://www.fintechee.com/forex-trading-strategies/) are used either
for trading securities ([stocks of corporations][4]), or [stock
indices][5].

It’s useful to know about such methods, if only because they may be the
future of [automated](https://www.fintechee.com/features/automated-forex-trading/) trading. If you have experience in using quant
[trading strategies](https://www.fintechee.com/forex-trading-strategies/), be sure to share it in the comments!

* * *

P.S. Did you like my article? Share it in social networks: it will be
the best “thank you" :)

Ask me questions and comment below. I’ll be glad to answer your
questions and give necessary explanations.

 **Useful links:**

  * I recommend trying to trade with a reliable broker [here][6]. The system allows you to trade by yourself or copy successful traders from all across the globe.
  * Use my promo-code BLOG for getting deposit bonus 50% on LiteForex platform. Just enter this code in the appropriate field while [depositing][7] your trading account.
  * Telegram channel with high-quality analytics, Forex reviews, training articles, and other useful things for traders <t.me/liteforex>

![Quantitative Trading][8]

The content of this article reflects the author’s opinion and does not
necessarily reflect the official position of LiteForex. The material
published on this page is provided for informational purposes only and
should not be considered as the provision of investment advice for the
purposes of Directive 2004/39/EC.

Rate this article:

{{value}}

( {{count}} {{title}} )

   1. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/kolichestvennye-strategii-i-kolichestvennyj-trejding/quantitative-trading.png?w=30&s=227136cb942e21352ea1b5218eb38222
   2. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/sharpe-ratio-trading-strategy-evaluation/
   3. my.liteforex.com/?type=cfd
   4. my.liteforex.com/trading?type=cfd
   5. my.liteforex.com/trading?type=index
   6. my.liteforex.com/?category=for-professionals&slug=quantitative-trading&openPopup=%2Fregistration%2Fpopup&utm_source=blog&utm_medium=article&utm_campaign=bonus
   7. my.liteforex.com/deposit/?category=for-professionals&slug=quantitative-trading&promo_code=BLOG&utm_source=blog&utm_medium=article&utm_campaign=bonus
   8. cdn.liteforex.com/cache/uploads/blog_post/blog_posts/kolichestvennye-strategii-i-kolichestvennyj-trejding/quant-trading-liteforex-blog.png?q=75&w=1000&s=ed449fc8982950439d5da082ef4455bb