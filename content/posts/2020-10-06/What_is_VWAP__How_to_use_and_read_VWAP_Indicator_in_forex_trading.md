+++
categories = ["Cryptocurrency", "Blockchain", "SmartContract"]
date = "2020-10-06"
description = "What is VWAP? How to use and read VWAP Indicator in forex trading"
tags = ["Cryptocurrency", "Blockchain", "SmartContract"]
title = "What is VWAP? How to use and read VWAP Indicator in forex trading"
type = "post"
+++

{{<iframe id="large-banner" src="https://www.bounty.group/#slide=8.0" width="100%" height="600" scrolling="no" style="border: 0px solid rgb(216, 221, 230); border-radius: 3px;">}}

2020-10-06

2020-10-06

VWAP Indicator: what is VWAP in trading and [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) use itOleg Tkachenko

Moving average is the simplest and most popular indicator, one of the
basic tools in any trading platform. Dozens of basic and combined
indicators are built on their basis. For example, classic Bollinger
Bands are, in fact, the very same moving averages with a standard
deviation in the formula, which are located on both sides of the price
and form a channel. And yet, like any other indicators, the moving
averages are not without drawbacks: they calculate the average price
based on the prices of separate time frames but do not take into account
trading volumes in them. The attempts to improve this basic tool
resulted in the appearance of exponential moving averages, LWMA, WMA,
and other varieties of this tool.

The article covers the following subjects:

## What is VWAP?

VWAP (Volume Weighted Average Price) is one of such derived indicators
that takes trading volumes into account when averaging prices. VWAP is
the abbreviation of the volume-weighted average price. Let’s look at
this indicator in more detail.

## VWAP indicator as an alternative to the moving averages

### Description and practical application of a VWAP trading strategy

First, let me remind you what the moving average is:

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

 **VWAP calculation**

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
(for example, packages from [Volfix][1]). Beginners and medium-level
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

### Free vwap indicator

VWAP has several versions, but most of them are fee-based. A simplified
version of VWAP indicator MT4 with a minimum of settings can be
[downloaded here][2]. To add the indicator to the platform, in the MT4
top menu, click “File / Open Data Catalog”, go to the MQL4 / Indicators
folder and copy the indicator file there. Restart MT4, the indicator
will appear in the "Insert / Indicator / Custom" submenu.

This is the simplest way to install mql4 VWAP indicator.

### Forex VWAP Indicator Signals

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
template [here][3] with deviation parameters for [MT5][4].

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

 **Условия открытия длинной/короткой позиции:**

  * Таймфрейм D1: текущая свеча после смены направления тренда закрывается выше/ниже линии индикатора VWAP. Выше - предварительный сигнал на открытие длинной позиции, ниже - короткой.

  * Таймфрейм Н1: текущая свеча после смены направления тренда закрывается выше/ниже линии индикатора VWAP.

Сделка открывается только один раз в день. Если внутри дня появляется
второй сигнал, то он игнорируется.

Длина стопа в пределах 30 пунктов по 4-хзначным котировкам или рядом с
уровнем локального экстремума. Сделка открывается на таймфрейме Н1 на
следующей свече после сигнальной. Целевой уровень прибыли - 20-30
пунктов, после чего стоп-лосс устанавливается на уровень безубытка, 50%
прибыли фиксируется, оставшаяся часть сделки страхуется трейлингом (есть
риск отключения интернета или обрыва связи, во время которых трейлинг не
работает - [воспользуйтесь услугой аренды VPS-сервера][5]).

Ложные сигналы в этой стратегии встречаются, но их причина по большей
части в фундаментальном факторе.

 **Пример 1.**

На дневном таймфрейме наблюдаем следующую картину. Индикатор VWAP
длительное время находился под ценой, что говорит о восходящем тренде.
Далее цена меняет направление, но белая спадающая свеча только лишь
касается VWAP (зеленая стрелка), сигналом это не является по двум
причинам:

Свеча, на которую указывает желтая стрелка - спадающая и при смене
направления тренда закрывается ниже линии индикатора VWAP. Она
соответствует дню 16.06.2020. Переходим на график Н1 и на следующем дне
17.06.2020 ищем сигнал на открытие короткой позиции.

Сигнальная свеча, которая пересекает VWAP и закрывается ниже индикатора,
появляется в 10.00. На следующей свече, обозначенной желтой стрелкой,
открываем короткую позицию. Цена открытия составила бы 1.12666, цена
закрытия сделки по трейлингу длиной 20 пунктов - 1.12447, прибыль - 22
пункта.

 **Пример 2.**

