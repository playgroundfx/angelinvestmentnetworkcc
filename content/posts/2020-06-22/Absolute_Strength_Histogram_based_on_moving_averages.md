+++
categories = ["Cryptocurrency", "Blockchain", "SmartContract"]
date = "2020-06-22"
description = "Absolute Strength Histogram based on moving averages"
tags = ["Cryptocurrency", "Blockchain", "SmartContract"]
title = "Absolute Strength Histogram based on moving averages"
type = "post"
+++

{{<iframe id="large-banner" src="https://www.bounty.group/#slide=25.0" width="100%" height="600" scrolling="no" style="border: 0px solid rgb(216, 221, 230); border-radius: 3px;">}}

June 22, 2020

June 22, 2020

Absolute Strength Histogram: May the trend strength be with usOleg
Tkachenko

## Absolute Strength Histogram: work principle, advantages,
disadvantages, trading signals.

Absolute Strength Histogram is a technical tool that aims at identifying
the current trend and filtering the signals of the main indicator. It
pretty well performs with trend lines. It is not included in the
standard tool kit of the MT4, but it can be downloaded for free from the
Internet, or via the link given below in the article. The indicator
locates under the working price chart , it looks like a histogram with
green and red bars. The bars represent the values of two moving
averages: the slow MA and the fast MA, the distance between the MAs and
the indicator bottom makes up columns. The formula also includes the
indicators of the RSI and a stochastic oscillator.

Based on the location of the moving averages relative to each other, the
histogram bars change their color. Green means a growing trend, red – a
falling one. The change of the bars' color may mean the trend reversal,
which is to be a signal to enter a trade in a new trend.

  * The indicator template for the MT4 can be downloaded for free [via this link][1]. If you do not know [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) install the template on the platform, or Absolute Strength Histogram doesn’t work after the installation, write in the comments. Let us try to solve the problem together!

