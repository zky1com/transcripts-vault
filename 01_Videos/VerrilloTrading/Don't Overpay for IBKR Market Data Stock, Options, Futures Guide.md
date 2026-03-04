---
title: "Don't Overpay for IBKR Market Data: Stock, Options, Futures Guide"
people_mentioned: ["Interactive Brokers", "Trading View", "North America"]
channel: "VerrilloTrading"
video_id: "zeUxXIJx_Ik"
url: "https://www.youtube.com/watch?v=zeUxXIJx_Ik"
publish_date: 2025-09-07
duration: "13:08"
word_count: 2473
content_type: "tutorial"
delivery_mode: "technique"
broad_category: "finance-investing"
subcategories: ["stock-analysis", "options-trading", "market-data"]
series_name: ""
episode_id: ""
primary_person: "Interactive Brokers"
host_names: []
interviewer_names: []
interviewee_profiles: []
speaker_profiles: ["Interactive Brokers"]
organizations_mentioned: ["VerrilloTrading"]
locations_mentioned: []
tools_mentioned: []
companies_mentioned: []
topics: ["stock-analysis", "options-trading", "market-data"]
tags: ["stock-analysis", "options-trading", "market-data"]
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

The discussion centers on data, market, trading. No, Trading View is actually already obtaining that data and then they see that you're subscribed to it on Interactive Brokers and then they. Now, when you subscribe to market data, you're making an agreement with the exchange that provides that market data. If you're trading through Trading View and you're trading New York Stock Exchange and American Stock Exchange symbols, then you need to subscribe to.

## Key Insights


- The thing that users need to remember here is that if you subscribe to market data at a point in the middle of a month or towards the end of the month, you will pay for the market data for the month, but then you will also get charged again for the market data when the new month begins.

- Now, one thing that's good about when you subscribe to Market Data is that if your broker allows an API connection outside of their platform or maybe they connect to a third-party software like Trading View, most of the time you'll be able to get the data that you subscribe to through your broker also on those thirdparty platforms.

- What I want to really demonstrate is that if you're only subscribed to NASDAQ, like network C, and you're not subscribed to network A or B, when you go on Trading View and you go to a a symbol that trades on New York Stock Exchange, you will not get the data for that because you're not subscribed to it.

- I'm not sure if this one is necessary if you're trading on Trading View, because the way Trading View works is they actually have their own connections to wherever they're obtaining the market data from, and then they just make sure that you've subscribed to those packages on your broker.

- No, Trading View is actually already obtaining that data and then they see that you're subscribed to it on Interactive Brokers and then they allow you to get the real-time data on Trading View.

- So if you're trading through Trading View and you're trading New York Stock Exchange and American Stock Exchange symbols, then you need to subscribe to all three networks.




## Key Quotes


> This video is going to contain everything you need to know about subscribing to market data with Interactive Brokers for US stocks, US options, futures.


> Also, how to get market data onto other platforms when you connect to Interactive Brokers there like on Trading View.


> Press the like button if you enjoy this content.


> I'm over here on Interactive Brokers client portal and I'm logged into my account and I've gone to the top right hand corner and selected settings.






## Full Transcript

<details>
<summary>Click to expand full transcript (2473 words)</summary>

