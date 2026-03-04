---
title: "How to use MT4/MT5 Python API to get Financial Data [FREE]ðŸ’¹"
people_mentioned: ["Ritvik Dashora", "Dot Login", "Learn More", "Financial Programmers"]
channel: "Financial Programming with Ritvik, CFA"
video_id: "XM0nAyVI0gA"
url: "https://www.youtube.com/watch?v=XM0nAyVI0gA"
publish_date: 2023-08-19
duration: "17:45"
word_count: 3428
content_type: "tutorial"
delivery_mode: "technique"
broad_category: "ai"
subcategories: ["ai-safety", "ai-regulation", "ai-jobs", "ai-agents", "ai-coding", "ai-economics"]
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
companies_mentioned: ["Google", "Meta"]
topics: ["ai-safety", "ai-regulation", "ai-jobs", "ai-agents", "ai-coding", "ai-economics", "lead-generation"]
tags: ["api-integration", "data-tools", "ai-coding", "lead-generation"]
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

The discussion centers on i'll, right, time. One thing I'll do it for one minute right so let's click onÂ one minute from so I'll just write date time. Write empty I'll press Tab and then I'll just write let's see yeah it's time frameÂ D1 it's a daily interval right. From so I'll just write date time dot now I'll have to import dateÂ time as well so I'll just come here.

## Key Insights


- One thing I'll do it for one minute right so let's click onÂ one minute from so I'll just write date time.
- Write empty I'll press Tab and then I'll just write let's see yeah it's time frameÂ D1 it's a daily interval right.
- From so I'll just write date time dot now I'll have to import dateÂ time as well so I'll just come here.
- Import date time actually I'll have to do home date timeÂ import date time right date time dot now and then.
- I'll just write accountÂ info is equal to NT dot account info that's it right if you run this cell you'll.
- Is done now my python code is now connected with MT5 right now we have to extractÂ information from MT5 into python.

## People Mentioned


- [[Ritvik Dashora]]

- [[Dot Login]]




## Full Transcript

<details>
<summary>Click to expand full transcript (3428 words)</summary>

