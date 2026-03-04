---
title: "How to Backtest a Trading Strategy on Tradingview"
people_mentioned: []
channel: "TradingLab"
video_id: "OwvElpGjLKI"
url: "https://www.youtube.com/watch?v=OwvElpGjLKI"
publish_date: 2021-11-13
duration: "7:57"
word_count: 1592
content_type: "tutorial"
delivery_mode: "technique"
broad_category: "finance-investing"
subcategories: ["stock-analysis", "portfolio-management"]
series_name: ""
episode_id: ""
primary_person: ""
host_names: []
interviewer_names: []
interviewee_profiles: []
speaker_profiles: []
organizations_mentioned: ["TradingLab"]
locations_mentioned: []
tools_mentioned: ["TradingView"]
companies_mentioned: ["TradingView"]
topics: ["stock-analysis", "portfolio-management", "ai-coding"]
tags: ["stock-analysis", "portfolio-management", "ai-coding"]
pipeline_stage: video_only
claims_status: pending
evidence_status: pending
claims_count: 0
evidence_count: 0
batch_id: ""
last_processed_at: "2026-03-03"
speech_status: pending
world_status: pending
speech_evidence_count: 0
world_evidence_count: 0
---


## Summary

The discussion centers on want, strategy, short. We want to reference what position we want to close, so we want to close a long trade, when short is true. Name this short , strategy we want is short, still have it as 1000 shares, then we want it to execute it when this. We want to buy, when the 50 day crosses below the 20 day, and we want to sell, when the 50 day crosses above.

## Key Insights


- The first parameter is the name, so we ll call this entry long, then the 2nd parameter is what we actually want to do, so we type in strategy.long , the 3rd parameter is how many shares you want to purchase, so in this example we will just do 1000 shares.

- So we want to reference what position we want to close, so we want to close a long trade, when short is true.

- So name this short , strategy we want is short, still have it as 1000 shares, then we want it to execute it when this short condition is true.

- If you want to see a more advanced tutorial on how to back test some advanced strategies, like this video and let me know in the comments if you want that, and I ll make a more advanced tutorial.

- We want to buy, when the 50 day crosses below the 20 day, and we want to sell, when the 50 day crosses above the 20 day.

- So we have the name, whether we want to go long or short, the amount of shares, and when want to execute.




## Key Quotes


> Have you ever thought to yourself, I wish I could instantly test my strategy with out waiting months or even years, to see if my trading strategy is even good or not.


> Well, what if I told you there s a way to test any trading strategy you want on years of data from the past, instantly.


> To see right then and there if your trading strategy is profitable or not.


> In this video, I m going to show you exactly how to do that.






## Full Transcript

<details>
<summary>Click to expand full transcript (1592 words)</summary>