This video is going to contain everything you need to know about subscribing to market data with Interactive Brokers for US stocks, US options, futures. Also, how to get market data onto other platforms when you connect to Interactive Brokers there like on Trading View. Let's talk about it right now. Press the like button if you enjoy this content. I'm over here on Interactive Brokers client portal and I'm logged into my account and I've gone to the top right hand corner and selected settings. That brings you to this window. You will also have to select which account if you have multiple accounts and then you'll get brought here. Then go ahead and select market data subscriptions. Now this pertains to real time market data. Real-time market data is important because it gives you the most up-to-date quotes for whichever markets you're tracking. If you don't subscribe to real-time data, you will have delayed data which is typically delayed by 10 to 15 minutes. Now, when you subscribe to market data, you're making an agreement with the exchange that provides that market data. And how you're doing this is typically through a middleman, which is normally your broker. Sometimes it could be a software platform or market data vendor, but in this case with Interactive Brokers, you do it directly through them. Now, the exchange categorizes market data subscribers in two ways. You're either a professional market data subscriber or you're a non-professional. Now, if you have an institutional account, typically the broker will automatically force you into being a professional subscriber status. But if you are an individual trader and you just opened up a personal brokerage account, you can categorize as a non-professional. What that really means is I get to pay lower fees for market data. And some of these fees can be pretty negligible. Like if you look at the fee for CME realtime or US options data, it's USD$150 a month. And that's pretty much all it costs. So, when you first go into your Interactive Brokers account, you have to subscribe to some real-time data at some point, or else you're going to get prompted with annoying messages in the trading platform. But before you do that, you need to make sure that your subscriber status is set to non-professional. So, you go over here and you click configure, set it to non-professional, and they're going to give you a questionnaire which is going to confirm that you're not a financial professional of any kind. they might force you to categorize as a professional subscriber. So, that's something you got to keep an eye out for. Now, one thing that's good about when you subscribe to Market Data is that if your broker allows an API connection outside of their platform or maybe they connect to a third-party software like Trading View, most of the time you'll be able to get the data that you subscribe to through your broker also on those thirdparty platforms. So, I'm going to show you in a moment how all these subscriptions that I've subscribed to here in IBKR, I can also get them on Trading View when I log into IBKR on Trading View. There's one other really important thing that you need to know about subscribing to Market Data, and that's about when you subscribe to it. So, market data subscription fees are charged in full at the beginning of a calendar month. And when you subscribe to it, it gives you market data for that whole calendar month. The thing that users need to remember here is that if you subscribe to market data at a point in the middle of a month or towards the end of the month, you will pay for the market data for the month, but then you will also get charged again for the market data when the new month begins. So for example, today we are the 26th of August. If I initiate a new market data subscription today, I'll be charged for it today. When we go into the next month, September, I'll be charged again at the beginning of September. That's why generally speaking, if you need to initiate a new market data subscription, it's recommended to do it at the beginning of the new month and not at the end of the previous month, unless you don't mind getting double charged. Let's talk about what subscriptions that you need for trading US stocks, US options, and also US futures. Now, there's two ways you can go about this. You can go about it the easy way, which has a little bit of a higher cost, and that's going to be using quote bundle packages that Interactive Brokers has. The second way is going to be subscribing to each exchange that you need individually, which could result in a lower cost depending upon how many exchanges you need to subscribe to. So I'm going to click on the gear icon which is going to give me the list of market data subscriptions that I can subscribe to. So let's click configure. Okay. So it starts by telling you which subscriptions that you're automatically subscribed to including some that are complimentary that are automatically provided by Interactive Brokers. So I'll scroll down. Some users ask about snapshot data. Generally this is not that important. All it means is that if you don't subscribe to real-time data for a symbol, you can generate a one-time realtime quote using something called a snapshot. You can do this in their trading platforms. So, we're primarily talking about the US market here. So, we go to North America and I'll start with the quote bundles because this is the simplest thing to understand. So, I brought down the drop-own list there. Now, if you need market data for US stocks, then they offer this US equity and options add-on streaming bundle. So, what this gives is US equities data for the three stock networks. Now, I don't want to lose you here, but this is how it works. US stocks, they trade on three primary networks. Network A, network B, and network C. The other names for those are network A is the New York Stock Exchange, network B is the American Stock Exchange, and network C is the NASDAQ stock exchange. Now, where users kind of get confused here is they think, well, I'm trading a lot of stocks on NASDAQ. Do I really need the network A and B? And the answer to that is it depends. If you use a time and sales, meaning you're viewing the transactions that come into the market one at a time, then I would say you do need all three networks because there are trades taking place on stocks that are primarily on NASDAQ. Some trades are taking place on the New York Stock Exchange and the American Stock Exchange for those exact symbols. So, if you are trading US stocks, I would generally recommend getting all three networks. Now you can grab this bundle right here. But the condition for grabbing this bundle is that they force you to get this NP subscription down here which is called US equities snapshot and futures value bundle. And this one costs 10 USD a month for non-professionals. But they will wave off the 10 USD when you generate more than $30 in commissions for your account. So if you're actively trading in your account, then you can typically just do this. You can grab the $10 a month one here and then you can grab the $450 a month here to get the US stock real-time data. Keep in mind this is all top of book data, level one data. This does not include level two data or the extended order book for your stocks. Now, one good thing about doing it this way is that they also include top of book or level one data for CME group futures. So like your S&P 500 futures or your NASDAQ futures, currency futures like euro against the dollar or Canadian against the dollar futures. So that's a little bit of a bonus. So the total cost for this would be $10 a month plus $4.50 a month for non-professionals. And then if you do more than $30 in commissions, they will wave off the 10. So it will pretty much cost you $4.50 a month. If you're primarily trading US stocks and options, I would also recommend getting the SIBO add-on bundle, which is just going to give you more transactions recorded on the time and sales. I'm not sure if this one is necessary if you're trading on Trading View, because the way Trading View works is they actually have their own connections to wherever they're obtaining the market data from, and then they just make sure that you've subscribed to those packages on your broker. If you've subscribed to them with your broker, then you get the market data on Trading View from wherever they're obtaining it from. So don't think that Interactive Brokers is providing the market data to Trading View. No, Trading View is actually already obtaining that data and then they see that you're subscribed to it on Interactive Brokers and then they allow you to get the real-time data on Trading View. Now, if you're trading US stocks and options, I'm going to show how to subscribe to the individual exchanges for those people that potentially may not be actively trading, so they don't want to pay this extra $10 a month. If you guys are enjoying the video up until now, I'd really appreciate if you press the like button and subscribe to the YouTube channel for more educational videos like this. If you guys are interested in checking out Interactive Brokers, but haven't done so yet, I really would appreciate if you check them out using the link down below in the description. It helps out the channel and helps justify the time it takes to make some of these videos. I use them myself. I've been using them since 2019. Now, if you're trading futures actively on Interactive Brokers, you can also grab this subscription over here, which is the US Futures Value Bundle Plus, which will give you the full order book. Actually, I wouldn't say it's full order book. It's only 10 levels of market depth for all four major CME futures exchanges. Let's go on and show the second method of subscribing to market data for US stocks and options which is by subscribing to each exchange individually. In the same market data selection list here, I'm going to select level one NBBO. NBBO stands for national best bid and offer. So it basically gives you the most realtime price and the best bid and offer currently in the marketplace for security. So, I'm going to scroll down a bit and you can subscribe to any level one data here, but we're going to talk specifically about US stocks and options. You can see I also have CME real time, which is futures data. So, I'll scroll down until we see some of the stock exchanges. Remember, there's three networks here. There's network A, B, and C. Could you subscribe to only one of the three networks and then get the data for the others? If you're logged into Interactive Brokers Trader Workstation or maybe their web platform, I think you can actually get away with just subscribing to NASDAQ because they do provide complimentary quotes for the other two exchanges. Though, this may not apply to all tickers. You have to test it yourself. Now, the catch to this is that if you're trading through Interactive Brokers on Trading View, then this is what happens. So, if I'm subscribed to NASDAQ and I go over to my Trading View platform, you can see I get market data for stocks that trade on NASDAQ like Apple. So, sometimes you'll see a message at the bottom there that says, "Caution, market data is not available." Probably that's due to the fact that you're already logged into your Interactive Brokers user in another place. In my case, I'm logged in to my live account on this other tab here, which is using the real-time quotes, and those quotes are being shared with this demo account, which is the reason why I can't see them here. What I want to really demonstrate is that if you're only subscribed to NASDAQ, like network C, and you're not subscribed to network A or B, when you go on Trading View and you go to a a symbol that trades on New York Stock Exchange, you will not get the data for that because you're not subscribed to it. So you'll get this at the top here which is going to say like nice C by SIBO1 or you might even just see a delayed symbol there telling you that the market data is delayed because you're not subscribed to it. So if you're trading through Trading View and you're trading New York Stock Exchange and American Stock Exchange symbols, then you need to subscribe to all three networks. So you can grab all three networks here if you need them. So you would do network C right there. Then you would scroll down until you see NIC network A. Grab that one right there. Then you would scroll down until you see Nicey American. This is network V. And you would select that one right there. And if you need options data, you can subscribe to it right here. OP R A. Just grab it right there. So now I'll close this window just to show that when I go on Trading View. Now when I go over to my watch list and I selected QQQ, you can see that I'm actually getting the real-time quotes updating there on Trading View. Now have a look at what happens when I select another NASDAQ symbol because I'm subscribed to NASDAQ. You see I get the quotes. Then I'll select CAT which trades on New York Stock Exchange. And you'll see I don't get this one or just looks delayed or something. Reason is because I'm not subscribed to New York Stock Exchange on on my account. Okay. I also get the options data. Let it load. There we go. If you guys want to go watch my video about Trading Views now supporting options trading on Interactive Brokers, definitely go watch it right over here and check out this playlist for a whole playlist of Interactive Brokers tutorials, learning more about their services that they offer. Thanks for watching. I'll see you guys in the next video. Take care.

</details>
