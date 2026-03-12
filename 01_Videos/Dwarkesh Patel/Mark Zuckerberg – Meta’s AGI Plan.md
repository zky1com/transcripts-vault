---
title: "Mark Zuckerberg â€“ Metaâ€™s AGI Plan"
people_mentioned: ["Little Llama", "Chatbot Arena"]
channel: "Dwarkesh Patel"
video_id: "rYXeQbTuVl0"
url: "https://www.youtube.com/watch?v=rYXeQbTuVl0"
publish_date: 2025-04-29
duration: "1:15:50"
word_count: 11136
content_type: "solo-talk"
delivery_mode: "opinion"
broad_category: "ai"
subcategories: ["ai-safety", "ai-regulation", "ai-jobs", "ai-agents", "ai-coding", "ai-economics"]
series_name: ""
episode_id: ""
primary_person: "Little Llama"
host_names: []
interviewer_names: []
interviewee_profiles: []
speaker_profiles: ["Little Llama - Meta"]
organizations_mentioned: ["Dwarkesh Patel"]
locations_mentioned: []
tools_mentioned: []
companies_mentioned: ["Meta"]
topics: ["ai-safety", "ai-regulation", "ai-jobs", "ai-agents", "ai-coding", "ai-economics", "product-management"]
tags: ["ai-safety", "ai-regulation", "ai-jobs", "ai-agents", "ai-coding", "ai-economics", "product-management"]
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

The discussion centers on more, it's, that's. If you think about it, the Meta socialÂ media view of the world is that yeah, people are going to spend a lot more. One other thought that I think is interesting to cover isÂ that I tend to think that, for at least the foreseeable future, this. If people are doing something, theyÂ probably think it's good for them.

## Key Insights


- If you think about it, the Meta socialÂ media view of the world is that yeah, people are going to spend a lot more time doingÂ.
- One other thought that I think is interesting to cover isÂ that I tend to think that, for at least the foreseeable future, this is going.
- If people are doing something, theyÂ probably think it's good for them.
- I also think we're goingÂ to want to have a business model that supports people using arbitrary amounts of compute to doÂ even more amazing things.
- The net result is that I actually think we're probablyÂ going to hire more customer support people.
- It's going to be a lot better, and it's going to help you connect,Â because it'll help express different ideas.

## People Mentioned


- [[Little Llama]]

- [[Chatbot Arena]]




## Full Transcript

<details>
<summary>Click to expand full transcript (11136 words)</summary>

