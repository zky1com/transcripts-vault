---
title: "How to build Financial Dashboard using Streamlit & EODHD Python API ðŸ”´"
people_mentioned: ["Ritvik Dashora"]
channel: "Financial Programming with Ritvik, CFA"
video_id: "qmkdASI8-oM"
url: "https://www.youtube.com/watch?v=qmkdASI8-oM"
publish_date: 2023-09-23
duration: "20:56"
word_count: 3776
content_type: "tutorial"
delivery_mode: "technique"
broad_category: "engineering-tools"
subcategories: ["api-integration", "data-tools"]
series_name: ""
episode_id: ""
primary_person: "Ritvik Dashora"
host_names: []
interviewer_names: []
interviewee_profiles: []
speaker_profiles: ["Ritvik Dashora"]
organizations_mentioned: ["Financial Programming with Ritvik, CFA"]
locations_mentioned: []
tools_mentioned: []
companies_mentioned: []
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

The discussion centers on data, i'll, let's. One right and let's see the data how does it lookÂ like okay it's this is also a dictionary so let's see. Data is not defined as of now so I'll just write data is equalÂ to request dot get and then URL. Can see it's done for stock news Insider transaction and fundamental data already now I'veÂ provided the live delay data sentiment analysis.

## Key Insights


- One right and let's see the data how does it lookÂ like okay it's this is also a dictionary so let's see.
- Data is not defined as of now so I'll just write data is equalÂ to request dot get and then URL.
- Can see it's done for stock news Insider transaction and fundamental data already now I'veÂ provided the live delay data sentiment analysis.
- Straight financialÂ data financial data and this one is options there are three types of options I'll come back to myÂ Jupiter.
- This data and then here theÂ identifier is basically the fundamental data right except let's write everything here I'llÂ just provide an.
- Perfect now if data type is equal to I'll just copy this and paste it here fundamentalÂ data then I want the.

## People Mentioned


- [[Ritvik Dashora]]




## Full Transcript

<details>
<summary>Click to expand full transcript (3776 words)</summary>

