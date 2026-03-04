---
title: "Build *interactive* Technical Indicators dashboard on Python using StreamlitðŸ”´"
people_mentioned: ["Bollinger Bands", "Ritvik Dashora", "Hello Financial Programmers", "Alpha Vantage"]
channel: "Financial Programming with Ritvik, CFA"
video_id: "_IZdL_rGAnU"
url: "https://www.youtube.com/watch?v=_IZdL_rGAnU"
publish_date: 2023-01-26
duration: "14:26"
word_count: 2446
content_type: "solo-talk"
delivery_mode: "opinion"
broad_category: "engineering-tools"
subcategories: ["api-integration", "data-tools"]
series_name: ""
episode_id: ""
primary_person: "Bollinger Bands"
host_names: []
interviewer_names: []
interviewee_profiles: []
speaker_profiles: ["Bollinger Bands"]
organizations_mentioned: ["Financial Programming with Ritvik, CFA"]
locations_mentioned: []
tools_mentioned: []
companies_mentioned: []
topics: ["api-integration", "data-tools", "ai-coding", "lead-generation"]
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

The discussion centers on data, actually, technical. Us which is a technical analysis dashboard perfect now hereÂ with Tech indicator St dot subheader Technical and now dashboard right control. Data is actually the pricing data that we extracted here if you see this one right soÂ low close High open. Data frame this is the main data frame that we'll be referring to now indicator list isÂ equal to DF dot ta.

## Key Insights


- Us which is a technical analysis dashboard perfect now hereÂ with Tech indicator St dot subheader Technical and now dashboard right control.
- Data is actually the pricing data that we extracted here if you see this one right soÂ low close High open.
- Data frame this is the main data frame that we'll be referring to now indicator list isÂ equal to DF dot ta.
- Because in this video we are just doing technical analysisÂ so and then let's just write here fundamental data let's keep.
- ThenÂ plot it with um close that's just a close price in order to get the technical indicator data we'llÂ use.
- We have created multiple tabs of different analysis like pricing data fundamentalÂ Data stock news open AI chat GPT yes guys I've.

## People Mentioned


- [[Bollinger Bands]]

- [[Ritvik Dashora]]




## Full Transcript

<details>
<summary>Click to expand full transcript (2446 words)</summary>

