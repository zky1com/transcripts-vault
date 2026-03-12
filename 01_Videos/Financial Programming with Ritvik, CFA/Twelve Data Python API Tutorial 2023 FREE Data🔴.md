---
title: "Twelve Data [Python] API Tutorial 2023: FREE DataðŸ”´"
people_mentioned: ["Ritvik Dashora", "Twelve Data", "Alpha Vantage"]
channel: "Financial Programming with Ritvik, CFA"
video_id: "LMSYFJVcEo8"
url: "https://www.youtube.com/watch?v=LMSYFJVcEo8"
publish_date: 2021-01-22
duration: "10:46"
word_count: 1788
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
speaker_profiles: ["Ritvik Dashora - Meta"]
organizations_mentioned: ["Financial Programming with Ritvik, CFA"]
locations_mentioned: []
tools_mentioned: []
companies_mentioned: ["Meta", "Bloomberg"]
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

The discussion centers on data, technical, provide. The 12data API provides data related to stocks, forex andÂ cryptocurrencies very similar to alpha vantage and IEX cloud APIs but the twelvedata API. Today I am going to talk about one of the mostÂ used and free financial data provider Twelve Data and we learn how to. Now let's see how to use 12 data API directly in python for this what youÂ need to do is first get a free.

## Key Insights


- The 12data API provides data related to stocks, forex andÂ cryptocurrencies very similar to alpha vantage and IEX cloud APIs but the twelvedata API also provides.
- Today I am going to talk about one of the mostÂ used and free financial data provider Twelve Data and we learn how to use 12.
- Now let's see how to use 12 data API directly in python for this what youÂ need to do is first get a free API key.
- Now let's check outÂ how to get the technical indicators data checking out the API documentation, you can click on theÂ left-hand side technical indicators and.
- To remind you Alpha Vantage does provide around 50 technicalÂ indicators data and IEX cloud does not provide any data related to technical indicators.
- If you want to get the technical indicators data you need to write hereÂ technical indicator from this LIST of technical indicators.

## People Mentioned


- [[Ritvik Dashora]]




## Full Transcript

<details>
<summary>Click to expand full transcript (1788 words)</summary>

