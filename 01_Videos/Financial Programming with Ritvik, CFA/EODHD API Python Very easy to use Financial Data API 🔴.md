---
title: "EODHD API Python [Very easy to use Financial Data API] ðŸ”´"
people_mentioned: ["Ritvik Dashora", "Forex Pairs"]
channel: "Financial Programming with Ritvik, CFA"
video_id: "yL7fcnn5P40"
url: "https://www.youtube.com/watch?v=yL7fcnn5P40"
publish_date: 2023-09-16
duration: "12:11"
word_count: 2193
content_type: "solo-talk"
delivery_mode: "opinion"
broad_category: "engineering-tools"
subcategories: ["api-integration", "data-tools"]
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
topics: ["api-integration", "data-tools", "ai-coding"]
tags: ["api-integration", "data-tools", "ai-coding"]
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

The discussion centers on data, video, i'll. Fundamental data for cryptocurrencies historical data historical market capitalizationÂ data sentimental data Financial API for news and tweets that's great macroeconomic data. Guys provide fundamental data for cryptocurrencies historical data sentiment dataÂ Financial API for news and tweets macroeconomic data API yeah these are. TheÂ type of data do they provide fundamentals end of the day which is historical data real-time dataÂ some delayed data as.

## Key Insights


- Fundamental data for cryptocurrencies historical data historical market capitalizationÂ data sentimental data Financial API for news and tweets that's great macroeconomic data.
- Guys provide fundamental data for cryptocurrencies historical data sentiment dataÂ Financial API for news and tweets macroeconomic data API yeah these are.
- TheÂ type of data do they provide fundamentals end of the day which is historical data real-time dataÂ some delayed data as.
- It's available for free will get the data yeah as you can see that it'sÂ a sentence data of BTC USD and.
- Can see that the data frame the historical data in front of you what are theÂ type of data which are available.
- It's 15 minutes delay data technical indicators data so if you wantÂ to extract information like SMA or EMA directly without.

## People Mentioned


- [[Ritvik Dashora]]

- [[Forex Pairs]]




## Full Transcript

<details>
<summary>Click to expand full transcript (2193 words)</summary>