Hello Hello mic test so if I change it say SMA we get the SMA graphÂ 
automatically vwap it is also here and aroon ADX is here the B bands which is Bollinger Bands isÂ 
also here so which actually you can just go and select this particular area and you can see uhÂ 
the entire analysis of this particular region Hello Financial Programmers I am Ritvik Dashora and I'm back with a new video and some newÂ 
learnings if you're interested to build a technical analysis dashboard on streamlit usingÂ 
python then you're at the right place in this video I will refer to uh the work that I have doneÂ 
in the past videos in this playlist on streamlit um and uh so yeah we have create if youÂ 
remember we have created multiple tabs of different analysis like pricing data fundamentalÂ 
Data stock news open AI chat GPT yes guys I've done that thing as well and the last one wouldÂ 
be technical analysis I'll just go through the entire script uh very quickly such that you haveÂ 
a proper understanding of what I have done in the past I would love if you refer to all the pastÂ 
videos as well but in this video we'll be just focusing on the technical analysis dashboard ifÂ 
you're new to my YouTube channel on this channel I turn all my viewers to successful FinancialÂ 
programmers here I am upload videos related to trading Bots implementation of AI in finance someÂ 
highly valuable Finance apis etc etc so if you are interested in my work then you should subscribeÂ 
to my YouTube channel and also click on the Bell icon there are a lot of things that I'm planningÂ 
actually and also quick shout out to my patreon members thank you so much guys I really appreciateÂ 
your support and I hope that the service that I'm providing over there is worth each and every pennyÂ 
for my new reverse just stay tuned to this video and I'll tell you what is patreon service thatÂ 
I provide so let's start the topics that we are going to cover today are actually I'll talk aboutÂ 
the last four videos or three videos actually four videos on stream lead that I have createdÂ 
I have started this playlist from as simple as installation of streamlit which is sometimesÂ 
very very difficult because we have to create some environment variables and use vs code thenÂ 
I talked about some basics of streamlit and then the third video was a very very important videoÂ 
was that is on building a simple stock dashboard which we continued in the fourth video where weÂ 
incorporated chat GPT open AI platform and thank you so much guys for giving a great response onÂ 
that video and in that video actually we connected with chat GPD directly and asked some questionsÂ 
on the reasons why we should buy msft the reasons why should why we should sell msft and the SWOTÂ 
analysis of msft that's the last video in this playlist in this video what I'll do is I'll referÂ 
to the library called pandas ta and how to use it and then we'll extract uh an entire list of allÂ 
major technical indicators I'll give an option on the streamlit dashboard on uh of of selecting anyÂ 
particular technical indicator for the analysis will extract the data of the technical indicatorsÂ 
uh we'll plot it with I would say against the close price and in the end we'll also extract theÂ 
technical uh indicator data edges into the close price to do some further analysis so guys this wasÂ 
uh was the code that we built in the last three four videos uh so we have extracted uh streamlitÂ 
pandas sorry imported streamlined pandas numpy wire finance and plotly and you can see that theÂ 
basic uh I would say implementation of streamlit library that is putting a title sidebar inputsÂ 
of ticker start date and end it we used y Finance which is actually a python wrapper for um YahooÂ 
Finance in order to extract the price pricing details of any particular ticker for example msftÂ 
we plotted the I would say the the adjacent close price on streamlit and then if you remember IÂ 
created four different tabs where we did different analysis for different things pricing data forÂ 
fundamental data we referred to Alpha Vantage for stock news data we referred to stock news API andÂ 
then in the end the last but not the least which is chat GPT we use Pi chat GPT library now in thisÂ 
case I will what I'll do is I'll create another tab which will be of technical indicators and thenÂ 
we'll just work on that particular tab so let me just do one thing Ctrl C and let's open a new fileÂ 
it will be a python file and then Ctrl V so I'm just actually referring to the entire code that IÂ 
have built in the last video now actually I don't want to have the open AI this thing because thisÂ 
would take some time to run so I'll just write here open AI so actually I'm just presenting I'mÂ 
just writing open AI over there so I'm not doing any analysis here I'll comment this as well andÂ 
let's just comment this one as well and just write here say St dot right stock use for news let's doÂ 
the same thing for fundamentals as well because in this video we are just doing technical analysisÂ 
so so and then let's just write here fundamental data let's keep the pricing pricing data as it isÂ 
and that's it I'll include another tab but yeah before that let's run this code we need to save itÂ 
first okay so Ctrl s let me just save it as Tech indicator dot py now let's run it perfect hereÂ 
in the bottom I'll just write stream let run and then take indicator dot py this should redirectÂ 
me to the Google Chrome yeah so you can see this so this is the stock dashboard we have let meÂ 
just write say msft start date is when you're back somewhere in January 2022 so yeah we've gotÂ 
all these things we have got the chart of msft using Y Finance price moments the pricing data ifÂ 
you see all the information is here that we have already code in the last video for fundamentalÂ 
data it's just just the text fundamental data same for the news and open AI chart GPD as wellÂ 
because I've actually commented all the lines and I've just provided some text over there now let'sÂ 
include another tab so I'll just go here in the tabs I'll just provide another one which is TechÂ 
indicator the title of this would be technical analysis dashboard Ctrl s let's go here rerunÂ 
we should have another tab here with us which is a technical analysis dashboard perfect now hereÂ 
with Tech indicator St dot subheader Technical and now dashboard right control s let's rerun thisÂ 
and we have got this one now the main idea here is to get the technical indicators data and thenÂ 
plot it with um close that's just a close price in order to get the technical indicator data we'llÂ 
use the library called pandas ta if you would like to know about pandas ta library in much detailÂ 
then you should watch my full-fledged video on pandas ta that I recorded I think a year backÂ 
so I covered almost all functionality of pandas TV library and it would be very helpful for youÂ 
guys to go through it but in this video I'll just pick the most important aspects of panda steelÂ 
Library extract the pricing or I would say the technical indicators information here and thenÂ 
just plot it uh here on the streamlit dashboard so let's start with the data frame DF is equalÂ 
to PD dot data frame this is the main data frame that we'll be referring to now indicator list isÂ 
equal to DF dot ta will have to import pandas ta as da d f d f dot t a DOT indicators a as listÂ 
is equal to true now let's just write s t dot write endless Ctrl s let's go here and run it weÂ 
should get the entire list of all indicators that we have so uh yeah so we have in the top 100 weÂ 
have all these indicators I can see B bands adx Etc and if we go here then there are 100 to 143 asÂ 
well so there are total 143 technical indicators that we can actually use here all these indicatorsÂ 
should be in a drop down right such that through drop down we select one of them and then plot itÂ 
on the graph cool let me just comment it again on streamlit we call drop down as select boxÂ 
so yeah I've just written this line which is a technical indicator is equal to St dot selectÂ 
box take indicator and then options is equal to all the options that would be end list which isÂ 
the list of the indicators right let me just save it let's go back here rerun so we've got thisÂ 
like this so you can see the entire list of all different technical indicators are SAS so SMAÂ 
we have got simple moving average EMA exponential moving average and so on now we have to extractÂ 
information of these technical indicators so uh method is equal to the the technicalÂ 
indicator that we are picking such as in this case uh previously I selected SMA right simpleÂ 
moving average so SMA is basically the method now there's a way in order to use this method uh andÂ 
then extract information is that is through get 80 ATT R right here I just need to provide the objectÂ 
which is TA and the method which is this one right now it should be provided with the low close HighÂ 
open and volume data and we have seen that all of those data is are actually here which is the dataÂ 
low the data is actually the the pricing data that we extracted here if you see this one right soÂ 
low close High open and volume let's just write it St dot right and let's see if it works rerunÂ 
exactly it is working actually so SM is the one if I just write e EMA we have got EMA if I justÂ 
write a rune we should get 3 4 exactly three three different columns and so on and you can seeÂ 
all the data is also present over here perfect so it's better to explicitly write PD dot data frameÂ 
although it was already in data frame just your safer side right and then indicator is equal toÂ 
this one perfect right now here we should have close as well which is close price as well uh theÂ 
last price or the adjusted price in the end then only it can be actually plotted on the uh on theÂ 
on the chart so for that it's basically indicator close is equal to data and then close let's justÂ 
write again which is s t dot right indicator Ctrl s let's go here rerun we have got theÂ 
close price as well now similar to the graph that we plotted above which is here which is pÂ 
x dot line I'm using the same concept here to uh to plot indicator which has the close priceÂ 
as well St dot plotly chart and then the this one that actually created for indicators and inÂ 
the end let me just uh put it over here that is we get the data in the end after we get theÂ 
plot we save it let's go back here rerun it you can see uh the the chart is in front of youÂ 
and we have got the data as well so if I change it say SMA we get the semi graph automaticallyÂ 
if it's EMA we get it the EM as well vwap it is also here and aroon adx is here the B bands whichÂ 
is Bollinger Bands is also here so which actually you can just go go and select this particularÂ 
area and you can see the entire analysis of this particular region and so on and if you have anyÂ 
questions please write it on the comment section if you're still watching this video please guysÂ 
I deserve one like just click on that one like button it's free of course for you guys butÂ 
it's very very important for me and also if you subscribe to my YouTube channel that wouldÂ 
be very very helpful very important Point guys some of you guys would know that I share my GoogleÂ 
Drive access with this community and I will have this code as well saved in the Google Drive andÂ 
not only this code there are many more codes saved in that Google Drive like my trading bot some ofÂ 
the projects that actually bid in last a few years in order to get an excess of my Google Drive youÂ 
just need to click on my say access to my Google Drive button and then just follow some steps it'sÂ 
like one third a cost of coffee that a month that would be the entire cost of my Google Drive alsoÂ 
guys if you're interested to join my exclusive patreon Community then definitely guys you shouldÂ 
check it out uh the link is in the description box and in through the patreon exclusive Community IÂ 
am in touch with all of them personally through WhatsApp and through one on one and group meetingsÂ 
and we have multiple conversations on different topics recently actually I'm starting anotherÂ 
type of meeting called connecting dots where we will be trying to connect the the knowledge thatÂ 
we guys have and we'll try to help each other over there the link is in the description boxÂ 
thank you so much guys for watching this video till the end you can click here to subscribeÂ 
to my YouTube channel and over there you'll see the entire playlist of streamlit uh from theÂ 
beginning till the end and down there you'll you can actually see the pandas ta library whereÂ 
you will understand each and everything about pandas ta Library so guys keep learning keepÂ 
exploring and I'll see you very very soon peace

</details>