Mark, thanks for coming on the podcast again.
Yeah, happy to do it. Good to see you. You too. Last time you were here, you hadÂ 
launched Llama 3. Now you've launched Llama 4. Well, the first version.
That's right. What's new? What's exciting? What's changed?
The whole field is so dynamic. I feel like a ton has changed since the last time we talked. Meta AIÂ 
has almost a billion people using it monthly now, which is pretty wild. I think this is going to beÂ 
a really big year for all of this, especially once you get the personalization loop going, whichÂ 
weâ€™re just starting to build in now really, from both the context that all the algorithmsÂ 
have about what youâ€™re interested in â€” feed, your profile information, your social graph informationÂ 
â€” but also what you're interacting with the AI about. Thatâ€™s going to be the next thingÂ 
that's super exciting. I'm really big on that. The modeling stuff continues to make reallyÂ 
impressive advances too. I'm pretty happy with the first set of Llama 4 releases.Â 
We announced four models and released the first two â€” the Scout and Maverick onesÂ 
â€” which are mid-size to small models. The most popular Llama 3 model was the 8Â 
billion parameter one. So weâ€™ve got one of those coming in the Llama 4 series too. OurÂ 
internal code name for it is â€œLittle Llama.â€ Thatâ€™s coming probably over the next few months.
Scout and Maverick are good. They have some of the highest intelligence per cost you can get ofÂ 
any model out there. Theyâ€™re natively multimodal, very efficient, run on one host. Theyâ€™re designedÂ 
to be very efficient and low latency, for a lot of the use cases weâ€™re building for internally.Â 
Thatâ€™s our whole thing. We build what we want, and then we open-source it so other peopleÂ 
can use it too. I'm excited about that. I'm also excited about the Behemoth model, whichÂ 
is coming up. It's going to be our first model that's sort of at the frontier â€” more thanÂ 
2 trillion parameters. As the name says, it's quite big. Weâ€™re trying to figure out howÂ 
to make that useful for people. Itâ€™s so big that we've had to build a bunch of infrastructureÂ 
just to be able to post-train it ourselves. Now we're trying to wrap our heads around, howÂ 
does the average developer out there actually use something like this? How do we make itÂ 
useful â€” maybe by distilling it into models that are a reasonable size to run? BecauseÂ 
you're obviously not going to want to run something like that in a consumer model.
As you saw with the Llama 3 stuff last year, the initial launch was exciting and then weÂ 
just built on that over the year. 3.1 released the 405 billion model, 3.2 is when we got all theÂ 
multimodal stuff in. We basically have a roadmap like that for this year too. So a lot going on.
I'm interested to hear more about it. There's this impression that the gap between the bestÂ 
closed-source and the best open-source models has increased over the last year. I know theÂ 
full family of Llama 4 models isn't out yet, but Llama 4 Maverick is at #35 on ChatbotÂ 
Arena. On a bunch of major benchmarks, it seems like o4-mini or Gemini 2.5 FlashÂ 
are beating Maverick, which is in the same class. What do you make of that impression?
There are a few things. First, I actually think this has been a very good year forÂ 
open source overall. If you go back to where we were last year, Llama was the onlyÂ 
real, super-innovative open-source model. Now you have a bunch of them in the field.
In general, the prediction that this would be the year open source generally overtakesÂ 
closed source as the most used models out there, I think that's generally on track to be true.
One interesting surprise â€” positive in some ways, negative in others, but overall good â€” is thatÂ 
itâ€™s not just Llama. There are a lot of good ones out there. I think that's quite good.
Then there's the reasoning phenomenon, which you're alluding to talking about o3, o4, andÂ 
other models. There's a specialization happening. If you want a model thatâ€™s the best atÂ 
math problems, coding, or different things like those tasks, then reasoning models thatÂ 
consume more test-time or inference-time compute in order to provide more intelligence are a reallyÂ 
compelling paradigm. And we're building a Llama 4 reasoning model too. It'll come out at some point.
But for a lot of the applications we care about, latency and good intelligence per cost are muchÂ 
more important product attributes. If you're primarily designing for a consumer product, peopleÂ 
don't want to wait half a minute to get an answer. If you can give them a generally good answerÂ 
in half a second, that's a great tradeoff. I think both of these are going to end upÂ 
being important directions. Iâ€™m optimistic about integrating reasoning models with the coreÂ 
language models over time. That's the direction Google has gone in with some of the more recentÂ 
Gemini models. I think that's really promising. But I think thereâ€™s just going to be aÂ 
bunch of different stuff that goes on. You also mentioned the whole Chatbot Arena thing,Â 
which I think is interesting and points to the challenge around how you do benchmarking. How doÂ 
you know what models are good for which things? One of the things we've generally tried to doÂ 
over the last year is anchor more of our models in our Meta AI product north star use cases.Â 
The issue with open source benchmarks, and any given thing like the LM Arena stuff, isÂ 
that theyâ€™re often skewed toward a very specific set of uses cases, which are often not actuallyÂ 
â€Šwhat any normal person does in your product. The portfolio of things theyâ€™re tryingÂ 
to measure is often different from what people care about in any given product.
Because of that, weâ€™ve found that trying to optimize too much for that kind of stuff hasÂ 
led us astray. Itâ€™s actually not led towards the highest quality product, the most usage, and bestÂ 
feedback within Meta AI as people use our stuff. So we're trying to anchor our north star onÂ 
the product value that people report to us, what they say that they want, and whatÂ 
their revealed preferences are, and using the experiences that we have. SometimesÂ 
these benchmarks just don't quite line up. I think a lot of them are quite easily gameable.
On the Arena you'll see stuff like Sonnet 3.7, which is a great model, and it's not near theÂ 
top. It was relatively easy for our team to tune a version of Llama 4 Maverick that couldÂ 
be way at the top. But the version we released, the pure model, actually has no tuning for thatÂ 
at all, so it's further down. So you just need to be careful with some of these benchmarks.Â 
We're going to index primarily on the products. Do you feel like there is some benchmark whichÂ 
captures what you see as a north star of value to the user which can be be objectively measuredÂ 
between different models and where you'd say, "I need Llama 4 to come out on top on thisâ€?
Our benchmark is basically user value in Meta AI. But you can't compare that to other models.
We might be able to, because we might be able to run other models and be able to tell. That'sÂ 
one of the advantages of open source. You have a good community of folks who can poke holesÂ 
in your stuff and point out, "Okay, where is your model not good, and where is it good?"
The reality at this point is that all these models are optimized for slightly differentÂ 
mixes of things. Everyone is trying to go towards the same end in that all the leadingÂ 
labs are trying to create general intelligence, superintelligence, whatever you call it. AIÂ 
that can lead toward a world of abundance where everyone has these superhuman toolsÂ 
to create whatever they want. That leads to dramatically empowering people andÂ 
creating all these economic benefits. However you define it, that's whatÂ 
a lot of the labs are going for. But there's no doubt that different folks haveÂ 
optimized toward different things. I think the Anthropic folks have really focused on coding andÂ 
agents around that. The OpenAI folks, I think, have gone a little more toward reasoning recently.
Thereâ€™s a space which, if I had to guess, I think will end up being the most usedÂ 
one: quick, very natural to interact with, natively multimodal, fitting throughout yourÂ 
day in the ways you want to interact with it. I think you got a chance to play around withÂ 
the new Meta AI app that we're releasing. One of the fun things we put in there is theÂ 
demo for the full-duplex voice. It's early. Thereâ€™s a reason why we haven't made that theÂ 
default voice model in the app yet. But there's something about how naturally conversationalÂ 
it is that's really fun and compelling. Being able to mix that in with the rightÂ 
personalization is going to lead toward a product experience whereâ€¦ If you fast-forwardÂ 
a few years, I think we're just going to be talking to AI throughout the day aboutÂ 
different things we're wondering about. You'll have your phone. You'll talk to itÂ 
while browsing your feed apps. It'll give you context about different stuff. It'll answer yourÂ 
questions. It'll help you as you're interacting with people in messaging apps. Eventually, IÂ 
think we'll walk through our daily lives and have glasses or other kinds of AI devices andÂ 
just seamlessly interact with it all day long. Thatâ€™s the north star. Whatever the benchmarksÂ 
are that lead toward people feeling like the quality is where they want to interact with it,Â 
that's what will ultimately matter the most to us. I got a chance to play around with both OrionÂ 
and also the Meta AI app, and the voice mode was super smooth. It was quite impressive.
On the point of what the different labs are optimizing for â€” to steelman their view â€” I thinkÂ 
a lot of them believe that once you fully automate software engineering and AI research, then you canÂ 
kick off an intelligence explosion. You would have millions of copies of these software engineersÂ 
replicating the research that happened between Llama 1 and Llama 4 â€” that scale of improvementÂ 
again â€” but in a matter of weeks or months rather than years. So it really matters to just close theÂ 
loop on the software engineer, and then you can be the first to ASI. What do you make of that?
I personally think that's pretty compelling. That's why we have a big codingÂ 
effort too. We're working on a number of coding agents inside Meta. BecauseÂ 
we're not really an enterprise software company, we're primarily building it for ourselves.
Again, we go for a specific goal. We're not trying to build a general developer tool. We're trying toÂ 
build a coding agent and an AI research agent that advances Llama research specifically. And it'sÂ 
fully plugged into our toolchain and all that. That's important and is going to end up beingÂ 
an important part of how this stuff gets done. I would guess that sometime in the next 12 toÂ 
18 months, we'll reach the point where most of the code that's going toward these efforts isÂ 
written by AI. And I don't mean autocomplete. Today you have good autocomplete. You startÂ 
writing something and it can complete a section of code. I'm talking more like: you give it aÂ 
goal, it can run tests, it can improve things, it can find issues, it writes higher qualityÂ 
code than the average very good person on the team already. I think that's going to beÂ 
a really important part of this for sure. But I don't know if that's the whole game. That'sÂ 
going to be a big industry, and it's going to be an important part of how AI gets developed. But IÂ 
think there are stillâ€¦ One way to think about it is that this is a massive space. I don't thinkÂ 
there's just going to be one company with one optimization function that serves everyone asÂ 
best as possible. There are going to be a bunch of different labs doing leading work in differentÂ 
domains. Some will be more enterprise-focused or coding-focused. Some will be moreÂ 
productivity-focused. Some will be more social or entertainment-focused.
Within the assistant space, there will be some that are more informational andÂ 
productivity-focused, and some that are more companion-focused. Itâ€™s going toÂ 
be a lot of stuff thatâ€™s just fun and entertaining and shows up in your feed.
There's just a huge amount of space. Part of what's fun about going toward this AGI futureÂ 
is that there are a bunch of common threads for what needs to get invented, but also a lot ofÂ 
things that still need to be created. I think you're going to start seeing more specializationÂ 
between different groups, if I had to guess. Itâ€™s really interesting to me that youÂ 
basically agree with the premise that there will be an intelligence explosion andÂ 
weâ€™ll get something like superintelligence on the other end. Tell me if I'm misunderstandingÂ 
you. If thatâ€™s the case, why even bother with personal assistants and whatever else? Why notÂ 
just get to superhuman intelligence first and then deal with everything else later?
I think that's just one aspect of the flywheel. Part of what I generally disagreeÂ 
with on the fast-takeoff view is that it takes time to build out physical infrastructure.
If you want to build a gigawatt cluster of compute, that just takes time. NVIDIA needs timeÂ 
to stabilize their new generation of systems. Then you need to figure out the networking aroundÂ 
it. Then you need to build the building. You need to get permitting. You need to get theÂ 
energy. Maybe that means gas turbines or green energy, either way, thereâ€™sÂ 
a whole supply chain of that stuff. We talked about this a bunch the last timeÂ 
I was on the podcast with you. I think some of these are just physical-world, human-timeÂ 
things. As you start getting more intelligence in one part of the stack, youâ€™re just goingÂ 
to run into a different set of bottlenecks. Thatâ€™s how engineering always works: solveÂ 
one bottleneck, you get another bottleneck. Another bottleneck in the system or ingredientÂ 
thatâ€™s going to make this work well, is people getting used to learning and having a feedbackÂ 
loop with using the system. These systems donâ€™t just show up fully formed with people magicallyÂ 
knowing how to use them. There's a co-evolution that happens where people are learning how to bestÂ 
use these AI assistants. At the same time, the AI assistants are learning what people care about.Â 
Developers are making the AI assistants better. You're building up a base of context too.Â 
You wake up a year or two into it and the assistant can reference things you talkedÂ 
about two years ago and thatâ€™s pretty cool. You couldnâ€™t do that even if you launched theÂ 
perfect thing on day one. Thereâ€™s no way it could reference what you talked about twoÂ 
years ago if it didnâ€™t exist two years ago. So I guess my view is that there's this hugeÂ 
intelligence growth. Thereâ€™s a very rapid curve on the uptake of people interacting with theÂ 
AI assistants, and the learning feedback and data flywheel around that. And then there isÂ 
also the buildout of the supply chains and infrastructure and regulatory frameworks toÂ 
enable the scaling of a lot of the physical infrastructure. At some level, all of those areÂ 
going to be necessary, not just the coding piece. One specific example of this that I think isÂ 
interesting. Even if you go back a few years ago, we had a project, I think it was on our ads team,Â 
to automate ranking experiments. That's a pretty constrained environment. It's not open-ended code.Â 
Itâ€™s basically, look at the whole history of the company â€” every experiment that any engineer hasÂ 
ever done in the ad system â€” and look at what worked, what didn't, and what the results of thoseÂ 
were. Then basically formulate new hypotheses for different tests that we should run that couldÂ 
improve the performance of the ad system. What we basically found was that we wereÂ 
bottlenecked on compute to run tests, based on the number of hypotheses. It turnsÂ 
out, even with just the humans we have right now on the ads team, we already have more good ideasÂ 
to test than we actually have either compute or, really, cohorts of people to test them with.
Even if you have three and a half billion people using your products, you still want each test toÂ 
be statistically significant. It needs to have hundreds of thousands or millions of people.Â 
There's only so much throughput you can get on testing through that. So we're already at theÂ 
point, even with just the people we have, that we can't really test everything that we want.
Now just being able to test more things is not necessarily going to be additive to that. We needÂ 
to get to the point where the average quality of the hypotheses that the AI is generatingÂ 
is better than all the things above the line that weâ€™re actually able to test that theÂ 
best humans on the team have been able to do, before it will even be marginally useful for it.
We'll get there I think pretty quickly. But it's not just, â€œOkay, cool, the thingÂ 
can write code, and now all of a sudden everything is just improving massively.â€ There areÂ 
real-world constraints that need to be overcome. Then you need to have the compute andÂ 
the people to test. Then over time, as the quality creeps up, are we here inÂ 
five or 10 years where no set of people can generate a hypothesis as good as the AIÂ 
system? I don't know, maybe. In that world, obviously that's going to be how all the valueÂ 
is created. But that's not the first step. So if you buy this view, that thisÂ 
is where intelligence is headed, the reason to be bullish on Meta is obviouslyÂ 
that you have all this distribution. You can also use that to learn more things that canÂ 
be useful for training. You mentioned the Meta AI app now has a billion active users.
Not the app. The app is a standalone thing that we're just launching now. Itâ€™ll be funÂ 
for people who want to use it. It's a cool experience. We can talk about that too becauseÂ 
weâ€™re experimenting with some new ideas in there that I think are novel and worth talking through.
But Iâ€™m mostly talking about our apps. Meta AI is actually most used in WhatsApp. WhatsApp isÂ 
mostly used outside of the U.S. We just passed like a hundred million people in the US, butÂ 
it's not the primary messaging system in the US, iMessage is. So people in the U.S. probablyÂ 
tend to underestimate Meta AI usage somewhat. But part of the reason the standalone app isÂ 
going to be so important is because the US, for a lot of reasons, is one of the most importantÂ 
countries. And the fact that WhatsApp is the main way people are using Meta AI and that's notÂ 
the main messaging system in the US means we need another way to build a first-classÂ 
experience that's really in front of people. And I guess, to finish the question, the bearishÂ 
case would be that if the future of AI is less about just answering your questions and moreÂ 
about being a virtual coworker, then it's not clear how Meta AI inside of WhatsApp givesÂ 
you the relevant training data to make a fully autonomous programmer or remote worker.Â 
In that case, does it not matter that much who has more distribution right now with LLMs?
Again, I just think there are going to be different things. Imagine you were sittingÂ 
at the beginning of the development of the internet and you asked, "What's going toÂ 
be the main internet thing? Is it going to be knowledge work or massive consumer apps?"
You got both. You donâ€™t have to choose one. The world is big and complicated. Does one companyÂ 
build all of that stuff? Normally the answer is no. But to your question, people do not code inÂ 
WhatsApp for the most part. And I don't foresee that people starting to write code in WhatsAppÂ 
is going to be a major use case. Although I do think people are going to ask AI to do a lot ofÂ 
things that result in the AI coding without them necessarily knowing it. That's a separate thing.
We do have a lot of people who are writing code at Meta and they use Meta AI. We haveÂ 
this internal thing called MetaMate, and a number of different coding and AI researchÂ 
agents that we're building around that. That has its own feedback loop and I think it can getÂ 
quite good for accelerating those efforts. But again, there are going to be a lot of things.Â 
AI is almost certainly going to unlock a massive revolution in knowledge work and code. I alsoÂ 
think itâ€™s going to be the next generation of search and how people get information,Â 
and do more complex information tasks. I also think it's going to be fun. People areÂ 
going to use it to be entertained. A lot of the internet today is memes and humor. We have thisÂ 
amazing technology at our fingertips. Itâ€™s amazing and funny when you think about how much of humanÂ 
energy just goes toward entertaining ourselves, designing, pushing culture forward, andÂ 
finding humorous ways to explain cultural phenomena that we observe. I think that's almostÂ 
certainly going to be the case in the future. Look at the evolution of things like InstagramÂ 
and Facebook. If you go back 10, 15, 20 years ago, it was text. Then we all got phones with cameras,Â 
and most of the content became photos. Then the mobile networks got good enough that if youÂ 
wanted to watch a video on your phone, it wasn't just buffering the whole time. So that got good.
Over the last 10 years, most of the content has moved toward video at this point. Today, mostÂ 
of the time spent on Facebook and Instagram is on video. But do you think in five years weâ€™reÂ 
just going to be sitting in our feed and consuming media that's just video? No, it's going to beÂ 
interactive. You'll be scrolling through your feed. There will be content that maybe looksÂ 
like a Reel to start. But you can talk to it, or interact with it, and it talks back,Â 
or it changes what it's doing. Or you can jump into it like a game and interactÂ 
with it. That's all going to be AI. My point is that there are going to be allÂ 
these different things. We're ambitious, so we're working on a bunch of them. But I don'tÂ 
think any one company is going to do all of it. On this point about AI-generated contentÂ 
and AI interactions, already people have meaningful relationships with AI therapists,Â 
AI friends, maybe more. This is just going to get more intense as these AIs become moreÂ 
unique, more personable, more intelligent, more spontaneous, more funny, and so forth.
People are going to have relationships with AI. How do we make sure theseÂ 
are healthy relationships? There are a lot of questions that you only canÂ 
really answer as you start seeing the behaviors. Probably the most important upfront thing isÂ 
just to ask that question and care about it at each step along the way. But I also think beingÂ 
too prescriptive upfront and saying, "We think these things are not good" often cuts off value.
People use stuff that's valuable for them. One of my core guiding principles in designingÂ 
products is that people are smart. They know what's valuable in their lives. EveryÂ 
once in a while, something bad happens in a product and you want to make sure youÂ 
design your product well to minimize that. But if you think something someone is doingÂ 
is bad and they think it's really valuable, most of the time in my experience, they're rightÂ 
and you're wrong. You just haven't come up with the framework yet for understanding why the thingÂ 
they're doing is valuable and helpful in their life. That's the main way I think about it.
I do think people are going to use AI for a lot of these social tasks. Already, one of theÂ 
main things we see people using Meta AI for is talking through difficult conversations theyÂ 
need to have with people in their lives. "I'm having this issue with my girlfriend. Help meÂ 
have this conversation.â€ Or, "I need to have a hard conversation with my boss at work. How do IÂ 
have that conversation?" That's pretty helpful. As the personalization loop kicks in and theÂ 
AI starts to get to know you better and better, that will just be really compelling.
Hereâ€™s one stat from working on social media for a long time that I always think is crazy. TheÂ 
average American has fewer than three friends, fewer than three people they would considerÂ 
friends. And the average person has demand for meaningfully more. I think it's something like 15Â 
friends or something. At some point you're like, "All right, I'm just too busy,Â 
I can't deal with more people." But the average person wants more connectionÂ 
than they have. There's a lot of concern people raise like, "Is this going to replace real-world, in-person connections?" And my default is that the answer to that is probably not.Â 
There are all these things that are better about physical connections when you can haveÂ 
them. But the reality is that people just don't have as much connection as they want. They feelÂ 
more alone a lot of the time than they would like. So I think a lot of these things â€” things thatÂ 
today might have a little bit of stigma around them â€” over time, we'll find the vocabulary asÂ 
a society to articulate why they are valuable, why the people who are doing them are rational forÂ 
doing it, and how it is actually adding value to their lives. But also the field is very early.Â 
There are a handful of companies doing virtual therapists, virtual girlfriend-type stuff. ButÂ 
it's very early. The embodiment in those things is still pretty weak. You open it up and it'sÂ 
just an image of the therapist or the person you're talking to. Sometimes there's some veryÂ 
rough animation, but it's not an embodiment. You've seen the stuff we're working on in RealityÂ 
Labs, where you have the Codec Avatars and it actually feels like a real person. That'sÂ 
where it's going. You'll be able to have an always-on video chat with the AI. The gestures areÂ 
important too. More than half of communication, when you're actually having a conversation, is notÂ 
the words you speak. It's all the nonverbal stuff. I did get a chance to check out Orion the otherÂ 
day, and I thought it was super impressive. I'm mostly optimistic about the technology. Generally,Â 
like you mentioned, I'm pretty libertarian about this. If people are doing something, theyÂ 
probably think it's good for them. Although, I actually don't know if it's theÂ 
case that if somebody is using TikTok, they would say that they're happy with how muchÂ 
time they're spending on TikTok or something. I'm mostly optimistic about it in the sense thatÂ 
if we're going to be living in this future world of AGI, we need to be upgrading our capabilitiesÂ 
too, with tools like this. And just generally, there can be more beauty in the world if youÂ 
can see Studio Ghibli everywhere or something. I was worried about one of the flagship useÂ 
cases that your team showed me. I'm sitting at the breakfast table and on the periphery of myÂ 
vision is just a bunch of Reels that are scrolling by. Maybe in the future, my AI girlfriend is onÂ 
the other side of the screen or something. So I am worried that we're just removing all theÂ 
friction between getting totally reward-hacked by our technology. How do we make sure thisÂ 
is not what ends up happening in five years? Again, I think people have a good sense of whatÂ 
they want. That experience you saw was just a demo to show multitasking and holograms. I agree,Â 
I don't think the future is one where you have stuff that's trying to compete for your attentionÂ 
in the corner of your vision all the time. I don't think people would like that too much.
As we're designing these glasses, it's actually one of the things that we're reallyÂ 
mindful of. Probably the number one thing the glasses need to do is get out of the way and beÂ 
good glasses. As an aside, I think that's part of the reason why the Ray-Ban Meta product hasÂ 
done so well. It's great for listening to music, taking phone calls, taking photos and videos. TheÂ 
AI is there when you want it. But when you don't, it's just a good-looking pair of glasses thatÂ 
people like. It gets out of the way well. I would guess that's going to be a very importantÂ 
design principle for the augmented reality future. The main thing that I see here is this. It's kindÂ 
of crazy that, for how important the digital world is in all of our lives, the only way we access itÂ 
is through these physical, digital screens. You have your phone, your computer. You can put a bigÂ 
TV on your wall. It's this huge physical thing. It just seems like we're at the point withÂ 
technology where the physical and digital world should really be fully blended. That'sÂ 
what holographic overlays allow you to do. But I agree. I think a big part of the designÂ 
principles around that will be around how you'll be interacting with people. You'll be ableÂ 
to bring digital artifacts into those interactions and do cool things very seamlessly.
If I want to show you something, hereâ€™s a screen. We can interact with it. ItÂ 
can be 3D. We can play with it. You want to play a card game? All right, hereâ€™s a deck ofÂ 
cards. We can play with it. If two of us are physically together and we have a third friendÂ 
whoâ€™s hologramming in, they can participate too. But in that world too â€” just as you don't wantÂ 
your physical space to be cluttered because it wears on you psychologically â€” I don't thinkÂ 
people are going to want their digital-physical space to feel that way either. â€ŠThat's more of anÂ 
aesthetic norm that will have to get worked out, but I think weâ€™ll figure that out.
Going back to the AI conversation, you were mentioning how big of a bottleneckÂ 
the physical infrastructure can be. Related to other open-source models, like DeepSeek andÂ 
so forth, DeepSeek right now has less compute than a lab like Meta and you could argueÂ 
that it's competitive with the Llama models. If China is better at physicalÂ 
infrastructure, industrial scale-ups, getting more power and more data centers online,Â 
how worried are you that they might beat us here? It's a real competition. You're seeing industrialÂ 
policies really play out. China is bringing online more power. Because of that, the US really needsÂ 
to focus on streamlining the ability to build data centers and produce energy. Otherwise, IÂ 
think weâ€™ll be at a significant disadvantage. At the same time, some of the export controlsÂ 
on things like chips, I think you can see how theyâ€™re clearly working in a way. There wasÂ 
all the conversation with DeepSeek about, "Oh, they did all these very impressiveÂ 
low-level optimizations." And the reality is, they did and that is impressive.
But then you ask, "Why did they have to do that, when none of the American labs did it?" Itâ€™sÂ 
because theyâ€™re using partially nerfed chips that are the only ones NVIDIA is allowedÂ 
to sell in China because of the export controls. DeepSeek basically had to spendÂ 
a bunch of their calories and time doing low-level infrastructure optimizationsÂ 
that the American labs didnâ€™t have to do. Now, they produced a good result on text. DeepSeekÂ 
is text-only. The infrastructure is impressive. The text result is impressive. But every newÂ 
major model that comes out now is multimodal. It's image, it's voice. Theirs isn't.
Now the question is, why is that the case? I donâ€™t think itâ€™s because theyâ€™reÂ 
not capable of doing it. It's because they had to spend their calories on doing theseÂ 
infrastructure optimizations to overcome the fact that there were these export controls.
But when you compare Llama 4 with DeepSeek â€”I mean our reasoning model isnâ€™t out yet, so the R1Â 
comparison isnâ€™t clear yetâ€” but weâ€™re basically in the same ballpark on all the text stuff thatÂ 
DeepSeek is doing but with a smaller model. So the cost-per-intelligence is lower withÂ 
what weâ€™re doing for Llama on text. On the multimodal side weâ€™re effectively leadingÂ 
at and it just doesnâ€™t exist in their models. So the Llama 4 models, when you compare themÂ 
to what DeepSeek is doing, are good. I think people will generally prefer to use the LlamaÂ 
4 models. But thereâ€™s this interesting contour where itâ€™s clearly a good team doing stuffÂ 
over there. And you're right to ask about the accessibility of power, the accessibility ofÂ 
compute and chips, because the work that you're seeing different labs do and the way it'sÂ 
playing out is somewhat downstream of that. So Sam Altman recently tweeted that OpenAI isÂ 
going to release an open-source SOTA reasoning model. I think part of the tweet was that theyÂ 
wonâ€™t do anything silly, like say you can only use it if you have less than 700 million users.
DeepSeek has the MIT license, whereas I think a couple of the contingencies in the LlamaÂ 
license require you to say "built with Llama" on applications using it or any model that youÂ 
train using Llama has to begin with the word "Llama." What do you think about the license?Â 
Should it be less onerous for developers? Look, we basically pioneered the open-sourceÂ 
LLM thing. So I don't consider the license to be onerous. When we were starting to push on openÂ 
source, there was this big debate in the industry. Is this even a reasonable thing to do? Can youÂ 
do something that is safe and trustworthy with open source? Will open source ever be able to beÂ 
competitive enough that anyone will even care? Basically, when we were answering thoseÂ 
questions a lot of the hard work was done by the teams at Meta. There wereÂ 
other folks in the industry but really, the Llama models were the ones that broke openÂ 
this whole open-source AI thing in a huge way. If weâ€™re going to put all this energy into it,Â 
then at a minimum, if you're going to have these large cloud companies â€” like Microsoft and AmazonÂ 
and Google â€” turn around and sell our model, then we should at least be able to have aÂ 
conversation with them before they do that around what kind of business arrangement we should have.
Our goal with the license, we're generally not trying to stop people from using the model. WeÂ 
just think that if you're one of those companies, or if you're Apple, just come talk toÂ 
us about what you want to do. Let's find a productive way to do it together.Â 
I think thatâ€™s generally been fine. Now, if the whole open-source part of theÂ 
industry evolves in a direction where there are a lot of other great options and the licenseÂ 
ends up being a reason why people donâ€™t want to use Llama, then weâ€™ll have to reevaluateÂ 
the strategy. What it makes sense to do at that point. But I donâ€™t think weâ€™re there.
Thatâ€™s not, in practice, something weâ€™ve seen, companies coming to us and saying, â€œWe donâ€™t wantÂ 
to use this because your license says if you reach 700 million people, you have to come talk to us.â€Â 
So far, thatâ€™s been more something weâ€™ve heard from open-source purists like, â€œIs this as cleanÂ 
of an open-source model as youâ€™d like it to be?â€ That debate has existed since the beginningÂ 
of open source. All the GPL license stuff versus other things, do you need to make itÂ 
so that anything that touches open source has to be open source too? Or can people takeÂ 
it and use it in different ways? I'm sure there will continue to be debates around this.
But if youâ€™re spending many billions of dollars training these models, I think asking the otherÂ 
companies â€” the huge ones that are similar in size and can easily afford to have a relationshipÂ 
with us â€” to talk to us before they use it seems like a pretty reasonable thing.
If it turns out that other models are also really good. Thereâ€™s a bunch of good open-sourceÂ 
models. So that part of your mission is fulfilled, and maybe other models are better at coding.
Is there a world where you just say, "Look, the open-source ecosystem is healthy. Thereâ€™s plentyÂ 
of competition. We're happy to just use some other model, whether it's for internal softwareÂ 
engineering at Meta or deploying to our apps. We don't necessarily need to build with Llama"?
Again, we do a lot of things. Let's take a step back. The reason why we're building our ownÂ 
big models is because we want to be able to build exactly what we want. None of the otherÂ 
models in the world are exactly what we want. If they're open source, you can take them andÂ 
fine-tune them in different ways. But you still have to deal with the model architectures.Â 
And they make different size tradeoffs that affect latency and inference cost. At the scaleÂ 
that we operate at, that stuff really matters. We made the Llama Scout and Maverick modelsÂ 
certain sizes for a specific reason. They fit on a host and we wanted certain latencyÂ 
â€” especially for the voice models that weâ€™re working on â€” that we want to pervade everythingÂ 
we're doing from the glasses to all of our apps to the Meta AI app and all that stuff.
There's a level of control of your own destiny that you only get when you build the stuffÂ 
yourself. That said, AI is going to be used in every single thing that every company does. WhenÂ 
we build a big model, we also have to choose which internal use cases we're going to optimize for.
So does that mean for certain things we might say, "Okay, maybe Claude is better for building thisÂ 
specific development tool that this team is usingâ€? All right, cool then use that. Great. WeÂ 
donâ€™t want to fight with one hand tied behind our back. Weâ€™re doing a lot of different stuff.
You also asked, would it not be important anymore because other people are doingÂ 
open source? On this, I'm a little more worried. You have to ask yourself this. For anyone whoÂ 
shows up now and is doing open source â€” now that we have done it â€” would they still beÂ 
doing open source if we werenâ€™t doing it? I think there are a handful of folks who seeÂ 
the trend that more and more development is going toward open source, and they're like, "OhÂ 
crap, we need to be on this train or else weâ€™re going to lose." If you have a closed-model API andÂ 
increasingly a lot of developers don't want that. So youâ€™re seeing a bunch of other players startÂ 
to do some work in open source. But it's unclear if it's dabbling, or fundamental for them theÂ 
way that it has been for us. A good example is what's going on with Android. Android startedÂ 
off as the open-source thing. There's not really any open-source alternative. Over time,Â 
Android has just gotten more and more closed. So if you're us, you need to worry that if weÂ 
stop pushing the industry in this direction, all these other peopleâ€¦ Maybe theyâ€™re only reallyÂ 
doing it because they're trying to compete with us and the direction weâ€™re pushing things. TheyÂ 
already showed their revealed preference for what they would do if open source didnâ€™t exist.Â 
And it wasnâ€™t open source. We just need to be careful about relying on that continuedÂ 
behavior for the future of the technology that we're going to build at the company.
Another thing I've heard you mention is that it's important that the standard gets built aroundÂ 
American models like Llama. I wanted to understand your logic there. With certain kinds of networks,Â 
it is the case that the Apple App Store just has a big contingency around what it's built around.
But it doesn't seem like if you built some sort of scaffold for DeepSeek, you couldn't haveÂ 
easily just switched it over to Llama 4, especially since between generations. LlamaÂ 
3 wasn't MoE and Llama 4 is. So things are changing between generations of models as well.
Whatâ€™s the reason for thinking things will get built out in this contingentÂ 
way on a specific standard? I'm not sure, what do you mean by contingent?
As in, it's important that people are building for Llama rather than for LLMs inÂ 
general, because that will determine what the standard is in the future.
Look, I think these models encode values and ways of thinking about the world.
We had this interesting experience early on, where we took an early version of Llama and translatedÂ 
it. I think it was French, or some other language. The feedback we got from French peopleÂ 
was, "This sounds like an American who learned to speak French. It doesnâ€™t soundÂ 
like a French person." And we were like, â€œwhat do you mean, does it not speak FrenchÂ 
well?â€ No, it speaks French fine. It was just that the way it thought about the world seemedÂ 
slightly American. So I think there are these subtle things that get built into the models.
Over time, as models get more sophisticated, they should be able to embody differentÂ 
value sets across the world. So maybe that's not a particularly sophisticated example,Â 
but I think it illustrates the point. Some of the stuff we've seen in testing someÂ 
of the models, especially coming out of China, have certain values encoded in them. And itâ€™sÂ 
not just a light fine-tune to change that. Now, language models â€” or something that has a kindÂ 
of world model embedded in it â€” have more values. Reasoning, I guess, you could say has values too.Â 
But one of the nice things about reasoning models is they're trained on verifiable problems. Do youÂ 
need to be worried about cultural bias if your model is doing math? Probably not. I thinkÂ 
the chance that some reasoning model built elsewhere is going to incept you by solvingÂ 
a math problem in a devious way seems low. But there's a whole different set of issuesÂ 
around coding, which is the other verifiable domain. You need to worry about waking up one dayÂ 
and if you're using a model that has some tie to another government, can it embed vulnerabilitiesÂ 
in code that their intelligence organizations could exploit later? In some future version you'reÂ 
using a model that came from another country and it's securing your systems. Then you wakeÂ 
up and everything is just vulnerable in a way that that country knows about and you donâ€™t.Â 
Or it turns on a vulnerability at some point. Those are real issues. I'm very interested inÂ 
studying this because I think one of the main things that's interesting about open source isÂ 
the ability to distill models. For most people, the primary value isn't just taking a modelÂ 
off the shelf and saying, "Okay, Meta built this version of Llama. I'm going to take it andÂ 
I'm going to run it exactly in my application." No, your application isn't doing anythingÂ 
different if you're just running our thing. You're at least going to fine-tune it, or try toÂ 
distill it into a different model. When we get to stuff like the Behemoth model, the whole valueÂ 
is being able to take this very high amount of intelligence and distill it down into a smallerÂ 
model that you're actually going to want to run. This is the beauty of distillation. It's one ofÂ 
the things that I think has really emerged as a very powerful technique over the last year, sinceÂ 
the last time we sat down. I think itâ€™s worked better than most people would have predicted. YouÂ 
can basically take a model that's much bigger, and capture probably 90 or 95% of its intelligence,Â 
and run it in something that's 10% of the size. Now, do you get 100% of the intelligence?Â 
No. But 95% of the intelligence at 10% of the cost is pretty good for a lot of things.
The other thing that's interesting is that now, with this more varied open-source community, it'sÂ 
not just Llama. You have other models too. You have the ability to distill from multiple sources.Â 
So now you can basically say, "Okay, Llamaâ€™s really good at this. Maybe its architecture isÂ 
really good because it's fundamentally multimodal, more inference-friendly, more efficient. But letâ€™sÂ 
say this other model is better at coding." Okay, great. You can distill from both of them andÂ 
build something that's better than either individually, for your own use case. That's cool.
But you do need to solve the security problem of knowing that you can distill it in a way that'sÂ 
safe and secure. This is something that we've been researching and have put a lot of time into.Â 
What we've basically found is that anything that's language is quite fraught. There's just a lot ofÂ 
values embedded into it. Unless you don't care about taking on the values from whatever modelÂ 
you're distilling from, you probably don't want to just distill a straight language world model.
On reasoning, though, you can get a lot of the way there by limiting it to verifiable domains, andÂ 
running code cleanliness and security filters. Whether it's using Llama Guard open source,Â 
or the Code Shield open source tools that we've done, things that allow you to incorporateÂ 
different input into your models and make sure that both the input and the output are secure.
Then itâ€™s just a lot of red teaming. Itâ€™s having experts who are looking at the modelÂ 
and asking, "Alright, is this model doing anything after distillation that we don't want?"Â 
I think with the combination of those techniques, you can probably distill on the reasoningÂ 
side for verifiable domains quite securely. That's something I'm pretty confident about andÂ 
something we've done a lot of research around. But I think this is a very big question. HowÂ 
do you do good distillation? Because thereâ€™s so much value to be unlocked. But at the sameÂ 
time, I do think there is some fundamental bias embedded in different models.
Speaking of value to be unlocked, what do you think the right way to monetizeÂ 
AI will be? Obviously digital ads are quite lucrative. But as a fraction of total GDP,Â 
it's small compared to all remote work. Even if you can increase productivity withoutÂ 
replacing work, that's still worth tens of trillions of dollars. Is it possible that adsÂ 
might not be it? How do you think about this? Like we were talking about before, there'sÂ 
going to be all these different applications, and different applicationsÂ 
tend toward different things. Ads are great when you want to offerÂ 
people a free service. Because it's free, you need to cover it somehow. Ads solve thisÂ 
problem where a person does not need to pay for something. They can get something that is amazingÂ 
for free. Also by the way, with modern ad systems, a lot of the time people think the adsÂ 
add value to the thing if you do it well. You need to be good at ranking and you need toÂ 
have enough liquidity of advertising inventory. If you only have five advertisers in theÂ 
system, no matter how good you are at ranking, you may not be able to show something toÂ 
someone that they're interested in. But if you have a million advertisers in the system,Â 
then you're probably going to be able to find something pretty compelling, if you're good atÂ 
picking out the different needles in the haystack that that person is going to be interested in.
So that definitely has its place. But there are also clearly going to be other businessÂ 
models as well, including ones that just have higher costs so it doesn't evenÂ 
make sense to offer them for free. By the way, there have always been business models like this.
There's a reason why social media is free and ad-supported, but then if you want toÂ 
watch Netflix or ESPN or something, you need to pay for that. The content that's goingÂ 
into that, they need to produce it, and that's very expensive for them to produce. They probablyÂ 
could not have enough ads in the service in order to make up for the cost of producing the content.Â 
Basically, you just need to pay to access it. The trade-off is fewer people do it. InsteadÂ 
of billions, you're talking about hundreds of millions of people using those services. There's aÂ 
value switch there. I think it's similar here. Not everyone is going to want a software engineer,Â 
or a thousand software engineering agents, or whatever it is. But if you do, that'sÂ 
something you're probably going to be willing to pay thousands, or tens of thousands,Â 
or hundreds of thousands of dollars for. That just speaks to the diversity ofÂ 
different things that need to get created. There are going to be business models atÂ 
each point along the spectrum. At Meta, for the consumer piece we definitely want toÂ 
have a free thing. I'm sure that will end up being ad-supported. But I also think we're goingÂ 
to want to have a business model that supports people using arbitrary amounts of compute to doÂ 
even more amazing things than what it would make sense to offer in the free service. For that, I'mÂ 
sure we'll end up having a premium service. But I think our basic values on this are that we wantÂ 
to serve as many people in the world as possible. How do you keep track of all these differentÂ 
projects, some of which we've talked about today. I'm sure there are many I don't evenÂ 
know about. As the CEO overseeing everything, there's a big spectrum between going toÂ 
the Llama team and saying, "Here are the hyperparameters you should use," versus justÂ 
giving a mandate like, "Go make the AI better." And there are so many differentÂ 
projects. How do you think about the way in which you can best deliver yourÂ 
value-add and oversee all these things? A lot of what I spend my time on is trying toÂ 
get awesome people onto the teams. There's that, and then there's stuff that cuts acrossÂ 
teams. You build Meta AI, and you want to get it into WhatsApp or Instagram. Okay, nowÂ 
I need to get those teams to talk together. Then there are a bunch of questions like, â€œdoÂ 
you want the thread for Meta AI in WhatsApp to feel like other WhatsApp threads, or do youÂ 
want it to feel like other AI chat experiences?â€ There are different idioms for those. So thereÂ 
are all these interesting questions that need to get answered around how does this stuffÂ 
basically fit into everything we're doing? Then there's a whole other part of what we'reÂ 
doing, which is pushing on the infrastructure. If you want to stand up a gigawatt cluster,Â 
first of all, that has a lot of implications for the way we're doing infrastructure buildouts.Â 
It has political implications for how you engage with the different states where you're buildingÂ 
that stuff. It has financial implications for the company in terms of: "All right, there's aÂ 
lot of economic uncertainty in the world. Do we double down on infrastructure right now? If so,Â 
what other trade-offs do we want to make around the company?" Those are the kinds of decisionsÂ 
that are tough for other people to really make. Then there's this question around taste andÂ 
quality. When is something good enough that we want to ship it? In general, I'm the stewardÂ 
of that for the company. Although we have a lot of other people who I think have good taste asÂ 
well and are also filters for different things. Those are basically the areas. AI is interestingÂ 
because, more than some of the other stuff that we do, it is more research and model-led than reallyÂ 
product-led. You can't just design the product that you want and then try to build the model toÂ 
fit into it. You really need to design the model first and the capabilities that you want, andÂ 
then you get some emergent properties. Then it's, "Oh, you can build some different stuff becauseÂ 
this turned out in a certain way." At the end of the day, people want to use the best model.
That's partially why, when we're talking about building the most personal AI, the best voice,Â 
the best personalization â€” and also a very smart experience with very low latency â€” those areÂ 
the things that we need to design the whole system to build. That's why we're working onÂ 
full-duplex voice. That's why we're working on personalization to both have good memoryÂ 
extraction from your interactions with AI, but also to be able to plug into all theÂ 
other Meta systems. That's why we design the specific models that we design, to have the kindÂ 
of size and latency parameters that they do. Speaking of politics, there's been thisÂ 
perception that some tech leaders have been aligning with Trump. You and others donatedÂ 
to his inaugural event and were on stage with him and I think you settled a lawsuitÂ 
that resulted in them getting $25 million. I wonder what's going on here? Does it feel likeÂ 
the cost of doing business with an administration? What's the best way to think about this?
My view on this is that he's the President of the United States. Our default, as an AmericanÂ 
company, should be to try to have a productive relationship with whoever is running theÂ 
government. We've tried to offer support to previous administrations as well. I've beenÂ 
pretty public with some of my frustrations with the previous administration,Â 
how they basically did not engage with us or the business community more broadly.
Frankly, thatâ€™s going to be necessary to make progress on some of these things. We're not goingÂ 
to be able to build the level of energy that we need if you don't have a dialogue, and if they'reÂ 
not prioritizing trying to do those things. A lot of people want to write this story aboutÂ 
what direction people are going. We're trying to build great stuff, and we want to have aÂ 
productive relationship with people. That's how I see it. It is also how I would guess most othersÂ 
see it, but obviously, I can't speak for them. You've spoken out about how you'veÂ 
rethought some of the ways in which you engage and defer to the government, inÂ 
terms of moderation stuff in the past. How are you thinking about AI governance? BecauseÂ 
if AI is as powerful as we think it might be, the government will want to get involved. WhatÂ 
is the most productive approach to take there, and what should the government be thinking about?
I guess in the past, most of the comments that I made were in the context of content moderation.Â 
It's been an interesting journey over the last 10 years on this. It's obviously been anÂ 
interesting time in history. There have been novel questions raised about online content moderation.
Some of those have led to productive new systems getting built, like our AI systems to detectÂ 
nation-states trying to interfere in each other's elections. I think we will continue buildingÂ 
that stuff out, and that has been net positive. With some other stuff, we went down someÂ 
bad paths. I just think the fact-checking thing was not as effective as Community NotesÂ 
because it's not an internet-scale solution. There weren't enough fact-checkers, and peopleÂ 
didn't trust the specific fact-checkers. You want a more robust system. So I think what we gotÂ 
with Community Notes is the right one on that. But my point on this was more that historically,Â 
I probably deferred a little too much to either the media and their critiques, or to theÂ 
government, on things that they did not really have authority over. But just as like a centralÂ 
figure, I think we tried to build systems where maybe we wouldn't have to make all of the contentÂ 
moderation decisions ourselves or something. I guess part of the growth process over the lastÂ 
10 years is realizing, â€œOkay, we're a meaningful company. We need to own the decisions that we needÂ 
to make. We should listen to feedback from people, but we shouldn't defer too much to people who doÂ 
not actually have authority over this. Because at the end of the day, we're in the seat, andÂ 
we need to own the decisions that we make.â€ It's been a maturation process, and inÂ 
some ways painful, but I think we're probably a better company for it.
Will tariffs increase the cost of building data centers in the US andÂ 
shift buildouts to Europe and Asia? It is really hard to know how that playsÂ 
out. I think we're probably in the early innings on that, and it's very hard to know.
What is your single highest-leverage hour in a week? What are you doing in that hour?
I don't know. Every week is a little bit different. It's probably got to be the caseÂ 
that the most leveraged thing you do in a week is not the same thing each week. Or else,Â 
by definition, you should probably spend more than one hour doing that thing every week.
I don't know. Part of the fun of this job, and also of the industry being so dynamic, isÂ 
that things really move around. The world is very different now than it was at the beginningÂ 
of the year, or even six months ago, or in the middle of last year. I think a lot has advancedÂ 
meaningfully. A lot of cards have been turned over since the last time that we sat down.Â 
I think that was about a year ago, right? Yeah. I guess what you were sayingÂ 
earlier that recruiting people is a super high-leverage thing you do.
It's very high-leverage, yeah. You talked about these models being mid-levelÂ 
software engineers by the end of the year. What would be possible if, say, softwareÂ 
productivity increased like 100x in two years? What kinds of things could beÂ 
built that can't be built right now? What kinds of things? That's an interestingÂ 
question. One theme of this conversation is that the amount of creativity that's goingÂ 
to be unlocked is going to be massive. If you look at the overall arc of humanÂ 
society and the economy over 100 or 150 years, it's basically people going from being primarilyÂ 
agrarian â€” with most human energy going toward just feeding ourselves â€” to that becoming aÂ 
smaller and smaller percent. And the things that take care of our basic physical needs have becomeÂ 
a smaller and smaller percent of human energy. That shift has led to two impacts: one is thatÂ 
more people are doing creative and cultural pursuits. The second is that more people, inÂ 
general, spend less time working and more time on entertainment and culture. I think that is almostÂ 
certainly going to continue as this goes on. This isn't the 1-2 year thing of what happens whenÂ 
you have a super powerful software engineer. But over time, if everyone has these superhumanÂ 
tools to create a ton of different stuff, you're going to get incredible diversity. PartÂ 
of it is going to be solving hard problems: solving diseases, advancing science, developingÂ 
new technology that makes our lives better. But I would guess that a lot of it is goingÂ 
to end up being cultural and social pursuits and entertainment. I would guess theÂ 
world is going to get a lot funnier, weirder, and quirkier, the way that memes onÂ 
the internet have gotten over the last 10 years. I think that adds a certain richness andÂ 
depth. In funny ways, it actually helps you connect better with people. Now all day long,Â 
I just find interesting stuff on the internet and send it in group chats to the people I careÂ 
about, who I think are going to find it funny. The media that people can produceÂ 
today to express very nuanced, specific cultural ideas is really cool.Â 
That'll continue to get built out. It does advance society in a bunch of ways, even if it'sÂ 
not the "hard science" way of curing a disease. If you think about it, the Meta socialÂ 
media view of the world is that yeah, people are going to spend a lot more time doingÂ 
that stuff in the future. It's going to be a lot better, and it's going to help you connect,Â 
because it'll help express different ideas. The world is going to get more complicated,Â 
but our technology, our cultural technology, to express these very complicated things â€” in a veryÂ 
kind of funny little clip or whatever â€” is going to get so much better. I think that's all great.
I don't know about next year. One other thought that I think is interesting to cover isÂ 
that I tend to think that, for at least the foreseeable future, this is going toÂ 
lead to more demand for people doing work, not less. Now, people have a choice ofÂ 
how much time they want to spend working. I'll give you one interesting example we wereÂ 
talking about recently. We have almost three and a half billion people using our servicesÂ 
every day. One question we've struggled with forever is how do we provide customer support?
Today, you can write an email, but we've never seriously been able to contemplate havingÂ 
voice support where someone can just call in. I guess that's maybe one of the artifactsÂ 
of having a free service. The revenue per person isn't high enough to have anÂ 
economic model where people can call in. But also, with three and a half billionÂ 
people using your service every day, the number of calls would be massive. Itâ€™d be likeÂ 
the biggest call center in the world. It would be like $10 or $20 billion a year to staff that.Â 
So we've never thought too seriously about it, because it always seemed like there wasÂ 
no way that could make sense. But now, as AI gets better, you're going to get to a placeÂ 
where AI can handle a bunch of people's issues. Not all of them â€” maybe 10 years from now it canÂ 
handle all of them â€” but thinking about a 3-5 year time horizon, it will be able to handle a bunch.Â 
It's kind of like a self-driving car. They can handle a bunch of terrain, but they're notÂ 
doing the whole route by themselves yet in most cases. People thought truck-driving jobsÂ 
were going to go away, but there's actually more truck-driving jobs now than when we first startedÂ 
talking about self-driving cars 20 years ago. Going back to the customer support thing, itÂ 
wouldn't make sense to staff out calling for everyone. But let's say AI can handle 90% of that.Â 
Then if it can't, it kicks it off to a person. If you get the cost of providing that service downÂ 
to one-tenth of what it would've otherwise been, then maybe now it actually makes senseÂ 
to do it. That would be cool. So the net result is that I actually think we're probablyÂ 
going to hire more customer support people. The common belief is that AI will automateÂ 
jobs away. But that hasn't really been how the history of technology has worked. Usually,Â 
you create things that take away 90% of the work, and that leads you to want more people, not less.
To close off the interviewâ€¦ I've been playing devil's advocate on a bunch of points, andÂ 
I really appreciate you being a good sport about it. But I do think there's no upper boundÂ 
to how much beauty there can be in the world, especially if there are billions of AIsÂ 
optimizing the amount of beauty you can see, the amount of connection you can have, andÂ 
so forth. I'm pretty optimistic about it. Final question: Who is the one person in theÂ 
world today who you most seek out for advice? Oh, man. I feel like part of my styleÂ 
is that I like having a breadth of advisors. It's not just one person.
We've got a great team. There are people at the company, people on our board. ThereÂ 
are a lot of people in the industry who are doing new stuff. There's not a single person.Â 
But it's fun. Also, when the world is dynamic, just having a reason to work with people you likeÂ 
on cool stuffâ€¦ To me, that's what life is about. Great note to close on. Thanks for doing this.
Yeah, thank you.

</details>