Have you ever thought to yourself, I wish
I could instantly test my strategy with out waiting months or even years, to see if my
trading strategy is even good or not. Well, what if I told you there s a way to
test any trading strategy you want on years of data from the past, instantly. To see right
then and there if your trading strategy is profitable or not.
Instead of just believing a YouTuber that says they have a 100% win rate strategy, why
not test it for yourself to see if it really is that good or not, and see how it compares
to your strategy that you re currently using. In this video, I m going to show you exactly
how to do that. By backtesting your strategy on TradingView with past years of data. So
you can see just how successful your trading strategy really is.
Let s get straight to it. First things first, we have to go to TradingView.
I ll have a link in the description. And as a side note, this is completely free to use
and you don t need a paid subscription or anything. Which is pretty awesome.
Once your on tradingview, go to chart option on the top here.
Then type in any security you want to test your strategy on. This will work with anything.
Stocks, forex, crypto, whatever. For this example, I m going to test the Vanguard
S&P 500. Now for this video we are going to test a
very simple trading strategy. Just so you guys can kind of get a grasp on the basics
of backtesting. If this video gets a good response and you guys really want to see more
of this, I ll do a 2nd video where I ll get a little more advanced.
The trading strategy example we will do, is just a simple moving average strategy.
It s pretty simple. We have a 20 day moving average and a 50 day moving average. We want
to buy, when the 50 day crosses below the 20 day, and we want to sell, when the 50 day
crosses above the 20 day. Like I said, very basic and simple trading
strategy, but this is just to show you the basics of backtesting.
I should also mention. That Tradingview has a page where it has a bunch of pre bult in
variables functions, so you don t have to custom make all of them. We are going to be
using a lot of them in this video. So I ll leave that in the description as well if you
want to check that out. So once you type in whatever security you
want to test. You are going to go down and click on this bottom tab that says pine editor
. The very first line, is what you want to name
your trading strategy. So, we are going to name this simple moving average strategy .
Next, we are going to set our variables. The first one we ll call ema20 for our 20 day
moving average and the second one we ll call ema50 for our 50 day average.
Next we are going to use the built in ema function from the tradingview page I was talking
about before. So we just type ema( . Now this function takes two parameters. The first parameter
is if you want the ema to read from the open or close of a candle as a reference point.
With moving averages, I think its best to read from the close. So we ll do that for
this strategy. Then the 2nd value is the time frame. So for
a 20 moving average we are going to set it to 20.
Then you re going to do the exact same thing for this one, but make it 50.
Next we are going to set our long and short conditions.
So we want to go long, if ema20 is above the ema50. Then we want to go short if the ema
20 is below ema50. So keep in mind, these aren t entry points,
but they are just simply telling the bot what we define as a long and what we think is a
short. To do entry points we are going to use another
built in function, which is strategy.entry .
The first parameter is the name, so we ll call this entry long, then the 2nd parameter
is what we actually want to do, so we type in strategy.long , the 3rd parameter is how
many shares you want to purchase, so in this example we will just do 1000 shares.
Then the 4th parameter is when we want to actually execute the trade, so we type when
= long . Which is saying we want to execute a long trade when these parameters above are
met. So we have the name, whether we want to go
long or short, the amount of shares, and when want to execute.
Then we are going to do the same thin g for a short trade. So name this short , strategy
we want is short, still have it as 1000 shares, then we want it to execute it when this short
condition is true. Right now we have it setup to where its longing
and shorting. But it s not actually closing positions at this time. It s just constantly
opening trades. So lets setup to where it actually closes
them. To do that, just simply use strategy.close
. Then we are going to give it a few values to tell the bot when we want to close a position.
So we want to reference what position we want to close, so we want to close a long trade,
when short is true. Then we will do the opposite for a short.
So close out a short position when long is true.
So just all this code alone, in theory, will buy every time when the 50 day crosses below
the 20 day, and will sell, when the 50 day crosses above the 20 day.
It will also do the opposite with short trades. Let s run it to see if it works.
To do that, go to this tab up here add to chart and that will start our backtest.
So it looks like it worked. The cool thing about tradingview, is that it will actually
display on the chart where it bought and sold. This way you can check to see if the bot is
running correctly and buying and selling where you actually want it to.
You also have these 3 different tabs. The overview tab will show you an equity curve,
your net profit, amount of trades, max drawdown, avg trade, etc.
The performance summary basically gives the same
information, but in a table format. Then theres the list of trades tab, where
it will show you every single trade and when and how it was executed. So you can see here,
that we went all the way back to the 1970s. So maybe you don t want to test all the way
back to 1970? Well you can actually edit the script to where you can tell the bot a specific
amount of time you want to test. To do that, just go to this line right here
and create a start and end variable. Then we are going to use the prebuilt timestamp
function So we are going to set our start, lets say 2019, august, 1, then hours, and
minutes. Then we ll just copy and paste this and set
our end point to 2020. So this will test our strategy from august
2019 to august 2020 on the s&p 500. Then we have to make an if statement. So if
time is greater than or equal to our start variable and if time is less than or equal
to our end variable. We will run this code below.
Then, you just indent this. Go to the add to chart button, and boom, you
see that it tested trades from only 2019 to 2020.
Now maybe you want to see your actually indicators from the bot on the chart. Well, theres actually
a way to do that. Theres a prebuilt function called the plot
function . So you just do plot( then whatever indicator you want, the name, the color, then
the width. Then boom, it shows you the moving averages
on the chart. Which is pretty cool. B ut maybe you want it actually overlayed
on the chart as you normally would have it when you add indicators.
To do that just go up here and set overlay to true.
Then botta bing botta boom, you have the indicator overlayed on the chart.
Like I said guys, this is a very basic strategy and example, but I just wanted to show you
the very basic opportunities you have with backtesting.
If you want to see a more advanced tutorial on how to back test some advanced strategies,
like this video and let me know in the comments if you want that, and I ll make a more advanced
tutorial. Because there s some pretty crazy things you
can to with this tradingview backtesing. Now that you know how to backtest, you should
backtest one of my strategies. Like this one, where I show you one of my secret strategies
that has a high pretty high success rate. Thanks for watching and I ll see you guys
next time.

</details>
