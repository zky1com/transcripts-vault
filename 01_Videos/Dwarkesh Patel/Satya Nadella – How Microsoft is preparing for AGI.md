---
title: "Satya Nadella â€“ How Microsoft is preparing for AGI"
people_mentioned: ["Satya Nadella", "Dylan Patel", "Scott Guthrie", "My God", "Take Vera Rubin"]
channel: "Dwarkesh Patel"
video_id: "8-boBsWcr5A"
url: "https://www.youtube.com/watch?v=8-boBsWcr5A"
publish_date: 2025-11-12
duration: "1:28:42"
word_count: 14151
content_type: "solo-talk"
delivery_mode: "knowledge"
broad_category: "ai"
subcategories: ["ai-safety", "ai-regulation", "ai-jobs", "ai-agents", "ai-coding", "ai-economics"]
series_name: ""
episode_id: ""
primary_person: "Satya Nadella"
host_names: []
interviewer_names: []
interviewee_profiles: []
speaker_profiles: ["Satya Nadella - Microsoft"]
organizations_mentioned: ["Dwarkesh Patel"]
locations_mentioned: []
tools_mentioned: []
companies_mentioned: ["Microsoft"]
topics: ["ai-safety", "ai-regulation", "ai-jobs", "ai-agents", "ai-coding", "ai-economics"]
tags: ["ai-safety", "ai-regulation", "ai-jobs", "ai-agents", "ai-coding", "ai-economics"]
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

The discussion centers on it's, that's, model. That's going to haveÂ power density that's going to be so different, with cooling requirements thatÂ are going to be so different.Â So you. Because right now you're charging like, "Hey,Â Â it's 20 bucks for Copilot." It's a great question because in some sense with the business. That's why we're going to have essentially anÂ end-user computing infrastructure business, which is going to just keep growing because it'sÂ going to grow.

## Key Insights


- That's going to haveÂ power density that's going to be so different, with cooling requirements thatÂ are going to be so different.Â So you kind of.
- Because right now you're charging like, "Hey,Â Â it's 20 bucks for Copilot." It's a great question because in some sense with the business models themselves,Â.
- That's why we're going to have essentially anÂ end-user computing infrastructure business, which is going to just keep growing because it'sÂ going to grow faster than.
- That's going to be one of the biggest places of innovation, because rightÂ now I want to be able to use multiple agents.Â I want to.
- In some sense, that's one of the reasons why, I believe, there's always going to be aÂ check to "Hey, can this one model have all.
- It's not like it's going to be usedÂ Â only for one workload forever.

## People Mentioned


- [[Satya Nadella]]

- [[Dylan Patel]]

- [[Scott Guthrie]]

- [[My God]]

- [[Take Vera Rubin]]




## Full Transcript

<details>
<summary>Click to expand full transcript (14151 words)</summary>

