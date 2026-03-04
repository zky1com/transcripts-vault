---
title: "Financial Modeling Prep API Python [MOST ACCURATE Financial Data API] ðŸ”´"
people_mentioned: ["Ritvik Dashora", "Financial Modeling Prep"]
channel: "Financial Programming with Ritvik, CFA"
video_id: "-nMISKKuKsc"
url: "https://www.youtube.com/watch?v=-nMISKKuKsc"
publish_date: 2023-07-22
duration: "15:06"
word_count: 2778
content_type: "solo-talk"
delivery_mode: "opinion"
broad_category: "finance-investing"
subcategories: ["stock-analysis", "market-data"]
series_name: ""
episode_id: ""
primary_person: "Ritvik Dashora"
host_names: []
interviewer_names: []
interviewee_profiles: []
speaker_profiles: ["Ritvik Dashora - Tesla"]
organizations_mentioned: ["Financial Programming with Ritvik, CFA"]
locations_mentioned: []
tools_mentioned: []
companies_mentioned: ["Tesla"]
topics: ["stock-analysis", "market-data", "ai-coding", "lead-generation"]
tags: ["stock-analysis", "market-data", "ai-coding", "lead-generation"]
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

The discussion centers on let's, data, statement. Name for example Apple wellÂ let's do Tesla right Tesla and let's I'm actually interested in cash flow statement of Tesla cashÂ. Are all the thingsÂ which are available for free income statement balance sheet statement cash flow statementÂ income statement growth balance sheet. Let's just import request library because I'll be using requests libraryÂ to extract the data Also let's get let's import the pandas.

## Key Insights


- Name for example Apple wellÂ let's do Tesla right Tesla and let's I'm actually interested in cash flow statement of Tesla cashÂ.
- Are all the thingsÂ which are available for free income statement balance sheet statement cash flow statementÂ income statement growth balance sheet.
- Let's just import request library because I'll be using requests libraryÂ to extract the data Also let's get let's import the pandas.
- Let's just come here and let's see theÂ data type is equal to in this case I'm just let's just copy.
- Let's see if I click on this particular link yeah soÂ this data is available for free let me just copy this.
- Flow statement growth of Tesla perfect so yeah this is the cash flow statement growth of TeslaÂ and I think it's available.

## People Mentioned


- [[Ritvik Dashora]]




## Full Transcript

<details>
<summary>Click to expand full transcript (2778 words)</summary>