Hello Hello MIC Test Follow Captions to Learn More! [Music] this video is very crucial for you guys becauseÂ 
the next video will be about how to make MT5 python trading bot and if you want to learn howÂ 
to make a trading bot then you should watch this video as well hello Financial Programmers,Â 
Iâ€™m Ritvik Dashora and I'm back with a new video and some new learnings in the last video weÂ 
learned about how to bridge MT5 with trading view via alerts webhook functionality and in thisÂ 
video I'm not going to trading view I'm using this MT5 python API to extract financial data inÂ 
Python and that is for free if you're new to my YouTube channel guys on this channel I uploadÂ 
videos related to making trading boards using some highly valuable Finance apis making some PineÂ 
script trading strategies or using AI in finance so if this is something that you are interestedÂ 
in then you should click on the Subscribe button and also hit on the Bell icon because there areÂ 
many playlists that are in my pipeline that will be uploaded on my YouTube channel for free theÂ 
topics that we are going to cover in this video so how to use MT5 Python API to extract financialÂ 
data the first thing that we'll be doing is we'll be installing MT5 python API package that's freeÂ 
second is we will authenticate it that is we will login into that one which will be integratedÂ 
with the MT5 platform that I download loaded in the last video if you remember we are using ICÂ 
markets as our backend broker you can have any other broker as well on the back end of MT5 thenÂ 
yes in the end we will be extracting the financial data in Python from MT5 so yes this is how weÂ 
can install MT5 in Python that is PIP install MetaTrader5 you can just click here to copy itÂ 
I will paste this link in the description box you can just click on that and come to this URLÂ 
let's come back to our python platform actually I'm using Jupiter lab in this video I try changingÂ 
my platforms for you guys sometimes I use vs code sometimes I use Google collabs just for you guysÂ 
to have a have an understanding of all these three different types of platforms perfect so I'll justÂ 
paste pip install MetaTrader5 I've already done the installation so most probably it will justÂ 
show that it's already satisfied but let's wait for some time yeah so its requirement is alreadyÂ 
satisfied in my case in your case it would be installing MetaTrader 5 python package okay soÂ 
we'll we can import MetaTrader5 as empty right shift enter now if you remember from the lastÂ 
video my login password is this one it's a demo account and I have showed you how to make a demoÂ 
account on IC markets but as I mentioned in the beginning you can have it for any other broker asÂ 
well right so the first thing that we'll be doing is empty dot initialize so when you run thisÂ 
cell it will open the MT5 platform that is the MT5 terminal automatically so you can see it hasÂ 
been opened here automatically I have one trade that is open here I'll just click on Cross as ofÂ 
now so yes as you can see that MT5 terminal got opened automatically right now we have to loginÂ 
so if you remember from our last video I created a demo account on IC markets I showed you how toÂ 
make it yeah and definitely you can do it for your broker as well and this was my login credentialsÂ 
it's a demo account so I'll just run this and then I will log in into it which is empty Dot LoginÂ 
inside this I'll provide login comma password comma server and it will give me true so myÂ 
authentication is done now my python code is now connected with MT5 right now we have to extractÂ 
information from MT5 into python right this is the the documentation you can click here to go to theÂ 
documentation of this of this python package again I'll be mentioning this link on the descriptionÂ 
box you can just click on that and as you can see we have done the first step which is PIP installÂ 
MetaTrader5 and these are all different types of functionalities or functions that we can use inÂ 
MT5 Python package right I'm not going to like show you all different like all these functionsÂ 
one by one because most of them are of no use we will be using some of them such as copy ratesÂ 
right and then in the next video we'll be using order send position Etc right so this copy ratesÂ 
from is the one which is very useful to extract the historical prices I'll just come here so let'sÂ 
just write is equal to Mt dot I pressed Tab and it showed me the entire I would say list of all theÂ 
functions that I can use right it's copy rates from inside this I'll just provide the name ofÂ 
I would say the ticker of this particular of any company that we want to extract data for so if youÂ 
remember in the last video we used the TSLA.NAS which is the ticker of Tesla for IC Brokers MT5Â 
like if you remember from the last video this instrument would be different for you or at leastÂ 
for your broker so you should definitely cross check it and how to do it just refer to my lastÂ 
video I want to see how to get the instrument for your broker I want it for daily intervals soÂ 
I'll just write empty I'll press Tab and then I'll just write let's see yeah it's time frameÂ 
D1 it's a daily interval right from so I'll just write date time dot now I'll have to import dateÂ 
time as well so I'll just come here and import date time actually I'll have to do home date timeÂ 
import date time right date time dot now and then comma How many I would say rows I want to extractÂ 
so let's just write 100 right shift enter so this an issue here date time is not defined I'll haveÂ 
to run this cell as well perfect so yeah let me just make some space here so rates yeah so you canÂ 
see this is the entire array of the time series data that we have in front of us and if you go inÂ 
the end you'll see what type of data the first one is time which is basically timestamp we'll have toÂ 
convert it into date time into a readable format then open high low close tick volume spread andÂ 
real volume right this is the entire array that can be actually used for any historical dataÂ 
analysis of this particular stock and actually we can just generalize it a bit more so I'll justÂ 
write ticker it's TSLA.NAS right interval is equal to empty dot time frame D1 from date is equal toÂ 
this one and then number of rows is equal to 100 and actually you can just write copy and pasteÂ 
it here to make it like this so because I would not like to change my this main line all the timeÂ 
so we'll just write interval and then this one is from date and the last one is number of rows asÂ 
simple as that guys if you do it we'll see the same result so now how to get account informationÂ 
here the account the demo account that we created in our last video if you want to extract all theÂ 
information related to that then there is a way to do it on python as well I'll just write accountÂ 
info is equal to NT dot account info that's it right if you run this cell you'll see this isÂ 
the entire information about my account so the Leverage is 1000 limit orders 200 balances aroundÂ 
1 million if you remember I selected 1 million fantasy money for this particular demo account inÂ 
the last video margin and then the name is account is demo USD etc etc so this is how we extract theÂ 
account information now when it is used when we'll be making our trading board in the next video weÂ 
would require this particular information which is the balance that we have in our account andÂ 
definitely we need to consider this to calculate the quantity to trade in any particular I wouldÂ 
say trading bot so yeah let's move ahead to the next function but yeah before that if you wantÂ 
to extract some information from this particular thing you'll see that we just we can just writeÂ 
account in four dot and then if you press tab you will see all the different things that youÂ 
can extract so suppose balance right I'll just double click on it and then shift enter you'll seeÂ 
this is the balance if I just write account info dot say login right it will give me the accountÂ 
number which is this one and so on right you can do it for other things as well now if you want toÂ 
see how many Securities or how many instruments are available on this particular platform whichÂ 
actually is dependent on the poker that we are using I just want to know the count of SecuritiesÂ 
that I can trade on IC markets MT5 platform so how to do it I'll just write num symbols is equalÂ 
to empty dot let's press Tab and then symbol total right so it will give me the total numberÂ 
of of symbols the total number of instruments that are available on MT5 that I can actually useÂ 
to trade in the trading bot that we want to build now if you want to get the entire information ofÂ 
all the different symbols that are available so I'll just write symbol info is equal to empty dotÂ 
symbol info empty dot symbol and then get right and that's it you'll see all the differentÂ 
like all 2 243 symbols info is now available and you can see it in front of you yeahÂ 
just like let's just go and control f which is I'll just search for a particularÂ 
company name say again Tesla only so if we just write Tesla you'll see this is the entireÂ 
information of Tesla about this particular symbol and the ticker for Tesla is TSLA.NAS it is listedÂ 
in NASDAQ there's a stock CFD that we are trading here again other other things like currenciesÂ 
USD margin Etc so this is how we extract the symbol information now when this is used this isÂ 
mostly used when we make a trading bot which runs multiple Securities in parallel right so in thatÂ 
case we have to understand the lot size we have to understand whether it's a CFD or something else weÂ 
have to understand the exchange sometimes it's on some other exchange like New York Stock ExchangeÂ 
or on NASDAQ Etc so these are some information that we need to analyze before making a tradingÂ 
bot and running multiple Securities in parallel so yeah that's why symbol get functionality is veryÂ 
very crucial as well now from this I want like all the information for suppose just Tesla rightÂ 
so what I'll do is I'll just write empty Dot and then symbol info right inside this I'll provideÂ 
TSLA Dot N A S which is the Picker of Tesla for IC markets MT5 platform right I'm repeating itÂ 
again and again but you should always understand this would be different for you shift enter you'llÂ 
see that this is the entire simple information if you want it in dictionary format just write DotÂ 
and then under underscore as and then ticked right you'll see this in a dictionary formatÂ 
so what are different things available so we'll see the name which is basically the symbol TeslaÂ 
TSLA.NAS the IC information is available company name other things like currency Volume last HighÂ 
last low bid ask Etc so all the different types of trading information is available here and andÂ 
if you remember guys I have not yet paid anything and I'm extracting all this information for freeÂ 
now extract OHLC data directly just before that guys I have a very important information toÂ 
share recently I launched a course on python for financial programming so if you are tryingÂ 
to Learn Python for finance from scratch that this is something that you might be interestedÂ 
in just go to my website which is fbrethwik.com python over here you will see two buttons IndianÂ 
candidates non-indian candidates so you can click as per your location it will redirect you toÂ 
this the main website where the entire course information is available you'll see that there areÂ 
five sessions 10 chapters 22 videos 10 quizzes and three assignments with two live projects and thisÂ 
is the entire syllabus of this course for all the people who are interested to Learn Python fromÂ 
scratch and who are struggling learning python on their own I highly recommend it because it'sÂ 
very very affordable and I I have covered a lot of things from a very very simplistic eyesightÂ 
and in the end in session four and five you'll see stock analysis and Investment Portfolio creationÂ 
projects which are my personal projects we did it using some financial analysis if you use RTK40Â 
code you'll get an instant 40 discount which is only available for the first 100 candidates so yesÂ 
guys I'll see you in the course let's come back to our code right so I'll just import pandas as PDÂ 
let's make some space again okay so empty dot if you just write copy and press tab you'll see allÂ 
different things we use copyrights from I'll just use this another one which is copy rates rangeÂ 
right inside this I'll provide the instrument ticker name the interval if you remember whichÂ 
is empty dot I'll just write capital T and then press tab let's do one hour right in this case IÂ 
am actually extracting one hour of data because actually we can let's see what all different inÂ 
intervals are available so I'll just write Tab and then time frame okay so it's one day one hourÂ 
12 hours two hour three hour four hour and so on then one minute okay so one minute data is alsoÂ 
available here and so on so let's do one thing I'll do it for one minute right so let's click onÂ 
one minute from so I'll just write date time and inside this I'll provide 2023 today is 21st ofÂ 
July the date on which I am recording this video so let's write 27 and then comma let's just do 21Â 
only so it will give me all the minute interval data for today right comma Now here in this caseÂ 
I don't need to provide the number of rows I will just I just need to provide it from one date toÂ 
another one that's why it's copy rates range so the second one is date time top dot now if IÂ 
press shift enter you'll see the entire minute by minute data of well it starts from 21st JulyÂ 
2023 till today there is a limit on the extraction of I would say minute by minute data at least forÂ 
the demo account so that's why we cannot like we cannot extract information from say 20 2010 orÂ 
2012 or something like that like for minute by minute information there would be a limit here forÂ 
example if I just click on say 2010 here it will be showing nothing so there's no data or they areÂ 
not showing it they are not providing it for free so I'll just write 2023 as of now so now we haveÂ 
to convert it into pandas data frame format so I'll just write PD dot data frame and inside thisÂ 
let's provide everything which is this one perfect so OHLC is equal to this one now we have toÂ 
convert the time frame I would set the timestamps into the date time format because this is notÂ 
readable this minute by minute data but we have to see that what's the exact time of this particularÂ 
time step so we will convert it with I would say fairly simple so we'll just write OHLC and I'llÂ 
replace this the same column only so which is the time would be pd.2 date time right then insideÂ 
this I'll write let me Zoom it a bit just one second yeah I think now that's good okay so insideÂ 
this I'll provide OHLC time only right comma and then unit is equal to S which is which goes toÂ 
seconds if I run this particular cell you'll see this column is now changed to the readable formatÂ 
so it starts from 2027 2023 now why it's 2020 not 2021 because it follows some other I would sayÂ 
time zone I follow Indian time zone as of now so that's why there's a difference but if youÂ 
see this is the entire one day data and you can see that it's all the rows have one minute say gapÂ 
between each other and yes we can definitely plot it so I'll just import plotly dot Express as PXÂ 
right the figure is p x dot line I want line chart and then OHLC comma the x-axis is OHLC and thenÂ 
time the y-axis is OHLC and close fake dot show and that's it if you run the cell it willÂ 
create a plot of Tesla for last Monday right you can just like select a particular range toÂ 
get more information or to zoom it or something like something like that so this is the entireÂ 
code that we have written and yes guys I will be saving this code in my Google Drive as well myÂ 
already existing subscribers know that I share my Google Drive access my new subscribers just waitÂ 
for a minute but before that guys if you liked even one thing about this video just click on theÂ 
like button because it's really really important for the algorithm and also mention in the commentÂ 
section if you want me to cover anything specific for the next video in the next video as IÂ 
mentioned I'll be making the trading board on MT5 and python so so while watching this videoÂ 
if you have any questions just mention in the comment section and I will answer all of them andÂ 
yes for freelancing inquiries just write an email on this particular email address and I'll reachÂ 
out to you as soon as possible now how to get my Google Drive access guys just go to my YouTubeÂ 
channel and click on that access to my Google Drive button and over there you'll see there areÂ 
some basic steps that you need to follow and you can see that the cost of Google Drive is very veryÂ 
small it's less than a third of a coffee price and and doing that you will be supporting my work asÂ 
well I had a couple of interns recently to help me provide the best possible study materials andÂ 
codes on Google Drive and not only this code will be saved over there there are many more codesÂ 
and study materials that are present on that particular Google Drive things like my tradingÂ 
board or some algorithmic trading strategies etc etc and yes the link of my course is inÂ 
the description box just check it out and let me know if you have any suggestions thank youÂ 
so much for watching this video till the end you can click here to subscribe to my YouTubeÂ 
channel and over there you'll see this entire playlist on MetaTrader5 and over there you'll seeÂ 
one of my most loved trading strategies that I created a few weeks back if you're confused aboutÂ 
anything just watch this video again because this will be very crucial for the next video on howÂ 
to make the trading bot and until then peace!

</details>