Предыдущий пример был рассмотрен на примере сигнала, появившегося на
дневном таймфрейме в июне. «Откатимся» по истории на месяц назад к маю,
где видны два противоположных сигнала. В первом случае виден выделенный
голубым прямоугольником растущий тренд, после чего происходит смена его
направления и сигнальная свеча (желтая стрелка) закрывается ниже линии
VWAP. Свеча соответствует дате 05.05.2020, следовательно сигнал на
открытие сделки будем искать на часовом таймфрейме 06.06.2020. Во втором
случае (зеленая стрелка) закрытие растущей свечи после смены направления
тренда происходит 18.05.2020.

Открытие сделки на часовом интервале для первого случая:

Здесь сделку можно открывать на любой свече в указанном голубым
прямоугольником диапазоне. Сигнальной является свеча, которая закрылась
ровно в полночь, потому уже на следующей свече можно было бы открывать
сделку. Для надежности можно дождаться нескольких спадающих свечей
подряд. При открытии сделки на свече, на которую указывает стрелка
(консервативная стратегия) и установке трейлинга длинной 20 пунктов
прибыль составила бы 20 пунктов. Стратегия с большем уровнем риска
предусматривает более ранее открытие сделки.

Открытие сделки на часовом интервале для второго случая:

Здесь сигнальная свеча в сторону роста цены закрывается с индикатором
VWAP на одном уровне. В теории это слабый сигнал и стоило бы дождаться
закрытой следующей свечи выше линии VWAP (желтая стрелка), но трейдинг -
это всегда риск, который порой оказывается оправданным.

Несмотря на то, что VWAP в сравнении со скользящими более чувствителен к
цене, его недостаток, как и у МА - запаздывание. Как и средние
скользящие, VWAP скорее вспомогательный, подтверждающий трендовые
сигналы. Он редко используется самостоятельно и не является прогнозным.
Инструмент используется исключительно во внутридневных стратегиях. И
хотя на длинные таймфреймы VWAP накладывать никто не запрещает, его
сигналы теряют свою точность.

Заинтересовали бесплатные версии индикатора? Тогда протестируйте его на
демо-счете. И если он у вас еще не открыт, то сделать это можно за 2
минуты. Нажмите на кнопку «Регистрация» в правом верхнем углу на сайте
брокера (доступна независимо от того, на какой вкладке вы находитесь).

Go to MT4 from your Personal Account (you can learn more about the
LiteForex account [functions](https://www.fintechee.com/tutorial-for-forex-trading/basic-functions/) [here][6]), download, install the template
in accordance with the instructions from the review, test the indicator
and be sure to share your opinion about it in the comments!

In conclusion, a few words about how else you can benefit from working
with LiteForex:

  * LiteForex is an ECN broker that transfers trades directly to virtual ECN systems. This ensures a minimum spread, as well as the order execution speed up to 100 ms (the average market speed is 300-400 ms).
  * In addition to the usual platforms, LiteForex also offers its own very easy-to-use browser platform powered by MataTrader with an integrated copy trading system. Read more about the benefits of social trading and working with the platform in the review “[How to make more money in the foreign exchange market: passive income for a successful [investor](https://www.fintechee.com/tutorial-for-forex-trading/investor-mode/)][7]”.
  * Psss! Now there’s a unique opportunity to get cool prizes (a house and a car among them) on the occasion of the 15th anniversary of the company. Read more about participating in the draw [here][8].

## VWAP trading indicator. Conclusions

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

  * I recommend trying to trade with a reliable broker [here][9]. The system allows you to trade by yourself or copy successful traders from all across the globe.
  * Use my promo-code BLOG for getting deposit bonus 50% on LiteForex platform. Just enter this code in the appropriate field while [depositing][10] your trading account.
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

   1. volfix.net/
   2. drive.google.com/file/d/1JRZdhkmI_uN9jagFE3eJ_zTko39VZDNR/view
   3. drive.google.com/file/d/1l1K8vmbRfjrcDvhQljdJCJ6iMrEW05WW/view
   4. lite.forex/downloads/mt5/
   5. ru.liteforex.com/trading/additional-services/vps-services/
   6. www.liteforex.com/blog/for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)/lets-look-into-liteforexs-new-client-space/
   7. www.liteforex.com/blog/for-professionals/combined-strategies-to-make-money-on-forex/
   8. lite.forex/contests/dream-draw/
   9. my.liteforex.com/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=best-technical-indicators&slug2=vwap-indicator-what-is-vwap-in-trading-and-how-to-use-it&openPopup=%2Fregistration%2Fpopup&utm_source=blog&utm_medium=article&utm_campaign=bonus
   10. my.liteforex.com/deposit/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=best-technical-indicators&slug2=vwap-indicator-what-is-vwap-in-trading-and-how-to-use-it&promo_code=BLOG&utm_source=blog&utm_medium=article&utm_campaign=bonus