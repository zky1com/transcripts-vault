---
title: "Real-Time Stock Screener using Financial Modeling Prep Websocket Python API ðŸ”´"
people_mentioned: ["Ritvik Dashora", "Run Stop", "Hello Financial Programmers"]
channel: "Financial Programming with Ritvik, CFA"
video_id: "LMKmusfT-2Y"
url: "https://www.youtube.com/watch?v=LMKmusfT-2Y"
publish_date: 2023-08-05
duration: "20:57"
word_count: 3588
content_type: "solo-talk"
delivery_mode: "knowledge"
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
topics: ["api-integration", "data-tools", "ai-coding", "product-management"]
tags: ["api-integration", "data-tools", "ai-coding", "product-management"]
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

The discussion centers on right, i'll, websocket. Will haveÂ to actually connect the WebSocket again because it's a separate button here right so I'll justÂ provide WebSocket dot connect. Directly using it in this video right soÂ the header is WebSocket API Financial modeling prep now let's do one thing. This particular message right I'll just comment this asÂ of now let's just save it and when we click on.

## Key Insights


- Will haveÂ to actually connect the WebSocket again because it's a separate button here right so I'll justÂ provide WebSocket dot connect.
- Directly using it in this video right soÂ the header is WebSocket API Financial modeling prep now let's do one thing.
- This particular message right I'll just comment this asÂ of now let's just save it and when we click on.
- Of web sockets like import WebSocket like pip installÂ WebSocket pip install WebSocket client and pip install web sockets right these are.
- DotÂ sidebar dot select box right here I'll just write instrument type AI comma options and inside thisÂ I'll write crypto or.
- Be imported from the API key file I'll just writeÂ from API key import API key right and this is the API.

## People Mentioned


- [[Ritvik Dashora]]

- [[Run Stop]]




## Full Transcript

<details>
<summary>Click to expand full transcript (3588 words)</summary>

