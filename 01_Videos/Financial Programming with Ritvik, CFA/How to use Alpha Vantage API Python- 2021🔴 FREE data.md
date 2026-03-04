---
title: "How to use Alpha Vantage API Python- 2021ðŸ”´ [FREE data]"
people_mentioned: ["Ritvik Dashora", "Alpha Vantage", "Technical Indicators", "Algorithmic Trading"]
channel: "Financial Programming with Ritvik, CFA"
video_id: "PytQROAncxg"
url: "https://www.youtube.com/watch?v=PytQROAncxg"
publish_date: 2021-01-13
duration: "11:46"
word_count: 1946
content_type: "tutorial"
delivery_mode: "technique"
broad_category: "finance-investing"
subcategories: ["stock-analysis", "portfolio-management"]
series_name: ""
episode_id: ""
primary_person: "Ritvik Dashora"
host_names: []
interviewer_names: []
interviewee_profiles: []
speaker_profiles: ["Ritvik Dashora - Google"]
organizations_mentioned: ["Financial Programming with Ritvik, CFA"]
locations_mentioned: []
tools_mentioned: []
companies_mentioned: ["Google"]
topics: ["stock-analysis", "portfolio-management", "data"]
tags: ["stock-analysis", "portfolio-management", "data"]
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

The discussion centers on data, need, alpha. Time-series data or I would say financial data,Â the statements data. Anyways so let's move to the fundamental dataÂ uh in order to get the fundamental data which is actually the statements data. We need to import IÂ would say from alpha_vantage dot fundamental data import fundamental data the key is the same whichÂ is.

## Key Insights


- Time-series data or I would say financial data,Â the statements data.
- Anyways so let's move to the fundamental dataÂ uh in order to get the fundamental data which is actually the statements data.
- We need to import IÂ would say from alpha_vantage dot fundamental data import fundamental data the key is the same whichÂ is.
- Me just delete it forÂ some time data is equal to fd dot get you can get balance sheet data, cash flowÂ.
- Data frame formatÂ and you can see the data is monthly.
- TheÂ monthly data output here if you're interested in interval data for example in this caseÂ if I write ticker as uh.

## People Mentioned


- [[Ritvik Dashora]]




## Full Transcript

<details>
<summary>Click to expand full transcript (1946 words)</summary>