Hello Hello Mic test ðŸ‘€ FOLLOW CAPTIONS TO KNOW MORE ðŸ‘€ [Music] just write the ticker name over here andÂ 
on the back end we are using the free API so you're not paying anything I'm actuallyÂ 
interested in cash flow statement of Tesla so yeah this is the cash flow statement of TeslaÂ 
I think it's available for many years since 2007. hello Financial programmers I am Ritvik DashoraÂ 
and I'm back with a new video and some new learnings this is the first video of our newÂ 
playlist and this one it's on Financial Modeling Prep python API as per their website they are theÂ 
most accurate financial data API and I'm making this video to figure it out in this video I willÂ 
cover all the free data aspects of this API and in the next video I will talk about some paid dataÂ 
as well and and in the last video I will cover websocket and we'll try to make something on thatÂ 
but before that guys if you are new to my YouTube channel guys on this channel I upload videosÂ 
related to trading Bots exploring some highly valuable Finance APIs like this one making someÂ 
Pine script reading strategies and implementation of AI in finance etc etc so if this is somethingÂ 
that you are interested in then just click on the Subscribe button and also hit on the Bell icon asÂ 
I have many more topics in my pipeline that will be covered on this particular YouTube channelÂ 
so what are the topics to cover in this video two SIM simple things first thing is we'll talkÂ 
about Financial Modeling Prep API and the second is we'll be exploring their documentationÂ 
and will create something great using that so without any further Ado let's start so guysÂ 
this is the website of Financial Modeling Prep which is financial modelingprep.com and you'llÂ 
see they cover a lot of stuff like latest news discounted cash flow model some insights about theÂ 
market there are some educational content as well and this is something that I'm interested in whichÂ 
is API docs I will talk about it in some time but before that let's explore what other things areÂ 
available on this particular platform so they provide a most surged tickers gainers losersÂ 
currencies cryptocurrencies sector performance which is industry performance and other thingsÂ 
as well so yeah it looks quite interesting and let's jump to the API docs here guys it asks meÂ 
to sign up I just signed up with one of my email address and yes so this is the API documentationÂ 
of Financial Modeling Prep I will provide this link in the description box for you and as IÂ 
mentioned they quote themselves as the most accurate financial data API they provide freeÂ 
stock data historical data financial statements Etc just below this one which is your detailsÂ 
you'll find your API key so you just copy and paste it and store it somewhere for theÂ 
coding purpose right so this is the first thing which is stock fundamentals right and IÂ 
think they have the direct URL through which we will extract the information so if we clickÂ 
on this particular link you'll see the output yeah perfect so we have a URL and then we'llÂ 
be extracting information through the URL this is my API key which I will definitely changeÂ 
after recording this video and the main idea here is to use this particular URL and thenÂ 
eventually using requests library to extract financial data in Python perfect let's come backÂ 
to our documentation so we have things like in the left hand side you can see stock fundamentals starÂ 
fundamentals analysis institutions stock ownership oh that's something very interesting here let'sÂ 
let me just click here I don't think they will provide it for free yeah for this I'll have toÂ 
upgrade it to the premium one anyways I will do it just after this video because the second videoÂ 
will be about the paid version only let's see ESG score is I think again something which willÂ 
be covered in the premium yeah subscription and then the price Target upgrades downgradesÂ 
ETF and mutual funds Holdings right employees and executive compensation stock calendars that'sÂ 
good company information stock news that's amazing 100 sure it would be a part of the paid versionÂ 
only so let's see yeah no worries we'll check it later other things market performance AdvancedÂ 
Data stock statistics insider trading again this would be paid only Senate trading economicsÂ 
stock price fund Holdings websocket this is something that I will cover in the last videoÂ 
stock list bulk and batch this is very helpful when we create a trading bot on multiple stocksÂ 
right so using this basically we can create API requests on multiple stickers so for example thisÂ 
is one is a batch request where we are doing we are extracting the stock news on Apple FacebookÂ 
and Google and Amazon so yeah market indices Euro next TCX and crypto Forex and community soÂ 
they have a lot of data to be honest and if they code themselves as the most accurate then I thinkÂ 
it's good it's like the One-Stop solution for us so I'll start with the first one I'm 100 sure theÂ 
company financial statements would be free let's see if I click on this particular link yeah soÂ 
this data is available for free let me just copy this particular link and let's come back to ourÂ 
code I'm using Google collab for writing this code you can use any other platform as well URLÂ 
is this particular and let's just provide it as string now I'll have to make this URL customizedÂ 
for different things so for in this example I'm actually extracting income statement of apple andÂ 
this is APA key right so let's just import request library because I'll be using requests libraryÂ 
to extract the data Also let's get let's import the pandas Library import pandas as PD thisÂ 
particular URL would be the base URL right so I'll just write base URL here let's just provideÂ 
it inside the string which is single or double inverted comma and here let's provide F stringÂ 
and just change this to base URL right this is income statement right I'm sure that this wouldÂ 
be changed if we extract some other information so for example if I just click on balance sheetÂ 
then yeah I have balance sheet statement here in the URL so let's just come here and let's see theÂ 
data type is equal to in this case I'm just let's just copy and paste it this one which is incomeÂ 
statement right and replace this to data type ticker is apple right inside the sticker limitÂ 
is 120 I will delete this part because I don't require it API key this is my API so I'll justÂ 
write API key is equal to this one which I'll be changing after recording this video anywaysÂ 
it's a free API you can get it for free so I'll just write API and then key it looks great nowÂ 
let's see if I just write URL and hit enter Then I should be getting the URL that will have all theÂ 
information okay so this is the URL I'll just copy this and just let's paste it here yeah perfectÂ 
so this is exactly the same URL that will give me the entire income statement of apple rightÂ 
so now let's use the requests Library which is response is equal to requests dot get I'm actuallyÂ 
doing the get request here and then URL right now let's convert this into Json format so responseÂ 
dot Json reason let's hit enter if I write data and hit enter you'll see the entire in an incomeÂ 
statement in front of us the last one is is dated as of September 2022 yeah it's not September 2023Â 
as of now as per the today's date so yeah the last one is this one let's see how many items are thereÂ 
inside this particular list there are five items so the data is of last five years right so whatÂ 
I'll do is the data frame is equal to P PD dot data frame and then inside this I will provideÂ 
data let's see what is date BF now perfect so this is DF where we have all the line items inÂ 
as a column header so I'll have to transport transpose it so I just write .T here and let'sÂ 
see what's the result now I want them as a row header exactly like this one so you can see thatÂ 
on the left hand side we have all the line items which is the type of data here and then on theÂ 
right hand side on the columns you'll see the data that we have this is the first one which is ninthÂ 
which is September 2022 then September 2021 and so on so yeah all this information is availableÂ 
things like operating expense cost and expenses Revenue cost of Revenue and I think then theÂ 
last line would be net income yeah here we have the net income oh that's great they have actuallyÂ 
provided a link of SEC filing as well right that's great just to provide the additional validation ofÂ 
the data that's great okay let's come to see what other things are available here but just beforeÂ 
that guys I have a very important information to share recently I launched a course on pythonÂ 
for financial programming so if you are trying to Learn Python for finance from scratch thenÂ 
this is something that you might be interested in just go to my website which is fbrethwik.comÂ 
python over here you will see two buttons Indian candidates non-indian candidates so you canÂ 
click as per your location it will redirect you to this the main website where the entire courseÂ 
information is available you'll see that there are five sessions 10 chapters 22 videos 10 quizzesÂ 
and three assignments with two live projects and this is the entire syllabus of this course for allÂ 
the people who are interested to Learn Python from scratch and who are struggling learning pythonÂ 
on their own I highly recommend it because it's very very affordable and I have covered a lot ofÂ 
things from a very very simplistic eyesight and in the end in session four and five you'll seeÂ 
stock analysis and Investment Portfolio creation projects which are my personal projects we didÂ 
it using some financial analysis if you use RTK40 code you'll get an instant 40 discount which isÂ 
only available for the first 100 candidates so yes guys I'll see you in the course let's come back toÂ 
our code okay so other things that are available on the free API apart from I think all the threeÂ 
statements are available which is income statement balance sheet and cash flow yeah cash flow isÂ 
also available so I'll just write it here all the things which are available so what I'm going to doÂ 
is just copy and paste it like I'll just copy this and then paste it here and it will give me theÂ 
balance sheet right so let's see yeah perfect we have got the balance sheet now net receivables andÂ 
so on so I will actually just make a list of all the different data tables that which are availableÂ 
income statement balance sheet cash flow statement what else if we click on sells sales to salesÂ 
product segmentation is not available for free no worries let's come back to the API documentationÂ 
so I'll let me just pause this video for a second I'll write down all the things which are availableÂ 
for the free course and we'll come back just one second okay guys so these are all the thingsÂ 
which are available for free income statement balance sheet statement cash flow statementÂ 
income statement growth balance sheet statement growth cash flow statement growth ratios whichÂ 
is trailing 12 months ratios Financial growth code which is basically the pricing informationÂ 
Enterprise Value key metrics TTM key metrics rating historical rating discounted cash flowÂ 
model historical discounted cash flow statement historical chart for different time intervalsÂ 
for example one minute discounted cash flow model which is DCF Model A very important andÂ 
useful model for valuation so this is as per the DCF the the price should be 193.9 right nowÂ 
the current price is 192. so these are all the different things which are available for free onÂ 
Financial Modeling Prep and guys while researching for the different types of data which is availableÂ 
for free I actually created one code on Visual Studio basically I'm using Streamlit here to makeÂ 
it look better than the Google collab which is this one because in this case I have to copy andÂ 
paste it again and again here and here I have just provided it as a select box you can just writeÂ 
this code on visual studio and use it or if you want to get this particular code I'll be savingÂ 
this code on my Google Drive how to get a Google Drive access or my already existing subscribersÂ 
know already if you are my new viewer then just wait for five minutes perfect so what we do hereÂ 
is I'll just write Streamlit run FMP underscore video one this is the file name basically productÂ 
dot py let's press enter it will automatically open a web application now if you guys areÂ 
facing any difficulty I have made an entire playlist on how to use Streamlit and it's a veryÂ 
very useful web application so basically here just write the ticker name over here and it will doÂ 
everything and again as I mentioned on the back end we are using the free API so you're not payingÂ 
anything to make this particular web application you can deploy this web application to someÂ 
other platforms as well if you want okay so I'll just write the ticker name for example Apple wellÂ 
let's do Tesla right Tesla and let's I'm actually interested in cash flow statement of Tesla cashÂ 
flow statement growth of Tesla perfect so yeah this is the cash flow statement growth of TeslaÂ 
and I think it's available for many years since 2007 right if you are interested in something elseÂ 
for example I am let's see Enterprise Value then yeah it has given me the Enterprise Value whereÂ 
markets market capitalization number of shares Enterprise Value Etc of Tesla in last I think 15Â 
years 15 or something 15 16 years perfect so yeah the VA Studio code which is this particular codeÂ 
will be saved on my Google Drive and not only this code there are many more codes saved on my GoogleÂ 
Drive like my personal trading bot and some point script strategies and in order to become a GoogleÂ 
Drive Community member just come to my channel and click on the access to my Google Drive buttonÂ 
and over there you just follow some basic steps in order to get the access of my Google DriveÂ 
you can see that it's very very affordable it costs less than a third of a coffee price andÂ 
this is something that I'm charging because I have recently hired an intern to provide the bestÂ 
possible service to all my community members if you like even one thing about this video then guysÂ 
just click on the like button down below it really helps with the algorithm and also subscribeÂ 
to my YouTube channel to not miss out on the future content for free in the next video I'llÂ 
be talking about more aspects of this particular library and I will actually buy the paid versionÂ 
of this API because I'm very interested to explore more things here and let's see if we can makeÂ 
something great for freelancing inquiries you can reach out to me on this email address andÂ 
the link of my a course on python for financial programming is in the description box thank you soÂ 
much for watching this video till the end you can click here to subscribe to my YouTube channelÂ 
and over there you'll see the entire playlist which covers these three videos on FinancialÂ 
Modeling Prep and over there you'll see the most recent video that I uploaded keep watching keepÂ 
learning and I'll see you very very soon, PEACE!

</details>
