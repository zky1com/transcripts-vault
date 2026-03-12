---
title: "Financial Modeling Prep | *GO-TO* Financial data API python for 2025 âš¡"
people_mentioned: ["Ritvik Dashora", "Financial Modeling Prep", "Advanced Data"]
channel: "Financial Programming with Ritvik, CFA"
video_id: "4mrGGb7j_14"
url: "https://www.youtube.com/watch?v=4mrGGb7j_14"
publish_date: 2024-12-28
duration: "15:06"
word_count: 2777
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

The discussion centers on let's, data, statement. Name for example Apple wellÂ let's do Tesla right Tesla and let's I'm actually interested in cash flow statement of Tesla cashÂ. Are all the things which are available for free income statement balance sheet statement cashÂ flow statement income statement growth balance sheet. Let's just import request library because I'll be using requests library to extract the dataÂ Also let's get let's import the pandas.

## Key Insights


- Name for example Apple wellÂ let's do Tesla right Tesla and let's I'm actually interested in cash flow statement of Tesla cashÂ.
- Are all the things which are available for free income statement balance sheet statement cashÂ flow statement income statement growth balance sheet.
- Let's just import request library because I'll be using requests library to extract the dataÂ Also let's get let's import the pandas.
- Let's just come here and let's see the data type is equal toÂ in this case I'm just let's just copy.
- Let's see if I click on this particular link yeah so this data is availableÂ for free let me just copy this.
- Flow statement growth of Tesla perfect so yeah this is the cash flow statement growth of TeslaÂ and I think it's available.

## People Mentioned


- [[Ritvik Dashora]]




## Full Transcript

<details>
<summary>Click to expand full transcript (2777 words)</summary>

