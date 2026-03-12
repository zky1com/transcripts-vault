---
title: "How to use EODHD Excel Add-In to get Financial Data [EODHD API] ðŸ”´"
people_mentioned: ["Ritvik Dashora", "Learn More", "Excel Hello Financial"]
channel: "Financial Programming with Ritvik, CFA"
video_id: "nLX_4WMMoKc"
url: "https://www.youtube.com/watch?v=nLX_4WMMoKc"
publish_date: 2023-09-30
duration: "13:57"
word_count: 2346
content_type: "tutorial"
delivery_mode: "technique"
broad_category: "finance-investing"
subcategories: ["stock-analysis", "options-trading"]
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
topics: ["stock-analysis", "options-trading", "ai-coding", "lead-generation"]
tags: ["stock-analysis", "options-trading", "ai-coding", "lead-generation"]
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

The discussion centers on data, let's, that's. Second one intraday data let's see what is integrated dataÂ get entered a historical data okay ticker msft.us right interval I want. Data here that's great let's see what else is there so I'll just name this oneÂ as well as historical data perfect. One minute interval dataÂ okay that's fine let's do it from one ascending let's unselect this uncheck this and load perfectÂ it.

## Key Insights


- Second one intraday data let's see what is integrated dataÂ get entered a historical data okay ticker msft.us right interval I want.
- Data here that's great let's see what else is there so I'll just name this oneÂ as well as historical data perfect.
- One minute interval dataÂ okay that's fine let's do it from one ascending let's unselect this uncheck this and load perfectÂ it.
- The options data to gettingÂ the ETF data fundamental data etc so there's a lot of things that we have extracted.
- It's yeah it's annualÂ data perfect let's see what else get ETF okay that I'll create a new sheet here called ETF.
- Historical data I click here tickers okay so let me just write aapl.us I wantÂ daily data from okay I will go.

## People Mentioned


- [[Ritvik Dashora]]




## Full Transcript

<details>
<summary>Click to expand full transcript (2346 words)</summary>