Hello Hello mic test ðŸ‘€ FOLLOW CAPTIONS TO LEARN MORE ðŸ‘€ [Music] so yeah this is how we extract the real-timeÂ 
information for stocks or crypto in our web application and make your own stock screenerÂ 
and you can see that the prices are coming continuously and it's very very efficient there'sÂ 
a great web application that we have built which can actually be used in a lot of applications likeÂ 
making our own trading bot and then deploying this on a server so yes this is something thatÂ 
we can consider for our further analysis Hello Financial Programmers, I am Ritvik Dashora and I'm back with a new video and some newÂ 
learnings this is the third video of our playlist on financial modeling prep in theÂ 
first video we explored all different free data types available on this API in the secondÂ 
video we explored the paid API data types and in this video I will be using their WebSocketÂ 
API to extract some real-time stock and crypto prices to make a real-time stock screener ifÂ 
you are new to my YouTube channel guys on this channel I upload videos related to tradingÂ 
boards some implementation of AI in finance using some highly valuable Finance apis likeÂ 
this one making Pine script reading strategies etc etc so if this is something that you areÂ 
interested in then you should click on the Subscribe button now and also smash to the BellÂ 
icon so yes guys this is the documentation of financial modeling prep as of now my experienceÂ 
has been quite good because they cover a lot of financial information through the API the firstÂ 
video we talked about stock fundamentals like income statement balance sheet statement cash flowÂ 
statements in the second video we covered about some paid data types like Revenue segmentation onÂ 
Jog on the basis of geographies on the basis of product and other things as well we also talkedÂ 
about institutional ownership ESG score stock news price Target upgrades and downgrades etc etcÂ 
and now we are coming down to explore the outside the hottest thing on this documentation which isÂ 
WebSocket for the people who don't know what is a WebSocket WebSocket is basically a communicationÂ 
Channel between two servers where two servers can actually send and receive messages right and inÂ 
our case we will be using WebSocket to extract some real-time prices of some of the instrumentsÂ 
like stocks or crypto right and if you see if you read here there are actually two types of thingsÂ 
which we need to provide in the function that will be created which is login and subscribe okay andÂ 
this will be the output or the response that we would be getting and yes this is for stocks if weÂ 
go a little bit more down then we can see the same for crypto as well if you click on this WebSocketÂ 
link it will actually open this particular web page where you can see a lot of information hereÂ 
and just scroll down a bit you'll see their python code example code that we would actually be justÂ 
directly copying so yes I have copied it and now let's come to vs Studio code and if you rememberÂ 
in the last video as well we use this platform I'll just click on this particular button and itÂ 
will create a new file let's just write streaming dot py right this is the file name I'll just pasteÂ 
the code that we have actually copied if you go to the API key dot py file I will paste my API keyÂ 
here in the single inverted or a double inverted comma and then I will be directly referring thisÂ 
particular API key through the dot py file that I am creating in the streaming.py file so yes IÂ 
have pasted my API key over there and saved it over in that file now here I will just be usingÂ 
this particular file directly in this code right so if you can see actually it's importing a coupleÂ 
of libraries here WebSocket simple Json time and SS the first thing is to create a WebSocketÂ 
here right and then this is the link the URL that is actually being used to connect withÂ 
the WebSocket if you remember it was different for crypto because if we go just actually in thisÂ 
one if we scroll a bit down you'll see for crypto it's a different one so yes I will actually makeÂ 
this as a variable and also this API key which is I'll have to hide it while editing this videoÂ 
but anyways my API key will also be let me just delete it and it's it will be linked with theÂ 
API key that I have actually provided in that particular file which is API key dot py right thenÂ 
you can see subscribe and unsubscribe then we are sending we are using dot send functionality ofÂ 
the WebSocket to up I would say authenticate it using the login details right basically in thatÂ 
we are just providing the API key right then we are subscribing to some tickers right in thisÂ 
case Apple this is not the market time so I will be doing it on crypto but yeah exactly the sameÂ 
thing can be done for stocks as well but actually I'll make the web application in a way that itÂ 
can be used for both stocks and crypto this is how we unsubscribe and this is how we extract theÂ 
the pricing information right so as I did in the last video I will be using streamlit here to makeÂ 
a web application because I really like streamlit also yeah it's it's very easy to use as well andÂ 
personally I have used it in a lot of application in my real world projects as well so yes importÂ 
streamlit as SD right I will have to install a couple of libraries like WebSocket and simple JsonÂ 
right but if you if you run this particular code it will throw some errors that there is no moduleÂ 
named WebSocket right so let's first install this one pip install simple Json okay it's alreadyÂ 
satisfied and it said it's present in Python 3 1 0 so I'll have to change the The Interpreter hereÂ 
I'll just go to basically I went to the this gear sign click on command palette and then interpreterÂ 
I will select three one zero and I think here this particular simple simple Json is actuallyÂ 
installed right so in order to install the WebSocket I highly recommend it in uninstallingÂ 
first because there are two three types of web sockets like import WebSocket like pip installÂ 
WebSocket pip install WebSocket client and pip install web sockets right these are the three oneÂ 
and for all of them the the way we import it is by the same thing which is import WebSocket so I willÂ 
uninstall all these three libraries first if it is already present in my system so pip uninstallÂ 
WebSocket it will ask me okay it's already not there pip uninstall web sockets right there'sÂ 
another one it is also not here in my system pip uninstall the spelling of uninstall an installÂ 
WebSocket client right this would definitely be there in my system perfect so I have uninstalledÂ 
all of them now let's install WebSocket client again pip install WebSocket client enter and itÂ 
will install the WebSocket client in your system right now let's first do one thing I will commentÂ 
this entire let me just bring it down a bit like this one I will comment this entire code and let'sÂ 
switch let's come to our streamlit platform which is St dot header and let's just write websiteÂ 
pocket API Financial modeling prep save it and here just write streamlit run and file name whichÂ 
is streaming.py I think now it's good so we'll just write streamlit run streaming Dot py and itÂ 
will open our a web application here right and the header is is WebSocket API Financial modelingÂ 
prep if you guys are confused about how to use streamlit I have made an entire playlist on how toÂ 
use streamlit and I highly recommend you guys to watch it because I covered all different aspectsÂ 
of streamlit library in that playlist and I'll be just directly using it in this video right soÂ 
the the header is WebSocket API Financial modeling prep now let's do one thing on the sidebar I willÂ 
provide the option of either going with crypto or stocks right so instrument is equal to St dotÂ 
sidebar dot select box right here I'll just write instrument type AI comma options and inside thisÂ 
I'll write crypto or stocks right so these are the two options if instrument is equal to cryptoÂ 
then WebSocket URL will be something I'll write it in some time if or I'll just write else WS URL isÂ 
equal to something else so let's come to this one and so this is the URL for stocks I'll just copyÂ 
it and paste it here and I'll just click on the crypto as well this is the URL for crypto and I'llÂ 
just paste it here so this is the URL I'll just remove the slash in the end here perfect so thisÂ 
is the WebSocket URL now I'll just uncomment all these things one by one WS WebSocket. WebSocketÂ 
yeah this is absolutely fine and this can be replaced with our WS URL right login is fineÂ 
there's no problem with that subscribe is fine right but And subscribe I will have to provideÂ 
a ticker as well so here only let's just write ticker is equal to St dot sidebar and then inputÂ 
in text right here I want thicker and the default text would be BTC USD let's just save it firstÂ 
so I'll just comment these again because I don't want WebSocket to be getting connected as of nowÂ 
so let's save it and this is our web application on the left hand side you can see there are twoÂ 
options crypto stocks here we'll write a vertical as per the documentation we will have to write ourÂ 
ticker in the lower case so we'll have to remember this thing always in our mind so yeah right nowÂ 
let's uncomment these two again I'll uncomment this entire thing right this apple should beÂ 
replaced with ticker right this API key will be imported from the API key file I'll just writeÂ 
from API key import API key right and this is the API key basically that I will be placing hereÂ 
right this is for subscribe and the same goes with answer in order to provide an option to stopÂ 
the WebSocket or run the WebSocket I will create another select box or Dropbox here on the sidebarÂ 
which will be actually giving us an option to run or stop this particular WebSocket I'll justÂ 
write run or stop and the options are run comma stop now I now I want all this only if we run itÂ 
so from here we're actually from here if Run Stop is equal to run then only do all these thingsÂ 
just provide this after an indentation right it will connect and then this is login subscribeÂ 
I am not changing anything here let's uncomment this as well right sleep of one second is notÂ 
required I'll just delete that this one as well subscribe see sleep is not required and thenÂ 
we have unsubscribed so I will have to provide unsubscribe separately so I'll just select it hereÂ 
in the end right if Run Stop is equal to stop then only it will be unsubscribing it right but I willÂ 
actually have to provide this down so like it would be like this right okay I'll just save itÂ 
and let's see I'll run this the web application on streamlit let's come here and let's click onÂ 
rerun okay this is run and stop I think I think I have selected a wrong yeah it should be selectÂ 
box Ctrl s to save if rent stop is equal to stop then unsubscribe and this and unsubscribe shouldÂ 
be to the ticker which is BTC us days off now and then it will unsubscribe post that we will closeÂ 
the WebSocket right and we'll just write st.write WebSocket closed right and yeah here we will haveÂ 
to actually connect the WebSocket again because it's a separate button here right so I'll justÂ 
provide WebSocket dot connect here as well let's just save it last thing which is this one here IÂ 
will have to actually write SC dot right and this particular message right I'll just comment this asÂ 
of now let's just save it and when we click on run here on the WebSocket so yes we have got loginÂ 
status is 200 message authenticated right then subscription is also being done with the BTCÂ 
USD and you can see the WebSocket is actually connected with our server and the real-timeÂ 
price of Bitcoin is actually coming right here as per the description LS is the amount ofÂ 
shares or volume traded at the last Price LP is the last price and you can we can see here LP hereÂ 
is last price which is thirty thousand three two hundred thirty for Bitcoin as of now and this isÂ 
the volume right of Bitcoin in this particular tick right this is the exchange and this isÂ 
the timestamp the ticker and that's it yeah so these are the all different things that we areÂ 
getting through the WebSocket now we'll have to structure it a bit because it's a bit difficultÂ 
to understand here so what I'll do is I'll just convert this entire thing into Json format and IÂ 
actually just need this time stamp and the last price information and even this timestamp shouldÂ 
be in a reading table date time format right so let's just do one thing let's click here if IÂ 
click on stop the WebSocket connection should be closed and this should stop happening yeahÂ 
perfect so WebSocket close and that's it so perfect the web application is working perfectlyÂ 
fine I will just make some data cleaning but just before that guys I have a very importantÂ 
information to share recently I launched a course on python for financial programming soÂ 
if you are trying to Learn Python for finance from scratch that this is something that youÂ 
might be interested in just go to my website which is fps.com python over here you will see twoÂ 
buttons Indian candidates non-indian candidates so you can click as per your location it willÂ 
redirect you to this the main website where the entire course information is available you'll seeÂ 
that there are five sessions 10 chapters 22 videos 10 quizzes and three assignments with two liveÂ 
projects and this is the entire syllabus of this course for all the people who are interestedÂ 
to Learn Python for from scratch and who are struggling learning python on their own I highlyÂ 
recommend it because it's very very affordable and I have covered a lot of things from a veryÂ 
very simplistic eyesight and in the end in session four and five you'll see stock analysisÂ 
and Investment Portfolio creation projects which are my personal projects we did it using someÂ 
financial analysis if you use RTK40 code you'll get an instant 40 discount which is only availableÂ 
for the first hundred candidates so yes guys I'll see you in the course let's come back to ourÂ 
code let's come back to our code this is the code now what I'll do here is first of all let'sÂ 
just write it another variable which is message this is the message and let's just convert toÂ 
json format Json dot loads and then inside this this is the message right now I'll just commentÂ 
this particular line rather than this I'll just write SD dot write message now I'll just use tryÂ 
and accept here try message and then inside this if you remember there equals t let us just runÂ 
the run the WebSocket again just to understand it even better so I'll just save it againÂ 
let's come back to our web application so yeah so D is the first one and LP small LP andÂ 
small T are the two things which I am actually interested in so I'll just stop it again it'sÂ 
come here now I'll just write try message â€˜tâ€™ which is the times this time or I'll just writeÂ 
time period is equal to this one and I'll have to divide it by 1000 because it's in millisecondsÂ 
I just want it in seconds so date time would be I'll have to import from date time import dateÂ 
time right here I'll just come here date time Dot from timestamp and then here I'll just write timeÂ 
period the last price if you remember it was LP so message and then inside this LP so just write SDÂ 
dot write and then here date right it's just after that we will write the date time same goes withÂ 
the last price as well last price right here and then St dot right last price right and then acceptÂ 
if this does not happen I'll just pass let's save it and I'll also remove or comment this particularÂ 
message I'm just interested in the date and the last price let's save it okay so when we click onÂ 
run here we can see that date and last price is in front of us this date is hour minute seconds andÂ 
even what's a milliseconds or in decimal points of seconds and you can see the data is extractingÂ 
really really fast so this is five seconds and then 11 seconds 12 seconds 18 seconds 22 secondsÂ 
so I think three in three to four seconds we are getting the prices of Bitcoin from best socketÂ 
and we are using Financial modeling prep as our backend API to extract the pricing details andÂ 
you can see that it's continuously coming now I'll just keep this video till here only this isÂ 
how we can actually make the the stock screener to extract the real-time prices of stocks and cryptoÂ 
the the market is not working currently but if you click on stocks and just write the sticker name ofÂ 
that stock for example AAPL in lower case then the same thing will be happening for stocks as wellÂ 
there's a great web application which is actually going to which can there's a great web applicationÂ 
that we have built which can actually be used in a lot of applications like making our own tradingÂ 
bot and then deploying this on a server so yes this is something that if definitely we canÂ 
consider for our further analysis and let's run let's stop this particular WebSocket when we clickÂ 
on stop the WebSocket will be close and that's it so yes guys I'll be saving this code in my GoogleÂ 
Drive and my already existing subscribers know that I share my Google Drive access my new viewersÂ 
or subscribers just wait for a couple of minutes I'll tell you how to get an access of my GoogleÂ 
Drive but yeah before that if you liked even one thing about this video guys just click on the likeÂ 
button because it really helps with algorithm and also click on the Subscribe button because thereÂ 
is a lot of content in my pipeline that will be covered on this YouTube channel and you can watchÂ 
all of them for free for freelancing inquiries you can contact me on this email address and I'll tryÂ 
my best to reach out to you as soon as possible in order to become the Google Drive CommunityÂ 
member just go to my YouTube channel and click on the access to my Google Drive button and overÂ 
there just follow some basic steps and you can see that it's really really affordable to join myÂ 
Google Drive Community which costs one third of a coffee price and I'm actually charging this smallÂ 
amount of money because I had a couple of interns who are actually managing that Google driveÂ 
to provide the best possible services to the community members and this code will give savedÂ 
in my Google Drive and not only this one there are many more codes and study materials thatÂ 
are saved in that particular Drive including my trading bot and other things as well like myÂ 
script trading strategies etc etc so just check it out and read the benefits of my Google DriveÂ 
also the link of my course is in the description box just check it out and let me know yourÂ 
thoughts on the comment section thank you so much for watching this video till the end youÂ 
can click here to subscribe to my YouTube channel and whether you'll see this entire playlist onÂ 
financial modeling prep which is of three videos is the last video and over there you'll see myÂ 
most recent video which is uploaded here so just keep learning keep Financial programming and I'llÂ 
see you very very soon next week until then PEACE!

</details>