If you want real-time financial data for freeÂ 
then watch this video till the end and there is also a small gift from my side to all my lovelyÂ 
subscribers. What is up everybody, I am Ritvik Dashora and I am back with a new video and someÂ 
new learnings. Today, I am going to talk about one of the most popular and a free data-providerÂ 
Alpha Vantage and how to use Alpha Vantage API directly in python such that you get all theÂ 
financial information for free. In the last video, I talked about IEX cloud API and you can click onÂ 
this i button to watch more about that, and just to remind IEX cloud is also a free data provider.Â 
Alpha Vantage provides data related to stocks such as time-series data or I would say financial data,Â 
the statements data. It also provides data related to Forex, Cryptocurrencies and there's also oneÂ 
great feature of Alpha Vantage that it gives us information about the Technical Indicators.Â 
It covers more than 50 technical indicators so it's quite useful if you directly synchronize itÂ 
with python and do your analysis for Algorithmic Trading purposes. For time-series data, severalÂ 
frames are available on Alpha Vantage and it goes as low as one-minute interval to monthlyÂ 
interval. Now let's see how to use alpha Vantage API in python. First of all, what you need toÂ 
do is go to uh the Alpha Vantage website. The link is in the description box and claim yourÂ 
API key. It's free of cost... just provide some very basic details here by clicking on thisÂ 
button which is "Get free API key". You'll get an API that you'll be using for extractingÂ 
financial information. The next step is to "pip install alpha_vantage" on whatever platformÂ 
you're using. Maybe you're using jupyterlab or google colab or spyder etc. pip install alphaÂ 
underscore vantage. It will take some time um to install it and as you can see it's alreadyÂ 
satisfied in my computer but in your case, it will be downloading some files. Now let'sÂ 
see the API documentation of alpha vantage um the link is in the description box. Just clickÂ 
on that and this is the API documentation you can see that on the left hand side it provides dataÂ 
related to stock time-series, Fundamental data, Forex, cryptocurrencies and technical indicatorsÂ 
and you can see the high usage parameters such as intraday or company overview or daily adjustedÂ 
stock time series data etc. It's quite big documentation but I would recommend you to skim itÂ 
at least such that you would have a basic idea of the API documentation. Now let's see one by oneÂ 
how to extract these financial informations such as time-series, Fundamental data etc. In python inÂ 
order to extract time series data, what we will be doing here is from alpha underscore vantage dotÂ 
time series import time series and then this is the API key that I got by making this account thatÂ 
I showed earlier. I'll be disabling this API key such that you guys don't use it just go here it'sÂ 
free of cost. Just get your own API and use it for your purposes um. Now what we need to do hereÂ 
is let me just introduce this parameter which is ts is equal to time series and then we need toÂ 
provide the API key which is key is equal to API key and the next thing is output formatÂ 
in my case I'm not interested in JSON format I'm interested in pandas from it so uh we'll beÂ 
getting the output uh which will be in data frame format so let me just run this uh cell now whatÂ 
I will be doing here is data is equal to ts it's fairly easy then get ts dot get daily adjustedÂ 
entry extended monthly monthly adjusted etc. You can see it in the API documentation thatÂ 
these are the data that will that can be provided by alpha vantage and we can directly getÂ 
it from here so on on writing get um let me just go to the monthly adjusted for example soÂ 
um the information that is required in this parenthesis is symbol which is the ticker. IfÂ 
you remember in IEX cloud, I explained how to use symbol which is ticker in IEX cloud. In thisÂ 
case, we just need to provide it in the string format which is AAPL for apple for MicrosoftÂ 
it will be MSFT and so on and let's see what is the data now. If I run this cell, I getÂ 
it in actually I get two output and I'm just interested in the first one which is if I take theÂ 
zeroth one then I get it this one which is in the data frame format pandas data frame formatÂ 
and you can see the data is monthly. If we had provided a get daily adjusted it would be dailyÂ 
data so we have open high low close adjusted close volume etc. Similarly, as I mentioned that if weÂ 
used in this case I have let me just change it to daily adjusted daily adjusted and then inÂ 
this case let's see apple and then by running it we will get the daily data. If youÂ 
are interested in intra-day um data uh with an interval of just 15 minutes thenÂ 
we just need to provide get entry ticker an interval is equal to 15 minutes or five minutesÂ 
or even one minute so for example, in this case, you can see the output is 15 minutes interval dataÂ 
if I change it to five minutes it will be the five minutes interval data which is quite useful uhÂ 
for algorithmic trading. I would say and doing the interval analysis you can make candlesticksÂ 
here etc. You can do a lot of analysis here. Before going to the fundamental data, um IÂ 
would like you to tell me in the comment box which topic you want me to make my next videoÂ 
on? And the comment with the highest likes will be the topic that I'll beÂ 
considering for my upcoming videos. Anyways so let's move to the fundamental dataÂ 
uh in order to get the fundamental data which is actually the statements data we need to import IÂ 
would say from alpha_vantage dot fundamental data import fundamental data the key is the same whichÂ 
is this, one you would have your own key. uh fd is equal to fundamental data the key is providedÂ 
and then output format is equal to pandas and like it's exactly the same as that we did for theÂ 
time series data then what you need to do here is actually let me just delete it forÂ 
some time data is equal to fd dot get you can get balance sheet data, cash flowÂ 
statement, company overview or income statement um data quarterly and annual. So letÂ 
me just take the income statement annual in the parenthesis I am justÂ 
required to provide the symbol which is ticker. Let me just write MSFT and then let's seeÂ 
what the data. So again you can see the data is um again there are two output I am just interestedÂ 
in the first one so data is zero this is the income statement but unfortunately, the um lineÂ 
items are on the column header and I'm interested I would be interested if it is in the transposedÂ 
format. So yeah exactly so this is the income statement. All the items related to incomeÂ 
statement are on the left-hand side and you can see the uh the financial date ending is 2020,Â 
2019, 2018, 2017, and 2016. So last five years of data and old data. If it were quarterly thenÂ 
it would have been quarterly data the currency and everything is here total revenue it's quiteÂ 
useful information that will we can use for our analysis purpose so and if you are interested inÂ 
say balance sheet data then you need to provide or say cash flow quarterly data for example youÂ 
just need to provide cash flow quarterly and MSFT and let me just first see what the data is.Â 
Perfect so the data let me just write zero and .T exactly so this is the cash flow statement. ForÂ 
balance sheet, again you just need to write fd.get underscore balance sheet and then provideÂ 
the ticker now you can see that the API documentation of alpha vantage and I wouldÂ 
say writing all these lines here is a kind of a LOT OF WORK. Here's a GIFT from my side to allÂ 
my subscribers. I have written a code here um that I'll be sharing with my subscribers in which youÂ 
what you need to do here is I've made different cells for different types of data and you justÂ 
need to provide the basic details and this will give you the output that you need. So for example,Â 
in this case, this is cell is for time series data. If you run this cell, it will ask someÂ 
information such as what ticker are you interested in MSFT MSFT and then what type of data you areÂ 
interested in for example in this case monthly, and then you'll see that you have got theÂ 
monthly data output here if you're interested in interval data for example in this caseÂ 
if I write ticker as uh ford and interval um what interval five minutes for example andÂ 
then you'll see the output of which is five five minutes interval data here. So it's kind ofÂ 
user-friendly code that I have written here for you for all of my subscribers. And for similarlyÂ 
for the fundamental data you just need to run this code here it will ask for some basic informationÂ 
such as ticker which is again let's say Apple and then annual data period what type of statement I'mÂ 
interested in income statement so income statement and then you'll see that you've gotÂ 
the income statement of apple annual um income statement of apple similarly for foreignÂ 
exchange for cryptocurrencies and for technical indicators I have made a code for you now. ForÂ 
my new viewers, I'll be saving this code on my google drive and all my subscribers can have AÂ 
FREE ACCESS OF MY GOOGLE DRIVE. What you need to do here is just subscribe to my youtube channelÂ 
and click on the get access of my google drive button on my youtube channel and then just provideÂ 
some basic details and I'll be using that email address to give a free access of my personalÂ 
google drive where I will be saving this code and not just this code there are a lot many umÂ 
codes and I would say files that are saved on that uh platform on that drive and you can use allÂ 
of them for your personal users and there will be no copyright issues from my side. Now itÂ 
can be fairly seen that I'm doing a lot of work for you guys so I don't need anythingÂ 
from you just LIKE this video and support me and also share it with your friends.Â 
If you find this video informative, subscribe to my youtube channel if you don'tÂ 
want to miss out on my future videos, and don't forget to comment the topic that you want meÂ 
to make my next video on. Also get a free access to my google drive by following the steps that IÂ 
mentioned already. Thank you so much see you soon.

</details>