hello hello mic test ðŸ‘€ Follow Captions to Learn More ðŸ‘€ it's quite a lot of information to be honest thatÂ 
they are providing in nsxl directly and as you can see I have not written even a single lineÂ 
of code in this video and you can see we have extracted a lot of data from making a screenerÂ 
to getting the options data to getting the ETF data fundamental data etc etc so there's aÂ 
lot of things that we have extracted in Excel Hello Financial Programmers, I am RitvikÂ 
Dashora and I'm back with a new video and some new learnings this is the third video of ourÂ 
playlist on exploring the EOD HD financial data API in the first video we talked about the basicÂ 
things on like exploring this entire platform we went through the documentation and we exploredÂ 
the free data financial data API of EODHD in the second video we made a detailed stock screenerÂ 
using both free and paid data APIs and in this video we are going to learn how to use theirÂ 
Excel API add-ins in order to extract all the information directly in either in Ms Excel orÂ 
Google spreadsheet without using any code this is how will be completing this entire playlist on EODÂ 
HD if you guys are new to my YouTube channel guys on this channel I convert all my viewers toÂ 
successful Financial programmers here I upload video related to trading boards implementationÂ 
of AI in finance exploring some highly valuable Finance APIs like this one making some bind scriptÂ 
trading strategies etc etc so if this is something that you are interested in then you should clickÂ 
on the Subscribe button and also hit on the Bell icon because there are a lot of playlists thatÂ 
are coming that are already in my Pipeline and you guys already know that I upload videos everyÂ 
Saturday and yes this will keep on happening so if you don't want to miss out on those amazing freeÂ 
content then just stay tuned by subscribing to my YouTube channel perfect so in this video we'llÂ 
just directly go to the Excel add-in functionality right so they have given all the information hereÂ 
directly so let's follow all these steps one by one to be honest I have not done it in the pastÂ 
and I'm also exploring it for the first time so this is great I just wanted to provide a candidÂ 
experience on this video that's why I kept it in this way only so let's do it perfect so the firstÂ 
thing that we need to do here is we'll have to download the Excel add-in here okay perfect it'sÂ 
getting downloaded okay got it so we'll have to install this thing welcome to the installationÂ 
wizard EOD add EOD add-in click on next exit the agreement next next next and install finish okayÂ 
that in includes downloading the data via EOD API with chart Auto generation change the test API keyÂ 
to your API key Atticus you want to download the data for okay got it and get results directly toÂ 
your Excel file with charts downloader for end of the day stock API recorded so there are good ExcelÂ 
templates as well that's very good I like it okay we can actually provide it in VBA code as wellÂ 
so we can actually do some automation on Excel as well perfect so let's open the Excel file okayÂ 
so while opening it automatically started this like open this thing with EOD HD APIs FinancialÂ 
add-in you'll be able to download all these things register login insert API key I'll just let'sÂ 
just click to insert APA okay got it I'll paste my APA key here okay so it has saved the APIÂ 
key do I need to log in as well click on login perfect I have logged it as well now let's hideÂ 
it Ah that's great I've got this ribbon already I don't didn't need to do anything here so yes I weÂ 
have actually provided the API key over there and I think that's now connected let's explore thingsÂ 
on how to extract the historical data I click here tickers okay so let me just write aapl.us I wantÂ 
daily data from okay I will go from I don't know want that old data so from 2010 January to 2023Â 
today yeah descending order once one worksheet only smart table I don't know what it is but let'sÂ 
see let's click here perfect so that's great so I've got the entire table of this historical dataÂ 
of Apple I can actually provide some filters here for example say newest to oldest it will change itÂ 
like this I have open high low close adjusted open adjusted High adjusted low and adjusted closeÂ 
and volume data here that's great let's see what else is there so I'll just name this oneÂ 
as well as historical data perfect second one intraday data let's see what is integrated dataÂ 
get entered a historical data okay ticker msft.us right interval I want one minute interval dataÂ 
okay that's fine let's do it from one ascending let's unselect this uncheck this and load perfectÂ 
it took some time but yeah the data is also a lot there are 65 000 rows here and if you see if I letÂ 
me just expand it a bit so what type of data do we have date of time and times time I think the otherÂ 
they're the same thing with different formats then we have open high low close and volume that'sÂ 
great I am not sure what is GMT offset which is always zero I think so that's no problem withÂ 
that so this is enter ID data that's cool if I'm actually a bit curious if you want to like extractÂ 
it continuously then in that case we'll have to write a VBA code to run this query again and againÂ 
to get the intraday data continuously that's not a problem with it would be a very I would say longÂ 
quote if you guys want me to make a video on that mention that in the comment section if I get a lotÂ 
of comments related do the same thing then I will make a video on that as well so this is CentralÂ 
ID data fundamental data so that's the third tab I'll click here okay so these types of data areÂ 
well all data General highlights if you remember guys I also created a drop down like this one onlyÂ 
in the stock screener that I created in the last video if you have not watched that video then IÂ 
highly recommend because I've already automated this thing in Python on a very interactive webÂ 
application called Streamlit so and all this information is over there already so yeah noÂ 
worries so these are the fundamental data bulk fundamentals let's just select in balance sheetersÂ 
of now ticker is msft or let's do TSLA dot us this time perfect so this is the balance sheet ofÂ 
Tesla for how many years from 2007 perfect and this is quarterly and then here is so they haveÂ 
actually provided both of them with grouping of like this so basically there's a grouping ofÂ 
quarterly and then we have it for annually as well perfect the filing date is available hereÂ 
currency and then other things okay these are all the items of balance sheet that's great IÂ 
I'm actually curious very curious to see what is there inside the bulk fundamentals this beforeÂ 
that guys I have a very important information to share recently I launched a course on pythonÂ 
for financial programming so if you are trying to Learn Python for finance from scratch thatÂ 
this is something that you might be interested in just go to my website which is fbrethwik.comÂ 
python over here you will see two buttons Indian candidates non-indian candidates so you canÂ 
click as per your location it will redirect you to this the main website where the entire courseÂ 
information is available you'll see that there are five sessions 10 chapters 22 videos 10 quizzesÂ 
and three assignments with two live projects and this is the entire syllabus of this course for allÂ 
the people who are interested to Learn Python from scratch and who are struggling learning python onÂ 
their own I highly recommend it because it's very very affordable and I have covered a lot ofÂ 
things from a very very simplistic eyesight and in the end in session four and five you'll seeÂ 
stock analysis and Investment Portfolio creation projects which are my personal projects we didÂ 
it using some financial analysis if you use RTK40 code you'll get an instant 40 discount whichÂ 
is only available for the first 100 candidates so yes guys I'll see you in the course let's comeÂ 
back to our code okay so here I'll provide ticker tsla.us okay there is another option here let meÂ 
just write aapl.us and then third one msft.us in one spreadsheet and sorry one worksheet separatedÂ 
I'll select I'm just interested in this one itself and load you are we are going to download threeÂ 
symbols or you want to proceed yes perfect so we have got multiple sheets here and a lot of data soÂ 
for Tesla apple and Microsoft all these different things are available now earnings I think yeah soÂ 
it has actually given all the data for the three companies here and I think it's yeah it's annualÂ 
data perfect let's see what else get ETF okay that I'll create a new sheet here called ETF let'sÂ 
click here ticker okay ETF ticker I don't know any ETF ticker let's go to their documentation so overÂ 
here you can see the code vti is a code is an ETF which is when got total stock market index fundÂ 
ETF shares so let's try this one only vti right VTI that's not B it's VTI and let's click on loadÂ 
insert exchange as well so let's try us only dot us and load perfect that's great we have got vtiÂ 
us okay that's grouped already so yeah all this information that's great so lot of informationÂ 
about an ETA because mostly the data is not very easily available for ETF except the pricingÂ 
data so that's good that's good that's a lot of information volatility sharpness show three returnÂ 
individual stock level analysis perfect let's go to the next one which is get options let'sÂ 
click here ticker APL dot us from this to this load okay perfect so I think yeah this is theÂ 
options data of apple as well right implied volatility put volume call volume what else openÂ 
interest call open open interest and options count what next get bulk EOD data I think it it willÂ 
just give me all this data in this one go so I'm not interested in that so let's see what is theÂ 
stock screener here I would like to create this one sector is technology industry is informationÂ 
technology services will change this to us and see I'll just write Microsoft but let's justÂ 
keep this one I want all tech companies based out of US exchange which is basically NASDAQ inÂ 
this case so let's see what do we get perfect so we've got all the companies who belong to sorryÂ 
who belong to a us and the sector is technology Industries Information Technology Services yeahÂ 
so we have this list of 100 companies here we can change I would say we can increase the limit fromÂ 
100 to a bigger number as well so here over there you you can see the limit here as hundred so youÂ 
can increase it to 500 as well so yeah perfect so then the next one is list of exchanges list ofÂ 
cryptocurrencies Etc if you want to get the list of those things that's good and then let's sayÂ 
settings if you want to change your APA so yeah it's quite a lot of information to be honestÂ 
that they are providing in MS Excel directly and as you can see I have not written even aÂ 
single line of code in this video so yes all this information requires no coding and you canÂ 
see we have extracted a lot of data from making a screener to getting the options data to gettingÂ 
the ETF data fundamental data etc etc so there's a lot of things that we have extracted in Excel soÂ 
guys if you like this video please click on the like button and also click on the Subscribe buttonÂ 
because I know these are just two clicks for you but these mean a lot to me most of my YouTubeÂ 
viewers are not subscribing to my YouTube channel and I got an email from YouTube so I'm just havingÂ 
a humble request please support my channel by clicking on like And subscribe button because itÂ 
will give you motivation to continue uploading this quality educational content for free forÂ 
any freelancing inquiries you can reach out to me on this email address and I'll reply as soonÂ 
as possible and last but not the least the link of my course is in the description box please checkÂ 
it out and let me know if you have any feedbacks thank you so much for watching this video tillÂ 
the end this was the last video of this playlist I hope you liked it click here to subscribe toÂ 
my YouTube channel and over there you'll see this entire playlist on EOD HD over there you'llÂ 
see one of my most loved video on making a trading bot on mt5 in less than one hour the next playlistÂ 
would be a very interesting playlist as well so just stay tuned the next video will beÂ 
live on next Saturday and until then peace!

</details>