Today we are interviewing Satya Nadella.Â Â  "We" being me and Dylan Patel, who isÂ 
founder of SemiAnalysis. Satya, welcome. Thank you. It's great. ThanksÂ 
for coming over to Atlanta.Â  Thank you for giving us theÂ 
tour of the new facility. It's been really cool to see.
Absolutely.Â  Satya and Scott Guthrie, Microsoft'sÂ 
EVP of Cloud and AI, give us a tour of their brand new Fairwater 2 data center,Â 
the current most powerful in the world.Â  We've tried to 10x the trainingÂ 
capacity every 18 to 24 months. So this would effectively be a 10xÂ 
increase from what GPT-5 was trained with.Â  So to put it in perspective in the number ofÂ 
optics, the network optics in this building is almost as much as all of Azure across allÂ 
our data centers two and a half years ago. It's got like five million network connections.
You've got all this bandwidth between different sites in a region and between the two regions.
So is this like a big bet on scaling in theÂ Â  future, that you anticipate in the future thatÂ 
there's going to be some huge model that will require two whole different regions to train?
The goal is to be able to aggregate these flops for a large training job and thenÂ 
put these things together across sites. The reality is you'll use it for training andÂ 
then you'll use it for data gen, you'll use it for inference in all sorts of ways.
It's not like it's going to be usedÂ Â  only for one workload forever.
Fairwater 4, which you're going to see under construction nearby, will also be onÂ 
that one petabit network so that we can actually link the two at a very high rate.
Then we do the AI WAN connecting toÂ Â  Milwaukee where we have multipleÂ 
other Fairwaters being built. Literally you can see the modelÂ 
parallelism and the data parallelism. It's kind of built for, essentially, theÂ 
training jobs, the super pods across this campus. And then with the WAN, you canÂ 
go to the Wisconsin data center. You literally run a training jobÂ 
with all of them getting aggregated.Â  What we're seeing right here is a cellÂ 
with no servers in it yet, no racks. How many racks are in a cell?
We don't necessarily share that per se, butâ€¦Â  Thatâ€™s the reason I ask.
You'll see upstairs. I'll start counting.
You can start counting.Â Â  We'll let you start counting.
How many cells are there in this building?Â  That part also I can't tell you.
Well, division is easy, right? My God, it's kind of loud.
Are you looking at this like,Â Â  "Now I see where my money is going."
It's like, "I run a software company. Welcome to the software company."
How big is the design space onceÂ Â  you've decided to use the GB200s and the NVLink?
How many other decisions are there to be made? There is coupling from the model architectureÂ 
to what is the physical plan that's optimized. And it's also scary in that sense, which is,Â 
there's going to be a new chip that'll comeÂ Â  out. Take Vera Rubin Ultra. That's going to haveÂ 
power density that's going to be so different, with cooling requirements thatÂ 
are going to be so different.Â  So you kind of don't want toÂ 
just build all to one spec. That goes back a little bitÂ 
to the dialogue we'll have,Â Â  which is that you want to be scaling in time asÂ 
opposed to scale once and then be stuck with it. When you look at all the past technologicalÂ 
transitionsâ€”whether it be railroads or the Internet or replaceable parts, industrialization,Â 
the cloud, all of these thingsâ€”each revolution has gotten much faster in the time itÂ 
goes from technology discovered to rampÂ Â  and pervasiveness through the economy.
Many folks who have been on Dwarkesh's podcast believe this is the finalÂ 
technological revolution or transition, and that this time is very, very different.
At least so far in the markets, in three years we've already skyrocketed to hyperscalersÂ 
doing $500 billion of capex next year,Â Â  which is a scale that's unmatched toÂ 
prior revolutions in terms of speed. The end state seems to be quite different.
Your framing of this seems quite different from what I would call theÂ 
"AI bro" who's like, "AGI is coming." I'd like to understand that more.
I start with the excitement that I also feel for the idea that maybe afterÂ 
the Industrial Revolution this is theÂ Â  biggest thing. I start with that premise. ButÂ 
at the same time, I'm a little grounded in the fact that this is still early innings.
We've built some very useful things,Â Â  we're seeing some great properties,Â 
these scaling laws seem to be working. I'm optimistic that they'll continue to work.
Some of it does require real science breakthroughs, but it's also a lotÂ 
of engineering and what have you.Â  That said, I also sort of take the viewÂ 
that even what has been happening in the last 70 years of computing has alsoÂ 
been a march that has helped us move. I like one of the things that RajÂ 
Reddy has as a metaphor for what AI is. He's a Turing Award winner at CMU. He hadÂ 
this, even pre-AGI. He had this metaphor for AI, it should either be a guardian angelÂ 
or a cognitive amplifier. I love that. It's a simple way to think about what this is.
Ultimately, what is its human utility? It is going to be a cognitiveÂ 
amplifier and a guardian angel.Â  If I view it that way, I view it as a tool.
But then you can also go very mystical about it and say this is more than a tool.
It does all these things, which onlyÂ Â  humans did before so far.
But that has been the case with many technologies in the past.
Only humans did a lot of things,Â Â  and then we had tools that did them.
We don't have to get wrapped up in the definition here, but one way to think about it is, maybeÂ 
it takes five years, ten years, twenty years.Â  At some point, eventually a machine is producingÂ 
Satya tokens, and the Microsoft board thinks that Satya tokens are worth a lot.
How much are you wasting ofÂ Â  this economic value by interviewing Satya?
I could not afford the API costs of Satya tokens. Whatever you want to call it, are theÂ 
Satya tokens a tool or an agent, whatever.Â  Right now, if you have models that cost on theÂ 
order of dollars or cents per million tokens, there's just an enormous roomÂ 
for margin expansion there,Â Â  where a million tokens of Satya are worth a lot.
Where does that margin go and what level of that margin is Microsoft involvedÂ 
in is the question I have. In some sense this goes back again to,Â 
essentially, what's the economic growthÂ Â  picture going to really look like?
What's the firm going to look like? What's productivity going to look like?
That to me is where, again, if the IndustrialÂ Â  Revolution createdâ€¦ After 70 years of diffusionÂ 
is when you started seeing the economic growth. That's the other thing to remember.
Even if the tech is diffusing fast this time around, for true economic growth to appearÂ 
it has to diffuse to a point where the work, the work artifact, and the workflow has to change.
So that's one place where I think the change management required for a corporation to trulyÂ 
change is something we shouldn't discount. Going forward, do humans and the tokens theyÂ 
produce get higher leverage, whether it's the Dwarkesh or the Dylan tokens of the future?
Think about the amount of technology. Would you be able to run SemiAnalysisÂ 
or this podcast without technology?Â  No chance, at the scale that you haveÂ 
been able to achieve, thereâ€™s no chance. So the question is, what's that scale?
Is it going to be 10x'ed with somethingÂ Â  that comes through? Absolutely. Therefore,Â 
whether you're ramped to some revenue number or you're ramped to some audience number or whatÂ 
have you, that I think is what's going to happen. The point is, what took 70 years, maybeÂ 
150 years for the Industrial Revolution, may happen in 20 years, 25 years.
I would love to compress what happened in 200 years of the Industrial RevolutionÂ 
into a 20-year period, if we're lucky. Microsoft historically has beenÂ 
perhaps the greatest software company,Â Â  the largest software-as-a-service company.
You've gone through a transition in the past where you used to sell Windows licensesÂ 
and disks of Windows or Microsoft,Â Â  and now you sell subscriptions to 365.
As we go from that transition to where your business is today, there's alsoÂ 
a transition going on after that.Â  Software-as-a-service has incrediblyÂ 
low incremental cost per user. There's a lot of R&D, there's aÂ 
lot of customer acquisition costs.Â  This is sort of why, not Microsoft, butÂ 
the SaaS companies have underperformed massively in the markets, because the COGS ofÂ 
AI is just so high, and that just completelyÂ Â  breaks how these business models work.
How do you, as perhaps the greatest software-as-a-service company, transitionÂ 
Microsoft to this new age where COGS matters a lot and the incremental cost per user is different?
Because right now you're charging like, "Hey,Â Â  it's 20 bucks for Copilot."
It's a great question because in some sense with the business models themselves,Â 
the levers are going to remain similar. If you look at the menu of models starting fromÂ 
consumer all the way, there will be some ad unit, there will be some transaction,Â 
there will be some device grossÂ Â  margin for somebody who builds an AI device.
There will be subscriptions, consumer and enterprise, and then there'll be consumption.
So I still think those are all the meters. To your point, what is a subscription?
Up to now, people like subscriptionsÂ Â  because they can budget for them.
They are essentially entitlements to some consumption rights that comeÂ 
encapsulated in a subscription.Â  So I think that in some senseÂ 
becomes a pricing decision. How much consumption you are entitled to is,Â 
if you look at all the coding subscriptions, kind of what they are, right?
Then you have the pro tier,Â Â  the standard tier, and what have you.
So I think that's how the pricing and the margin structures will get tiered.
The interesting thing is that at Microsoft, the good news for us is we are inÂ 
that business across all those meters. At a portfolio level, we pretty muchÂ 
have consumption, subscriptions, to all of the other consumer levers as well.
I think time will tell which of these models make sense in what categories.
One thing on the SaaS side, since you brought it up, which I think a lot about.
Take Office 365 or Microsoft 365. Having a low ARPU is great, becauseÂ 
here's an interesting thing.Â  During the transition from server to cloud, oneÂ 
of the questions we used to ask ourselves is, "Oh my God, if all we did was just basicallyÂ 
move the same users who were using our Office licenses and our Office servers at theÂ 
time to the cloud, and we had COGS, this is going to not only shrink our margins butÂ 
we'll be fundamentally a less profitable company." Except what happened was the move to theÂ 
cloud expanded the market like crazy. We sold a few servers inÂ 
India, we didn't sell much.Â  Whereas in the cloud suddenlyÂ 
everybody in India also could afford fractionally buying servers, the IT cost.
In fact, the biggest thing I had not realized, for example, was the amount of money people wereÂ 
spending buying storage underneath SharePoint. In fact, EMC's biggest segment may haveÂ 
been storage servers for SharePoint. All that sort of dropped in theÂ 
cloud because nobody had to go buy.Â  In fact, it was working capital,Â 
meaning basically, it was cash flow out. So it expanded the market massively.
So this AI thing will be that. If you take coding, what we built withÂ 
GitHub and VS Code over decades, suddenly the coding assistant is that big in one year.
That I think is what's going to happen as well, which is the market expands massively.
Thereâ€™s a question of, the market will expand, but will the parts of the revenue thatÂ 
touch Microsoft expand? Copilot is an example. If you look earlier this year, accordingÂ 
to Dylan's numbers, GitHub Copilot revenue was like $500 million or something likeÂ 
that and there were no close competitors.Â  Whereas now you have ClaudeÂ 
Code, Cursor, and Copilot with around similar revenue, around a billion.
Codex is catching up around $700â€“800 million. So the question is, across all the surfaces thatÂ 
Microsoft has access to, what is the advantageÂ Â  that Microsoft's equivalents of Copilot have?
By the way, I love this chart. I love this chart for so many reasons.
One is we're still on the top. Second is all these companies that are listedÂ 
here are all companies that have been born in the last four or five years.
That to me is the best sign.Â  You have new competitors,Â 
new existential problems. When you say, who's it now?
Claude's going to kill you,Â Â  Cursor is going to kill you, it's not boreland.Â 
Thank God. That means we are in the right direction. This is it. The fact that we went fromÂ 
nothing to this scale is the market expansion. This is like the cloud-like stuff.
Fundamentally, this category ofÂ Â  coding and AI is probably going toÂ 
be one of the biggest categories. It is the software factory category.
In fact, it may be bigger than knowledge work.Â  I want to keep myself open-minded about it.
We're going to have tough competition. That's your point, which is a great one.
But I'm glad we have parlayed what we had into this and now we have to compete.
On the competing side, even in the last quarter we just finished, we did our quarterly announcementÂ 
and I think we grew from 20 to 26 million subs. I feel good about our sub growth andÂ 
where the direction of travel on that is.Â  But the more interesting thing that has happenedÂ 
is, guess where all the repos of all these other guys who are generating lots and lots of code go?Â 
They go to GitHub. GitHub is at an all-time high in terms of repo creation, PRs, everything.
In some sense we want to keep that open, by the way.
That means we want to have that.Â  We don't want to conflateÂ 
that with our own growth. Interestingly enough, we are gettingÂ 
one developer joining GitHub a secondÂ Â  or something, that is the stat, I think.
And 80% of them just fall into some GitHub Copilot workflow, just because there are.
By the way, many of these things will evenÂ Â  use some of our coding code review agents, whichÂ 
are by default on, just because you can use it. We'll have many, many structural shots at this.
The thing that we're also goingÂ Â  to do is what we did with Git.
The primitives of GitHub, starting with Git, to issues, to actions, these are powerful, lovelyÂ 
things because they kind of are all built around your repo. We want to extend that. Last weekÂ 
at GitHub Universe, that's kind of what we did. We said Agent HQ was the conceptual thingÂ 
that we said we're going to build out. This is where, for example, youÂ 
have a thing called Mission Control.Â  You go to Mission Control, and now I can fire off.
Sometimes I describe it as the cable TV of all these AI agents because I'll have, essentiallyÂ 
packaged into one subscription, Codex, Claude, Cognition stuff, anyone's agents,Â 
Grok, all of them will be there.Â  So I get one package and then I can literallyÂ 
go issue a task and steer them so they'll all be working in their independent branches. I canÂ 
monitor them. I think that's going to be one of the biggest places of innovation, because rightÂ 
now I want to be able to use multiple agents.Â  I want to be able to then digestÂ 
the output of the multiple agents. I want to be able to thenÂ 
keep a handle on my repo.Â  If there's some kind of a heads-up displayÂ 
that needs to be built and then for me to quickly steer and triage what the coding agentsÂ 
have generated, that to me, between VS Code, GitHub, and all of these new primitives we'llÂ 
build as Mission Control with a control plane. Observabilityâ€¦ Just think about everyoneÂ 
who is going to deploy all this.Â  It will require a whole host of observabilityÂ 
of what agent did what at what time to what code base. I feel that's the opportunity. AtÂ 
the end of the day your point is well taken, which is we better be competitive and innovate.
If we don't, we will get toppled.Â  But I like the chart, at least as long asÂ 
we're on the top, even with competition. The key point here is sort ofÂ 
that GitHub will keep growingÂ Â  regardless of whose coding agent wins.
But that market only grows at say 10, 15, 20%, which is way above GDP. It's a greatÂ 
compounder. But these AI coding agents have grown from say $500 million run rate at the endÂ 
of last yearâ€”which was just GitHub Copilotâ€”to now where the current run rate across GitHubÂ 
Copilot, Claude Code, Cursor, Cognition, Windsurf, Replit, OpenAI Codexâ€¦ Thatâ€™s run rating atÂ 
$5â€“6 billion now for the Q4 of this year. That's 10x. When you look at the TAM of softwareÂ 
agents, is it the $2 trillion of wages you pay people, or is it something beyond that?
Because every company in the world will now be able to develop software more?
No question Microsoft takes a slice of that. But you've gone from near 100%,Â 
or certainly way above 50%,Â Â  to sub-25% market share in just one year.
What is the confidence that people can get that Microsoft will keep winning?
It goes back a little bit, Dylan,Â Â  to that there's no birthright here,Â 
that we should have any confidence other than to say we should go innovate.
Knowing the lucky break we have, in some sense, is that this category is going to be a lotÂ 
bigger than anything we had high share in. Let me say it that way.
You could say we had highÂ Â  share in VS Code, we had high share in theÂ 
repos with GitHub, and that was a good market. But the point is that even having a decentÂ 
share in what is a much more expansive marketâ€¦ You could say we had a high shareÂ 
in client-server server computing.Â  We have much lower share than that in hyperscale.
But is it a much bigger business? By orders of magnitude. So at least it's existence proof thatÂ 
Microsoft has been okay even if our share position has not been as strong as it was, as long asÂ 
the markets we are competing in are creating more value. And there are multiple winners. That'sÂ 
the stuff. But I take your point that ultimately it all means you have to get competitive. IÂ 
watch that every quarter. Thatâ€™s why I'm very optimistic about what we're going to do withÂ 
Agent HQ, turning GitHub into a place where all these agents come.
As I said, we'll haveÂ Â  multiple shots on goal on there.
It need not beâ€¦ Some of these guys can succeed along with us, so it doesn't needÂ 
to be just one winner and one subscription. I guess the reason to focus on thisÂ 
question is that it's not just about GitHub,Â Â  but fundamentally about Office and allÂ 
the other software that Microsoft offers. One vision you could have about how AIÂ 
proceeds is that the models are going to keep being hobbled and you'll need thisÂ 
direct visible observability all the time. Another vision is that over time these modelsÂ 
which are now doing tasks that take two minutes,Â Â  in the future, they'll be doingÂ 
tasks that take 10, 30 minutes. In the future, maybe they're doingÂ 
days worth of work autonomously.Â  Then the model companies are charging thousandsÂ 
of dollars maybe for access to, really, a coworker which could use any UI to communicateÂ 
with their human and migrate between platforms. If weâ€™re getting closer to that, whyÂ 
aren't the model companies that areÂ Â  just getting more and more profitable,Â 
the ones that are taking all the margin? Why is the place where the scaffolding happens,Â 
which becomes less and less relevant as the AIÂ Â  becomes more capable, going to be that important?
That goes to Office as it exists now versus coworkers that are just doing knowledge work.
That's a great point. Does all the value migrate just to the model?
Or does it get split between the scaffolding and the model?
I think that time will tell. But my fundamental point also is thatÂ 
the incentive structure gets clear. Letâ€™s take information work, or take even coding.
Already in fact, one of my favorite settings in GitHub Copilot is calledÂ 
auto, which will just optimize. In fact I buy a subscription and the autoÂ 
one will start picking and optimizing for what I am asking it to do.
It could even be fully autonomous.Â  It could arbitrage the tokens availableÂ 
across multiple models to go get a task done. If you take that argument, theÂ 
commodity there will be models.Â  Especially with open source models, youÂ 
can pick a checkpoint and you can take a bunch of your data and you're seeing it.
I think all of us will start, whetherÂ Â  it's from Cursor or from Microsoft,Â 
seeing some in-house models even. And then you'll offload most of your tasks to it.
So one argument is if you win the scaffoldingâ€”which today is dealingÂ 
with all the hobbling problems or the jaggedness of these intelligence problems,Â 
which you kind of have toâ€”if you win that, then you will vertically integrate yourselfÂ 
into the model just because you will haveÂ Â  the liquidity of the data and what have you.
There are enough and more checkpoints that are going to be available. That's the otherÂ 
thing. Structurally, I think there will always be an open source model that will be fairlyÂ 
capable in the world that you could then use, as long as you have something that you can useÂ 
that with, which is data and a scaffolding. I can make the argument that if you're aÂ 
model company, you may have a winner's curse. You may have done all the hard work,Â 
done unbelievable innovation, exceptÂ Â  it's one copy away from that being commoditized.
Then the person who has the data for grounding and context engineering, and the liquidity of dataÂ 
can then go take that checkpoint and train it. So I think the argument can be made both ways.
Unpacking what you said,Â Â  there's two views of the world.
One is that there are so many different models out there. Open source exists. ThereÂ 
will be differences between the models thatÂ Â  will drive some level of who wins and who doesn't.
But the scaffolding is what enables you to win. The other view is that,Â 
actually, models are the key IP.Â  And everyone's in a tight race and there'sÂ 
some, "Hey, I can use Anthropic or OpenAI." You can see this in the revenue charts.
OpenAI's revenue started skyrocketing once theyÂ Â  finally had a code model with similar capabilitiesÂ 
to Anthropic, although in different ways. There's the view that the model companiesÂ 
are the ones that garner all the margin.Â  Because if you look across thisÂ 
year, at least at Anthropic, their gross margins on inference went from wellÂ 
below 40% to north of 60% by the end of the year. The margins are expanding there despiteÂ 
more Chinese open source models than ever.Â  OpenAI is competitive, Google isÂ 
competitive, X/Grok is now competitive. All these companies are now competitive, andÂ 
yet despite this, the margins have expanded atÂ Â  the model layer significantly.
How do you think about that? It's a great question. Perhaps a few years agoÂ 
people were saying, "Oh, I could just wrap a model and build a successful company."
That has probably gotten debunked just because of the model capabilities,Â 
and the tools used, in particular.Â  But the interesting thing is, when I look atÂ 
Office 365, let's take even this little thing we built called Excel Agent. It's interesting.Â 
Excel Agent is not a UI-level wrapper. It's actually a model that is in the middle tier.
In this case, because we have all the IP from the GPT family, we are taking that andÂ 
putting it into the core middle tier of the Office system to teach it what it means toÂ 
natively understand Excel, everything in it. It's not just, "Hey, I just haveÂ 
a pixel-level understanding."Â  I have a full understanding ofÂ 
all the native artifacts of Excel. Because if you think about it, if I'mÂ 
going to give it some reasoning task,Â Â  I need to even fix the reasoning mistakes I make.
That means I need to not just see the pixels, I need to be able to see, "Oh, I got thatÂ 
formula wrong," and I need to understand that.Â  To some degree, that's all being done notÂ 
at the UI wrapper level with some prompt, but it's being done in the middle tierÂ 
by teaching it all the tools of Excel.Â  I'm giving it essentially a markdown toÂ 
teach it the skills of what it means to be a sophisticated Excel user.
It's a weird thing that it goesÂ Â  back a little bit to the AI brain.
You're building not just Excel, business logic in its traditional sense.
You're taking the Excel business logicÂ Â  in the traditional sense and wrappingÂ 
essentially a cognitive layer to it, using this model which knows how to use the tool.
In some sense, Excel will come with an analyst bundled in and with all the tools used.
That's the type of stuff that will get built by everybody.
So even for theÂ Â  model companies, theyâ€™ll have to compete.
If they price stuff high, guess what, if I'm a builder of a tool like this, I'll substitute you.
I may use you for a while.Â  So as long as there's competitionâ€¦Â 
There's always a winner-take-all thing. If there's going to be one model thatÂ 
is better than everybody else withÂ Â  massive distance, yes, that's a winner-take-all.
But as long as there's competition where there are multiple models, just like hyperscale competition,Â 
and there's an open source check, there is enough room here to go build value on top of models.
At Microsoft, the way I look at it is that we are going to be in the hyperscaleÂ 
business, which will support multiple models. We will have access to OpenAI models for sevenÂ 
more years, which we will innovate on top of. Essentially, I think of ourselves asÂ 
having a frontier-class model that we canÂ Â  use and innovate on with full flexibility.
And we'll build our own models with MAI. So we will always have a model level.
And then we'll buildâ€”whether it's in security,Â Â  whether it's in knowledge work, whether it'sÂ 
in coding, or in scienceâ€”our own application scaffolding, which will be model-forward.Â  It won't be a wrapper on a model, but theÂ 
model will be wrapped into the application. I have so many questions aboutÂ 
the other things you mentioned.Â  But before we move onto those topics,Â 
I still wonder whether this is not forward-looking on AI capabilities, whereÂ 
you're imagining models like they exist today. It takes a screenshot of your screen, but it can'tÂ 
look inside each cell and what the formula is.Â  I think the better mental model here isÂ 
just imagining that these models will be able to use a computer as well as a human.
A human knowledge worker who is using Excel can look into the formulas, can use alternativeÂ 
software, can migrate data between Office 365 and another piece of software if theÂ 
migration is necessary, et cetera.Â  That's kind of what I'm saying.
But if that's the case, then the integration with Excel doesn't matter that much.
No, no, don't worry about the Excel integration. After all, Excel was built as a tool forÂ 
analysts. Great. So whoever is this AI that is an analyst should have tools that they can use.
They have the computer. Just the way a human can use a computer. That's their tool.
The tool is the computer. So allÂ Â  Iâ€™m saying is that I'm building anÂ 
analyst as essentially an AI agent, which happens to come with an a priori knowledgeÂ 
of how to use all of these analytical tools. Just to make sure we're talkingÂ 
about the same thing, is it a thingÂ Â  that a human like me using Excelâ€¦
No, it's completely autonomous. So we should now maybe lay out what IÂ 
think the future of the company is.Â  The future of the company would be the toolsÂ 
business in which I have a computer, I use Excel. In fact, in the future I'll even have aÂ 
Copilot, and that Copilot will also have agents.Â  But it's still me steering everything, andÂ 
everything is coming back. That's one world. The second world is the company just literallyÂ 
provisions a computing resource for an AI agent, and that is working fully autonomously.
That fully autonomous agent will have essentially an embodied set of thoseÂ 
same tools that are available to it. So this AI tool that comes inÂ 
also has not just a raw computer, because it's going to be more token-efficientÂ 
to use tools to get stuff done.Â  In fact, I kind of look atÂ 
it and say that our business, which today is an end-user tools business,Â 
will become essentially an infrastructureÂ Â  business in support of agents doing work.
It's another way to think about it. In fact, all the stuff we built underneathÂ 
M365 still is going to be very relevant. You need some place to store it, some placeÂ 
to do archival, some place to do discovery, some place to manage all of these activities, evenÂ 
if you're an AI agent. It's a new infrastructure. To make sure I understand, you'reÂ 
saying theoretically a future AI thatÂ Â  has actual computer useâ€”which all these modelÂ 
companies are working on right nowâ€”could use, even if it's not partnered with MicrosoftÂ 
or under our umbrella, Microsoft software.Â  But you're saying, if you're workingÂ 
with our infrastructure, we're going to give them lower-level access that makes itÂ 
more efficient for you to do the same thingsÂ Â  you could have otherwise done anyways?
100%. What happened is we had servers, then there was virtualization,Â 
and then we had many more servers.Â  That's another way to think about this.
Don't think of the tool as the end thing. What is the entire substrateÂ 
underneath that tool that humans use? That entire substrate is theÂ 
bootstrap for the AI agent as well,Â Â  because the AI agent needs a computer.
In fact, one of the fascinating things where we're seeing a significant amountÂ 
of growth is all these guys who are doing theseÂ Â  Office artifacts and what have you, as autonomousÂ 
agents and so on want to provision Windows 365. They really want to be able to provisionÂ 
a computer for these agents. Absolutely. That's why we're going to have essentially anÂ 
end-user computing infrastructure business, which is going to just keep growing because it'sÂ 
going to grow faster than the number of users. That's one of the other questions people ask me,Â 
"Hey, what happens to the per-user business?"Â  At least the early signs maybe, the wayÂ 
to think about the per-user business is not just per user, it's per agent.
And if you say it's per user and per agent, the key is what's the stuffÂ 
to provision for every agent?Â  A computer, a set of security thingsÂ 
around it, an identity around it. All those things, observability andÂ 
so on, are the management layers.Â  That's all going to get baked into that.
The way to frame itâ€”at least the way I currently think about it and Iâ€™d like to hear your viewâ€”isÂ 
that these model companies are all buildingÂ Â  environments to train their models to use Excel orÂ 
Amazon shopping or whatever it is, book flights. But at the same time, they're alsoÂ 
training these models to do migration.Â  Because that is probably the most immediatelyÂ 
valuable thing: converting mainframe-based systems to standard cloud systems, convertingÂ 
Excel databases into real databases with SQL, or converting what is done in Word and ExcelÂ 
to something that is more programmatic and more efficient in a classical senseÂ 
that can be done by humans as well.Â  It's just not cost-effective forÂ 
the software developer to do that. That seems to be what everyone is goingÂ 
to do with AI, for the next few years atÂ Â  least, to massively drive value.
How does Microsoft fit into that if the models can utilize the toolsÂ 
themselves to migrate to something?Â  Yes, Microsoft has a leadership positionÂ 
in databases and in storage and in all these other categories, but the useÂ 
of an Office ecosystem is going to be significantly less just like the use of aÂ 
mainframe ecosystem could be potentially less.Â  Now mainframes have grown for the last two decadesÂ 
actually, even though no one talks about them anymore. They've still grown.
100%, I agree with that.Â  How does that flow?
At the end of the day, there is going to be a significant amount of time whereÂ 
there's going to be a hybrid world, because peopleÂ Â  are going to be using the tools that are goingÂ 
to be working with agents that have to use tools, and they have to communicate with each other.
What's the artifact I generate thatÂ Â  then a human needs to see?
All of these things will be real considerations in any place, the outputs, inputs.
I don't think it'll just be about,Â Â  "Oh, I migrated off."
The bottom line is that I have to live in this hybrid world.
But that doesn't fully answer yourÂ Â  question because there can be a real newÂ 
efficient frontier where it's just agents working with agents and completely optimized.
Even when agents are working with agents, what are the primitives that are needed?
Do you need a storage system?Â  Does that storage system need to have e-discovery?
Do you need to have observability? Do you need to have an identity systemÂ 
that is going to use multiple modelsÂ Â  with all having one identity system?
These are all the core underlying rails we have today for what are theÂ 
Office systems or what have you.Â  And that's what we will have in the future asÂ 
well. You've talked about databases. I mean man, I would love all of ExcelÂ 
to have a database backend.Â  I would love for all that to happen immediately.
And that database is a good database. Databases in fact will beÂ 
a big thing that will grow.Â  If I think about all of the Office artifactsÂ 
being structured better, the ability to do the joins between structured and unstructured betterÂ 
because of the agentic world, that will grow theÂ Â  underlying infrastructure business.
It happens that the consumption of that is all being driven by agents.
You could say all that is just-in-time generatedÂ Â  software by a model company. That could also beÂ 
true. We will be one such model company too. We will build in... The competition could be that weÂ 
will build a model plus all the infrastructure and provision it, and then there will be competitionÂ 
between a bunch of those folks who can do that. Speaking of model companies, you say notÂ 
only will you have the infrastructure,Â Â  you'll have the model itself.
Right now, Microsoft AI's most recent model that was released twoÂ 
months ago is 36 in Chatbot Arena. You obviously have the IP rights to OpenAI.
To the extent you agree with that,Â Â  it seems to be behind.
Why is that the case, especially given the fact that you theoretically have the right toÂ 
fork OpenAI's monorepo or distill their models, especially if it's a big part of your strategyÂ 
that you need to have a leading model company?Â  First of all, we are absolutelyÂ 
going to use the OpenAI models to the maximum across all of our products.
That's the core thing that we're going to continue to do all the way for the next seven years,Â 
and not just use it but then add value to it. That's where the analyst and this ExcelÂ 
agent, these are all things that we willÂ Â  do where we'll do RL fine-tuning.
We'll do some mid-training runs on top of a GPT family where we haveÂ 
unique data assets and build capability. With the MAI model, the way that I thinkÂ 
weâ€™re going to think about it is that the good news here with the new agreement isÂ 
we can be very, very clear that we're goingÂ Â  to build a world-class superintelligenceÂ 
team and go after it with a high ambition. But at the same time, we're alsoÂ 
going to use this time to be smartÂ Â  about how to use both these things.
That means we will, on one end, be very product-focused, and on theÂ 
other end, be very research-focused. Because we have access to the GPT family, the lastÂ 
thing I want to do is use my flops in a way that is just duplicative and doesn't add much value.
I want to be able to take the flops that we use to generate a GPT family and maximize its value,Â 
while my MAI flops are being used forâ€¦ Let's take the image model that we launched, which IÂ 
think is at number nine in the image arena. We're using it both for costÂ 
optimization, it's on Copilot,Â Â  it's in Bing, and we're going to use that.
We have an audio model in Copilot. It's got personality and what have you.
We optimized it for our product. So we willÂ Â  do those. Even on the LMArena, we startedÂ 
on the text one and it debuted at like 13. By the way, it was doneÂ 
only on around 15,000 H100s.Â  It was a very small model.
So it was, again, to prove out the core capability, the instructionÂ 
following, and everything else.Â  We wanted to make sure we couldÂ 
match what was state of the art. That shows us, given scaling laws, what we areÂ 
capable of doing if we gave more flops to it. The next thing we will do is an omni-model whereÂ 
we will take the work we have done in audio, what we have done in image,Â 
and what we have done in text.Â  That will be the next pit stop on the MAI side.
So when I think about the MAI roadmap, we are going to build a first-classÂ 
superintelligence team.Â  We are going to continue to drop, andÂ 
do it in the open, some of these models. They will either be used in our products,Â 
because they're going to be latency-friendly,Â Â  cost-friendly, or what have you, orÂ 
they'll have some special capability. And we will do real research in order toÂ 
be ready for the next five, six, seven,Â Â  eight breakthroughs that are all needed onÂ 
this march towards superintelligenceâ€”while exploiting the advantage we have of having theÂ 
GPT family that we can work on top of as well. Say we roll forward seven years, youÂ 
no longer have access to OpenAI models. What does Microsoft do to make sure theyÂ 
are leading, or have a leading AI lab? Today, OpenAI has developed many of theÂ 
breakthroughs, whether it be scaling or reasoning. Or Google's developed all theÂ 
breakthroughs like transformers.Â  But it is also a big talent game.
You've seen Meta spend north of $20 billion on talent.
You've seen Anthropic poach the entire Blueshift reasoning team from Google last year.
You've seen Meta poach a large reasoning andÂ Â  post-training team from Google more recently.
These sorts of talent wars are very capital intensive.
Arguably, if you're spendingÂ Â  $100 billion on infrastructure, you shouldÂ 
also spend X amount of money on the people using the infrastructure so that they're moreÂ 
efficiently making these new breakthroughs.Â  What confidence can one get that MicrosoftÂ 
will have a team that's world-class that can make these breakthroughs?
Once you decide to turn onÂ Â  the money faucetâ€”you're being a bit capitalÂ 
efficient right now, which is smart it seems, to not waste money doing duplicative workâ€”but onceÂ 
you decide you need to, how can one say, "Oh yeah, now you can shoot up to the top five model?"
At the end of the day, we're going to build a world-class team and we already have aÂ 
world-class team that's beginning to be assembled.Â  We have Mustafa coming in, we have Karen.
We have Amar Subramanya who did a lot of the post-training at Gemini 2.5 who's at Microsoft.
Nando, who did a lot of the multimedia work at DeepMind, is there.
We're going to build a world-class team.Â  In fact, later this week even, MustafaÂ 
will publish something with a little more clarity on what our lab is going to go do.
The thing that I want the world to know, perhaps, is that we are going to build the infrastructureÂ 
that will support multiple models. Because from a hyperscale perspective, we wantÂ 
to build the most scaled infrastructure fleet that's capable of supporting all the models theÂ 
world needs, whether it's from open source or obviously from OpenAI and others. That's oneÂ 
job. Secondly, in our own model capability, we will absolutely use the OpenAI model in ourÂ 
products and we'll start building our own model. And we mayâ€”like in GitHub Copilot where AnthropicÂ 
is usedâ€”even have other frontier models that are going to be wrapped into our products, as well.
I think thatâ€™s how each timeâ€¦ At the end of the day, the eval of the product as it meets aÂ 
particular task or a job is what matters. We'll start back from there into the verticalÂ 
integration needed, knowing that as long as you're serving the market well with theÂ 
product, you can always cost-optimize. There's a question going forward.Â 
Right now, we have models that haveÂ Â  this distinction between training and inference.
One could argue that there's a smaller and smaller difference between the different models.
Going forward, if you're reallyÂ Â  expecting something like human-levelÂ 
intelligence, humans learn on the job. If you think about your last 30 years,Â 
what makes Satya tokens so valuable?Â  It's the last 30 years of wisdom andÂ 
experience you've gained in Microsoft. We will eventually have models, if theyÂ 
get to human level, which will haveÂ Â  this ability to continuously learn on the job.
That will drive so much value to the model company that is ahead, at least in my view, because youÂ 
have copies of one model broadly deployed throughÂ Â  the economy learning how to do every single job.
And unlike humans, they can amalgamate their learnings to that model.
So there's this sort of continuousÂ Â  learning exponential feedback loop, which almostÂ 
looks like a sort of intelligence explosion. If that happens and Microsoft isn'tÂ 
the leading model company by that timeâ€¦ You're saying that well, we substitute one modelÂ 
for another, et cetera. Doesnâ€™t that then matterÂ Â  less? Because it's like this one modelÂ 
knows how to do every single job in the economy, the others in the long tail don't.
Your point, if there's one model that is the only model that's most broadly deployed in the worldÂ 
and it sees all the data and it does continuousÂ Â  learning, that's game set match and you stop shop.
The reality that at least I see is that in the world today, for all the dominance ofÂ 
any one model, that is not the case. Take coding, there are multiple models.
In fact, everyday it's less the case. There is not one model thatÂ 
is getting deployed broadly.Â  There are multiple models that are gettingÂ 
deployed. It's like databases. It's always the thing, "Can one database be the one thatÂ 
is just used everywhere?" Except it's not. There are multiple types of databases thatÂ 
are getting deployed for different use cases. I think that there are going to be someÂ 
network effects of continual learningâ€”I call it data liquidityâ€”that any one model has.
Is it going to happen in all domains? I don't think so. Is it going to happen in all geos?Â 
I don't think so. Is it going to happen in allÂ Â  segments? I don't think so. It'll happen in allÂ 
categories at the same time? I don't think so. So therefore I feel like the design space isÂ 
so large that there's plenty of opportunity. But your fundamental point is having a capabilityÂ 
which is at the infrastructure layer, model layer, and at the scaffolding layer, and thenÂ 
being able to compose these things notÂ Â  just as a vertical stack, but to be able toÂ 
compose each thing for what its purpose is. You can't build an infrastructureÂ 
that's optimized for one model.Â  If you do that, what if you fall behind?
In fact, all the infrastructure you built will be a waste.
You kind of need to build anÂ Â  infrastructure that's capable of supportingÂ 
multiple families and lineages of models. Otherwise the capital you put in, which isÂ 
optimized for one model architecture, meansÂ Â  you're one tweak away, some MoE-like breakthroughÂ 
that happens, and your entire network topology goes out of the window. That's a scary thing.Â 
Therefore you kind of want the infrastructure to support whatever may come in your own modelÂ 
family and other model families. You've got to be open. If you're serious about the hyperscaleÂ 
business, you've got to be serious about that.Â  If you're serious about being a modelÂ 
company, you have to basically say, "What are the ways people can do things on top ofÂ 
the model so that I can have an ISV ecosystem?" Unless I'm thinking I'll own everyÂ 
category, that just can't be that.Â  Then you won't have an API business and that, byÂ 
definition, will mean you'll never be a platform company that's successfully deployed everywhere.
Therefore the industry structure is such that it will really force people to specialize.
In that specialization, a company like Microsoft should compete in each layer by its merits, butÂ 
not think that this is all about the road to game set match, where I just compose verticallyÂ 
all these layers. That just doesn't happen. So last year Microsoft was on path to beÂ 
the largest infrastructure provider by far. You were the earliest in 2023, so you wentÂ 
out there, you acquired all the resourcesÂ Â  in terms of leasing data centers, startingÂ 
construction, securing power, everything. You guys were on pace toÂ 
beat Amazon in 2026 or 2027. Certainly by 2028 you were going to beat them.
Since then, letâ€™s call it, in the second half of last year, Microsoft did this big pause, whereÂ 
they let go of a bunch of leasing sites that they were going to take, which then Google, Meta,Â 
Amazon in some cases, Oracle, took these sites. We're sitting in one of the largest data centersÂ 
in the world, so obviously it's not everything,Â Â  you guys are expanding like crazy.
But there are sites that you just stopped working on. Why did you do this?
This goes back a little bit to, what is the hyperscale business all about?
One of the key decisions we made was that if we're going to build out Azure toÂ 
be fantastic for all stages of AIâ€”from training to mid-training to data gen toÂ 
inferenceâ€”we just need fungibility of the fleet. So that entire thing caused us basicallyÂ 
not to go build a whole lot of capacity with a particular set of generations.
Because the other thing you have toÂ Â  realize is that having up to now 10x'edÂ 
every 18 months enough training capacity for the various OpenAI models, we realizedÂ 
that the key is to stay on that path. But the more important thing is to have a balance,Â 
to not just train, but to be able to serve these models all around the world.
Because at the end of the day,Â Â  the rate of monetization is whatÂ 
will then allow us to keep funding. And then the infrastructure was goingÂ 
to need us to support multiple models. So once we said that that's the case, weÂ 
just course-corrected to the path we're on. If I look at the path we're on, weÂ 
are doing a lot more starts now.Â  We are also buying up as much managedÂ 
capacity as we can, whether it's to build, whether it's to lease, or even GPUs as a service.
But we're building it for where we see the demand and the serving needs and our training needs.
We didn't want to just be a hoster for one company and have just a massive bookÂ 
of business with one customer.Â  That's not a business, you should beÂ 
vertically integrated with that company. Given that OpenAI was going to beÂ 
a successful independent company,Â Â  which is fantastic. It makes sense. And evenÂ 
Meta may use third-party capacity, but ultimately they're all going to be first-party.
For anyone who has large scale,Â Â  they'll be a hyperscaler on their own.
To me, it was to build out a hyperscale fleet and our own research compute. That's whatÂ 
the adjustment was. So I feel very, very good. By the way, the other thing is that I didn't wantÂ 
to get stuck with massive scale of one generation. We just saw the GB200s, the GB300s are coming.
By the time I get to Vera Rubin, Vera Rubin Ultra, the data center is going to look very differentÂ 
because the power per rack, power per row, is going to be so different.
The cooling requirements areÂ Â  going to be so different.
That means I don't want to just go build out a whole number of gigawattsÂ 
that are only for a one-generation, one family. So I think the pacing matters, theÂ 
fungibility and the location matters, the workload diversity matters, customer diversityÂ 
matters and that's what weâ€™re building towards.Â  The other thing that we've learnedÂ 
a lot is that every AI workload does require not only the AI accelerator, butÂ 
it requires a whole lot of other things.Â  In fact, a lot of the margin structureÂ 
for us will be in those other things. Therefore, we want to build out Azure as beingÂ 
fantastic for the long tail of the workloads, because that's the hyperscale business, whileÂ 
knowing that we've got to be super competitive starting with the bare-metalÂ 
for the highest end training.Â  But that can't crowd out the rest of theÂ 
business, because we're not in the business of just doing five contracts with five customersÂ 
being their bare-metal service. That's not a Microsoft business. That may be a businessÂ 
for someone else, and that's a good thing.Â  What we have said is that we're in theÂ 
hyperscale business, which is at the end of the day a long tail business for AI workloads.
And in order to do that, we will have some leading bare-metal-as-a-service capabilitiesÂ 
for a set of models, including our own. And that, I think, is the balance you see.
Another question that comes aroundÂ Â  this whole fungibility topic.
Okay, it's not where you want it, you would rather have it in a good population center, likeÂ 
Atlanta. We're here. There's also the question of, how much does that matter as the horizon of AIÂ 
tasks grows? 30 seconds for a reasoning prompt, or 30 minutes for a deep research, or it's goingÂ 
to be hours for software agents at some point and days and so on and so forth,Â 
the time to human interaction.Â  Why does it matter if it's location A, B, or C?
Itâ€™s a great question. That's exactly it. In fact, that's one of the other reasons why we want toÂ 
think about what an Azure region looks like andÂ Â  what is the networking between Azure regions.
This is where I think as the model capabilities evolve and the usage of these tokens evolves,Â 
whether it's synchronously or asynchronously, you don't want to be out of position.
Then on top of that, by the way,Â Â  what are the data residency laws?
Thereâ€™s the entire EU thing, where we literally had to create an EU Data Boundary.
That basically meant that you can't just roundtrip a call to wherever, even if it's asynchronous.
Therefore you need to have maybe regional things that are high density, andÂ 
then the power costs and so on.Â  But you're 100% right in bringing up that theÂ 
topology as we build out will have to evolve. One, for tokens per dollar per watt. WhatÂ 
are the economics? Overlay that with, what is the usage pattern?
Usage pattern in termsÂ Â  of synchronous, asynchronous.
But also what is the compute storage? Because the latencies may matter for certainÂ 
things. The storage better be there. If I haveÂ Â  a Cosmos DB close to this for session data or evenÂ 
for an autonomous thing, then that also has to be somewhere close to it, and so on.
All of those considerations areÂ Â  what will shape the hyperscale business.
Prior to the pause, what we had forecasted for you, by 2028 you were going to be 12â€“13 gigawatts.
Now we're at nine and a half or so. But something that's even more relevantâ€”andÂ 
I just want you to more concretely state that this is the business you don't want to beÂ 
inâ€”is that Oracle's going from 1/5th yourÂ Â  size to bigger than you by the end of 2027.
While it's not a Microsoft-level quality of return on invested capital, they'reÂ 
still making 35% gross margins.Â  So the question is, maybe it's not Microsoft'sÂ 
business to do this, but you've created a hyperscaler now by refusing this business, byÂ 
giving away the right of first refusal, et cetera. First of all, I don't want to take awayÂ 
anything from the success Oracle has had in building their business and I wish them well.
The thing that I think I've answered for youÂ Â  is that it didn't make sense for us toÂ 
go be a hoster for one model company with limited time horizon RPO.
Let's just put it that way.Â  The thing that you have to think throughÂ 
is not what you do in the next five years, but what you do for the next 50.
We made our set of decisions. I feel very good about our OpenAIÂ 
partnership and what we're doing.Â  We have a decent book of business.
We wish them a lot of success. In fact, we are buyers of Oracle capacity.Â 
We wish them success. But at this point, I think the industrial logic for what we areÂ 
trying to do is pretty clear, which is that it'sÂ Â  not about chasingâ€¦ First of all, I track, byÂ 
the way, your things whether it's AWS or Google and ours, which I think is super useful.
But it doesn't mean I have to chase those. I have to chase them for not just the gross marginÂ 
that they may represent in a period of time. What is this book of business thatÂ 
Microsoft uniquely can go clear, whichÂ Â  makes sense for us to clear? That's what we'll do.
I have a question even stepping back from this, I take your point that it's a better businessÂ 
to be in, all else equal, to have a long tail of customers you can have higher margin fromÂ 
rather than serving bare metal to a few labs. But then there's a question of,Â 
which way is the industry evolving?Â  If we believe we're on the path to smarterÂ 
and smarter AIs, then why isn't the shape of the industry that the OpenAIs and Anthropics andÂ 
DeepMinds are the platform on which the long tail of enterprises are actually doing business?
They need bare metal, but they are the platform. What is the long tail thatÂ 
is directly using Azure?Â  Because you want to useÂ 
the general cognitive core. But those models are all going to be availableÂ 
on Azure, so any workload that says, "Hey,Â Â  I want to use some open source model and anÂ 
OpenAI model," if you go to Azure Foundry today, you have all these models that you canÂ 
provision, buy PTUs, get a Cosmos DB,Â Â  get a SQL DB, get some storage, get some compute.
That's what a real workload looks like. A real workload is not justÂ 
an API call to a model.Â  A real workload needs all of these things toÂ 
go build an app or instantiate an application. In fact, the model companiesÂ 
need that to build anything.Â  It's not just like, "I have a token factory."
I have to have all of these things. That's the hyperscale business. And it's not onÂ 
any one model, but all of these models. So if you want Grok plus, say, OpenAI plusÂ 
an open source model, come to Azure Foundry, provision them, build your application. Here isÂ 
a database. That's kind of what the business is. There is a separate business called just sellingÂ 
raw bare-metal services to model companies.Â  And that's the argument aboutÂ 
how much of that business you want to be in and not be in and what that is.
It's a very different segment of the business,Â Â  which we are in, and we also have limits to howÂ 
much of it is going to crowd out the rest of it. But that's kind of at least the way I look at it.Â  There are sort of two questions here.
One is, why couldn't you just do both? The other one is, given our estimatesÂ 
on what your capacity is in 2028, it's three and a half gigawatts lower.
Sure, you could have dedicated that toÂ Â  OpenAI training and inference capacity,Â 
but you could have also dedicated that to actually just running Azure, runningÂ 
Microsoft 365, running GitHub Copilot. I could have just built itÂ 
and not given it to OpenAI.Â  Or I may want to build it in a different location.
I may want to build it in the UAE, I may want to build it in India,Â 
I may want to build it in Europe.Â  One of the things is, as I said, where we haveÂ 
real capacity constraints right now, given the regulatory needs and the data sovereigntyÂ 
needs, we've got to build all over the world.Â  First of all, stateside capacity is superÂ 
important, and we want to build everything. But when I look out to 2030, I have aÂ 
global view of what is Microsoft's shape of business by first-party and third-party.
Third-party segmented by the frontier labs and how much they want versus the inferenceÂ 
capacity we want to build for multiple models, and our own research compute needs.
That's all going into my calculus. You're rightfully pointing out the pause,Â 
but the pause was not done because we said, "Oh my God, we don't want to build that."
We realized that we want to build what we want to build slightly differently by both workloadÂ 
type as well as geo-type and timing as well. We'll keep ramping up our gigawatts, and theÂ 
question is at what pace and in what location. And how do I ride Moore's law on it, which is,Â 
do I really want to overbuild three and a half in 2027 or do I want to spread that in 2027-28Â 
knowing evenâ€¦ One of the biggest learnings we had even with Nvidia is that their pace increasedÂ 
in terms of their migrations. That was a big factor. I didn't want to go get stuck for fourÂ 
or five years of depreciation on one generation. In fact, Jensen's advice to me was two things.
One is, get on the speed-of-light execution.Â  That's why the execution inÂ 
this Atlanta data center.... I mean, it's like 90 days between when weÂ 
get it and to hand off to a real workload.Â  That's real speed-of-lightÂ 
execution on that front. I wanted to get good on that.
And then that way I'm buildingÂ Â  each generation in scaling.
And then every five years, you have something much more balanced.
So it becomes literally like a flow for a large-scale industrial operation likeÂ 
this where you're suddenly not lopsided,Â Â  where you've built up a lot in one time and thenÂ 
you take a massive hiatus because you're stuck with all this, to your point, in one locationÂ 
which may be great for training, or it may notÂ Â  be great for inference because I can't serve,Â 
even if it's all asynchronous, because Europe won't let me round-trip to Texas.
So that's all of the things.Â  How do I rationalize this statement withÂ 
what you've done over the last few weeks? You've announced deals with IrisÂ 
Energy, with Nebius, and Lambda Labs, and there's a few more coming as well.
You're going out there and securing capacityÂ Â  that you're renting from the neocloudsÂ 
rather than having built it yourself. It's fine for us because now when you have lineÂ 
of sight to demand, which can be served where people are building, it's great.
In fact we will take leases, we will take build-to-suit, we'll even takeÂ 
GPUs-as-a-service where we don't have capacity but we need capacity and someone else has that.
And by the way, I would even sort of welcome every neocloud to just be part of our marketplace.Â 
Because guess what? If they go bring their capacity into our marketplace, that customer whoÂ 
comes through Azure will use the neocloud, whichÂ Â  is a great win for them, and will use compute,Â 
storage, databases, all the rest from Azure. So I'm not at all thinking of this as, "Hey, IÂ 
should just go gobble up all of that myself." You mentioned how this depreciating asset, in fiveÂ 
or six years, is 75% of the TCO of a data center. And Jensen is taking a 75% margin on that.
So what all the hyperscalers are trying to do is develop their own accelerator so thatÂ 
they can reduce this overwhelming cost for equipment, to increase their margins.
And when you look at where they are,Â Â  Google's way ahead of everyone else.
They've been doing it for the longest. They're going to make something like fiveÂ 
to seven million chips of their own TPUs.Â  You look at Amazon and they're trying to makeÂ 
three to five million [Lifetime shipment units]. But when we look at what Microsoft is orderingÂ 
of their own chips, it's way below that number. You've had a program for just as long.
What's going on with your internal chips?Â  Itâ€™s a good question. A couple of things.Â 
One is that the thing that is the biggest competitor for any new accelerator is kindÂ 
of even the previous generation of Nvidia.Â  In a fleet, what I'm going toÂ 
look at is the overall TCO. The bar I have, even for our ownâ€¦ By theÂ 
way, I was just looking at the data forÂ Â  Maia 200 which looks great, except that oneÂ 
of the things that we learned even on the compute sideâ€¦ We had a lot of Intel, thenÂ 
we introduced AMD, and then we introducedÂ Â  Cobalt. That's how we scaled it. We have goodÂ 
existence proof of, at least in core compute, how to build your own silicon and then manage aÂ 
fleet where all three are at play in some balance. Because by the way, even Google'sÂ 
buying Nvidia, and so is Amazon.Â  It makes sense because Nvidia is innovatingÂ 
and it's the general-purpose thing. All models run on it and customer demand is there.
Because if you build your own vertical thing, you better have your own model, which is eitherÂ 
going to use it for training or inference,Â Â  and you have to generate your own demandÂ 
for it or subsidize the demand for it. So therefore you want to makeÂ 
sure you scale it appropriately.Â  The way we are going to do it is to have a closeÂ 
loop between our own MAI models and our silicon, because I feel like that's what gives youÂ 
the birthright to do your own silicon, where you literally have designed theÂ 
microarchitecture with what you're doing, and then you keep pace with your own models.
In our case, the good news here is that OpenAI has a program which we have access to.
So therefore to think that MicrosoftÂ Â  is not going to have something that'sâ€”
What level of access do you have to that? All of it.
You just get the IP for all of that?Â  So the only IP you don'tÂ 
have is consumer hardware?Â  That's it.
Oh, okay. Interesting. By the way, we gave them a bunchÂ 
of IP as well to bootstrap them.Â  This is one of the reasons why theyâ€¦ BecauseÂ 
we built all these supercomputers together. We built it for them and theyÂ 
benefited from it, rightfully so.Â  And now as they innovate, even at theÂ 
system level, we get access to all of it. And we first want to instantiate what theyÂ 
build, for them, but then we'll extend it. So if anything, the way I think about yourÂ 
question is, Microsoft wants to be a fantastic, I'll call it, speed-of-lightÂ 
execution partner for Nvidia.Â  Because quite frankly that fleet is life itself.
Obviously Jensen's doing super well with his margins, but the TCO has many dimensionsÂ 
to it and I want to be great at that TCO. On top of that, I want to be able toÂ 
really work with the OpenAI lineage and the MAI lineage and the system design,Â 
knowing that we have the IP rights on both ends. Speaking of rights, you had an interview aÂ 
couple days ago where you said that in the new agreement you made with OpenAI you haveÂ 
rights, the exclusivity, to the stateless API calls that OpenAI makes.
We were sort of confused aboutÂ Â  if there's any state whatsoever.
You were just mentioning a second ago that all these complicated workloads thatÂ 
are coming up are going to require memory andÂ Â  databases and storage and so forth.
Is that now not stateless if ChatGPT is storing stuff on sessions?
That's the reason why. The strategic decision we made, and also accommodating for the flexibilityÂ 
OpenAI needed in order to be able to procure compute forâ€¦ Essentially think of OpenAI havingÂ 
a PaaS business and a SaaS business. The SaaS business is ChatGPT. Their PaaS business isÂ 
their API. That API is Azure-exclusive. The SaaS business, they can run it anywhere.
And they can partner with anyone theyÂ Â  want to to build SaaS products?
If they want a partner and that partner wants to use a stateless API, then AzureÂ 
is the place where they can get the stateless API. It seems like there's a way for them to buildÂ 
the product together and it's a stateful thingâ€¦ No, for even that they'll have to come to Azure.
Again, this is done in the spirit of "what is it that we value as part of our partnership."
And we made sure that, at the same time,Â Â  we were good partners to OpenAI givenÂ 
all the flexibility they needed. So for example, Salesforce wants to integrateÂ 
OpenAI. It's not through an API. They actuallyÂ Â  work together, train a model togetherÂ 
and deploy it on, let's say, Amazon now. Is that allowed or do they have to use yourâ€¦
For any custom agreement like that, they will have to come run itâ€¦ There are some few exceptions,Â 
the US government and so on, that we made,Â Â  but other than that, they'd have to come to Azure.
Stepping back, when we were walking back and forth through the factory, one of the thingsÂ 
you were talking about is that Microsoft,Â Â  you can think of it as a software business, butÂ 
now it's really becoming an industrial business. There's all this capex,Â 
there's all this construction.Â  If you just look over the last twoÂ 
years, your capex has sort of tripled. Maybe you extrapolate that forward, it actuallyÂ 
just becomes this huge industrial explosion. Other hyperscalers are taking loans. MetaÂ 
has done a $20 billion loan at Louisiana.Â Â  They've done a corporate loan. It seems clearÂ 
everyone's free cash flow is going to zero, which I'm sure Amy is going to beat you up ifÂ 
you even try to do that, but what's happening? I think the structural change is whatÂ 
you're referencing, which is massive. I describe it as we are now a capital-intensiveÂ 
business and a knowledge-intensive business. In fact, we have to use our knowledge toÂ 
increase the ROIC on the capital spend. The hardware guys have done aÂ 
great job of marketing Moore's Law,Â Â  which I think is unbelievable and it's great. But if you even look at some of the stats I evenÂ 
did in my earnings call, for a given GPT family, the software improvements of really throughputÂ 
in terms of tokens-per-dollar-per-watt that we're able to get quarter-over-quarter,Â 
year-over-year, itâ€™s massive. It's 5x, 10x, maybe 40x in some of theseÂ 
cases, just because of how you can optimize. That's knowledge intensity comingÂ 
to bring out capital efficiency. That, at some level, is what we have to master.
Some people ask me, what is the difference between a classic old-time hoster and a hyperscaler?Â 
Software. Yes, it is capital intensive, but as long as you have systems know-how, softwareÂ 
capability to optimize by workload, by fleet... That's why when we say fungibility,Â 
there's so much software in it.Â  It's not just about the fleet.
It's the ability to evict a workload and then schedule another workload.
Can I manage that algorithm of scheduling around? That is the type of stuff thatÂ 
we have to be world-class at.Â  So yes, I think we'll still remain a softwareÂ 
company, but yes, this is a different business and we're going to manage.
At the end of the day,Â Â  the cash flow that Microsoft has allowsÂ 
us to have both these arms firing well. It seems like in the shortÂ 
term you have more credenceÂ Â  on things taking a while, being more jagged.
But maybe in the long term you think the people who talk about AGI and ASI are correct. SamÂ 
will be right, eventually. I have a broader question about what makes sense for a hyperscalerÂ 
to do, given that you have to invest massively in this thing which depreciates over five years.
So if you have 2040 timelines to the kind of thing that somebody like Sam anticipatesÂ 
in three years, what is a reasonable thing for you to do in that world?
There needs to be an allocation to, I'll call it, research compute.
That needs to be done like you did R&D. That's the best way to evenÂ 
account for it, quite frankly.Â  We should think of it as just R&D expense andÂ 
you should say, "What's the research compute and how do you want to scale it?"
Let's even say it's an order of magnitude scale in some period.
Pick your thing, is it two years?Â Â  Is it 16 months? What have you. That's sort of oneÂ 
piece, which is table stakes, that's R&D expenses. The rest is all demand driven.
Ultimately, you're allowed to buildÂ Â  ahead of demand, but you better have a demandÂ 
plan that doesn't go completely off kilter. Do you buyâ€¦ These labs are now projectingÂ 
revenues of $100 billion in 2027â€“28 and they're projecting revenue to keepÂ 
growing at this rate of 3x, 2x a yearâ€¦Â  In the marketplace there's all kinds ofÂ 
incentives right now, and rightfully so. What do you expect an independent lab thatÂ 
is sort of trying to raise money to do?Â  They have to put some numbers out thereÂ 
such that they can actually go raise money so that they can pay their billsÂ 
for compute and what have you. And it'sÂ Â  a good thing. Someone's going to take some riskÂ 
and put it in there, and they've shown traction. It's not like it's all risk without seeingÂ 
the fact that they've been performing,Â Â  whether it's OpenAI, or whether it's Anthropic.
So I feel great about what they've done, and we have a massive book of business with theseÂ 
chaps. So therefore that's all good. But overall ultimately, there's two simple things.
One is you have to allocate for R&D.Â Â  You brought up talent. The talent forÂ 
AI is at a premium. You have to spend there. You've got to spend on compute.
So in some sense researcher-to-GPU ratios have to be high.
That is sort of what it takesÂ Â  to be a leading R&D company in this world.
And that's something that needs to scale, and you have to have a balance sheet that allowsÂ 
you to scale that long before it's conventionalÂ Â  wisdom and so on. That's kind of one thing. ButÂ 
the other is all about knowing how to forecast. As we look across the world, AmericaÂ 
has dominated many tech stacks. The US owns Windows through Microsoft,Â 
which is deployed even in China,Â Â  that's the main operating system.
Of course, there's Linux, which is open source, but Windows is deployedÂ 
everywhere in China on personal computers. You look at Word, it's deployed everywhere.
You look at all these various technologies,Â Â  it's deployed everywhere.
And Microsoft and other companies have grown elsewhere.
They're building data centersÂ Â  in Europe and in India and in all these otherÂ 
places, in Southeast Asia and LatAm and Africa. In all of these different places, you're buildingÂ 
capacity. But this seems quite different. Today, the political aspect of technology,Â 
of computeâ€¦ The US administration didn't care about the dot-com bubble.
It seems like the US administration,Â Â  as well as every other administrationÂ 
around the world, cares a lot about AI. The question is, we're sort of in a bipolar world,Â 
at least with the US and China, but Europe and India and all these other countries are saying,Â 
"No, we're going to have sovereign AI as well."Â  How does Microsoft navigate the difference to theÂ 
90sâ€”where there's one country in the world that matters, it's America, and our companiesÂ 
sell everywhere and therefore MicrosoftÂ Â  benefits massivelyâ€”to a world where it is bipolar?
Where Microsoft can't just necessarily have the right to win all of Europe or India or Singapore.
There are actually sovereign AI efforts. What is your thought process hereÂ 
and how do you think about this?Â  It's a super critical piece. I think thatÂ 
the key, key priority for the US tech sector and the US government is to ensure thatÂ 
we not only do leading innovative work, but that we also collectively buildÂ 
trust around the world on our tech stack. Because I always say the United States is justÂ 
an unbelievable place. It's just unique in history. It's 4% of the world's population,Â 
25% of the GDP, and 50% of the market cap. I think you should think aboutÂ 
those ratios and reflect on it.Â  That 50% happens because quite frankly theÂ 
trust the world has in the United States, whether it's its capital marketsÂ 
or whether it's its technology andÂ Â  its stewardship of what matters at anyÂ 
given time in terms of leading sector. If that is broken, then that's notÂ 
a good day for the United States.Â  We start with that, which I think PresidentÂ 
Trump gets, the White House, David Sacks, everyone really, I think, gets it.
So therefore I applaud anything that the United States government and theÂ 
tech sector jointly does to, for example, put our own capital at risk, collectivelyÂ 
as an industry, in every part of the world.Â  I would like the USG to take creditÂ 
for foreign direct investment by American companies all over the world.
It's the least talked about, but the best marketing that the United States should be doingÂ 
is that it's not just about all the foreign directÂ Â  investment coming into the United States, but theÂ 
most leading sector, which is these AI factories, are all being created all over the world. ByÂ 
whom? By America and American companies. And so you start there, and then you even buildÂ 
other agreements around it, which are around their continuity, their legitimate sovereigntyÂ 
concerns, around whether it's data residency, for them to have real agency andÂ 
guarantees on privacy, and so on. In fact, our EuropeanÂ 
commitments are worth reading.Â  We made a series of commitments to Europe on howÂ 
we will govern our hyperscale investment there such that the European Union and theÂ 
European countries have sovereignty.Â  We're also building sovereignÂ 
clouds in France and in Germany. We have something called Sovereign Services onÂ 
Azure, which literally gives people key management services along with confidential computing,Â 
including confidential computing in GPUs, which we've done great innovative work with Nvidia.
So I feel very, very good about being able to build, both technically and through policy,Â 
this trust in the American tech stack. How do you see this shaking out as you haveÂ 
this network effect with continual learningÂ Â  and things on the model level?
Maybe you have equivalent things at the hyperscaler level as well.
Do you expect that the countries will say,Â Â  "Look, it's clear one model or a couple modelsÂ 
are the best, and so we're going to use them, but we're going to have some laws around theÂ 
weights having to be hosted in our country"?Â  Or do you expect that there will be this push soÂ 
that it has to be a model trained in our country? Maybe an analogy here is that semiconductorsÂ 
are very important to the economy,Â Â  and people would like to have their sovereignÂ 
semiconductors, but TSMC is just better. And semiconductors are so important toÂ 
the economy that you will just go toÂ Â  Taiwan and buy the semiconductors. YouÂ 
have to. Will it be like that with AI? Ultimately, what matters is the use of AIÂ 
in their economy to create economic value. That's the diffusion theory, whichÂ 
ultimately, it's not the leading sector, but it's the ability to use the leading technologyÂ 
to create your own comparative advantage. So I think that willÂ 
fundamentally be the core driver.Â  But that said, they will want continuity of that.
So in some sense, that's one of the reasons why, I believe, there's always going to be aÂ 
check to "Hey, can this one model have all the runaway deployment?"
That's why open sourceÂ Â  is always going to be there.
There will be, by definition, multiple models. That'll be one way. That's one way forÂ 
people to sort of demand continuity and not have concentration risk, thatâ€™s another way to say it.
And so you say, "Hey, I want multiple models, and then I want an open source."
I feel that as long as that's there,Â Â  every country will feel like, "Okay, I don'tÂ 
have to worry about deploying the best model and broadly diffusing because I can always takeÂ 
what is my data and my liquidity and move it to another model, whether it's open sourceÂ 
or from another country or what have you."Â  Concentration risk and sovereignty, which isÂ 
really agency, those are the two things that will drive the market structure.
The thing about this is thatÂ Â  this doesn't exist for semiconductors.
All refrigerators, cars have chips made in Taiwan. It didn't exist until now.
Even then, if Taiwan is cut off, there are no more cars or no more refrigerators.
TSMC Arizona is not replacing any real fraction of the production.
The sovereignty is a bit of a scam, if you will. It's worthwhile having it, it'sÂ 
important to have it, but it's notÂ Â  real sovereignty. We're a global economy.
I think itâ€™s kind of like saying, "Hey, at this point, we've not learned anything aboutÂ 
what resilience means and what one needs to do." Any nation state, including the UnitedÂ 
States, at this point will do what it takes to be more self-sufficient onÂ 
some of these critical supply chains. So I, as a multinational company, have toÂ 
think about that as a first-class requirement. If I don't, then I'm not respecting what is inÂ 
the policy interests of that country long-term. I'm not saying they won't makeÂ 
practical decisions in the short term.Â  Absolutely, globalization can't just be rewound.
All these capital investments cannot be made in a way, at the pace at whichâ€¦ But at the sameÂ 
time, think about it, if somebody showed up in Washington and said, "Hey, we're not going toÂ 
build any semiconductor plants," they're goingÂ Â  to be kicked out of the United States.
The same thing is going to be true in every other country, too.
So therefore we have to, as companies, respect what the lessons learned are, whetherÂ 
it's that the pandemic woke us up or whatever. But nevertheless people are saying,Â 
"Look, globalization was fantastic.Â  It helped supply chains beÂ 
globalized and be super efficient. But there's such a thing calledÂ 
resilience, and we want resilience."Â  So therefore that feature will get built.
At what pace, I think, is the point you are making.
You can't snap your fingersÂ Â  and say all the TSMC plants now are all inÂ 
Arizona with all their capability. They're not going to be. But is there a plan? ThereÂ 
will be a plan. And should we respect that?Â Â  Absolutely. So I feel that thatâ€™s the world.
I want to meet the world where it is and on what it wants to do going forward, as opposedÂ 
to saying, "Hey, we have a point of viewÂ Â  that doesn't respect your view."
Just to make sure I understand, the idea here is that each country will wantÂ 
some kind of data residency, privacy, et cetera. And Microsoft is especially privileged hereÂ 
because you have relationships with theseÂ Â  countries, you have expertise in settingÂ 
up these kinds of sovereign data centers. Therefore Microsoft is uniquely fit for aÂ 
world with more sovereignty requirements. I don't want to sort of describe itÂ 
as somehow we're uniquely privileged.Â  I would just say I think of that as a businessÂ 
requirement that we have been doing all the hard work all these decades, and we plan to.
So my answer to Dylan's previous questionÂ Â  was that I takeâ€”whether it's in the UnitedÂ 
States, or when the White House and the USG says, "We want you to allocate more of your waferÂ 
starts to fabs in the US"â€”we take that seriously. Or whether it is data centers and theÂ 
EU boundary, we take that seriously.Â  So to me, respecting what are legitimateÂ 
reasons why countries care about sovereignty, building for it as a software andÂ 
a physical plant, is what we'll do. As we go to the bipolar worldâ€”US,Â 
Chinaâ€”it's not just you versus Amazon, or you versus Anthropic, or you versus Google.
There is a whole host of competition. How does America rebuild the trust?
What do you do to rebuild the trust?Â  To say, "Actually, no, American companiesÂ 
will be the main provider for you." And how do you think about competition withÂ 
up and coming Chinese companies, whether itÂ Â  be ByteDance and Alibaba or Deepseek and Moonshot?
To add to that question, one concern is how we're talking about how AI is becoming this industrialÂ 
capex race where you're rapidly having to build quickly across all loads of supply chain.
When you hear that, at least up until now,Â Â  you just think about China. This is theirÂ 
comparative advantage. And especially if we're not going to moonshot to ASI next year, but it's goingÂ 
to be decades of buildouts and infrastructure, how do you deal with Chinese competition?
Are they privileged in that world?Â  Itâ€™s a great question. In fact, you justÂ 
made the point of why trust in American tech is probably the most important feature.
It's not even the model capability, maybe. It is, "can I trust you, the company,Â 
can I trust you, your country, and its institutions to be a long-term supplier?"
That may be the thing that wins the world. That's a good note to end on.
Satya, thank you for doing this.Â  Thank you so much. Thank you.
Thank you.Â  It's awesome. You two guys are quite the team.

</details>