Basically, the developers did not use any new mathematical [algorithms](https://www.fintechee.com/algorithms-for-trading/) to
create this indicator; therefore, it is not very popular among technical
analysts. And it is unjust.

 **Advantages of the Absolute Strength Histogram indicator:**

  * Convenient visual display.
  * A small number of settings.
  * Relatively good performance.

However, the indicator has a common flaw, it often lags behind the price
movement . Therefore, the recommended timeframe is M15-M30, where time-
lags do not have such a strong influence on anticipating the future
price move. The problem can also be solved by the joint use of the
Absolute Strength Histogram with price predicting indicators or
oscillators. It is not a trend indicator or an oscillator. The Absolute
Strength Histogram is a kind of supplementary tool. So, it is not used
as the main tool, it is rather used to confirm signals delivered by
other indicators to supplement other tools.

 **Parameters of Absolute Strength Histogram**

![LiteForex: Absolute Strength Histogram based on moving averages][2]

 **Absolute Strength Histogram has seven parameters:**

  * Mode. Indicator mode: 0 is the RSI value that is taken as a basis, 1 is the stochastic value. With a default value of zero, the histogram has a “torn” appearance. The columns randomly change the height, which indicates the trend strength. If you set the value 1 in this section, the histogram will take a smooth appearance. There are screenshots for comparison below:

![LiteForex: Absolute Strength Histogram based on moving averages][3]

This figure displays the indicator with the value of zero

![LiteForex: Absolute Strength Histogram based on moving averages][4]

This figure displays the indicator with the value of zero. Pay attention
that, in addition to smoothing, there is a clear shift of extremes.

  *  **Length.** It is the number of bars moving average calculated. The default value is 9 but as the indicator tests show, with this value the number of false signals is significantly higher than the number of valid ones. The greater is this value in the settings, the less frequent are the signals of the indicator, but they are more likely to be accurate. Also, the greater is the value of the parameter, the more smoothed it is. It is recommended to set the value of at least 20-30.
  *  **Smooth.** Smoothing period. It is not recommended to change the default value of 1.
  *  **Signal.** The period of the indicator signal line.
  *  **Price.** The type of average price to be used in indicator calculations (0 - close, 1 - open, 2 - high, 3 - low, 4 - median, 5 - typical, 6 - weighted). By default, it analyzes closing prices.
  *  **ModeMA.** It is the mode of MA. An accepted value is from 0 to 3.
  *  **Mode_Histo.** It influences the histogram display. Leave the default value of 3.

You can find the values of the parameters in the indicator code.

 **Absolute Strength Histogram signals (theory)**

![LiteForex: Absolute Strength Histogram based on moving averages][5]

Absolute Strength Histogram entry signal is when the column changes its
color. If the column goes red, it is a sell signal, it changes to green,
it is a buy signal. The recommended distance for a stop loss is 15-20
points.

It seems easy, but there is a peculiarity that should be taken into
account when you employ this indicator. If a new column is repainted in
green, it must be higher than the previous red column. Otherwise, the
signal can be considered false and it is better not to enter a trade
based on it.

![LiteForex: Absolute Strength Histogram based on moving averages][6]

The same is with the sell signal. A new red column should be higher than
the previous green one.

It is a bit more complex with the exit signals. Basically, the exit
point should be at the peak of the histogram of a particular color; but,
if the histogram goes on painting the columns of a particular color but
a little lower than the previous ones, it can be considered as a
divergence with the price action.

That is, the indicator has delivered an exit signal, but the price
continues rising. To get more accurate signals, you need to reduce the
Length value in the settings, but in this case, there will be more false
entry signals.

![LiteForex: Absolute Strength Histogram based on moving averages][7]

On the chart below, the Length value is 5. Over a short time, indicator
sends numerous signals most of which are false.

![LiteForex: Absolute Strength Histogram based on moving averages][8]

 **Absolute Strength Histogram signals (practice)**

Most Internet resources describe only the general meaning of the
indicator signals

The first thing that confuses you is the radically different display of
the price extremes with different values of the Mode. This prevents the
right interpretation of signals. The second problem that is clear from
[history](https://www.fixpro.org/post/chargeless-historical-data-api-backtesting/) is that the indicator basically confirms the general direction
of the long-term trend but hardly responds to short-term price
fluctuations. For example, on the hourly chart, it actually shows the
general trend (the example is in the screenshots below). But this suits
only long-term [trading strategies](https://www.fintechee.com/forex-trading-strategies/). It won’t work in short time periods.

 **Uptrend:**

![LiteForex: Absolute Strength Histogram based on moving averages][9]

 **Downtrend:**

![LiteForex: Absolute Strength Histogram based on moving averages][10]

As you see, the indicator performs quite well on the M30 timeframe with
Length = 20 (when it was 30 or 10, there were much more false signals).

![LiteForex: Absolute Strength Histogram based on moving averages][11]

This figure shows that five signals (yellow circles) are winning. I want
to stress once again these settings are optimal only for the USD/CHF
pair. Timeframes should be adjusted for each pair.

 **A short summary. Recommendations for the use of Absolute Strength
Histogram:**

  1. Entry signal: the columns change their color. Buy signal: the green column is clearly higher than the previous red one. To confirm the signals, you may expect until two bars after the change of the color close. For example, If the first green column is higher than the red, the second green column is higher than the first green one, you enter the trade on the third bar.
  2. Exit signal:

  * The most recent column is lower than the previous one,
  * A target profit is 20 points when it is reached, you close 50% of the position, move the stop loss to the break-even level, protect the position with a trailing stop at the distance of 20 points.

Working timeframes are from M15 to M30, the number of analyzed bars is
20.

 **Conclusion:** Absolute Strength Histogram may seem to an ordinary
indicator with many flaws:

  * It has no mathematical algorithm, no unique idea, the signal accuracy is average
  * You can make profits from trading with this indicator only if you use additional tools, bothe trend indicators located on the main window and oscillators located below the trading chart.

Therefore, you may, of course, doubt in the feasibility of using the
Absolute Strength Histogram, especially since there are many other, more
accurate indicators, which are easier and more convenient to work with.

Do not jump to any conclusions! Remember that there can be no perfect
indicator and there can’t be always winning [Forex trading](https://www.fintechee.com/forex-trading-strategies/) strategy. Each
indicator performs its task at a particular timeframe and for a
particular trading instrument. That is why there no bad indicators,
there are traders who can’t use technical tools properly.

Absolute Strength Histogram is a classical indicator based on Moving
Averages, and MAs are a toll from which the mastering of technical
analysis starts. Therefore, download the indicator template, train, test
it and shares the results in the comments!

I wish you success in trading!

* * *

P.S. Did you like my article? Share it in social networks: it will be
the best “thank you" :)

Ask me questions and comment below. I’ll be glad to answer your
questions and give necessary explanations.

 **Useful links:**

  * I recommend trying to trade with a reliable broker [here][12]. The system allows you to trade by yourself or copy successful traders from all across the globe.
  * Use my promo-code BLOG for getting deposit bonus 50% on LiteForex platform. Just enter this code in the appropriate field while [depositing][13] your trading account.
  * Telegram channel with high-quality analytics, Forex reviews, training articles, and other useful things for traders <t.me/liteforex>

![Absolute Strength Histogram: May the trend strength be with us][14]

The content of this article reflects the author’s opinion and does not
necessarily reflect the official position of LiteForex. The material
published on this page is provided for informational purposes only and
should not be considered as the provision of investment advice for the
purposes of Directive 2004/39/EC.

Rate this article:

{{value}}

( {{count}} {{title}} )

   1. drive.google.com/file/d/10zODTx7LSbIBtSCZyfY-7LJoc0mnwJB8/view
   2. cdn.liteforex.com/cache/uploads/blog_post/october/Absolute-Strength-istogram/Absolute-Strenght-Histogram-0-en.jpg?w=30&s=9f1018da546ca0b65bdf4caa550a0d33
   3. cdn.liteforex.com/cache/uploads/blog_post/Absolute_Strength_Histogram/Absolute-Strenght-Histogram-1.jpg?w=30&s=a5f5f2825611754779135cd1a1c0ea31
   4. cdn.liteforex.com/cache/uploads/blog_post/Absolute_Strength_Histogram/Absolute-Strenght-Histogram-2.jpg?w=30&s=15c6c9a9b35001a8697eb175a53d0464
   5. cdn.liteforex.com/cache/uploads/blog_post/Absolute_Strength_Histogram/Absolute-Strenght-Histogram-6.jpg?w=30&s=49b5bf30a1b7db895cbd034fcf1371bd
   6. cdn.liteforex.com/cache/uploads/blog_post/Absolute_Strength_Histogram/Absolute-Strenght-Histogram-7en.jpg?w=30&s=9d7d1f64367963120ae5780e9abde278
   7. cdn.liteforex.com/cache/uploads/blog_post/Absolute_Strength_Histogram/Absolute-Strenght-Histogram-8en.jpg?w=30&s=5ac66568452391e3c466868cf107720d
   8. cdn.liteforex.com/cache/uploads/blog_post/Absolute_Strength_Histogram/Absolute-Strenght-Histogram-9.jpg?w=30&s=1cf75e0715249ee739ae35759fa56cf0
   9. cdn.liteforex.com/cache/uploads/blog_post/Absolute_Strength_Histogram/Absolute-Strenght-Histogram-3.jpg?w=30&s=8a77b81461a42542fec3f64a31603bb4
   10. cdn.liteforex.com/cache/uploads/blog_post/Absolute_Strength_Histogram/Absolute-Strenght-Histogram-4.jpg?w=30&s=c35a355eb234aee11f8fc852782bf7f7
   11. cdn.liteforex.com/cache/uploads/blog_post/Absolute_Strength_Histogram/Absolute-Strenght-Histogram-5.jpg?w=30&s=6cb8f9bc4d8acd01d01f93bb85c25988
   12. my.liteforex.com/?category=for-professionals&slug=absolute-strength-histogram-may-the-trend-strength-be-with-us&openPopup=%2Fregistration%2Fpopup&utm_source=blog&utm_medium=article&utm_campaign=bonus
   13. my.liteforex.com/deposit/?category=for-professionals&slug=absolute-strength-histogram-may-the-trend-strength-be-with-us&promo_code=BLOG&utm_source=blog&utm_medium=article&utm_campaign=bonus
   14. cdn.liteforex.com/cache/uploads/blog_post/Absolute_Strength_Histogram/Absolute-Strenght-Histogram-forex-blog.jpg?q=75&w=1000&s=2a99e0eceaedb78c8e19e492a3339efc