Hello Hello Mic test ðŸ‘€ FOLLOW CAPTIONS TO KNOW MORE ðŸ‘€ just write the ticker name over hereÂ 
and on the back end we are using the free API so you're not paying anything I'm actuallyÂ 
interested in cash flow statement of Tesla so yeah this is the cash flow statement of TeslaÂ 
I think it's available for many years since 2007. hello Financial programmers I am RitvikÂ 
Dashora and I'm back with a new video and some new learnings this is the first video of our newÂ 
playlist and this one it's on Financial Modeling Prep python API as per their website they are theÂ 
most accurate financial data API and I'm making this video to figure it out in this video I willÂ 
cover all the free data aspects of this API and in the next video I will talk about some paidÂ 
data as well and and in the last video I will cover websocket and we'll try to make somethingÂ 
on that but before that guys if you are new to my YouTube channel guys on this channel I uploadÂ 
videos related to trading Bots exploring some highly valuable Finance APIs like this oneÂ 
making some Pine script reading strategies and implementation of AI in finance etc etc so ifÂ 
this is something that you are interested in then just click on the Subscribe button and also hitÂ 
on the Bell icon as I have many more topics in my pipeline that will be covered on this particularÂ 
YouTube channel so what are the topics to cover in this video two SIM simple things first thingÂ 
is we'll talk about Financial Modeling Prep API and the second is we'll be exploring theirÂ 
documentation and will create something great using that so without any further Ado let's startÂ 
so guys this is the website of Financial Modeling Prep which is financial modelingprep.comÂ 
and you'll see they cover a lot of stuff like latest news discounted cash flow modelÂ 
some insights about the market there are some educational content as well and this is somethingÂ 
that I'm interested in which is API docs I will talk about it in some time but before that let'sÂ 
explore what other things are available on this particular platform so they provide a most surgedÂ 
tickers gainers losers currencies cryptocurrencies sector performance which is industry performanceÂ 
and other things as well so yeah it looks quite interesting and let's jump to the API docs hereÂ 
guys it asks me to sign up I just signed up with one of my email address and yes so this is the APIÂ 
documentation of Financial Modeling Prep I will provide this link in the description box for youÂ 
and as I mentioned they quote themselves as the most accurate financial data API they provide freeÂ 
stock data historical data financial statements Etc just below this one which is your detailsÂ 
you'll find your API key so you just copy and paste it and store it somewhere for the codingÂ 
purpose right so this is the first thing which is stock fundamentals right and I think they haveÂ 
the direct URL through which we will extract the information so if we click on this particular linkÂ 
you'll see the output yeah perfect so we have a URL and then we'll be extracting informationÂ 
through the URL this is my API key which I will definitely change after recording this video andÂ 
the main idea here is to use this particular URL and then eventually using requests library toÂ 
extract financial data in Python perfect let's come back to our documentation so we haveÂ 
things like in the left hand side you can see stock fundamentals star fundamentals analysisÂ 
institutions stock ownership oh that's something very interesting here let's let me just click hereÂ 
I don't think they will provide it for free yeah for this I'll have to upgrade it to the premiumÂ 
one anyways I will do it just after this video because the second video will be about the paidÂ 
version only let's see ESG score is I think again something which will be covered in the premiumÂ 
yeah subscription and then the price Target upgrades downgrades ETF and mutual funds HoldingsÂ 
right employees and executive compensation stock calendars that's good company information stockÂ 
news that's amazing 100 sure it would be a part of the paid version only so let's see yeahÂ 
no worries we'll check it later other things market performance Advanced Data stock statisticsÂ 
insider trading again this would be paid only Senate trading economics stock price fund HoldingsÂ 
websocket this is something that I will cover in the last video stock list bulk and batch thisÂ 
is very helpful when we create a trading bot on multiple stocks right so using this basically weÂ 
can create API requests on multiple stickers so for example this is one is a batch request whereÂ 
we are doing we are extracting the stock news on Apple Facebook and Google and Amazon so yeahÂ 
market indices Euro next TCX and crypto Forex and community so they have a lot of data to be honestÂ 
and if they code themselves as the most accurate then I think it's good it's like the One-StopÂ 
solution for us so I'll start with the first one I'm 100 sure the company financial statementsÂ 
would be free let's see if I click on this particular link yeah so this data is availableÂ 
for free let me just copy this particular link and let's come back to our code I'm using GoogleÂ 
collab for writing this code you can use any other platform as well URL is this particular and let'sÂ 
just provide it as string now I'll have to make this URL customized for different things so forÂ 
in this example I'm actually extracting income statement of apple and this is APA key right soÂ 
let's just import request library because I'll be using requests library to extract the dataÂ 
Also let's get let's import the pandas Library import pandas as PD this particular URL would beÂ 
the base URL right so I'll just write base URL here let's just provide it inside the stringÂ 
which is single or double inverted comma and here let's provide F string and just change thisÂ 
to base URL right this is income statement right I'm sure that this would be changed if we extractÂ 
some other information so for example if I just click on balance sheet then yeah I have balanceÂ 
sheet statement here in the URL so let's just come here and let's see the data type is equal toÂ 
in this case I'm just let's just copy and paste it this one which is income statement right andÂ 
replace this to data type ticker is apple right inside the sticker limit is 120 I will delete thisÂ 
part because I don't require it API key this is my API so I'll just write API key is equal to thisÂ 
one which I'll be changing after recording this video anyways it's a free API you can get it forÂ 
free so I'll just write API and then key it looks great now let's see if I just write URL and hitÂ 
enter Then I should be getting the URL that will have all the information okay so this is theÂ 
URL I'll just copy this and just let's paste it here yeah perfect so this is exactly the sameÂ 
URL that will give me the entire income statement of apple right so now let's use the requestsÂ 
Library which is response is equal to requests dot get I'm actually doing the get request hereÂ 
and then URL right now let's convert this into Json format so response dot Json reason let'sÂ 
hit enter if I write data and hit enter you'll see the entire in an income statement in front ofÂ 
us the last one is is dated as of September 2022 yeah it's not September 2023 as of now as perÂ 
the today's date so yeah the last one is this one let's see how many items are there inside thisÂ 
particular list there are five items so the data is of last five years right so what I'll do isÂ 
the data frame is equal to P PD dot data frame and then inside this I will provide data let's seeÂ 
what is date BF now perfect so this is DF where we have all the line items in as a column headerÂ 
so I'll have to transport transpose it so I just write .T here and let's see what's the result nowÂ 
I want them as a row header exactly like this one so you can see that on the left hand side weÂ 
have all the line items which is the type of data here and then on the right hand side onÂ 
the columns you'll see the data that we have this is the first one which is ninth which isÂ 
September 2022 then September 2021 and so on so yeah all this information is available things likeÂ 
operating expense cost and expenses Revenue cost of Revenue and I think then the last line wouldÂ 
be net income yeah here we have the net income oh that's great they have actually provided aÂ 
link of SEC filing as well right that's great just to provide the additional validation of theÂ 
data that's great okay let's come to see what other things are available here but just beforeÂ 
that guys I have a very important information to share recently I launched a course on pythonÂ 
for financial programming so if you are trying to Learn Python for finance from scratch thenÂ 
this is something that you might be interested in just go to my website which is fbrethwik.comÂ 
python over here you will see two buttons Indian candidates non-indian candidates so you canÂ 
click as per your location it will redirect you to this the main website where the entire courseÂ 
information is available you'll see that there are five sessions 10 chapters 22 videos 10 quizzes andÂ 
three assignments with two live projects and this is the entire syllabus of this course for all theÂ 
people who are interested to Learn Python from scratch and who are struggling learning pythonÂ 
on their own I highly recommend it because it's very very affordable and I have covered a lot ofÂ 
things from a very very simplistic eyesight and in the end in session four and five you'll seeÂ 
stock analysis and Investment Portfolio creation projects which are my personal projects we didÂ 
it using some financial analysis if you use RTK40 code you'll get an instant 40 discount which isÂ 
only available for the first 100 candidates so yes guys I'll see you in the course let's comeÂ 
back to our code okay so other things that are available on the free API apart from I thinkÂ 
all the three statements are available which is income statement balance sheet and cash flow yeahÂ 
cash flow is also available so I'll just write it here all the things which are available so whatÂ 
I'm going to do is just copy and paste it like I'll just copy this and then paste it here andÂ 
it will give me the balance sheet right so let's see yeah perfect we have got the balance sheetÂ 
now net receivables and so on so I will actually just make a list of all the different data tablesÂ 
that which are available income statement balance sheet cash flow statement what else if we clickÂ 
on sells sales to sales product segmentation is not available for free no worries let's come backÂ 
to the API documentation so I'll let me just pause this video for a second I'll write down all theÂ 
things which are available for the free course and we'll come back just one second okay guys soÂ 
these are all the things which are available for free income statement balance sheet statement cashÂ 
flow statement income statement growth balance sheet statement growth cash flow statementÂ 
growth ratios which is trailing 12 months ratios Financial growth code which is basicallyÂ 
the pricing information Enterprise Value key metrics TTM key metrics rating historical ratingÂ 
discounted cash flow model historical discounted cash flow statement historical chart for differentÂ 
time intervals for example one minute discounted cash flow model which is DCF Model A veryÂ 
important and useful model for valuation so this is as per the DCF the the price should beÂ 
193.9 right now the current price is 192. so these are all the different things which are availableÂ 
for free on Financial Modeling Prep and guys while researching for the different types of dataÂ 
which is available for free I actually created one code on Visual Studio basically I'm usingÂ 
Streamlit here to make it look better than the Google collab which is this one because in thisÂ 
case I have to copy and paste it again and again here and here I have just provided it as a selectÂ 
box you can just write this code on visual studio and use it or if you want to get this particularÂ 
code I'll be saving this code on my Google Drive how to get a Google Drive access or my alreadyÂ 
existing subscribers know already if you are my new viewer then just wait for five minutes perfectÂ 
so what we do here is I'll just write Streamlit run FMP underscore video one this is the file nameÂ 
basically product dot py let's press enter it will automatically open a web application now if youÂ 
guys are facing any difficulty I have made an entire playlist on how to use Streamlit and it's aÂ 
very very useful web application so basically here just write the ticker name over here and it willÂ 
do everything and again as I mentioned on the back end we are using the free API so you're not payingÂ 
anything to make this particular web application you can deploy this web application to someÂ 
other platforms as well if you want okay so I'll just write the ticker name for example Apple wellÂ 
let's do Tesla right Tesla and let's I'm actually interested in cash flow statement of Tesla cashÂ 
flow statement growth of Tesla perfect so yeah this is the cash flow statement growth of TeslaÂ 
and I think it's available for many years since 2007 right if you are interested in something elseÂ 
for example I am let's see Enterprise Value then yeah it has given me the Enterprise Value whereÂ 
markets market capitalization number of shares Enterprise Value Etc of Tesla in last I think 15Â 
years 15 or something 15 16 years perfect so yeah the VA Studio code which is this particularÂ 
code will be saved on my Google Drive and not only this code there are many more codes savedÂ 
on my Google Drive like my personal trading bot and some point script strategies and in order toÂ 
become a Google Drive Community member just come to my channel and click on the access to my GoogleÂ 
Drive button and over there you just follow some basic steps in order to get the access of myÂ 
Google Drive you can see that it's very very affordable it costs less than a third of a coffeeÂ 
price and this is something that I'm charging because I have recently hired an intern to provideÂ 
the best possible service to all my community members if you like even one thing about thisÂ 
video then guys just click on the like button down below it really helps with the algorithm and alsoÂ 
subscribe to my YouTube channel to not miss out on the future content for free in the next video I'llÂ 
be talking about more aspects of this particular library and I will actually buy the paid versionÂ 
of this API because I'm very interested to explore more things here and let's see if we can makeÂ 
something great for freelancing inquiries you can reach out to me on this email address andÂ 
the link of my a course on python for financial programming is in the description box thank you soÂ 
much for watching this video till the end you can click here to subscribe to my YouTube channelÂ 
and over there you'll see the entire playlist which covers these three videos on FinancialÂ 
Modeling Prep and over there you'll see the most recent video that I uploaded keep watching keepÂ 
learning and I'll see you very very soon, PEACE!

</details>