Welcome back to another API tutorial on gettingÂ 
financial data for free. Bloomberg is extremely expensive and this is my effort to help you guysÂ 
get as much financial data as possible for free. Watch this video till the end and there is aÂ 
beautiful gift for all my lovely subscribers. What is up everybody I am Ritvik Dashora and IÂ 
am back with a new video and some new learnings? Today I am going to talk about one of the mostÂ 
used and free financial data provider Twelve Data and we learn how to use 12 data API directlyÂ 
in python. In the last two videos, I talked about Alpha Vantage API and IEX cloud API. If you wantÂ 
to learn more you can click on this "i" button and Just to remind you that these two are alsoÂ 
free financial data providers. The 12data API provides data related to stocks, forex andÂ 
cryptocurrencies very similar to alpha vantage and IEX cloud APIs but the twelvedata API also provides Â 
100+ technical indicators data. Just to remind you Alpha Vantage does provide around 50 technicalÂ 
indicators data and IEX cloud does not provide any any data related to technical indicators. AlsoÂ 
for time series, there are several time frames available on TWELVEdata ranging from as low asÂ 
1-minute to 1-month. Now let's see how to use 12 data API directly in python for this what youÂ 
need to do is first get a free API key by clicking clicking on the link which is mentioned in theÂ 
description box. You'll have to make an account you can make it by clicking on sign up andÂ 
then this window will open just copy this API and store it somewhere there is a 12 data libraryÂ 
available which you can install by writing pip install twelvedata, but I don't recommend it becauseÂ 
sometimes it gives an error. So what we'll be doing here is we will be extracting information fromÂ 
"URL". If you remember in IEX cloud also we did the same so if you remember my IEX cloud API 
video, we'll be importing requests here as well in order to get information from a URL andÂ 
then this is my API key that I'll be using. I will disable this API after recordingÂ 
this video because I don't want you to use my API... just get your own API by followingÂ 
the steps I mentioned now let's check out the API documentation of TWELVE data the link is in theÂ 
description box. You can see that on left-hand side the TWELVEdata API provides information related toÂ 
the time series information related to stocks forex, cryptocurrencies, ETFs, indices and TechnicalÂ 
Indicators, etc. By clicking on stocks we can just scroll down a bit and get this URL which isÂ 
important and that will be using this URL to extract this information. Let's pasteÂ 
this URL here, so it will be getting information from the twelvedata.com API sorry website and it's aÂ 
time-series data. Symbol = 'MSFT' Interval is 1day output size is 12 and API is demo letÂ 
me just let me just do one thing is provide f-string here. Change this to API key. Also what weÂ 
can do here is provide ticker = say MSFT and interval = 1day letÂ 
me just change this ticker and this one to interval. So now this link is more user friendlyÂ 
I would say and then we'll be using this dot get request in order to get information in JSON
format and let's see what is the data. The data is actually I don't require meta, I just need valuesÂ 
here. This is in dictionary format because you know JSON provides data in dictionary format so whatÂ 
we can do here is let's just import pandas library import pandas as pd. data1, data1 pd.DataFrame. Perfect so we have got the data in the dataframe format. Let me just copy and paste this hereÂ 
and this one here. Now let's see what inputs we can provide in this URL. On checking onÂ 
the API documentation, we can see that the inputs can be actually symbol isÂ 
required, interval is required, exchange is optional, country, type, output size, format API keyÂ 
is important advance... order is important if I want data in ascending format or descending format. TheÂ 
default is descending from it okay and then start and end. This is an important parameterÂ 
very important parameter. I would say so just after the symbol and time zone which we don'tÂ 
require, we need to provide start date and then end [DATE] it just after this ticker let me justÂ 
put it like this and we can delete this time parameter and you can easily put this you canÂ 
easily provide a variable here and then put it in the string format to mention the startÂ 
and the end date if I do it like this then i should get the data of let me just change thisÂ 
data to 2020 started zero one zero one and then twenty twenty zero one one zero. Perfect so I'veÂ 
got the data from the first of January to the 10th of January now. Let's get the forex data ifÂ 
you go to API documentation and click on forex on right-hand side you can see that symbol is equalÂ 
to foreign exchange and all other parameters are exactly the same so what we need to do here isÂ 
just provide foreign exchange at the place of ticker and if you run this cell then you'll getÂ 
the foreign exchange data of the mentioned like between the mentioned dates. Now my most favorite: 
CryptoCurrency data. If you click on cryptocurrency here again it's exactly the same we just needÂ 
to provide symbol is equal to the cryptocurrency exchange and all other parameters are exactly theÂ 
same so I can just provide ticker is equal to BTC/USD and I can see that the data that I'veÂ 
got is this one and similarly for ETFs and indices data also what we need to do is we just need toÂ 
provide the ticker here IXIC represents NASDAQ and SPX represents S&P500. Now before movingÂ 
to the technical indicators mention in the comment box "Which topic you want me to make my nextÂ 
video on?" and I'll be considering the comment with the highest number of likes. Now let's check outÂ 
how to get the technical indicators data checking out the API documentation, you can click on theÂ 
left-hand side technical indicators and let's see uh how to get the b-bands which is BollingerÂ 
bands. Let's scroll down a bit and you will get the url which is useful to extract information ofÂ 
Bollinger bands and the URL is exactly the same except "bbands" which is present where it wasÂ 
time_series in the last URL. So what I will be doing here is let me just copy this entire codeÂ 
and paste it here and then change it to "bbands" actually I would introduce another parameter whichÂ 
is technical and then bbands. Let me just change a to technical and if I run this code I will get theÂ 
bollinger bands we can also get the open close and a low high price. So let me just go to the endÂ 
and write it like this. Let me just provide and "include_ohlc=true" and if I run thisÂ 
code I will get the Bbands with the open high low close and volume data. If you are interestedÂ 
in any other technical indicator what we need to do is we just need to copy um say this beta on theÂ 
place of technical and just write beta here to get the the the statistic beta function here so weÂ 
have a column called beta. Now you can see that it's fairly easy to use the TWELVE data API but itÂ 
can be fairly seen that it requires a lot of work if you want to work on uh the different typeÂ 
of inputs to modify the URL, so in order to help you and this is the GIFT to all my subscribersÂ 
I have made a code already and what you need to do here is run this code and it will ask someÂ 
information say time series or technical indicator I'm interested in time series data enter andÂ 
then ticker I can provide all these types of tickers and let me just see Tesla I'm interestedÂ 
in say 45-minute interval in descending order and '2020-01-01' to '2020-01-10' and you can see that the data of Teslaor 45-minutesÂ 
interval is now on the screen. You can also Let's go to check any other type ofÂ 
data time series and then I'm interested in say index data SPX data, so I'll just copyÂ 
this and paste it here I'm interested in say 1day data and in this case in ascending fromÂ 
2020-01-01 TO 2020-01-10 and you'll see that the S&P500 data from the 1st of January to 10th ofÂ 
January is available. If you want to get the technical indicators data you need to write hereÂ 
technical indicator from this LIST of technical indicators you'll have to write exactly asÂ 
mentioned in order to get the right data otherwise it will be an error so I'm interested inÂ 
say "ema" so I'll just copy and paste it like this and the type of data say Apple 45-minutesÂ 
descending order 2020-01-01 and then 2020-01-10, so this data of 45-minutes interval isÂ 
available and with ema technical indicator so it can be seen that it's very user-friendly codeÂ 
that I've made for you this code will be available on my google drive. For my new viewers, you can getÂ 
a free access of my google drive by subscribing to my youtube channel and then clicking on accessÂ 
to my google drive button and then just provide some basic details and I'll be using this emailÂ 
address in order to give you access of my personal google drive and this service is only availableÂ 
for my subscribers, if you like my work then you can support me by buying me a coffeeâ˜•. The link isÂ 
in the description box. Please justify my hard work by liking this video and sharing with your friendsÂ 
also subscribe to this YouTube Channel if you don't want to miss out my future videos. SomethingÂ 
great is coming in my upcoming video. Also mention in the comment box the topic that you want me toÂ 
cover in my future videos and get a free access of my google drive by following the steps thatÂ 
I mentioned. Thank you so much. See you in my next video. "SUBSCRIBE TO FINANCIAL PROGRAMMING WITH RITVIK"

</details>
