+++
categories = ["Cryptocurrency", "Blockchain", "SmartContract"]
date = "2020-12-31"
description = "MQL4 vs MQL5. MQL4 programming tutorial and difference with MQL5"
tags = ["Cryptocurrency", "Blockchain", "SmartContract"]
title = "MQL4 vs MQL5. MQL4 programming tutorial and difference with MQL5"
type = "post"
+++

{{<iframe id="large-banner" src="https://www.bounty.group/#slide=24.0" width="100%" height="600" scrolling="no" style="border: 0px solid rgb(216, 221, 230); border-radius: 3px;">}}

2020-12-31

2020-12-31

Metaquotes languages MQL4 vs MQL5: difference & programming
[tutorial](https://www.fintechee.com/tutorial-for-forex-trading/)Michael Chistyukhin

MetaQuotes Language 4 and 5 are tools for developing applications for
the MetaTrader Client Terminal based on the platforms of MetaTrader
family of the fourth and fifth generations respectively. These languages
provide users with tools to develop client-side [automated](https://www.fintechee.com/features/automated-forex-trading/) trading
strategies

The article covers the following subjects:

I have prepared for you a detailed [tutorial](https://www.fintechee.com/tutorial-for-forex-trading/) on MetaTrader programming
MQL4 vs MQL5. After reading this article, you will understand what MQL
is, the differences between the two latest versions of languages, and
[how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) work with them. Here you will find detailed instructions with
pictures on [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) write an expert [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/). Let's get started!

## What are MQL4 and MQL5?

In many ways, the MQL4 and MQL5 languages are very similar. Therefore,
we will talk separately about the differences, but for now we will agree
to call them both MQL in the singular and without specifying the
version.

MQL is a programming language built into the MetaTrader platform.
MetaQuotes Language Editor development environment is used to write your
own trading [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/)s, indicators or other applications in MQL, as well as
to compile and debug them. This environment is supplied with MetaTrader
Client Terminal along with all the reference information.

If you have invested in certain assets at least once, maybe you just
bought dollars to keep in the bank, then you understand that the
investment requires relentless control. I bet you have asked yourself
questions like these more than once:

  * Is it time to exit the trade while the price is at its peak?
  * How to determine whether the price of an asset will continue to rise or the market will turn around?
  * Maybe this time a false signal was received and there is no need to take risks and rush to open a position?

You need to keep up with the market and make timely trading decisions.
It is advisable to do this day and night in the most active sessions.
When work is carried out with several assets at the same time, the
situation is becoming more and more aggravated.

MQL allows you to implement any trading strategy or algorithm in the
form of a computer program. Then this program is launched and constantly
runs on a workstation in the MetaTrader Client Terminal. In addition,
the delivery set includes a number of trading [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/)s, indicators and
scripts from the platform developer in the form of source codes, which
greatly facilitates the development of the language and its inherent
techniques. Also MQL is provided with detailed online and offline
reference information. There is a huge community around the language.

Let's say you have come up with some cool indicator or a clever trading
algorithm that you want to use in your work or maybe you want to analyze
the market using [neural network](https://www.fintecher.org/2020/03/17/added-genetic-algorithm-for-trading/)s? There are no restrictions. With MQL,
you can implement any idea in the form of an indicator, expert or other
application, compile, debug, check on [historical](https://www.fintechee.com/services/historical-data-for-forex/) data in the strategy
tester – all without involving financial risks and use it actively in
trading.

Let's summarize! MQL solves the problem of writing utilities for
monitoring the state of a trading account, calculating indicators and
levels, receiving trading signals and determining entry and exit points
from the market. Language tools allow a trading [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/) or indicator to
organize information exchange with a remote server using the TCP
protocol, including the TLS encryption or the HTTP protocol. It is
possible to send data via FTP as well as push notifications to
MetaTrader mobile clients or to user's email. Once a well-written and
debugged program will work until you decide to make changes or replace
it entirely with another. All you need to care about is general control.

### The story behind MQL4 and MQL5 Languages

MQL emerged as a result of the evolutionary development of the platform.
It is a tool for the automatic management of trading accounts in
MetaTrader. I will not dwell on this point in detail, but go over it
superficially.

            MetaQuotes released MetaQuotes Language along with the
MetaTrader platform, which was previously the FXCharts application. MQL
grew to the second version along with the MetaTrader 3 update. Here
MetaQuotes rolled out the API, which was provided to clients as an
additional layer between MetaTrader Client and MetaTrader Server.

            The release of the fourth generation of the platform took
place on July 1, 2005. Along with it, MQL4 was released. Backward
compatibility with the previous version of the language has been lost.
MetaQuotes also stopped supporting the client terminal API, but expanded
the capabilities of the language itself and provided ways to integrate
custom DLL [Libra](https://www.playgroundfx.com/blog/libra-creator/)ries into MQL applications. The API remained available
only to brokers at the server, administration and management levels.

In June 2010, after numerous releases, MetaTrader 5 was launched.
MetaQuotes redesigned the trading logic, removing most of the
restrictions imposed by the internal structure of the platform. But
until now MT5 is not competing with the fourth generation in popularity.

In February 2014, MQL4 was updated along with the 600 build of the MT4
client terminal. MetaQuotes improved the language, introduced most of
the features from MQL5 and at the same time accelerated it to the level
of a successor.

## Features of MQL4 and MQL5 programming languages

MQL is used to create [automated](https://www.fintechee.com/features/automated-forex-trading/) [trading strategies](https://www.fintechee.com/forex-trading-strategies/). The MQL code is
preliminarily interpreted into C++ code, which is then compiled into an
executable code that works inside the terminal as an included dynamic
[Libra](https://www.playgroundfx.com/blog/libra-creator/)ry. If we draw a parallel with the ancestor, then it will be
similar to including DLL [Libra](https://www.playgroundfx.com/blog/libra-creator/)ry in the executable code of the main
program. This approach contributes to ease of development and a low
threshold for entry into the field of [automated](https://www.fintechee.com/features/automated-forex-trading/) trading. This language
is popular among traders, despite its narrow specialization and
dependence of the language on the platform.

MetaQuotes took care of their users and provided all their applications
with detailed help information. References for MQL4 programming and MQL5
are supplied with MetaEditor in several languages in the form of HTM
files. Therefore, you always have a detailed guide with code examples on
[how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) implement the required behaviour.

A large community of traders and programmers has formed around MQL.
There are tools to facilitate communication between programmers and
traders. A layer of ready-made applications has already formed to
simplify the trading process. There is a market for exchanging
applications on a paid or free basis available at mql5.com. The trading
terminal integrates application store, codebase, articles and signals
from other traders. The app store offers hundreds of both paid and free
solutions such as indicators, [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/)s, scripts and all kinds of
utilities. This is in case it is easier to purchase a ready-made program
than to “reinvent the wheel”.

If you have firmly decided to master MQL on your own and dive into the
world of creating your own applications, you can use this article to
learn about problems that a beginner encounters when taking the first
steps in this direction. The advanced reader is unlikely to learn
something new from the text below.

Developers provide information support to the MQL community by regularly
publishing [tutorial](https://www.fintechee.com/tutorial-for-forex-trading/)s in the form of articles on various topics from the
world of trading. The authors of the articles consider new programming
techniques, including the creation of [neural network](https://www.fintecher.org/2020/03/17/added-genetic-algorithm-for-trading/)s, analysis and
solution of problems and limitations of the language, analysis and
testing of [trading strategies](https://www.fintechee.com/forex-trading-strategies/), search and implementation of new
[algorithms](https://www.fintechee.com/algorithms-for-trading/).

MQL Wizard offers 8 [options](https://www.fixpro.org/post/options-liquidity/) for MQL4 and 10 [options](https://www.fixpro.org/post/options-liquidity/) for MQL5. Here are
the screenshots of the file wizard for both versions of the language.

Let's consider the most popular ones:

  * Expert Advisor/Trading [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/);
  * Indicator;
  * Script;
  * Include files (.mqh) [Libra](https://www.playgroundfx.com/blog/libra-creator/)ry.

After compilation, these applications in the form of executable code are
placed in the appropriate directory of the MetaTrader Client Terminal
(File -> Open Data Folder): Experts, Indicators, Scripts, etc. Then,
after initialization on the chart, they are launched in response to
events generated by the MetaTrader Client Terminal during operation.
Events are a trigger for launching custom programs and allow you to
track initialization and deinitialization, receipt of a new quote,
custom event on the chart, and more.

In addition, it is now possible to create applications in Python.
Accordingly, Python tools have become available in the trading terminal.

The following event handlers are described in the MQL4 Reference.

In MQL5, the number of handlers has been increased compared to the
previous generation. Now the list looks as follows:

Later the list of events has been expanded. And now it looks as follows:

### Trading [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/) or Expert Advisor

In the trader community, it is also referred to as an Expert. The Expert
Advisor is attached to the chart in the MetaTrader Client Terminal and
works constantly as long as the trading terminal is running and a
connection to the trading server is available. Expert Advisors are used
to implement absolutely any [trading strategies](https://www.fintechee.com/forex-trading-strategies/), control the account
status, conduct trading operations under certain conditions, and manage
graphical objects. Every time the trading [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/) receives a new tick for
an instrument, it starts working opening trades. The Expert Advisor can
also be launched in response to a number of other events: OnTimer,
OnChartEvent, OnTesterTimer, etc.

Expert Advisors are used to create user interfaces. Robots, as well as
indicators, have access to graphical objects.

Below is the code for a simple trading [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/). After every new tick on
the symbol on the chart of which the EA is working, market deals are
checked. If there is already a trade for some symbol, the EA waits for
it to close. If there is no trade, then one is opened in the direction
opposite to the previous deal. The EA parameters: volume, stop loss and
take profit levels are set by the user. At the time of the first launch,
it will open a long position on some currency. After it closes, the next
one will be a short trade, then again long, and so on. In case of an
unsuccessful attempt to open a deal, the EA writes an error message to
the log and falls asleep for 60 seconds, then the attempt is repeated.
The EA does not check the parameters entered by the user for accuracy,
thus, carefully monitor this aspect. Here are some of the potential
problems that are immediately visible:

  * Overall trading ability is not checked. It can be disabled by the user in the terminal or specifically for this [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/). The trading server may also have restrictions on [automated](https://www.fintechee.com/features/automated-forex-trading/) trading.
  * The volume may be less than the smaller or larger than the larger one, and may not be suitable if the server has a limit on the volume step. For example, a user enters 0.23 lots, and the server has a minimum change of 0.05 lots. As a result, the deal will not be opened and the OrderSend function will return an error.
  * Stop levels for a trade are also not checked for accuracy. They may not fit within the minimum/maximum allowable values or may not fit within the limits set by the freeze levels.

The simplest code that can be used as a template for implementing
larger-scale solutions.

This code compiles and runs in MetaQuotes Language Editor 5 build 2375
on 31 March 2020.

### Indicator

Indicator is used to display information about price data converted in
some way. All kinds of oscillators, trend lines, fractals are all
indicators. The indicators have access to graphic tools. There are 6 of
them in MQL4, while in MQL5 their number is 18. For example, Moving
Average displays some averaged and/or smoothed price value for a price
period in the past and indirectly indicates the future direction of the
price for an instrument. It works on the chart all the time. The
indicator is updated and recalculated every time a tick is received for
the instrument on the chart of which the indicator is working, or when
events are received from the user.

One or several buffers are associated with any indicator inside the
MetaTrader Client Terminal, into which numeric data is placed. MQL4
provides 32 buffers for one indicator, while in MQL5 it allows you to
operate 512 buffers.

Below is an example of the source code of the Bears indicator, which is
provided by the platform developers together with MetaTrader4.

### Script

Developers use scripts to create [algorithms](https://www.fintechee.com/algorithms-for-trading/) that do not require real-
time data processing. For example, to download statistical data or
output debug information. Scripts are executed once when attached to any
chart by the OnStart event. It is the only one that the script can
process.

The picture below shows the script code for closing all market orders on
the account. The script will process all orders, regardless of which
symbol’s chart it is launched on. In this case, pending orders are
ignored.

The result of running this script will be the following output to the
MetaTrader log:

It will take more effort to teach this script to process pending orders
separately in MQL4. First, let's create a Property so that the script
can show a window with input data. Next, add an Enum containing 3
[options](https://www.fixpro.org/post/options-liquidity/) for closing deals with a script: only market orders, only
pending orders, or all deals that are on the account at the moment. Then
we add an array for storing pending order tickets and fill it
accordingly in the first For loop. Now it remains to process the option
of closing deals selected by the user.

As a result, we got a script like this, which not only closes all trades
but takes into account the user's choice.

### Include files (.mqh) [Libra](https://www.playgroundfx.com/blog/libra-creator/)ry

It is used, as the name implies, for inclusion in other types of
programs for the MetaTrader Client Terminal. An experienced developer
has a set of their own tools that can be reused many times in various
applications.

In the MetaQuotes Language Editor, you only need to specify the path to
the included header file relative to the location of the file into which
the inclusion is taking place. When compiling the program, MetaEditor
will find this file and include the code from it instead of the #include
directive. Now all the [Libra](https://www.playgroundfx.com/blog/libra-creator/)ry code can be used in the application.

Similarly, C and C++ programmers reuse code by including header files in
their projects and linking with binaries.

The example below presents the most simplified interpretation of a
dynamic array aka std::vector from the standard C ++ [Libra](https://www.playgroundfx.com/blog/libra-creator/)ry. This code
compiles and works with MetaEditor version: 5.00 build 2375 31 March
2020.

## Data types and syntax of MQL4 and MQL5 languages

The data types and syntax of the language are inherited from C++. Before
compilation, the MQL code is preprocessing and interpreted into the
corresponding C++ code, therefore, language constructs that are valid in
the ancestor will most likely be compiled and will work in MQL. A
programmer familiar with C, C++ or C# can easily figure out [how to](https://www.playgroundfx.com/blog/forex-trading-how-to/) write
MQL code

### Data types

The following fundamental data types exist in MQL:

  * Boolean values;
  * Single and double-precision floating-point numbers;
  * Integers, also single and double precision, signed and unsigned;
  * Char for storing character data;
  * Enum enumerations, but enum class is not supported;
  * Structures, classes and class templates.

At the same time, there is additional support for color, string and
datetime as built-in types, which, of course, somewhat simplifies the
developer's life. Working with these types is organized in the C style
using global [functions](https://www.fintechee.com/tutorial-for-forex-trading/basic-functions/). The behavior of an MQL string is fundamentally
different from the std::string family of templates for C++03. Don’t
confuse them.

### Syntax of MetaQuotes languages

MQL has a syntax similar to C++. The semantics of the ancestor of the
C++03 standard has been transferred to MQL with minor changes.
Currently, MQL complies with the C++03 standard in [terms](https://www.fintechee.com/terms/) of
capabilities.

The main difference between MQL and C++ is the different semantics of
pointers. If in C++ it is a virtual address at which data is located,
then in MQL it is a descriptor, an analogue of a POSIX standard
descriptor, a numeric identifier, a kind of wrapper over a raw pointer,
by which objects created in dynamic memory and associated with this
identifier exist. The arrow operator “->” is not supported for MQL
pointers, dereferencing is performed using the dot operator “.”. The
descriptor, just like the pointer, must be deleted after the program
finishes. However, if you forget to destroy the object that this handle
refers to, the runtime will do it for you when the program is
deinitialized.

The MQL language lacks the concept of a temporary variable and data
movement. Passing variables by reference and by value differs from C++
and is implemented in MQL in its own manner. Any complex object or
custom class will be passed to the function by reference whether you use
Ampersand operator or not.

There are a number of restrictions on the ancestor. You cannot write
[functions](https://www.fintechee.com/tutorial-for-forex-trading/basic-functions/) and templates with a variable number of arguments. But, what
is remarkable, a number of built-in [functions](https://www.fintechee.com/tutorial-for-forex-trading/basic-functions/) such as iCustom (which we
will analyze later in this article), printf, StringFormat, PrintFormat
take a variable number of arguments. Paradox!

Working with data and object references differs in some aspects compared
to C++, but they are all easily eliminated using messages from the
compiler. There are differences in the signatures of the copy
constructor and the copy assignment operator due to different semantics
of passing variables by reference. Also, there is no move semantics for
moving variables and object instances in MQL.

## Difference between MQL4 and MQL5 codes

The differences between the fourth and fifth generation of MQL languages
​​are due to the differences between MetaTrader4 and MetaTrader5
platforms themselves. It should be noted that since the release of the
600 MT4 build, only the fifth version of MetaQuotes Language Editor is
used to write and compile programs in MQL4 and MQL5. In particular,
languages ​​operate in different ways with trading operations, since the
fifth platform has more trading modes and the concepts of order, deal
and position are separated.

Now to send requests only the OrderSend function is used, in contrast to
the fourth version, where separate [functions](https://www.fintechee.com/tutorial-for-forex-trading/basic-functions/) are used to set a
modification or delete an order.



|

MQL4

|

MQL5  
  
---|---|---  
Timeframes|

9 (M1, M5, M15, M30, H1, H4, D, W, MN)

|

21 (M1, M2, M3, M4, M5, M6, M10, M12, M15, M20, M30, H1, H2, H3, H4, H6,
H8, H12, D1, W1, MN1)  
  
Drawing styles|

6

DRAW_NONE

DRAW_LINE

DRAW_SECTION

DRAW_HISTOGRAM

DRAW_ARROW

DRAW_ZIGZAG

With build 600, the number has become consistent with the fifth version

|

18

DRAW_NONE

DRAW_LINE

DRAW_SECTION

DRAW_HISTOGRAM

DRAW_HISTOGRAM2

DRAW_ARROW

DRAW_ZIGZAG

DRAW_FILLING

DRAW_BARS

DRAW_CANDLES

DRAW_COLOR_LINE

DRAW_COLOR_SECTION

DRAW_COLOR_HISTOGRAM

DRAW_COLOR_HISTOGRAM2

DRAW_COLOR_ARROW

DRAW_COLOR_ZIGZAG

DRAW_COLOR_BARS

DRAW_COLOR_CANDLES  
  
Event-driven launch model|

OnInit

OnStart

OnDeinit

OnTick

OnCalculate

OnTimer

OnChartEvent

OnTester



|

OnInit

OnStart

OnDeinit

OnTick

OnCalculate

OnTimer

OnTrade

OnTradeTransaction

OnBookEvent

OnChartEvent

OnTester

OnTesterInit

OnTesterDeinit

OnTesterPass  
  
Trading|

OrderSend

OrderModify

OrderDelete

The behavior is specified by a separate set of parameters for each
function. It complicates writing and debugging programs.

|

OrderSend

One function for all operations. The required behavior is specified in
the MqlTradeRequest structure. The response is returned to the
MqlTradeResult structure. It is easier to design the behavior, test the
result, and debug the program.  
  
Indicator data buffers|

32

|

512  
  
Built-in indicators|

Quantity: 30

|

Quantity: 38

Indicators are created using handles. The number of copies and memory
consumption have been reduced.  
Trading Modes| Hedging|

Netting

Hedging

Stock  
OpenCL and DirectX graphics tools|

No

|

Yes  
  
Generation of trading [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/)s|

No

| Yes. At the same time, you can specify custom signal modules.  
  
So, there are a few differences, but they do exist. After the update in
build 600, MQL4 differs from MQL5 only in the part where one platform
differs from another. The LiteForex blog already has an article devoted
to comparing MetaTrader 4 and MetaTrader 5, which I strongly recommend
to read if you want to deepen your knowledge on this topic.

## MQL4 indicator programming: How to write an Expert Advisor in MQL4 or
MQL5

Before you start writing an Expert Advisor, you need to understand that
you must already have a trading strategy. Only then you can start
realizing the idea in the form of a formal algorithm. The code itself
only provides language tools for the implementation of a certain idea.

So, the first thing you need is a working trading strategy. The question
of developing this is outside the scope of this article, so let's take
something simple as an example. Let's assume the following. During
periods of low activity of the instrument “on a flat”, it is possible to
open deals in opposite directions with small levels of limits. This will
allow you to take advantage of small sideways market movements and make
a profit.

We will write an Expert Advisor that will automate the manual opening of
trades and control over their limits and will launch it on a trading
account during flat periods.

Initially, the procedure is the same regardless of the language version.
To write programs in MQL, you need to install the MetaTrader Client
Terminal, the delivery package of which includes MetaEditor. Now we can
launch MetaEditor directly from the working directory of the terminal,
or through the main menu in the trading terminal: Tools and then
MetaQuotes Language Editor (F4). In the MetaEditor window in the main
menu, click on File -> New. The same is done after clicking New in the
graphical menu.

### How to create MQL4 trading [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/)

In the MQL4 EA builder application Wizard select the Expert Advisor
(template) and click Next.

Next, enter the parameters that provide the user with an interface for
interacting with the program, and confirm by clicking OK. Here we add:

  1. Tool for trading
  2. Choice of a direction for the first deal that the [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/) will open. For now, this is an integer type, but later we'll fix the code so that only Buy or Sell can be selected.

MetaEditor will automatically include the OnTick event handler in the
code. The rest you need to choose yourself. As you can see, we
additionally have access to OnTimer, which is called every time with the
frequency set for the timer and OnChartEvent, which will be called in
response to user actions with the chart. Here you can see that more
handlers are available for MQL5.

Go further and select the event handlers in test mode. In MQL5 you can
choose more events in the tester mode, and accordingly, more handlers
are available for them.

During the previous two steps, I left all [options](https://www.fixpro.org/post/options-liquidity/) blank. All our logic
will be executed with the OnTick function. It is called every time a new
tick for a symbol arrives.

After clicking the Finish button, MetaEditor will create a template for
the future Expert Advisor with the specified name and parameters. The
selected event handlers will also be included in the code. I will not
dwell on each of them in detail. All the necessary information about
this is in the reference guide.

This code can already be compiled and run in the trading terminal. But
nothing will happen. We have input variables, but we are not using them
yet. The OnInit function always informs the terminal about successful
initialization, while OnTick and OnDeinit do not contain any
instructions.

Let's start writing the code.

Let's clean up first. Remove extra spaces and shorten comments to one
line. Then we define **enum** **TradeCmd** (lines 11-14) to indicate the
direction for the first trade in a natural way rather than a number.
Then change the input type of the **FirstTradeDirection** variable from
**int** to **TradeCmd** (20). The next step is to create a static global
variable Direction with the **TradeCmd** type to take into account the
direction of the previous deal and change it to the opposite for the
next one.

In the beginning, I forgot to add variables for the volume of deals,
stop-loss and take-profit levels in the wizard. We add them now with the
input keyword and them with the rest of the external settings.

Let's move on to the OnTick function. We analyze the availability of
open deals. To do this, we iterate over all open trades using a simple
cycle in the range [0, TotalTrades). We check one by one that the symbol
of the selected deal matches the one specified in the InputSymbol. Once
there is at least one such deal, nothing needs to be done. And we exit
the OnTick function ahead of schedule with Return (lines 29-35). Wait
for the next launch.

Otherwise, you need to open a deal. Let's refer to the MQL4
documentation in order to use the **OrderSend** function correctly, with
the help of which we will send a request to the trade server. The
declaration looks like this:

Let's consider the parameters in order:

  1. Symbol. We already have it, but we do not check the correctness in any way and rely only on correct input from the user.
  2. CMD. For this, we use the Direction global static variable.
  3. Volume. Specified by the user. Again, it would be necessary to check the entered value for the limits: minimum, maximum and minimum step of volume change.
  4. Price. Ask if we are buying, Bid if we are selling.
  5. Slippage. In our case, it doesn't really matter. Set it to 2 pips.
  6. Stoploss. Again, it depends on the direction of the transaction. Should be less than the opening price if we are buying, and more than the opening price if we are selling.
  7. Takeprofit. Like stop loss, it depends on the direction of the trade.

The other 4 parameters with a default value are not of interest to us
yet. As a result, to open a deal we have: **InputVolume** (i.e. volume),
**Direction** (i.e. direction of the deal), **InputSymbol** (i.e.
symbol), set the slippage to 1 point. What we need to calculate
depending on the **Direction** : **price** (i.e. ****open price), **sl**
(i.e. stop loss) and **tp** (i.e. ****take profit). If we buy, then the
price is Ask, Stop loss is lower than the current price, Take profit is
higher, otherwise, if we sell, then the price is Bid, Stop loss is
higher than the current price, and Take profit is lower. We also need 2
additional variables. The first one is for converting the level of
limits from points to nominal value **point** which is the minimum value
by which the quote for a symbol can change. The second one is for
normalization of values with **digit** floating point ​​which is the
number of significant digits in the fractional part of the quote.

Convert this to MQL.

We proceed directly to opening a deal. We reset the **_LastError**
system variable with the **ResetLastError** built-in function. We send a
request using **OrderSend** , and write the result to the **result**
variable. There are two [options](https://www.fixpro.org/post/options-liquidity/) for the development of events:

  1. The deal has been successfully opened if **result** contains a value greater than zero, the deal's ticker. So, we need to change the Direction value in order to open a deal in the opposite direction next time.
  2. If **result** contains a negative value, then the deal was not opened. You need to check the last error using **GetLastError** , analyze it and do something: try again, fall asleep for a while, output debug information to the log, etc. For the sake of simplicity, I output the value of the last error to the log.

Let’s take a look at it.

So, we have written several dozen lines of code and the trading [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/) is
ready. I admit that it is not very functional yet, but it can serve as
an excellent example of the fact that writing code does not require a
lot of knowledge and significant effort.

Here is a complete listing, in case you need it.

We compile the code and launch the Expert Advisor in the trading
terminal.

### How to create an Expert Advisor in MQL5

Here MQL5 has an undeniable advantage over MQL4. You can create a
trading [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/) for the fifth version in a few clicks without actually
writing a single line of code.

In MetaEditor, click New and select Expert Advisor (generate) in the
application wizard.

Let's name our Expert Advisor MQL5_Generated_Robot. Optionally, we
indicate the author and his [website](https://www.playgroundfx.com/blog/website-for-forex-trading/) or profile. Add the parameters of
the [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/), if necessary: the symbol and the timeframe for trading.
Double-clicking activates the parameter, clicking on the name or value
of the variable allows you to change the proposed defaults. You can set
any symbol you want. I defined it as the current one, on the chart of
which the EA will work. I set the timeframe at M15 to increase the
likelihood of trading signals.

Let's move on. Now we need to select a signal and settings for it. Here
you can improvise and try different combinations of the signals
suggested by the developers. These signals will generate events for the
expert to make deals.

You can add custom signals to this section, including those from
monitoring on the mql5.com. The following [options](https://www.fixpro.org/post/options-liquidity/) are provided with the
platform by default:

I chose “Trading at the intersection of two averages” and set the
periods equal to 21 and 55. It is undesirable to choose too short
periods if you need to reduce the number of false positives. We leave
the current symbol. For example, we will trade[][1][EURJPY][1] and
receive signals from moving averages applied to the price data of the
same EURJPY. Choose a different symbol here if your strategy involves
trading the instrument depending on the behavior of some other one. I
also set the timeframe at M15.

Confirm. We see that a signal has been added for the current symbol and
timeframe, which will generate events for the EA.

Move on to the Trailing Stop mode. Here I have chosen a fixed size
limit. I also set stop loss at 150 points and take profit at 200 points.

Next, we can choose one out of five modes of money management for a
trading account. Trading is available with:

  * Fixed trade volume;
  * Fixed margin;
  * Fixed risk;
  * Minimal allowed trade volume;
  * Optimized trade volume.

I settled on trading with the fixed risk of 1% of the funds in the
account.

Click Done and gain profit! We have created an Expert Advisor without
writing a single line of code.

Let's take a closer look and conduct a small analysis of the sources.

Head of the table and attributes - everything is familiar. Then comes
the inclusion of [Libra](https://www.playgroundfx.com/blog/libra-creator/)ry modules. Expert is our [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/). MACross is a
signal generator for Moving Average crossing, TrailingFixedPips is a
limit level control module, MoneyFixedRisk is a risk management module.
Then the settings that include input variables that define the interface
for interacting with the application. It looks familiar, doesn't it? Of
course! We set them up in the Expert Advisor Generation Wizard. In the
future, the default values may be changed here.

Next, an automatic global variable of the CExpert type is declared,
which is initialized with a default value. For an object, this means
that the default constructor has been called. In the body OnInit, the EA
is initialized, signals and filters are created and initialized with the
values specified in the settings. Below is the code from which I removed
all the checks of the initialization results for success and the
descriptors for validity in order to visually reduce the amount of code.

Below you can see OnDeinit, OnTick, OnTimer, OnTrade [functions](https://www.fintechee.com/tutorial-for-forex-trading/basic-functions/). Each of
them simply calls the corresponding method of the CExpert class.

If you look closely, in the navigator on the left in the Include ->
Experts folder, you can see the signals and modules available in the
generator. Accordingly, you can add some specialized solutions to the
generator and create some for any need in a few clicks.

Let's try to compile the code. 0 errors and 0 warnings is a success. To
launch the strategy testing mode press Ctrl and F5 simultaneously or
click the button in the graphical menu at the top.

Control is transferred to the MetaTrader Client Terminal in the settings
of the strategy tester. Then we select the file to test and configure
the rest of the parameters: symbol, timeframe, [history](https://www.fixpro.org/post/chargeless-historical-data-api-backtesting/) depth, balance
and leverage of the trading account, etc. There are many settings, and
for each of them, there is a description in the reference file. For
detailed information on settings and testing mode focus on the tester
and press F1.

To begin, press Start in the lower right corner of the tester and, if
testing occurs without [optimization](https://www.fintechee.com/features/genetic-algorithm-for-trading/), then you can select the
visualization mode for your strategy.

The developers have kindly provided a description for each built-in
module and signal
on[][2]<www.mql5.com/ru/docs/standard[Libra](https://www.playgroundfx.com/blog/libra-creator/)ry/expertclasses>. Do
not hesitate to refer to the documentation to expand your knowledge in
the question.

## Pros and Cons of MQL4 and MQL5 languages

The main drawback lies in the very purpose of these languages.
MetaQuotes Querying Language is a language for writing applications only
for MetaTrader. It is possible to compile and debug MQL code only in the
MetaEditor environment. Only MetaTrader Client Terminal can launch the
program for execution. There is no manual memory management. You still
choose to create the variable on the stack or in dynamic scope, but in
either case, you don't have access to its virtual address.

He has much more merits. Low threshold of entry, especially if you
already have experience in developing in statically typed languages.
High performance at the C and C++ level. Support for object-oriented
programming style: encapsulation and extensibility, inheritance,
polymorphism and virtual methods of classes. It is possible to create
templates for classes and [functions](https://www.fintechee.com/tutorial-for-forex-trading/basic-functions/), that is, parametric polymorphism.
All this allows the code to be reused many times. Free infrastructure
includes a trading terminal, development environment, strategy tester,
included [Libra](https://www.playgroundfx.com/blog/libra-creator/)ries.

## MQL4 to MQL5 conversion

Let us consider the transformation of updating a program from one
version to another using the example of a [robot](https://www.playgroundfx.com/blog/automated-forex-trading-robot/), which was previously
presented in this article in the section about the capabilities of the
language. To do this create an empty Expert Advisor in MetaEditor 5 and
copy the source code of the MQL4_Example_EA Expert Advisor into it. You
won't be able to compile this code without changes, a lot of errors will
occur when trying.

At first, almost nothing changes, except for a couple of points:

  1. Remove **#property strict** from preprocessor directives, so it makes sense when compiling MQL4 code.
  2. Transfer the creation of the Direction static variable above the EA initialization function to initialize it in OnInit in a special way, depending on the available positions. In the future, this will allow to change the EA settings in the middle of the trading process.

Note that it is now easier to select a deal for any symbol in MQL5 using
the built-in PositionSelect function, without having to search through
all open deals.

Let’s fully consider the **OnTick** function. We use **PositionSelect**
to check for an open position for a symbol. If there is no such one,
then go inside the **if** body and prepare to send a request to open a
deal. MQL5 kindly provides us with the **MqlTradeRequest** structure for
creating a request, as opposed to a bunch of parameters in MQL4. I will
not now consider each of its fields separately. Let me just note that
just like in MQL4, we have 4 out of 7 required parameters: trade symbol,
volume, direction and deviation from the requested price. We calculate
the remaining three (the opening price, stop loss and take profit)
depending on the direction of the transaction. We fill in the structure
in order. Now there is no need to normalize floating-point numbers, so
there is no need for the **digit** variable.

Sending a request in the latest version of the language looks much more
concise. All information about the result of executing the OrderSend
function is now returned to us in **MqlTradeResult**.

I ended up with the following code after debugging and a series of
tests. The size has not changed, although we made a change in the logic
that required additional actions at the initialization stage in OnInit.

Let's summarize. Upgrading applications from MQL4 to MQL5 is easy. If
you have basic knowledge of MQL, it will not be difficult to do it
yourself.

Further, I specially selected for you a number of the most common MQL
questions and tried to answer them briefly and thoroughly.

## MQL4 and MQL5 FAQ

How to use iCustom MQL4?

The built-in iCustom function allows you to use signals from indicators
to implement trading logic inside the EA. If you have your own indicator
and you want to generate trading signals in the [advisor](https://www.fintechee.com/tutorial-for-forex-trading/expert-advisor/) to carry out
trading operations, you need to use iCustom for this. Let's look at the
documentation. Here you can see the following definition of MQL4:  
  
  
  
MQL5 definition:  
  
  
  
Basically, the function does the same thing, even though its signature
is different in the fourth and fifth versions of the language.Let's take
a closer look at each of the parameters:  
  
1\. String symbol line. It is the symbol that will be calculated.  
  
2\. Timeframe. In MQL4 it is an integer type int, in MQL5 it is also an
integer but enum that contains enumerations of timeframes.  
  
3\. String parameter name. You need to pass the path to the indicator
into it (if, for example, it is located in another directory) and also
the indicator name together with the extension for which we want to
calculate. Next, the required parameters are passed for the indicator
that we want to use.  
  
4\. A list of parameters for the indicator, which will be launched by
the iCustom function. Their number depends on how many arguments are
needed to get the required value from your indicator. It makes sense
that the function takes a variable number of parameters. For example,
for Alligator (it is included in the MetaTrader Client Terminal
installation package):  
  
  
  
Or, for example, for Ichimoku it will be some other set of variables:  
  
  
  
Thus, in the first case, you will need to pass 6 parameters to the
function to get the correct value, and 3 in the second.  
  
5\. There are two more parameters in MQL4 of the fourth version. The
first is an integer mode that denotes the indicator line index and is
used by the runtime for internal indexing of data buffers.  
  
6\. The next integer shift indicates the forward or backward shift of
the indicator along the timeline.

How to convert MQL4 to MQL5?

Converting MQL4 to MQL5 is a trivial task for a beginner programmer, but
it will require your attention and patience. The compiler will show you
most of the things incompatible with MQL5 on its own.  
  
Attention should be paid to processing trade orders and sending them to
the server.  
  
· In MQL4, a trade request is implemented using OrderSend function and a
set of parameters for it. Modification of an order and deletion of a
pending order are implemented by separate [functions](https://www.fintechee.com/tutorial-for-forex-trading/basic-functions/). The result of the
query is determined by the Boolean value returned at the end of the
function. The analysis of the result is reduced to determining the
server return code using the GetLastError function.  
  
· MQL5 has a special MqlTradeRequest structure for sending trade orders
to the server. You need to fill it with the appropriate type of
operation and type of order. To get the result, you need to declare and
pass an instance of the MqlTradeResult structure by reference when
calling OrderSend to receive a response from the server, combine the
disparate parameters previously passed when calling OrderSend into a
single MqlTradeRequest structure and send to the server. We analyze the
MqlTradeResult structure received in response. All necessary information
will be available in the response from the server.  
  
Pay special attention to event handlers in your code. MQL5 has
OnTesterTick, OnTesterTimer, OnBookEvent in addition. Various
applications are launched in response to events from the trading
terminal.  
  
For experts:  
  
OnInit, OnDeinit, OnTimer, OnTick, OnChartEvent, OnTester  
  
For indicators:  
  
OnInit, OnDeinit, OnTimer, OnCalculate, OnChartEvent, OnTester  
  
For scripts:  
  
OnStart (this handler cannot be used in indicators and scripts).  
  
There is no launch facility for the included [Libra](https://www.playgroundfx.com/blog/libra-creator/)ries, as they are used
exclusively within other larger projects.  
  
Another difference is that the predefined variables Ask, Bid, as well as
arrays Open [], High [], Low [], Close [], Volume [], Time [] are absent
in MQL5. Therefore, the program code must be corrected in order to
independently obtain this data using the built-in [functions](https://www.fintechee.com/tutorial-for-forex-trading/basic-functions/) for
accessing the time series CopyRates, CopyOpen, CopyHigh, etc. Declare a
dynamic array and get data into it. The function providing the result
will take care of the resizing of the array on its own.

* * *

P.S. Did you like my article? Share it in social networks: it will be
the best “thank you" :)

Ask me questions and comment below. I’ll be glad to answer your
questions and give necessary explanations.

 **Useful links:**

  * I recommend trying to trade with a reliable broker [here][3]. The system allows you to trade by yourself or copy successful traders from all across the globe.
  * Use my promo-code BLOG for getting deposit bonus 50% on LiteForex platform. Just enter this code in the appropriate field while [depositing][4] your trading account.
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

   1. my.liteforex.com/trading/chart?symbol=EURJPY
   2. www.mql5.com/ru/docs/standard[Libra](https://www.playgroundfx.com/blog/libra-creator/)ry/expertclasses
   3. my.liteforex.com/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=what-is-metatrader&slug2=metaquotes-languages-mql4-vs-mql5-difference-programming-[tutorial](https://www.fintechee.com/tutorial-for-forex-trading/)&openPopup=%2Fregistration%2Fpopup&utm_source=blog&utm_medium=article&utm_campaign=bonus
   4. my.liteforex.com/deposit/?category=for-[beginners](https://www.playgroundfx.com/blog/forex-for-beginners/)&slug=what-is-metatrader&slug2=metaquotes-languages-mql4-vs-mql5-difference-programming-[tutorial](https://www.fintechee.com/tutorial-for-forex-trading/)&promo_code=BLOG&utm_source=blog&utm_medium=article&utm_campaign=bonus