hello hello mic test ðŸ‘€ FOLLOW CAPTIONS TO LEARN MORE ðŸ‘€ so these are the different types of financialÂ 
data that these guys provide fundamental data for cryptocurrencies historical data sentiment dataÂ 
Financial API for news and tweets macroeconomic data API yeah these are all different things andÂ 
they have different APIs for different things hello Financial programming Iâ€™m Ritvik Dashora andÂ 
I'm back with a new video and some new learnings this is the starting of a new playlist and I gotÂ 
many comments on covering EOD HD API it's another financial data API if you remember I made anÂ 
entire playlist for FMP which is financial modeling prep thank you so much for giving such aÂ 
great response on that playlist and in your demand now there's another playlist where I am coveringÂ 
EOD HD this is a three video playlist in the first video I'll be explaining all different types ofÂ 
functionalities of EOD HD and will be just doing some small of coding here the second videoÂ 
we will be making a stock screener it's very similar to the one that we made with FMP as wellÂ 
but there are some changes here which are some of the specialty of EODHD and the third video wouldÂ 
talk about some Excel Ms Excel implementation of this API so if you want to extract some FinancialÂ 
information directly in Excel without doing any coding then you guys should wait for that videoÂ 
which will be the third video of this playlist all the videos will be uploaded on Saturdays andÂ 
I think by now you guys already know that I upload a video every Saturday and I cover all aspectsÂ 
of programming in finance if you are new to my YouTube channel guys on this channel I turn allÂ 
my viewers to successful Financial programmers here I upload videos related to making tradingÂ 
Bots making trading strategies on Pine script implementation of AI in finance exploring someÂ 
financial data APIs like this one and there are many more topics so if you guys are interestedÂ 
in what I am doing then you should click on the Subscribe button and also hit on the Bell iconÂ 
because there are many playlists that will be coming on this YouTube channel and everything isÂ 
for free and I'm 100 sure that you will learn a lot with me here okay so without any further AdoÂ 
let's start so guys this is the the website of EOD HD which is EODHD.com and you can see that theyÂ 
have have 30 years of data financial information of different types of Securities what are theÂ 
type of data do they provide fundamentals end of the day which is historical data real-time dataÂ 
some delayed data as well it's 15 minutes delay data technical indicators data so if you wantÂ 
to extract information like SMA or EMA directly without doing any calculations they do it onÂ 
their end itself and then you just extract it directly in python or Excel intraday data screenerÂ 
they have some amazing screeners alternative data economic which is macroeconomics data delistedÂ 
Forex Pairs and spreadsheets as I mentioned that they have some great APIs for Ms Excel and GoogleÂ 
spreadsheet as well I'm sorry guys my voice is not supporting me today so please pardon me for thatÂ 
okay in the programming languages they offer help in Python PHP Matlab or Excel and so on so andÂ 
you can see all the code examples by clicking here will be referring to it in second video weÂ 
can get a free API by clicking here I'll just click on that after some time this is the pricingÂ 
and that's it so let me just click on get free API key here and let's sign up on EODHD API right soÂ 
I'll just provide all this information and then click on register okay guys so yeah it was veryÂ 
simple I it's I think it's just one step process I got the API key directly so I'll just copy it fromÂ 
here and I'll save it somewhere it sets a free API right now so there are some limits of using thisÂ 
free API which is 20 API calls in a day which can be extended to 500 right you you can also buy someÂ 
extra limits and this is all the information that we get for free which is EOD HD EOD historicalÂ 
data only for the free package for like if we have the paid package you'll get all these otherÂ 
things as well so I'll get the paid packages well and let's see what are other things as wellÂ 
but in this video I'll be just focusing on the EOD historical data on the top here we haveÂ 
Academy to help us understand the API they have a Blog as well let's I'll just directly clickÂ 
on the full documentation here right so these are the different types of financial data that theseÂ 
guys provide fundamental data for cryptocurrencies historical data historical market capitalizationÂ 
data sentimental data Financial API for news and tweets that's great macroeconomic data API and soÂ 
on so yeah these are all different things and they have different APIs for different things thereÂ 
are a couple of python libraries available as well for your DHD but they are not official butÂ 
I think these guys support those python packages as well but in this video what I'll be doing isÂ 
I'll be directly using the requests library to to hit their API directly and get the informationÂ 
I'm not using any python library in all these three videos so if we just click on any one ofÂ 
them so for example let's click on the fundamental data for cryptocurrencies right you'll see theyÂ 
create a URL actually and we'll be just using this particular URL we will customize it based onÂ 
the type of data do we need to get for example in this case it's BTC USD we can be doing it forÂ 
say Apple stock right we have the API token here which will be I would say a variable asÂ 
well and then using the requests Library we will be extracting information in Python and thenÂ 
over there I'll be just using some pandas library to clean the data to make it I would say presentÂ 
in a in a tabular format so that's the overall idea and I have seen that in all of the type ofÂ 
APIs that they provide they have links directly so for example in this case sentiments analysisÂ 
they have the link directly which can be copied and then paste it in our code and then it canÂ 
be customized so that's the great thing if we click on say sentiment data which is actuallyÂ 
I think that's for free it's available for free will get the data yeah as you can see that it'sÂ 
a sentence data of BTC USD and apple you can see it's a Json format data a lot of things in frontÂ 
of you right now it's very difficult to visualize but definitely we can extract in in Python and itÂ 
can actually convert it into tabular format to to visualize it much better this is the main focusÂ 
of this video so let's start let's jump to I would say the Google collab let's use Google collabÂ 
in this video in the next video I'll be using visual studio this before that guys I have a veryÂ 
important information to share recently I launched a course on python for financial programming soÂ 
if you are trying to Learn Python for finance from scratch that this is something that you mightÂ 
be interested in just go to my website which is fps.com python or here you will see two buttonsÂ 
Indian candidates non-Indian candidates so you can click as per your location it will redirect youÂ 
to this the main website where the entire course information is available you'll see that there areÂ 
five sessions 10 chapters 22 videos 10 quizzes and three assignments with two live projects and thisÂ 
is the entire syllabus of this course for all the people who are interested to Learn Python fromÂ 
scratch and who are struggling learning python on their own I highly recommend it because it'sÂ 
very very affordable and I have covered a lot of things from a very very simplistic eyesight andÂ 
in the end in session four and five you'll see stock analysis and Investment Portfolio creationÂ 
projects which are my personal projects we did it using some financial analysis if you use rtk40Â 
code you'll get an instant 40 discount which is only available for the first 100 candidates so yesÂ 
guys I'll see you in the course let's come back to our code okay guys so this is Google collab I'veÂ 
given the name of this file as EOD HD video one Port requests Library here this is the URL thatÂ 
I copied from there for historical data I will actually provide the API key as a variable so I'llÂ 
just write API key here but for that I'll have to provide it inside the if string the EPA tokenÂ 
is equal to API key right here I will provide the API key that's one thing second is the tickerÂ 
should also be a variable which is thicker here the variable say ticker is AAPL dot I think theyÂ 
use dot us everywhere so yeah it was mcd.us so it should be aapl.us as well and the other thingsÂ 
can actually be kept like this only perfect so I have provided the API key above and the URL isÂ 
here perfect now what I'm going to do here is I'll just write data is equal to I'll be using requestsÂ 
Library I'll I just write I just wrote req U and then Google collab is giving me this suggestionÂ 
which is requests dot get and then inside this I will provide the URL I want it into the JsonÂ 
format so dot Json right now let me just zoom it a bit yeah perfect now if you see data it is it willÂ 
be a big dictionary with a lot of details in it so let's see what are the keys of this dictionaryÂ 
okay it's a list it's not a dictionary so let's see what is the length of this particular listÂ 
it's one zero seven six six that's a lot perfect I I'm directly gonna use pandas Library hereÂ 
to make it in a tabular format so data frame DF is equal to PD dot data frame and then insideÂ 
this I'll just provide data and then let's see what what is DF perfect so this is the historicalÂ 
data then the data of is also available from 1980 of Apple so I think it's since the beginningÂ 
only yes guys you can see that the data frame the historical data in front of you what are theÂ 
type of data which are available these are date open high low close adjusted close and volumeÂ 
this data is free of cost if you use EODHD and that's the main focus of this video as well in theÂ 
next video I will be covering the paid version of EODHD as well the main focus of this video wasÂ 
to make you understand the the documentation because in the next video I'll go very deeperÂ 
into the documentations of other APIs as well guys if you like my work as you can see I spend aÂ 
lot of time to make the content and to be honest it's my hobby but I need some motivation as wellÂ 
just give me that two clicks one is click on the like button and second is click on the SubscribeÂ 
button that's it guys I'm not asking for anything else it really helps because most of my viewersÂ 
are not subscribing to my YouTube channel and I I don't know why they just come here learn andÂ 
then go but if you just give me those two clicks that would be very helpful for me and it willÂ 
give me motivation to keep on going for any freelancing inquiries just reach out to me onÂ 
this email address and I will reply to you as soon as possible the next video would be aboutÂ 
how to make a detailed stocks stock screener using streamlit and EOD HD API and yes guysÂ 
last but not the least the link of my course is in the description box check it out and letÂ 
me know if you have any feedbacks thank you so much guys for watching this video till the end youÂ 
can click here to subscribe to my YouTube channel and over there you'll see this entire playlistÂ 
of EODHD this is the first video and there are two more videos that are coming and over thereÂ 
you'll see my highly loved video on making an mt5 trading bot stay tuned to my YouTube channelÂ 
and I'll see you next Saturday until then peace

</details>