hello hello mic test ðŸ‘€ Follow Captions to Learn more ðŸ‘€ for different like I would say more data typesÂ 
here I can see it's done for stock news Insider transaction and fundamental data already now I'veÂ 
provided the live delay data sentiment analysis and earning calendars Trends IPOs Etc informationÂ 
as well hello Financial programmers I am Ritvik Dashora and I'm back with a new video and someÂ 
new learnings this is the second video of our playlist on EOD HD and as you guys already knowÂ 
I'm making this playlist after getting a lot of comments on covering all different aspects ofÂ 
different types of APIs that are provided by EOD HD the first video we talked about the basicÂ 
things like what are the different things that they provide we went through their documentationÂ 
and then we checked on how to get the free API data in Python in this video I will be exploringÂ 
their paid API version I have already bought the API it's not very expensive but yes it's veryÂ 
important for me to cover it on my YouTube so let's make a stock screener using the data thatÂ 
they provide such that you guys get the overall perspective of this particular API and youÂ 
can actually make a comparison to other API a financial data providers as well that's the mainÂ 
motive of this video and my YouTube channel if you guys are new to my YouTube channel guysÂ 
on this channel I convert all my viewers to a successful Financial programmers here I uploadÂ 
videos related to trading boards implementation of AI in finance using some highly valuable FinanceÂ 
APIs like this one and also making some trading strategies on Pine script trading view so ifÂ 
this is something that you are interested in then you should click on the Subscribe button andÂ 
also hit on the Bell icon because there are a lot of playlists that are in my mind which will beÂ 
coming on this YouTube channel you guys already know that I upload video every Saturday and I willÂ 
keep on working on making this channel as big as possible to spread the awareness and education asÂ 
much as possible for free first of all sorry guys my throat is not supporting me I have got someÂ 
cough and cold so I pardon for that the topics that we are going to cover in this video asÂ 
we know that we are making a detailed stock screener using Streamlit and EODHD python APIÂ 
the first thing that we will be doing here is we will be understanding the API documentation IÂ 
would say much deeper and we'll be making the streamlined web application I have if you guysÂ 
know I have made many videos on Streamlit in the past so I think if you guys have alreadyÂ 
watched my videos in the past then it's very good if you struggle on installing StreamlitÂ 
if you have any issues with anything related to Streamlit I have made an entire playlist inÂ 
the past on how to use Streamlit in the best possible way it's I would say one of the bestÂ 
web application that is available for free and it requires a very small amount of code and IÂ 
think it's a it's a worth platform to explore so yeah the the third point is that we'll beÂ 
creating some drop downs on different types of data types that we will be selecting and the lastÂ 
thing is that we will be doing the data extraction and then showing it on Streamlit web applicationÂ 
okay guys so without any further Ado let's start so yeah if you guys watch my last video this isÂ 
the website of EODHD and we can actually explore the documentation of EODHD from here here we canÂ 
click on the full documentation to understand the entire functionalities which we can actuallyÂ 
use to extract the data let's select a couple of actually three APIs for the stock screenerÂ 
which can be extended to any number of APIs so I'm interested in the fundamental data stocksÂ 
ETF mutual funds indices that's the first one the stock news and sentiment of those news andÂ 
tweets right and the third one let's take this one which is inside a transaction API perfect soÂ 
fundamental data stocks ETF mutual fund indices so it's a simple access to a fundamental data APIÂ 
for stock CTF initial fund analysis from different exchanges in countries almost all major U.S UKÂ 
EU India and Asia exchanges right so these are the two inputs here which is the first one is theÂ 
ticker they use sticker as sticker m.us right for us companies for Indian companies it would be inÂ 
so aapl.us consists of two part symbol name and exchange ID right aapl.mx would be MexicanÂ 
Stock Exchange and so on API key is the one that we get when we open the account in the lastÂ 
video I already explored how to get the API key and this is the URL that we have for fundamentalÂ 
data same goes with The Insider transaction data as well this is the the URL that we are going toÂ 
refer and these are the different types of inputs that we can provide over there and for newsÂ 
stock market and financial news API we have the URL like this one right so these are the threeÂ 
things that I'm gonna use here on the code okay so let's come to vs Studio code so as I did in theÂ 
last video I'll be using a requests Library here that's the first thing second is if you see I haveÂ 
actually create created a file code called API info.py inside this I have saved my API key so IÂ 
am importing API info let's just do from API info import EPA key so that's the only variable thatÂ 
I provided inside that particular file right now what else yeah we need to import the StreamlitÂ 
as well perfect so let's run this code right and here I'll just write stream let run the name ofÂ 
the file which is EOD HD underscore screener dot py it will open a web application in the in theÂ 
browser that I'm using and yeah as you can see we've got the web application here there's nothingÂ 
inside it because we have not provided anything as of now so we have got the web application so let'sÂ 
start with the header simple header which is SD dot header I'll just write EOD HD detailed stocksÂ 
screener right it if you save it let's come here click on rerun it will give me your DC detailsÂ 
top screen app now on the left hand side I'll create a sidebar and over there I will actuallyÂ 
provide some places to write the ticker name and some other things for example to select theÂ 
data type that they would they would like to see in the screener so let's just write sd.sidebar dotÂ 
input text right what's the label the label is a ticker I'll provide default as aapl.us perfect andÂ 
the name of this particular variable is sticker If you save it let's come back here rerun it willÂ 
create a sidebar on the left hand side now the second one which is data type it's another segmentÂ 
of the sidebar dot select box I'm actually I want a drop down here so in Excel Ms Excel we callÂ 
it data validation right on Streamlit we call it select box so the name of this one is dataÂ 
type only comma options is equal to I'll provide all the things inside a list here one by one soÂ 
right now just do it for fundamentals fundamental data right whenever whenever you extend it forÂ 
other things you'll keep on adding different things here I'll do it for other like two moreÂ 
segments which are news and Insider transactions so this is the data type I'll just save itÂ 
let's come back here rerun you'll see that there's one only one drop down here as of nowÂ 
so perfect now if data type is equal to I'll just copy this and paste it here fundamentalÂ 
data then I want the URL to be whatever the URL is over there let's just come here copy thisÂ 
so yeah I have provided the URL API key and this one would be ticker perfect so let's just do itÂ 
here on the Google call app first and then I'll just copy and paste it over there that would beÂ 
that would be easier for you to understand so let's just I'll just copy this right and pasteÂ 
it here this is the URL right so data was if you just click on I'll just copy this right and pasteÂ 
it here okay so yeah this is data here now we'll have to get out some of the things here so if weÂ 
just write key easier I think there are a couple of okay there are a lot of things here which areÂ 
provided here which is we get General information highlight valuation share stat technicals splitsÂ 
dividends analyst ratings holders inside your transactions look inside the transactionsÂ 
can be covered here itself okay that's great and other things as well perfect and this isÂ 
the financial okay got it so the fundamentals which are balance sheet income statement and theÂ 
cash flow would be inside this one so I actually that's that's great I can directly provide thisÂ 
as an input inside I would say the the select box of Streamlit so whenever we go here wheneverÂ 
someone clicks on fundamental data it will pop up another I would say a drop down here which givesÂ 
us an option to select one of these types of data so this is the list of the data that if if thisÂ 
is financials then we want balance sheet income statements around so let's see what what is insideÂ 
this financials so I click on this one I think yeah I I can see that let's see this if you writeÂ 
dot Keys here you'll see balance sheet cash flow income statement perfect so basically there areÂ 
these many types of data and inside this we have financials inside financials we have the threeÂ 
statements data here perfect if I just write data and say let's just select the first one which isÂ 
General right so these are all the data if I if I just import let me just zoom it a bit as wellÂ 
pandas SPD and here I provide it as PD dot data frame and then inside this let's see how the howÂ 
does the table look like ah it looks quite good perfect so we can use this type of data directlyÂ 
if I click on select say ESC scores perfect say evaluation okay so it's not working on valuationÂ 
I think it would be a dictionary only yeah it's it's a dictionary so we need to provide indexÂ 
here got it got it so I'll just create a try and accept condition on on vs studio so thisÂ 
is something that I found it really well so I'll just copy it let's come here now if someoneÂ 
selects this one it will open another drop down which is say fundamental data is equal to theÂ 
space data for some time let's just copy this paste it here like this I'll cut this and theÂ 
options would be this list right data is not defined as of now so I'll just write data is equalÂ 
to request dot get and then URL dot Json perfect if fundamental data is equal to what is thatÂ 
it was I think financials based financials here then it will open another drop down which is sayÂ 
statement and here I'll I'll have to change this one as say fundamental like straight financialÂ 
data financial data and this one is options there are three types of options I'll come back to myÂ 
Jupiter lab and our Jupiter Labs Google collab I'll copy this and paste it here perfect nowÂ 
let's come back to Jupiter Google collab this is the financials data if I just provide it sayÂ 
if I just select a balance sheet it's the first one right and let's see the data how does it lookÂ 
like okay it's this is also a dictionary so let's see what are the keys of this dictionary so weÂ 
have currency symbol quarterly and and yearly so let's just select quarter layers off nowÂ 
you can make annually that's your homework on how to convert this entire thing into a annual orÂ 
yearly as well I'll for this video I'll just do it for quarterly so yeah perfect if I just do PD dotÂ 
data frame and then provide everything inside this I think we'll get the financial statement ofÂ 
balance sheet no there's no I have to change the spelling here perfect that's it so you canÂ 
see 2023 and the last one is 1985 that's a lot of data that's great perfect so I'll just copyÂ 
this and paste it here this is DF PD I have to import pandas as well as PD pd.DataFrame dataÂ 
financials and here I'll just write statement right because anyways we are getting it fromÂ 
here and then quarterly right now else they'll select financials or other things in the in thisÂ 
list I'll just write a try and accept condition here because if you remember there was sometimesÂ 
there's just one dictionary and sometimes we can actually make it in a pandas a pandas data frameÂ 
format so this is right DF is equal to PD dot data frame and inside this data and then here theÂ 
identifier is basically the fundamental data right except let's write everything here I'llÂ 
just provide an index as well here so I'll just random index like index perfect let's just saveÂ 
it and let's see if it's working let's come back to here rerun for fundamental data perfect soÂ 
we have these three things General perfect we have got the very good drop down here right ifÂ 
we select any one of these ah I forgot to like print it here on the screen let's come backÂ 
here and basically down here I'll just write SD dot right and then TF so actually I can do itÂ 
here as well save it perfect so if you click on say General I'll get the general informationÂ 
of Apple if you click on any other things say inside the transactions you'll get the insideÂ 
to transaction information of all the people doing it outstanding shares so you can see thatÂ 
everything is automated this is something that endless rating endless ratings so it comes so youÂ 
can see everything is automated here if you click on financials it should actually open another dropÂ 
down here as you can see balance sheet cash flow statement income statement you can see balanceÂ 
sheet in front of you then we have cash flow statement and income statement as well now I'llÂ 
create another option for this one fundamental data this before that guys I have a very importantÂ 
information to share recently I launched a course on python for financial programming so if youÂ 
are trying to Learn Python for finance from scratch that this is something that you mightÂ 
be interested in just go to my website which is fps.com python over here you will see two buttonsÂ 
Indian candidates non-Indian candidates so you can click as per your location it will redirect youÂ 
to this the main website where the entire course information is available you'll see that there areÂ 
five sessions 10 chapters 22 videos 10 quizzes and three assignments with two live projects and thisÂ 
is the entire syllabus of this course for all the people who are interested to Learn Python fromÂ 
scratch and who are struggling learning python on their own I highly recommend it because it'sÂ 
very very affordable and I have covered a lot of things from a very very simplistic eyesight andÂ 
in the end in session four and five you'll see stock analysis and Investment Portfolio creationÂ 
projects which are my personal projects we did it using some financial analysis if you use rtkÂ 
40 code you'll get an instant 40 discount which is only available for the first 100 candidatesÂ 
so yes guys I'll see you in the course let's come back to our code so let's just increase itÂ 
quickly to the next one I actually am interested in using The Insider transaction data whichÂ 
is separately shown in the APA documentation so I'll just write Insider transaction here in theÂ 
main drop box and here I'll just write F data type is equal to inside a transaction then yes this isÂ 
the API URL right I have actually made this as a variable API key data as you know and then dataÂ 
frame and this one so let's just save it let's rerun if let's go here and then we have anotherÂ 
option here which is inside the transaction you can see inside your transaction information it'sÂ 
I think same only so I don't know why they have provided it as a different API separate API butÂ 
yeah the last one is news and their sentiments I would say respective Sentiments of those viewsÂ 
so I'll come here make one more addition here which is stock news in sentiment analysis let'sÂ 
come here if data type is equal to stock news and sentiment analysis so yes I've written thisÂ 
code so basically what I'm what I'm doing here is I have pasted the API here API URL API key andÂ 
pick up variables data is request.get URL Json as you already know DF is equal to PD dot data FrameÂ 
data now actually I've created a small for Loop here basically I want to get the title of theÂ 
news and then the content of the news and then the sentiment of that news so such that we haveÂ 
a better understanding of different types of news so yeah that's a very simple for loop I think it'sÂ 
not a big deal for you guys to understand it so let's just save it I'll come back here I'll rerunÂ 
and click on the stock news and sentiment analysis and yes you guys can see that we have got theÂ 
title of the news the the content of the news and the the sentiment of that particular news so thisÂ 
new 12 this is a bit positive mostly neutral only and you can see a lot of data is in front of youÂ 
so yes this is how we can actually make a stock screener very easily using EODHD API we have doneÂ 
it for these three things Financial fundamental data inside and transaction and stock news andÂ 
settlement analysis as you can see all types of news and everything is in front of you you canÂ 
actually extend it to a lot more things and you could see that it required a very small amount ofÂ 
code I have extended guys it for different like I would say more data types here I can see it's doneÂ 
for stock news Insider transaction and fundamental data already now I've provided the live delayÂ 
data sentiment analysis and earning calendars Trends IPOs Etc information as well so and thisÂ 
is this entire code of this entire stock screener I'll slowly scroll it down and you can pauseÂ 
it and write it yourself or if you want to get this code directly and save it then guys I willÂ 
save this particular code on my Google Drive my already existing subscribers know that I share myÂ 
Google Drive access with my community members and not only this particular code there are many moreÂ 
codes that are saved on my Google Drive like my my trading bot some algorithms on trading strategiesÂ 
on Pine script etc etc how to become a Google Drive Community member just go to my channelÂ 
guys and then click on this button which is not available as of now I don't know why YouTube tookÂ 
it out a few few days earlier there was an option for us to like provide some buttons here but it'sÂ 
not a problem just go to the about section right and click on this particular thing which is accessÂ 
to my Google Drive Link and over there just follow some some of these steps over there and then youÂ 
can see that I will provide you the access in 48 hours it's very very affordable guys the costÂ 
of my Google Drive is less than a coffee so I highly recommend you to go through it and thisÂ 
is how you'll be supporting my channel as well if you liked even one thing about this videoÂ 
guys just please click on that like button also click on the Subscribe button I know it'sÂ 
just a couple of clicks for you guys but it's really really important for me I got an emailÂ 
from YouTube that most of my viewers are not subscribing I don't know why people just comeÂ 
and learn and then go you can just give me those two clicks guys so please I highly request youÂ 
to like this video And subscribe to my YouTube channel in the next video I'll be talking aboutÂ 
the Excel API of EODHD and that would be the last video if you want me to cover more things justÂ 
keep writing me on the comment section and I'll review all of them for any freelancing inquiriesÂ 
you can reach out to me on this email address and I'll reach out to you as soon as possible and yesÂ 
guys last but not the least the link of my course is in the description box just check it out andÂ 
let me know if you have any feedbacks thank you so much for watching this video till the end youÂ 
can click here to subscribe to my YouTube channel and over there you'll see this entire playlist ofÂ 
EODHD and over there you will see my very recent video which is loved a lot by my viewers whichÂ 
is on making a mt5 trading bot in less than one hour thank you so much for loving my work andÂ 
I'll see you next Saturday till then Peace!

</details>
