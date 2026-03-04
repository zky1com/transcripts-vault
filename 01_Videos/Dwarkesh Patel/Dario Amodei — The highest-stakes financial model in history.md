---
title: "Dario Amodei â€” The highest-stakes financial model in history"
people_mentioned: ["Compute Hypothesis", "Rich Sutton"]
channel: "Dwarkesh Patel"
video_id: "n1E9IZfvGMA"
url: "https://www.youtube.com/watch?v=n1E9IZfvGMA"
publish_date: 2026-02-13
duration: "2:22:20"
word_count: 21361
content_type: "solo-talk"
delivery_mode: "opinion"
broad_category: "ai"
subcategories: ["ai-safety", "ai-regulation", "ai-jobs", "ai-agents", "ai-coding", "ai-economics"]
series_name: ""
episode_id: ""
primary_person: "Compute Hypothesis"
host_names: []
interviewer_names: []
interviewee_profiles: []
speaker_profiles: ["Compute Hypothesis - OpenAI"]
organizations_mentioned: ["Dwarkesh Patel"]
locations_mentioned: []
tools_mentioned: []
companies_mentioned: ["OpenAI", "Meta", "Anthropic"]
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

The discussion centers on it's, we're, that's. I actually predict that it's going to existÂ alongside other models, but we're always going to have the API business model because there'sÂ always. I don't think it's guaranteedÂ that it's going to be immediate. I actually do think that the API model is more durable than many people think.

## Key Insights


- I actually predict that it's going to existÂ alongside other models, but we're always going to have the API business model because there'sÂ always going to.
- I don't think it's guaranteedÂ that it's going to be immediate.
- I actually do think that the API model is more durable than many people think.
- Because it's a new industry, a lot of things are going to be tried.
- I have a hunchâ€”this is more like a 50/50Â thingâ€”that it's going to be more like one to two, maybe more like one to three.
- There's another thing that's more interesting to people, so let's make this edit." I think the "country of geniuses in a data center" will be able.

## People Mentioned


- [[Compute Hypothesis]]

- [[Rich Sutton]]




## Full Transcript

<details>
<summary>Click to expand full transcript (21361 words)</summary>

We talked three years ago. In your view, what hasÂ 
been the biggest update over the last three years? What has been the biggest differenceÂ 
between what it felt like then versus now? Broadly speaking, the exponential of theÂ 
underlying technology has gone about as I expected it to go.
There's plus or minus a year or two here and there.
I don't know that I would've predicted the specific direction of code.
But when I look at the exponential, it is roughly what I expected in terms ofÂ 
the march of the models from smart high school student to smart college student toÂ 
beginning to do PhD and professional stuff, and in the case of code reaching beyond that.
The frontier is a little bit uneven, but it's roughly what I expected.
What has been the most surprising thing is the lack of public recognition of howÂ 
close we are to the end of the exponential. To me, it is absolutely wild that you haveÂ 
people â€” within the bubble and outside the bubble â€” talking about the same tired, oldÂ 
hot-button political issues, when we are near the end of the exponential.
I want to understand what that exponential looks like right now.
The first question I asked you when we recorded three years ago was, "whatâ€™sÂ 
up with scaling and why does it work?" I have a similar question now,Â 
but it feels more complicated. At least from the public's point of view, threeÂ 
years ago there were well-known public trends across many orders of magnitude of computeÂ 
where you could see how the loss improves. Now we have RL scaling and there'sÂ 
no publicly known scaling law for it. It's not even clear what the story is.
Is this supposed to be teaching the model skills? Is it supposed to be teaching meta-learning?
What is the scaling hypothesis at this point? I actually have the same hypothesisÂ 
I had even all the way back in 2017. I think I talked about it last time, but I wroteÂ 
a doc called "The Big Blob of Compute Hypothesis". It wasn't about the scaling ofÂ 
language models in particular. When I wrote it GPT-1 had just come out.
That was one among many things. Back in those days there was robotics.
People tried to work on reasoning as a separate thing from language models,Â 
and there was scaling of the kind of RL that happened in AlphaGo and in Dota at OpenAI.
People remember StarCraft at DeepMind, AlphaStar. It was written as a more general document.
Rich Sutton put out "The Bitter Lesson" a couple years later.
The hypothesis is basically the same. What it says is that all the cleverness, all theÂ 
techniques, all the "we need a new method to do something", that doesn't matter very much.
There are only a few things that matter. I think I listed seven of them.
One is how much raw compute you have. The second is the quantity of data.
The third is the quality and distribution of data. It needs to be a broad distribution.
The fourth is how long you train for. The fifth is that you need an objectiveÂ 
function that can scale to the moon. The pre-training objective functionÂ 
is one such objective function. Another is the RL objectiveÂ 
function that says you have a goal, you're going to go out and reach the goal.
Within that, there's objective rewards like you see in math and coding, and there'sÂ 
more subjective rewards like you see in RLHF or higher-order versions of that.
Then the sixth and seventh were things around normalization or conditioning,Â 
just getting the numerical stability so that the big blob of compute flows in thisÂ 
laminar way instead of running into problems. That was the hypothesis, andÂ 
it's a hypothesis I still hold. I don't think I've seen veryÂ 
much that is not in line with it. The pre-training scaling laws were one exampleÂ 
of what we see there. Those have continued going. Now it's been widely reported,Â 
we feel good about pre-training. Itâ€™s continuing to give us gains.
What has changed is that now we're also seeing the same thing for RL.
We're seeing a pre-training phase and then an RL phase on top of that.
With RL, itâ€™s actually just the same. Even other companies have published things inÂ 
some of their releases that say, "We train the model on math contests â€” AIME or other thingsÂ 
â€” and how well the model does is log-linear in how long we've trained it."
We see that as well, and it's not just math contests.
It's a wide variety of RL tasks. We're seeing the same scaling inÂ 
RL that we saw for pre-training. You mentioned Rich Sutton and "The Bitter Lesson".
I interviewed him last year, and he's actually very non-LLM-pilled.
I donâ€™t know if this is his perspective, but one way to paraphrase his objection is:Â 
Something which possesses the true core of human learning would not require all these billionsÂ 
of dollars of data and compute and these bespoke environments, to learn how to use Excel, how toÂ 
use PowerPoint, how to navigate a web browser. The fact that we have to build in these skillsÂ 
using these RL environments hints that we are actually lacking a core human learning algorithm.
So we're scaling the wrong thing. That does raise the question. Why are we doing all this RL scalingÂ 
if we think there's something that's going to be human-like in its ability to learn on the fly?
I think this puts together several things that should be thought of differently.
There is a genuine puzzle here, but it may not matter.
In fact, I would guess it probably doesn't matter. There is an interesting thing. LetÂ 
me take the RL out of it for a second, because I actually think it's a red herring to say that RLÂ 
is any different from pre-training in this matter. If we look at pre-trainingÂ 
scaling, it was very interesting back in 2017 when Alec Radford was doing GPT-1.
The models before GPT-1 were trained on datasets that didn't represent a wide distribution of text.
You had very standard language modeling benchmarks.
GPT-1 itself was trained on a bunch of fanfiction, I think actually.
It was literary text, which is a very small fraction of the text you can get.
In those days it was like a billion words or something, so small datasets representingÂ 
a pretty narrow distribution of what you can see in the world. It didn't generalize well.Â 
If you did better on some fanfiction corpus, it wouldn't generalize that well to otherÂ 
tasks. We had all these measures. We had all these measures of how well it did atÂ 
predicting all these other kinds of texts. It was only when you trained over all the tasksÂ 
on the internet â€” when you did a general internet scrape from something like Common Crawl orÂ 
scraping links in Reddit, which is what we did for GPT-2 â€” that you started to get generalization.
I think we're seeing the same thing on RL. We're starting first with simple RL tasks likeÂ 
training on math competitions, then moving to broader training that involves things like code.
Now we're moving to many other tasks. I think then we're going toÂ 
increasingly get generalization. So that kind of takes out theÂ 
RL vs. pre-training side of it. But there is a puzzle either way, which is thatÂ 
in pre-training we use trillions of tokens. Humans don't see trillions of words.
So there is an actual sample efficiency difference here.
There is actually something different here. The models start from scratchÂ 
and they need much more training. But we also see that once they're trained,Â 
if we give them a long context length of a million â€” the only thing blocking longÂ 
context is inference â€” they're very good at learning and adapting within that context.
So I donâ€™t know the full answer to this. I think there's something goingÂ 
on where pre-training is not like the process of humans learning, but it'sÂ 
somewhere between the process of humans learning and the process of human evolution.
We get many of our priors from evolution. Our brain isn't just a blank slate.
Whole books have been written about this. The language models areÂ 
much more like blank slates. They literally start as random weights, whereasÂ 
the human brain starts with all these regions connected to all these inputs and outputs.
Maybe we should think of pre-training â€” and for that matter, RL as well â€” as somethingÂ 
that exists in the middle space between human evolution and human on-the-spot learning.
And we should think of the in-context learning that the models do as something between long-termÂ 
human learning and short-term human learning. So there's this hierarchy. Thereâ€™s evolution,Â 
there's long-term learning, there's short-term learning, and there's just human reaction.
The LLM phases exist along this spectrum, but not necessarily at exactly the same points.
Thereâ€™s no analog to some of the human modes of learning the LLMs are falling inÂ 
between the points. Does that make sense? Yes, although some thingsÂ 
are still a bit confusing. For example, if the analogy is that thisÂ 
is like evolution so it's fine that it's not sample efficient, then if we'reÂ 
going to get super sample-efficient agent from in-context learning, why are weÂ 
bothering to build all these RL environments? There are companies whose work seems toÂ 
be teaching models how to use this API, how to use Slack, how to use whatever.
It's confusing to me why there's so much emphasis on that if the kind of agent that can just learnÂ 
on the fly is emerging or has already emerged. I can't speak for the emphasis of anyone else.
I can only talk about how we think about it. The goal is not to teach the modelÂ 
every possible skill within RL, just as we don't do that within pre-training.
Within pre-training, we're not trying to expose the model to every possible wayÂ 
that words could be put together. Rather, the model trains on a lot of things andÂ 
then reaches generalization across pre-training. That was the transition from GPT-1 to GPT-2 thatÂ 
I saw up close. The model reaches a point. I had these moments where I was like, "Oh yeah, youÂ 
just give the model a list of numbers â€” this is the cost of the house, this is the square feet ofÂ 
the house â€” and the model completes the pattern and does linear regression."
Not great, but it does it, and it's never seen that exact thing before.
So to the extent that we are building these RL environments, the goal is very similar to whatÂ 
was done five or ten years ago with pre-training. We're trying to get a whole bunch of data, notÂ 
because we want to cover a specific document or a specific skill, but because we want to generalize.
I think the framework you're laying down obviously makes sense. We're making progress toward AGI.Â 
Nobody at this point disagrees we're going to achieve AGI this century.
The crux is you say we're hitting the end of the exponential.
Somebody else looks at this and says, "We've been making progress since 2012,Â 
and by 2035 we'll have a human-like agent." Obviously weâ€™re seeing in these modelsÂ 
the kinds of things that evolution did, or that learning within a human lifetime does.
I want to understand what youâ€™re seeing that makes you think it's oneÂ 
year away and not ten years away. There are two claims you could makeÂ 
here, one stronger and one weaker. Starting with the weaker claim, whenÂ 
I first saw the scaling back in 2019, I wasnâ€™t sure. This was a 50/50 thing. IÂ 
thought I saw something. My claim was that this was much more likely than anyone thinks.
Maybe there's a 50% chance this happens. On the basic hypothesis of, as you put it, withinÂ 
ten years we'll get to what I call a "country of geniuses in a data center", I'm at 90% on that.
It's hard to go much higher than 90% because the world is so unpredictable.
Maybe the irreducible uncertainty puts us at 95%, where you get to things like multiple companiesÂ 
having internal turmoil, Taiwan gets invaded, all the fabs get blown up by missiles.
Now you've jinxed us, Dario. You could construct a 5% world whereÂ 
things get delayed for ten years. There's another 5% which is that I'm veryÂ 
confident on tasks that can be verified. With coding, except for thatÂ 
irreducible uncertainty, I think we'll be there in one or two years.
There's no way we will not be there in ten years in terms of being able to do end-to-end coding.
My one little bit of fundamental uncertainty, even on long timescales, is about tasks thatÂ 
aren't verifiable: planning a mission to Mars; doing some fundamental scientificÂ 
discovery like CRISPR; writing a novel. Itâ€™s hard to verify those tasks.
I am almost certain we have a reliable path to get there, but if there'sÂ 
a little bit of uncertainty it's there. On the ten-year timeline I'm at 90%,Â 
which is about as certain as you can be. I think it's crazy to say thatÂ 
this won't happen by 2035. In some sane world, it wouldÂ 
be outside the mainstream. But the emphasis on verification hints to me aÂ 
lack of belief that these models are generalized. If you think about humans, we're both goodÂ 
at things for which we get verifiable reward and things for which we don't.
No, this is why Iâ€™m almost sure. We already see substantial generalizationÂ 
from things that verify to things that don't. We're already seeing that.
But it seems like you were emphasizing this as a spectrum which will split apartÂ 
which domains in which we see more progress. That doesn't seem like how humans get better.
The world in which we don't get there is the world in which we do all the verifiable things.
Many of them generalize, but we don't fully get there.
We donâ€™t fully color in the other side of the box. It's not a binary thing.
Even if generalization is weak and you can only do verifiable domains, it's not clear to me you couldÂ 
automate software engineering in such a world. You are "a software engineer" in some sense, butÂ 
part of being a software engineer for you involves writing long memos about your grand vision.
I donâ€™t think thatâ€™s part of the job of SWE. That's part of the job of theÂ 
company, not SWE specifically. But SWE does involve designÂ 
documents and other things like that. The models are already prettyÂ 
good at writing comments. Again, Iâ€™m making much weaker claims here thanÂ 
I believe, to distinguish between two things. We're already almost thereÂ 
for software engineering. By what metric? There's one metric which isÂ 
how many lines of code are written by AI. If you consider other productivity improvementsÂ 
in the history of software engineering, compilers write all the lines of software.
There's a difference between how many lines are written and how big the productivityÂ 
improvement is. "Weâ€™re almost there" meaningâ€¦ How big is the productivity improvement,Â 
not just how many lines are written by AI? I actually agree with you on this.
I've made a series of predictions on code and software engineering.
I think people have repeatedly misunderstood them. Let me lay out the spectrum.
About eight or nine months ago, I said the AI model will be writing 90% ofÂ 
the lines of code in three to six months. That happened, at least at some places.
It happened at Anthropic, happened with many people downstream using our models.
But that's actually a very weak criterion. People thought I was saying that we won't need 90%Â 
of the software engineers. Those things are worlds apart. The spectrum is: 90% of code is written byÂ 
the model, 100% of code is written by the model. That's a big difference in productivity.
90% of the end-to-end SWE tasks â€” including things like compiling, setting up clustersÂ 
and environments, testing features, writing memos â€” are done by the models. 100%Â 
of today's SWE tasks are done by the models. Even when that happens, it doesn't meanÂ 
software engineers are out of a job. There are new higher-level thingsÂ 
they can do, where they can manage. Then further down the spectrum, there'sÂ 
90% less demand for SWEs, which I think will happen but this is a spectrum.
I wrote about it in "The Adolescence of Technology" where I went throughÂ 
this kind of spectrum with farming. I actually totally agree with you on that. These are very differentÂ 
benchmarks from each other, but we're proceeding through them super fast.
Part of your vision is that going from 90 to 100 is going to happen fast, and that itÂ 
leads to huge productivity improvements. But what I notice is that even in greenfieldÂ 
projects people start with Claude Code or something, people report starting a lot ofÂ 
projectsâ€¦ Do we see in the world out there a renaissance of software, all these newÂ 
features that wouldn't exist otherwise? At least so far, it doesn't seem like we see that.
So that does make me wonder. Even if I never had to intervene withÂ 
Claude Code, the world is complicated. Jobs are complicated. Closing the loop onÂ 
self-contained systems, whether itâ€™s just writing software or something, how muchÂ 
broader gains would we see just from that? Maybe that should dilute our estimationÂ 
of the "country of geniuses". I simultaneously agree with you that it's aÂ 
reason why these things don't happen instantly, but at the same time, I thinkÂ 
the effect is gonna be very fast. You could have these two poles.
One is that AI is not going to make progress. It's slow. It's going to takeÂ 
forever to diffuse within the economy. Economic diffusion has become one ofÂ 
these buzzwords that's a reason why we're not going to make AI progress,Â 
or why AI progress doesn't matter. The other axis is that we'll get recursiveÂ 
self-improvement, the whole thing. Can't you just draw anÂ 
exponential line on the curve? We're going to have Dyson spheres around theÂ 
sun so many nanoseconds after we get recursive. I'm completely caricaturing the viewÂ 
here, but there are these two extremes. But what we've seen from the beginning, at leastÂ 
if you look within Anthropic, there's this bizarre 10x per year growth in revenue that we've seen.
So in 2023, it was zero to $100 million. In 2024, it was $100 million to $1 billion.
In 2025, it was $1 billion to $ 9-10 billion. You guys should have just bought a billionÂ 
dollars of your own products so you could justâ€¦ And the first month of thisÂ 
year, that exponential is... You would think it would slow down, but weÂ 
added another few billion to revenue in January. Obviously that curve can't go on forever.
The GDP is only so large. I would even guess that it bends somewhat thisÂ 
year, but that is a fast curve. That's a really fast curve. I would bet it stays pretty fastÂ 
even as the scale goes to the entire economy. So I think we should be thinking about this middleÂ 
world where things are extremely fast, but not instant, where they take time because of economicÂ 
diffusion, because of the need to close the loop. Because it's fiddly: "I have to do changeÂ 
management within my enterpriseâ€¦ I set this up, but I have to change the security permissionsÂ 
on this in order to make it actually workâ€¦ I had this old piece of software thatÂ 
checks the model before it's compiled and released and I have to rewrite it.
Yes, the model can do that, but I have to tell the model to do that.
It has to take time to do that." So I think everything we've seen so far isÂ 
compatible with the idea that there's one fast exponential that's the capability of the model.
Then there's another fast exponential that's downstream of that, which is theÂ 
diffusion of the model into the economy. Not instant, not slow, much faster than anyÂ 
previous technology, but it has its limits. When I look inside Anthropic, when I look at ourÂ 
customers: fast adoption, but not infinitely fast. Can I try a hot take on you?
Yeah. I feel like diffusion is cope that people say.
When the model isn't able to do something, they're like, "oh, but it's a diffusion issue."
But then you should use the comparison to humans. You would think that the inherent advantagesÂ 
that AIs have would make diffusion a much easier problem for new AIs getting onboardedÂ 
than new humans getting onboarded. An AI can read your entireÂ 
Slack and your drive in minutes. They can share all the knowledge that theÂ 
other copies of the same instance have. You don't have this adverse selectionÂ 
problem when you're hiring AI, so you can just hire copies of a vetted AI model.
Hiring a human is so much more of a hassle. People hire humans all the time.
We pay humans upwards of $50 trillion in wages because they're useful, even though inÂ 
principle it would be much easier to integrate AIs into the economy than it is to hireÂ 
humans. The diffusion doesn't really explain. I think diffusion is very realÂ 
and doesn't exclusively have to do with limitations on the AI models.
Again, there are people who use diffusion as kind of a buzzword to say this isn't aÂ 
big deal. I'm not talking about that. I'm not talking about how AI will diffuseÂ 
at the speed of previous technologies. I think AI will diffuse much faster than previousÂ 
technologies have, but not infinitely fast. I'll just give an example of this. There's ClaudeÂ 
Code. Claude Code is extremely easy to set up. If you're a developer, you canÂ 
just start using Claude Code. There is no reason why a developer at aÂ 
large enterprise should not be adopting Claude Code as quickly as an individualÂ 
developer or developer at a startup. We do everything we can to promote it.
We sell Claude Code to enterprises. Big enterprises, big financial companies, bigÂ 
pharmaceutical companies, all of them are adopting Claude Code much faster than enterprisesÂ 
typically adopt new technology. But again, it takes time. Any given feature or any givenÂ 
product, like Claude Code or Cowork, will get adopted by the individual developers who are onÂ 
Twitter all the time, by the Series A startups, many months faster than they will get adoptedÂ 
by a large enterprise that does food sales. There are just a number of factors.
You have to go through legal, you have to provision it for everyone.
It has to pass security and compliance. The leaders of the company who are further awayÂ 
from the AI revolution are forward-looking, but they have to say, "Oh, it makesÂ 
sense for us to spend 50 million. This is what this Claude Code thing is.
This is why it helps our company. This is why it makes us more productive."
Then they have to explain to the people two levels below.
They have to say, "Okay, we have 3,000 developers. Here's how we're going to rollÂ 
it out to our developers." We have conversations like this every day.
We are doing everything we can to make Anthropic's revenue grow 20 orÂ 
30x a year instead of 10x a year. Again, many enterprises are justÂ 
saying, "This is so productive. We're going to take shortcuts inÂ 
our usual procurement process." They're moving much faster thanÂ 
when we tried to sell them just the ordinary API, which many of them use.
Claude Code is a more compelling product, but it's not an infinitely compelling product.
I don't think even AGI or powerful AI or "country of geniuses in a data center"Â 
will be an infinitely compelling product. It will be a compelling product enough maybe toÂ 
get 3-5x, or 10x, a year of growth, even when you're in the hundreds of billions of dollars,Â 
which is extremely hard to do and has never been done in history before, but not infinitely fast.
I buy that it would be a slight slowdown. Maybe this is not your claim, butÂ 
sometimes people talk about this like, "Oh, the capabilities are there, but because ofÂ 
diffusion... otherwise we're basically at AGI". I don't believe we're basically at AGI.
I think if you had the "country of geniuses in a data center"...
If we had the "country of geniuses in a data center", we would know it.
We would know it if you had the "country of geniuses in a data center".
Everyone in this room would know it. Everyone in Washington would know it.
People in rural parts might not know it, but we would know it. We don'tÂ 
have that now. That is very clear. Coming back to concrete predictionâ€¦ Because thereÂ 
are so many different things to disambiguate, it can be easy to talk past each otherÂ 
when we're talking about capabilities. For example, when I interviewed you threeÂ 
years ago, I asked you a prediction about what we should expect three years from now. You wereÂ 
right. You said, "We should expect systems which, if you talk to them for the course of anÂ 
hour, it's hard to tell them apart from a generally well-educated human."
I think you were right about that. I think spiritually I feel unsatisfied because myÂ 
internal expectation was that such a system could automate large parts of white-collar work.
So it might be more productive to talk about the actual end capabilitiesÂ 
you want from such a system. I will basically tell you where I think we are.
Let me ask a very specific question so that we can figure out exactly what kinds ofÂ 
capabilities we should think about soon. Maybe I'll ask about it in the context of a jobÂ 
I understand well, not because it's the most relevant job, but just because I can evaluateÂ 
the claims about it. Take video editors. I have video editors. Part of their job involvesÂ 
learning about our audience's preferences, learning about my preferences and tastes,Â 
and the different trade-offs we have. Theyâ€™re, over the course of many months,Â 
building up this understanding of context. The skill and ability they have sixÂ 
months into the job, a model that can pick up that skill on the job on the fly,Â 
when should we expect such an AI system? I guess what you're talking about is thatÂ 
we're doing this interview for three hours. Someone's going to come in,Â 
someone's going to edit it. They're going to be like, "Oh, I don't know, DarioÂ 
scratched his head and we could edit that out." "Magnify that."
"There was this long discussion that is less interesting to people.
There's another thing that's more interesting to people, so let's make this edit."
I think the "country of geniuses in a data center" will be able to do that.
The way it will be able to do that is it will have general control of a computer screen.
You'll be able to feed this in. It'll be able to also use the computer screenÂ 
to go on the web, look at all your previous interviews, look at what people are sayingÂ 
on Twitter in response to your interviews, talk to you, ask you questions, talk toÂ 
your staff, look at the history of edits that you did, and from that, do the job.
I think that's dependent on several things. I think this is one of the thingsÂ 
that's actually blocking deployment: getting to the point on computer use where theÂ 
models are really masters at using the computer. We've seen this climb in benchmarks, andÂ 
benchmarks are always imperfect measures. But I think when we first released computer use aÂ 
year and a quarter ago, OSWorld was at maybe 15%. I don't remember exactly, butÂ 
we've climbed from that to 65-70%. There may be harder measures as well, but I thinkÂ 
computer use has to pass a point of reliability. Can I just follow up on that beforeÂ 
you move on to the next point? For years, I've been trying to buildÂ 
different internal LLM tools for myself. Often I have these text-in, text-outÂ 
tasks, which should be dead center in the repertoire of these models.
Yet I still hire humans to do them. If it's something like, "identify what theÂ 
best clips would be in this transcript", maybe the LLMs do a seven-out-of-ten job on them.
But there's not this ongoing way I can engage with them to help them get better at theÂ 
job the way I could with a human employee. That missing ability, even if youÂ 
solve computer use, would still block my ability to offload an actual job to them.
This gets back to what we were talking about before with learning on the job. It's veryÂ 
interesting. I think with the coding agents, I don't think people would say that learning onÂ 
the job is what is preventing the coding agents from doing everything end to end. TheyÂ 
keep getting better. We have engineers at Anthropic who don't write any code.
When I look at the productivity, to your previous question, we have folks who say, "ThisÂ 
GPU kernel, this chip, I used to write it myself. I just have Claude do it."
There's this enormous improvement in productivity. When I see Claude Code, familiarity withÂ 
the codebase or a feeling that the model hasn't worked at the company for a year, that'sÂ 
not high up on the list of complaints I see. I think what I'm saying is that we'reÂ 
kind of taking a different path. Don't you think with coding that's because there is an external scaffold of memory whichÂ 
exists instantiated in the codebase? I don't know how many other jobs have that.
Coding made fast progress precisely because it has this unique advantage thatÂ 
other economic activity doesn't. But when you say that, what you're implying isÂ 
that by reading the codebase into the context, I have everything that the humanÂ 
needed to learn on the job. So that would be an example ofâ€”whether it'sÂ 
written or not, whether it's available or notâ€”a case where everything you neededÂ 
to know you got from the context window. What we think of as learningâ€”"I started this job,Â 
it's going to take me six months to understand the code base"â€”the model just did it in the context.
I honestly don't know how to think about this because there are people whoÂ 
qualitatively report what you're saying. I'm sure you saw last year, there was a majorÂ 
study where they had experienced developers try to close pull requests in repositories that theyÂ 
were familiar with. Those developers reported an uplift. They reported that they felt moreÂ 
productive with the use of these models. But in fact, if you look at their outputÂ 
and how much was actually merged back in, there was a 20% downlift.
They were less productive as a result of using these models.
So I'm trying to square the qualitative feeling that people feel with theseÂ 
models versus, 1) in a macro level, where is this renaissance of software?
And then 2) when people do these independent evaluations, why are we not seeing theÂ 
productivity benefits we would expect? Within Anthropic, this is just really unambiguous.
We're under an incredible amount of commercial pressure and make it even harder for ourselvesÂ 
because we have all this safety stuff we do that I think we do more than other companies.
The pressure to survive economically while also keeping our values is just incredible.
We're trying to keep this 10x revenue curve going. There is zero time for bullshit.
There is zero time for feeling like we're productive when we're not.
These tools make us a lot more productive. Why do you think we're concernedÂ 
about competitors using the tools? Because we think we're ahead of the competitors.
We wouldn't be going through all this trouble if this were secretly reducing our productivity.
We see the end productivity every few months in the form of model launches.
There's no kidding yourself about this. The models make you more productive.
1) People feeling like they're productive is qualitatively predicted by studies like this.
But 2) if I just look at the end output, obviously you guys are making fast progress.
But the idea was supposed to be that with recursive self-improvement, you makeÂ 
a better AI, the AI helps you build a better next AI, et cetera, et cetera.
What I see insteadâ€”if I look at you, OpenAI, DeepMindâ€”is that people are justÂ 
shifting around the podium every few months. Maybe you think that stopsÂ 
because you've won or whatever. But why are we not seeing the person withÂ 
the best coding model have this lasting advantage if in fact there are these enormousÂ 
productivity gains from the last coding model. I think my model of the situation is thatÂ 
there's an advantage that's gradually growing. I would say right now the codingÂ 
models give maybe, I don't know, a 15-20% total factor speed up. That'sÂ 
my view. Six months ago, it was maybe 5%. So it didn't matter. 5% doesn't register.
It's now just getting to the point where it's one of several factors that kind of matters.
That's going to keep speeding up. I think six months ago, there were severalÂ 
companies that were at roughly the same point because this wasn't a notable factor, butÂ 
I think it's starting to speed up more and more. I would also say there are multiple companies thatÂ 
write models that are used for code and we're not perfectly good at preventing some of these otherÂ 
companies from using our models internally. So I think everything we're seeing isÂ 
consistent with this kind of snowball model. Again, my theme in all of this is all of thisÂ 
is soft takeoff, soft, smooth exponentials, although the exponentials are relatively steep.
So we're seeing this snowball gather momentum where it's like 10%, 20%, 25%, 40%.
As you go, Amdahl's law, you have to get all the things that are preventingÂ 
you from closing the loop out of the way. But this is one of the biggestÂ 
priorities within Anthropic. Stepping back, before in the stack we were talkingÂ 
about when do we get this on-the-job learning? It seems like the point you were makingÂ 
on the coding thing is that we actually don't need on-the-job learning.
You can have tremendous productivity improvements, you can have potentially trillionsÂ 
of dollars of revenue for AI companies, without this basic human ability to learn on the job.
Maybe that's not your claim, you should clarify. But in most domains of economic activity, peopleÂ 
say, "I hired somebody, they weren't that useful for the first few months, and then over timeÂ 
they built up the context, understanding." It's actually hard to defineÂ 
what we're talking about here. But they got something and then now they'reÂ 
a powerhorse and they're so valuable to us. If AI doesn't develop this ability to learn on theÂ 
fly, I'm a bit skeptical that we're going to see huge changes to the world without that ability.
I think two things here. There's the state of the technology right now.
Again, we have these two stages. We have the pre-training and RL stage whereÂ 
you throw a bunch of data and tasks into the models and then they generalize.
So it's like learning, but it's like learning from more data and not learningÂ 
over one human or one model's lifetime. So again, this is situated betweenÂ 
evolution and human learning. But once you learn allÂ 
those skills, you have them. Just like with pre-training, just how the modelsÂ 
know more, if I look at a pre-trained model, it knows more about the historyÂ 
of samurai in Japan than I do. It knows more about baseball than I do.
It knows more about low-pass filters and electronics, all of these things.
Its knowledge is way broader than mine. So I think even just that may get us to theÂ 
point where the models are better at everything. We also have, again, just with scaling the kindÂ 
of existing setup, the in-context learning. I would describe it as kind ofÂ 
like human on-the-job learning, but a little weaker and a little short term.
You look at in-context learning and if you give the model a bunch of examples it does get it.
There's real learning that happens in context. A million tokens is a lot.
That can be days of human learning. If you think about the model readingÂ 
a million words, how long would it take me to read a million? Days or weeksÂ 
at least. So you have these two things. I think these two things within the existingÂ 
paradigm may just be enough to get you the "country of geniuses in a data center".
I don't know for sure, but I think they're going to get you a large fraction of it.
There may be gaps, but I certainly think that just as things are, this is enough to generateÂ 
trillions of dollars of revenue. That's one. Two, is this idea of continual learning, thisÂ 
idea of a single model learning on the job. I think we're working on that too.
There's a good chance that in the next year or two, we also solve that.
Again, I think you get most of the way there without it.
The trillions of dollars a year market, maybe all of the national security implicationsÂ 
and the safety implications that I wrote about in "Adolescence of Technology" can happen without it.
But we, and I imagine others, are working on it. There's a good chance that we willÂ 
get there within the next year or two. There are a bunch of ideas.
I won't go into all of them in detail, but one is just to make the context longer.
There's nothing preventing longer contexts from working.
You just have to train at longer contexts and then learn to serve them at inference.
Both of those are engineering problems that we are working on and I would assumeÂ 
others are working on them as well. This context length increase, it seemedÂ 
like there was a period from 2020 to 2023 where from GPT-3 to GPT-4 Turbo, there was anÂ 
increase from 2000 context lengths to 128K. I feel like for the two-ish years sinceÂ 
then, we've been in the same-ish ballpark. When context lengths get much longerÂ 
than that, people report qualitative degradation in the ability of theÂ 
model to consider that full context. So I'm curious what you're internally seeingÂ 
that makes you think, "10 million contexts, 100 million contexts to get six monthsÂ 
of human learning and building context". This isn't a research problem. This isÂ 
an engineering and inference problem. If you want to serve long context, youÂ 
have to store your entire KV cache. It's difficult to store all the memoryÂ 
in the GPUs, to juggle the memory around. I don't even know the details.
At this point, this is at a level of detail that I'm no longer able to follow, although IÂ 
knew it in the GPT-3 era. "These are the weights, these are the activations you have to storeâ€¦"
But these days the whole thing is flipped because we have MoE models and all of that.
Regarding this degradation you're talking about, without getting too specific, there's two things.
There's the context length you train at and there's a context length that you serve at.
If you train at a small context length and then try to serve at a long contextÂ 
length, maybe you get these degradations. It's better than nothing, you might stillÂ 
offer it, but you get these degradations. Maybe it's harder to trainÂ 
at a long context length. I want to, at the same time, askÂ 
about maybe some rabbit holes. Wouldn't you expect that if you hadÂ 
to train on longer context length, that would mean that you're able to get lessÂ 
samples in for the same amount of compute? Maybe it's not worth diving deep on that.
I want to get an answer to the bigger picture question.
I don't feel a preference for a human editor that's been working forÂ 
me for six months versus an AI that's been working with me for six months, what yearÂ 
do you predict that that will be the case? My guess for that is there's a lot of problemsÂ 
where basically we can do this when we have the "country of geniuses in a data center".
My picture for that, if you made me guess, is one to two years, maybe one to three years. It'sÂ 
really hard to tell. I have a strong viewâ€”99%, 95%â€”that all this will happen in 10 years.
I think that's just a super safe bet. I have a hunchâ€”this is more like a 50/50Â 
thingâ€”that it's going to be more like one to two, maybe more like one to three.
So one to three years. Country of geniuses, and the slightly less economicallyÂ 
valuable task of editing videos. It seems pretty economicallyÂ 
valuable, let me tell you. It's just there are a lot of use cases like that.
There are a lot of similar ones. So you're predicting thatÂ 
within one to three years. And then, generally, Anthropic has predicted thatÂ 
by late '26 or early '27 we will have AI systems that "have the ability to navigate interfacesÂ 
available to humans doing digital work today, intellectual capabilities matching or exceedingÂ 
that of Nobel Prize winners, and the ability to interface with the physical world".
You gave an interview two months ago with DealBook where you were emphasizingÂ 
your company's more responsible compute scaling as compared to your competitors.
I'm trying to square these two views. If you really believe that we're going toÂ 
have a country of geniuses, you want as big a data center as you can get.
There's no reason to slow down. The TAM of a Nobel Prize winner, thatÂ 
can actually do everything a Nobel Prize winner can do, is trillions of dollars.
So I'm trying to square this conservatism, which seems rational if you have more moderateÂ 
timelines, with your stated views about progress. It actually all fits together. We go back toÂ 
this fast, but not infinitely fast, diffusion. Let's say that we're making progress at this rate.
The technology is making progress this fast. I have very high conviction that we'reÂ 
going to get there within a few years. I have a hunch that we're goingÂ 
to get there within a year or two. So thereâ€™s a little uncertainty onÂ 
the technical side, but pretty strong confidence that it won't be off by much.
What I'm less certain about is, again, the economic diffusion side.
I really do believe that we could have models that are a country of geniusesÂ 
in the data center in one to two years. One question is: How many years after thatÂ 
do the trillions in revenue start rolling in? I don't think it's guaranteedÂ 
that it's going to be immediate. It could be one year, it could be twoÂ 
years, I could even stretch it to five years although I'm skeptical of that. So we haveÂ 
this uncertainty. Even if the technology goes as fast as I suspect that it will, we don't knowÂ 
exactly how fast it's going to drive revenue. We know it's coming, but with the way you buyÂ 
these data centers, if you're off by a couple years, that can be ruinous.
It is just like how I wrote in "Machines of Loving Grace".
I said I think we might get this powerful AI, this "country of genius in the data center".
That description you gave comes from "Machines of Loving Grace".
I said we'll get that in 2026, maybe 2027. Again, that is my hunch. I wouldn't be surprised ifÂ 
I'm off by a year or two, but that is my hunch. Let's say that happens. That's the starting gun.Â 
How long does it take to cure all the diseases? That's one of the ways that drives a huge amountÂ 
of economic value. You cure every disease. There's a question of how much of that goes to theÂ 
pharmaceutical company or the AI company, but there's an enormous consumer surplus becauseÂ 
â€”assuming we can get access for everyone, which I care about greatlyâ€”we cure all ofÂ 
these diseases. How long does it take? You have to do the biological discovery,Â 
you have to manufacture the new drug, you have to go through the regulatory process.
We saw this with vaccines and COVID. We got the vaccine out to everyone,Â 
but it took a year and a half. My question is: How long does it take to getÂ 
the cure for everythingâ€”which AI is the genius that can in theory inventâ€”out to everyone?
How long from when that AI first exists in the lab to when diseases haveÂ 
actually been cured for everyone? We've had a polio vaccine for 50 years.
We're still trying to eradicate it in the most remote corners of Africa.
The Gates Foundation is trying as hard as they can.
Others are trying as hard as they can. But that's difficult. Again, IÂ 
don't expect most of the economic diffusion to be as difficult as that. That's the mostÂ 
difficult case. But there's a real dilemma here. Where I've settled on it is that it willÂ 
be faster than anything we've seen in the world, but it still has its limits.
So when we go to buying data centers, again, the curve I'm looking at is: we'veÂ 
had a 10x a year increase every year. At the beginning of this year, we're lookingÂ 
at $10 billion in annualized revenue. We have to decide how much compute to buy.
It takes a year or two to actually build out the data centers, to reserve the data center.
Basically I'm saying, "In 2027, how much compute do I get?"
I could assume that the revenue will continue growing 10x a year,Â 
so it'll be $100 billion at the end of 2026 and $1 trillion at the end of 2027.
Actually it would be $5 trillion dollars of compute because it would be $1Â 
trillion a year for five years. I could buy $1 trillion of computeÂ 
that starts at the end of 2027. If my revenue is not $1 trillion dollars, if it'sÂ 
even $800 billion, there's no force on earth, there's no hedge on earth that could stop meÂ 
from going bankrupt if I buy that much compute. Even though a part of my brain wondersÂ 
if it's going to keep growing 10x, I can't buy $1 trillion a year of compute in 2027.
If I'm just off by a year in that rate of growth, or if the growth rate is 5x a year insteadÂ 
of 10x a year, then you go bankrupt. So you end up in a world where you'reÂ 
supporting hundreds of billions, not trillions. You accept some risk that there's so muchÂ 
demand that you can't support the revenue, and you accept some risk that youÂ 
got it wrong and it's still slow. When I talked about behaving responsibly, whatÂ 
I meant actually was not the absolute amount. I think it is true we're spending somewhatÂ 
less than some of the other players. It's actually the other things, like have we beenÂ 
thoughtful about it or are we YOLOing and saying, "We're going to do $100 billionÂ 
here or $100 billion there"? I get the impression that some of theÂ 
other companies have not written down the spreadsheet, that they don't reallyÂ 
understand the risks they're taking. They're just doing stuff because it soundsÂ 
cool. We've thought carefully about it. We're an enterprise business. Therefore, we can relyÂ 
more on revenue. It's less fickle than consumer. We have better margins, which is the bufferÂ 
between buying too much and buying too little. I think we bought an amount that allowsÂ 
us to capture pretty strong upside worlds. It won't capture the full 10x a year.
Things would have to go pretty badly for us to be in financial trouble.
So we've thought carefully and we've made that balance.
That's what I mean when I say that we're being responsible.
So it seems like it's possible that we actually just have different definitions ofÂ 
the "country of a genius in a data center". Because when I think of actual human geniuses, anÂ 
actual country of human geniuses in a data center, I would happily buy $5 trillion worthÂ 
of compute to run an actual country of human geniuses in a data center.
Let's say JPMorgan or Moderna or whatever doesn't want to use them.
I've got a country of geniuses. They'll start their own company. If they can'tÂ 
start their own company and they're bottlenecked by clinical trialsâ€¦ It is worth stating that withÂ 
clinical trials, most clinical trials fail because the drug doesn't work. There's not efficacy.
I make exactly that point in "Machines of Loving Grace", I say the clinicalÂ 
trials are going to go much faster than we're used to, but not infinitely fast.
Okay, and then suppose it takes a year for the clinical trials to work out so that you'reÂ 
getting revenue from that and can make more drugs. Okay, well, you've got a countryÂ 
of geniuses and you're an AI lab. You could use many more AI researchers.
You also think there are these self-reinforcing gains from smart people working on AI tech.
You can have the data center working on AI progress.
Are there substantially more gains from buying $1 trillion a year ofÂ 
compute versus $300 billion a year of compute? If your competitor is buyingÂ 
a trillion, yes there is. Well, no, there's some gain, but then again,Â 
there's this chance that they go bankrupt before. Again, if you're off by only a year, youÂ 
destroy yourselves. That's the balance. We're buying a lot. We're buying a hell of a lot.
We're buying an amount that's comparable to what the biggest players in the game are buying.
But if you're asking me, "Why haven't we signed $10 trillion of compute starting in mid-2027?"...
First of all, it can't be produced. There isn't that much in the world.
But second, what if the country of geniuses comes, but it comes in mid-2028Â 
instead of mid-2027? You go bankrupt. So if your projection is one to threeÂ 
years, it seems like you should want $10 trillion of compute by 2029 at the latest?
Even in the longest version of the timelines you state, the compute you are rampingÂ 
up to build doesn't seem in accordance. What makes you think that?
Human wages, let's say, are on the order of $50 trillion a yearâ€”
So I won't talk about Anthropic in particular, but if you talk about the industry, the amountÂ 
of compute the industry is building this year is probably, call it, 10-15 gigawatts.
It goes up by roughly 3x a year. So next year's 30-40 gigawatts. 2028 might beÂ 
100 gigawatts. 2029 might be like 300 gigawatts. I'm doing the math in my head, butÂ 
each gigawatt costs maybe $10 billion, on the order of $10-15 billion a year.
You put that all together and you're getting about what you described. Youâ€™reÂ 
getting exactly that. You're getting multiple trillions a year by 2028 or 2029.
You're getting exactly what you predict. That's for the industry.
That's for the industry, thatâ€™s right. Suppose Anthropic's compute keeps 3x-ing a year,Â 
and then by 2027-28, you have 10 gigawatts. Multiply that by, as you say, $10 billion.
So then it's like $100 billion a year. But then you're saying theÂ 
TAM by 2028 is $200 billion. Again, I don't want to give exact numbers forÂ 
Anthropic, but these numbers are too small. Okay, interesting.
You've told investors that you plan to be profitable starting in 2028.
This is the year when we're potentially getting the country of geniuses as a data center.
This is now going to unlock all this progress in medicine and health and new technologies.
Wouldn't this be exactly the time where you'd want to reinvest in the business and build biggerÂ 
"countries" so they can make more discoveries? Profitability is this kindÂ 
of weird thing in this field. I don't think in this field profitabilityÂ 
is actually a measure of spending down versus investing in the business.
Let's just take a model of this. I actually think profitability happens when youÂ 
underestimated the amount of demand you were going to get and loss happens when you overestimatedÂ 
the amount of demand you were going to get, because you're buying the data centers aheadÂ 
of time. Think about it this way. Again, these are stylized facts. These numbers are notÂ 
exact. I'm just trying to make a toy model here. Let's say half of your compute is for trainingÂ 
and half of your compute is for inference. The inference has some grossÂ 
margin that's more than 50%. So what that means is that if you were inÂ 
steady-state, you build a data center and if you knew exactly the demand you were getting,Â 
you would get a certain amount of revenue. Letâ€™s say you pay $100 billion a year for compute.
On $50 billion a year you support $150 billion of revenue.
The other $50 billion is used for training. Basically youâ€™re profitable andÂ 
you make $50 billion of profit. Those are the economics of the industryÂ 
today, or not today but where weâ€™re projecting forward in a year or two.
The only thing that makes that not the case is if you get less demand than $50 billion.
Then you have more than 50% of your data center for research and you're not profitable.
So you train stronger models, but you're not profitable.
If you get more demand than you thought, then research gets squeezed, but you're kind of able toÂ 
support more inference and you're more profitable. Maybe I'm not explaining it well, butÂ 
the thing I'm trying to say is that you decide the amount of compute first.
Then you have some target desire of inference versus training, butÂ 
that gets determined by demand. It doesn't get determined by you.
What I'm hearing is the reason you're predicting profit is that you areÂ 
systematically underinvesting in compute? No, no, no. I'm saying it's hard to predict.
These things about 2028 and when it will happen, that's our attempt to do theÂ 
best we can with investors. All of this stuff is really uncertainÂ 
because of the cone of uncertainty. We could be profitable in 2026Â 
if the revenue grows fast enough. If we overestimate or underestimateÂ 
the next year, that could swing wildly. What I'm trying to get at is that you have aÂ 
model in your head of a business that invests, invests, invests, gets scaleÂ 
and then becomes profitable. There's a single point atÂ 
which things turn around. I don't think the economics ofÂ 
this industry work that way. I see. So if I'm understanding correctly,Â 
you're saying that because of the discrepancy between the amount of compute we should haveÂ 
gotten and the amount of compute we got, we were sort of forced to make profit.
But that doesn't mean we're going to continue making profit.
We're going to reinvest the money because now AI has made so much progressÂ 
and we want a bigger country of geniuses. So back into revenue is high,Â 
but losses are also high. If every year we predict exactly what the demandÂ 
is going to be, we'll be profitable every year. Because spending 50% of your compute on research,Â 
roughly, plus a gross margin that's higher than 50% and correct demand prediction leads to profit.
That's the profitable business model that I think is kind of there, but obscured by theseÂ 
building ahead and prediction errors. I guess you're treating the 50% as aÂ 
sort of given constant, whereas in fact, if AI progress is fast and you can increase theÂ 
progress by scaling up more, you should just have more than 50% and not make profit.
But here's what I'll say. You might want to scale it up more.
Remember the log returns to scale. If 70% would get you a very little bit ofÂ 
a smaller model through a factor of 1.4x... That extra $20 billion, each dollar there is worthÂ 
much less to you because of the log-linear setup. So you might find that it's betterÂ 
to invest that $20 billion in serving inference or in hiring engineers who areÂ 
kind of better at what they're doing. So the reason I said 50%... That's not exactlyÂ 
our target. It's not exactly going to be 50%. Itâ€™ll probably vary over time. What I'm sayingÂ 
is the log-linear return, what it leads to is you spend of order one fraction of the business. LikeÂ 
not 5%, not 95%. Then you get diminishing returns. I feel strange that I'm convincing DarioÂ 
to believe in AI progress or something. Okay, you don't invest in researchÂ 
because it has diminishing returns, but you invest in the other things you mentioned.
I think profit at a sort of macro levelâ€” Again, I'm talking about diminishing returns,Â 
but after you're spending $50 billion a year. This is a point I'm sure you would make,Â 
but diminishing returns on a genius could be quite high.
More generally, what is profit in a market economy?
Profit is basically saying other companies in the market can do moreÂ 
things with this money than I can. Put aside Anthropic. I don't wantÂ 
to give information about Anthropic. Thatâ€™s why I'm giving these stylized numbers.
But let's just derive the equilibrium of the industry.
Why doesn't everyone spend 100% of their compute on training and not serve any customers?
It's because if they didn't get any revenue, they couldn't raise money,Â 
they couldn't do compute deals, they couldn't buy more compute the next year.
So there's going to be an equilibrium where every company spends less than 100% on trainingÂ 
and certainly less than 100% on inference. It should be clear why you don't just serve theÂ 
current models and never train another model, because then you don't have any demand becauseÂ 
you'll fall behind. So there's some equilibrium. It's not gonna be 10%, it's not gonna be 90%.
Let's just say as a stylized fact, it's 50%. That's what I'm getting at. I think we're gonna beÂ 
in a position where that equilibrium of how much you spend on training is less than the grossÂ 
margins that you're able to get on compute. So the underlying economics are profitable.
The problem is you have this hellish demand prediction problem when you're buying the nextÂ 
year of compute and you might guess under and be very profitable but have no compute for research.
Or you might guess over and you are not profitable and you have all the compute forÂ 
research in the world. Does that make sense? Just as a dynamic model of the industry?
Maybe stepping back, I'm not saying I think the "country of geniuses" is going to come in twoÂ 
years and therefore you should buy this compute. To me, the end conclusion you'reÂ 
arriving at makes a lot of sense. But that's because it seems like "country ofÂ 
geniuses" is hard and there's a long way to go. So stepping back, the thing I'm trying to getÂ 
at is more that it seems like your worldview is compatible with somebody who says, "We'reÂ 
like 10 years away from a world in which we're generating trillions of dollars of value."
That's just not my view. So I'll make another prediction. It is hard for meÂ 
to see that there won't be trillions of dollars in revenue before 2030.
I can construct a plausible world. It takes maybe three years. That would beÂ 
the end of what I think it's plausible. Like in 2028, we get the real "countryÂ 
of geniuses in the data center". The revenue's going into the low hundredsÂ 
of billions by 2028, and then the country of geniuses accelerates it to trillions.
Weâ€™re basically on the slow end of diffusion. It takes two years to get to the trillions.
That would be the world where it takes until 2030. I suspect even composing the technicalÂ 
exponential and diffusion exponential, weâ€™ll get there before 2030.
So you laid out a model where Anthropic makes profit because it seems like fundamentallyÂ 
we're in a compute-constrained world. So eventually we keep growing computeâ€”
I think the way the profit comes isâ€¦ Again, let's just abstract the whole industry here.
Let's just imagine we're in an economics textbook. We have a small number of firms.
Each can invest a limited amount. Each can invest some fraction in R&D.
They have some marginal cost to serve. The gross profit margins on that marginal costÂ 
are very high because inference is efficient. There's some competition, but theÂ 
models are also differentiated. Companies will compete to pushÂ 
their research budgets up. But because there's a small number ofÂ 
players, we have the... What is it called? The Cournot equilibrium, I think, is whatÂ 
the small number of firm equilibrium is. The point is it doesn't equilibrate toÂ 
perfect competition with zero margins. If there's three firms in the economy and allÂ 
are kind of independently behaving rationally, it doesn't equilibrate to zero.
Help me understand that, because right now we do have three leading firms andÂ 
they're not making profit. So what is changing? Again, the gross marginsÂ 
right now are very positive. What's happening is a combination of two things.
One is that we're still in the exponential scale-up phase of compute. A modelÂ 
gets trained. Let's say a model got trained that costs $1 billion last year.
Then this year it produced $4 billion of revenue and cost $1 billion to inference from.
Again, I'm using stylized numbers here, but that would be 75% gross margins and this 25% tax.
So that model as a whole makes $2 billion. But at the same time, we're spending $10Â 
billion to train the next model because there's an exponential scale-up. SoÂ 
the company loses money. Each model makes money, but the company loses money.
The equilibrium I'm talking about is an equilibrium where we have the "countryÂ 
of geniuses in a data center", but that model training scale-up has equilibrated more.Â 
Maybe it's still going up. We're still trying to predict the demand, but it's more leveled out.
I'm confused about a couple of things there. Let's start with the current world.
In the current world, you're right that, as you said before, if you treat eachÂ 
individual model as a company, it's profitable. But of course, a big part of the productionÂ 
function of being a frontier lab is training the next model, right?
Yes, that's right. If you didn't do that, then you'dÂ 
make profit for two months and then you wouldn't have margins becauseÂ 
you wouldn't have the best model. But at some point that reaches theÂ 
biggest scale that it can reach. And then in equilibrium, we have algorithmicÂ 
improvements, but we're spending roughly the same amount to train the next model asÂ 
we spend to train the current model. At some point you run out of money in the economy.
A fixed lump of labor fallacyâ€¦ The economy is going to grow, right? That's oneÂ 
of your predictions. We're going to have the data centers in space.
Yes, but this is another example of the theme I was talking about.
The economy will grow much faster with AI than I think it ever has before.
Right now the compute is growing 3x a year. I don't believe the economyÂ 
is gonna grow 300% a year. I said this in "Machines of LovingÂ 
Grace", I think we may get 10-20% per year growth in the economy, but we'reÂ 
not gonna get 300% growth in the economy. So I think in the end, if compute becomesÂ 
the majority of what the economy produces, it's gonna be capped by that.
So let's assume a model where compute stays capped.
The world where frontier labs are making money is one where they continue to make fast progress.
Because fundamentally your margin is limited by how good the alternative is.
So you are able to make money because you have a frontier model.
If you didn't have a frontier model you wouldn't be making money.
So this model requires there never to be a steady state.
Forever and ever you keep making more algorithmic progress.
I don't think that's true. I mean, I feel like we're in an economics class.
Do you know the Tyler Cowen quote? We never stop talking about economics.
We never stop talking about economics. So no, I don't think thisÂ 
field's going to be a monopoly. All my lawyers never want meÂ 
to say the word "monopoly". But I don't think this field'sÂ 
going to be a monopoly. You do get industries in whichÂ 
there are a small number of players. Not one, but a small number of players.
Ordinarily, the way you get monopolies like Facebook or Metaâ€”I always call themÂ 
Facebookâ€”is these kinds of network effects. The way you get industries in whichÂ 
there are a small number of players, is very high costs of entry. Cloud is likeÂ 
this. I think cloud is a good example of this. There are three, maybe four, players within cloud.
I think that's the same for AI, three, maybe four. The reason is that it's so expensive.
It requires so much expertise and so much capital to run a cloud company.
You have to put up all this capital. In addition to putting up all this capital,Â 
you have to get all of this other stuff that requires a lot of skill to make it happen.
So if you go to someone and you're like, "I want to disrupt this industry, here's $100 billion."
You're like, "okay, I'm putting in $100 billion and also betting that you can do all theseÂ 
other things that these people have been doing." Only to decrease the profit.
The effect of your entering is that profit margins go down.
So, we have equilibria like this all the time in the economy where we have a fewÂ 
players. Profits are not astronomical. Margins are not astronomical, but they're not zero.
That's what we see on cloud. Cloud is very undifferentiated. Models areÂ 
more differentiated than cloud. Everyone knows Claude is good at different thingsÂ 
than GPT is good at, than Gemini is good at. It's not just that Claude's good atÂ 
coding, GPT is good at math and reasoning. It's more subtle than that. Models are good atÂ 
different types of coding. Models have different styles. I think these things are actually quiteÂ 
different from each other, and so I would expect more differentiation than you see in cloud.
Now, there actually is one counter-argument. That counter-argument is if theÂ 
process of producing models, if AI models can do that themselves, thenÂ 
that could spread throughout the economy. But that is not an argument forÂ 
commoditizing AI models in general. That's kind of an argument forÂ 
commoditizing the whole economy at once. I don't know what quite happens inÂ 
that world where basically anyone can do anything, anyone can build anything,Â 
and there's no moat around anything at all. I don't know, maybe we want that world.
Maybe that's the end state here. Maybe when AI models can do everything, if we'veÂ 
solved all the safety and security problems, that's one of the mechanisms for theÂ 
economy just flattening itself again. But that's kind of far post-"countryÂ 
of geniuses in the data center." Maybe a finer way to put that potential pointÂ 
is: 1) it seems like AI research is especially loaded on raw intellectual power, which willÂ 
be especially abundant in the world of AGI. And 2) if you just look at the world today,Â 
there are very few technologies that seem to be diffusing as fast as AI algorithmic progress.
So that does hint that this industry is sort of structurally diffusive.
I think coding is going fast, but I think AI research is a superset of coding andÂ 
there are aspects of it that are not going fast. But I do think, again, once we get coding, once weÂ 
get AI models going fast, then that will speed up the ability of AI models to do everything else.
So while coding is going fast now, I think once the AI models are building the next AIÂ 
models and building everything else, the whole economy will kind of go at the sameÂ 
pace. I am worried geographically, though. I'm a little worried that just proximity to AI,Â 
having heard about AI, may be one differentiator. So when I said the 10-20% growth rate, a worryÂ 
I have is that the growth rate could be like 50% in Silicon Valley and parts of the world that areÂ 
socially connected to Silicon Valley, and not that much faster than its current pace elsewhere.
I think that'd be a pretty messed up world. So one of the things I think aboutÂ 
a lot is how to prevent that. Do you think that once we have thisÂ 
country of geniuses in a data center, that robotics is sort of quickly solved afterwards?
Because it seems like a big problem with robotics is that a human can learn how to teleoperateÂ 
current hardware, but current AI models can't, at least not in a way that's super productive.
And so if we have this ability to learn like a human, shouldn't it solveÂ 
robotics immediately as well? I don't think it's dependentÂ 
on learning like a human. It could happen in different ways.
Again, we could have trained the model on many different video games, which are like roboticÂ 
controls, or many different simulated robotics environments, or just train them to controlÂ 
computer screens, and they learn to generalize. So it will happen... it's not necessarilyÂ 
dependent on human-like learning. Human-like learning is one way it could happen.
If the model's like, "Oh, I pick up a robot, I don't know how to use it, I learn," that couldÂ 
happen because we discovered continual learning. That could also happen because we trainedÂ 
the model on a bunch of environments and then generalized, or it could happen becauseÂ 
the model learns that in the context length. It doesn't actually matter which way.
If we go back to the discussion we had an hour ago, that type of thing canÂ 
happen in several different ways. But I do think when for whatever reason theÂ 
models have those skills, then robotics will be revolutionizedâ€”both the design of robots, becauseÂ 
the models will be much better than humans at that, and also the ability to control robots.
So we'll get better at building the physical hardware, building the physical robots, andÂ 
we'll also get better at controlling it. Now, does that mean the roboticsÂ 
industry will also be generating trillions of dollars of revenue?
My answer there is yes, but there will be the same extremely fast, but not infinitely fastÂ 
diffusion. So will robotics be revolutionized? Yeah, maybe tack on another year or two.
That's the way I think about these things. Makes sense. There's a general skepticism aboutÂ 
extremely fast progress. Here's my view. It sounds like you are going to solve continual learningÂ 
one way or another within a matter of years. But just as people weren't talking aboutÂ 
continual learning a couple of years ago, and then we realized, "Oh, why aren't theseÂ 
models as useful as they could be right now, even though they are clearly passing the TuringÂ 
test and are experts in so many different domains? Maybe it's this thing." Then we solve this thingÂ 
and we realize, actually, there's another thing that human intelligence can do that's a basisÂ 
of human labor that these models can't do. So why not think there will beÂ 
more things like this, where we've found more pieces of human intelligence?
Well, to be clear, I think continual learning, as I've said before, might not be a barrier at all.
I think we may just get there by pre-training generalization and RL generalization.
I think there just might not be such a thing at all.
In fact, I would point to the history in ML of people coming up with thingsÂ 
that are barriers that end up kind of dissolving within the big blob of compute.
People talked about, "How do your models keep track of nouns and verbs?"Â 
"They can understand syntactically, but they can't understand semantically?
It's only statistical correlations." "You can understand a paragraph,Â 
you canâ€™t understand a word. There's reasoning, you can't do reasoning."
But then suddenly it turns out you can do code and math very well.
So I think there's actually a stronger history of some of these things seemingÂ 
like a big deal and then kind of dissolving. Some of them are real. The need for data is real,Â 
maybe continual learning is a real thing. But again, I would groundÂ 
us in something like code. I think we may get to the point inÂ 
a year or two where the models can just do SWE end-to-end. That's a whole task.Â 
That's a whole sphere of human activity that we're just saying models can do now.
When you say end-to-end, do you mean setting technical direction, understandingÂ 
the context of the problem, et cetera? Yes. I mean all of that.
Interesting. I feel like that is AGI-complete, which maybe is internally consistent.
But it's not like saying 90% of code or 100% of code.
No, I gave this spectrum: 90% of code, 100% of code, 90% ofÂ 
end-to-end SWE, 100% of end-to-end SWE. New tasks are created for SWEs.
Eventually those get done as well. It's a long spectrum there, but we'reÂ 
traversing the spectrum very quickly. I do think it's funny that I've seenÂ 
a couple of podcasts you've done where the hosts will be like, "But Dwarkesh wroteÂ 
the essay about the continuous learning thing." It always makes me crack up becauseÂ 
you've been an AI researcher for 10 years. I'm sure there's some feeling of,Â 
"Okay, so a podcaster wrote an essay, and every interview I get asked about it."
The truth of the matter is that we're all trying to figure this out together.
There are some ways in which I'm able to see things that others aren't.
These days that probably has more to do with seeing a bunch of stuff within Anthropic andÂ 
having to make a bunch of decisions than I have any great research insight that others don't.
I'm running a 2,500 person company. It's actually pretty hard for me to have concreteÂ 
research insight, much harder than it would have been 10 years ago or even two or three years ago.
As we go towards a world of a full drop-in remote worker replacement, does an APIÂ 
pricing model still make the most sense? If not, what is the correctÂ 
way to price AGI, or serve AGI? I think there's going to be a bunch ofÂ 
different business models here, all at once, that are going to be experimented with.
I actually do think that the API model is more durable than many people think.
One way I think about it is if the technology is advancing quickly, if it's advancingÂ 
exponentially, what that means is there's always a surface area of new use cases thatÂ 
have been developed in the last three months. Any kind of product surface you put in place isÂ 
always at risk of sort of becoming irrelevant. Any given product surface probably makes senseÂ 
for a range of capabilities of the model. The chatbot is already running into limitationsÂ 
where making it smarter doesn't really help the average consumer that much.
But I don't think that's a limitation of AI models.
I don't think that's evidence that the models are good enough and themÂ 
getting better doesn't matter to the economy. It doesn't matter to that particular product.
So I think the value of the API is that the API always offers an opportunity, very close to theÂ 
bare metal, to build on what the latest thing is. There's always going to be this frontÂ 
of new startups and new ideas that weren't possible a few months ago and areÂ 
possible because the model is advancing. I actually predict that it's going to existÂ 
alongside other models, but we're always going to have the API business model because there'sÂ 
always going to be a need for a thousand different people to try experimenting with the model in aÂ 
different way. 100 of them become startups and ten of them become big successful startups.
Two or three really end up being the way that people use the model of a given generation.
So I basically think it's always going to exist. At the same time, I'm sure there'sÂ 
going to be other models as well. Not every token that's output byÂ 
the model is worth the same amount. Think about what is the value of the tokensÂ 
that the model outputs when someone calls them up and says, "My Mac isn't working," orÂ 
something, the model's like, "restart it." Someone hasn't heard that before, butÂ 
the model said that 10 million times. Maybe that's worth like a dollarÂ 
or a few cents or something. Whereas if the model goes to one of theÂ 
pharmaceutical companies and it says, "Oh, you know, this molecule you're developing, youÂ 
should take the aromatic ring from that end of the molecule and put it on that end of the molecule.
If you do that, wonderful things will happen." Those tokens could be worthÂ 
tens of millions of dollars. So I think we're definitely going toÂ 
see business models that recognize that. At some point we're going to see "pay for results"Â 
in some form, or we may see forms of compensation that are like labor, that kind of work by theÂ 
hour. I don't know. I think because it's a new industry, a lot of things are going to be tried.
I don't know what will turn out to be the right thing.
I take your point that people will have to try things to figure out whatÂ 
is the best way to use this blob of intelligence. But what I find striking is Claude Code.
I don't think in the history of startups there has been a single application that hasÂ 
been as hotly competed in as coding agents. Claude Code is a category leader here. ThatÂ 
seems surprising to me. It doesn't seem intrinsically that Anthropic had to build this.
I wonder if you have an accounting of why it had to be Anthropic or how Anthropic endedÂ 
up building an application in addition to the model underlying it that was successful.
So it actually happened in a pretty simple way, which is that we had our own codingÂ 
models, which were good at coding. Around the beginning of 2025, I said, "IÂ 
think the time has come where you can have nontrivial acceleration of your own researchÂ 
if you're an AI company by using these models." Of course, you need an interface,Â 
you need a harness to use them. So I encouraged people internally. I didn'tÂ 
say this is one thing that you have to use. I just said people should experiment with this.
I think it might have been originally called Claude CLI, and then the nameÂ 
eventually got changed to Claude Code. Internally, it was the thing that everyone wasÂ 
using and it was seeing fast internal adoption. I looked at it and I said, "Probably weÂ 
should launch this externally, right?" It's seen such fast adoption within Anthropic.
Coding is a lot of what we do. We have an audience of many, many hundredsÂ 
of people that's in some ways at least representative of the external audience.
So it looks like we already have product market fit. Let's launch this thing. And thenÂ 
we launched it. I think just the fact that we ourselves are kind of developing the model and weÂ 
ourselves know what we most need to use the model, I think it's kind of creating this feedback loop.
I see. In the sense that you, let's say a developer at Anthropic is like, "Ah, it wouldÂ 
be better if it was better at this X thing." Then you bake that into theÂ 
next model that you build. That's one version of it, but then there'sÂ 
just the ordinary product iteration. We have a bunch of coders withinÂ 
Anthropic, they use Claude Code every day and so we get fast feedback.
That was more important in the early days. Now, of course, there are millionsÂ 
of people using it, and so we get a bunch of external feedback as well.
But it's just great to be able to get kind of fast internal feedback.
I think this is the reason why we launched a coding model and didn'tÂ 
launch a pharmaceutical company. My background's in biology, but weÂ 
don't have any of the resources that are needed to launch a pharmaceutical company.
Let me now ask you about making AI go well. It seems like whatever vision we have about howÂ 
AI goes well has to be compatible with two things: 1) the ability to build and run AIs isÂ 
diffusing extremely rapidly and 2) the population of AIs, the amount we have and theirÂ 
intelligence, will also increase very rapidly. That means that lots of people will be ableÂ 
to build huge populations of misaligned AIs, or AIs which are just companiesÂ 
which are trying to increase their footprint or have weird psyches likeÂ 
Sydney Bing, but now they're superhuman. What is a vision for a world in which weÂ 
have an equilibrium that is compatible with lots of different AIs, some ofÂ 
which are misaligned, running around? I think in "The Adolescence of Technology",Â 
I was skeptical of the balance of power. But the thing I was specifically skeptical ofÂ 
is you have three or four of these companies all building models that are derived from theÂ 
same thing, that they would check each other. Or even that any number ofÂ 
them would check each other. We might live in an offense-dominant world whereÂ 
one person or one AI model is smart enough to do something that causes damage for everything else.
In the short run, we have a limited number of players now.
So we can start within the limited number of players.
We need to put in place the safeguards. We need to make sure everyoneÂ 
does the right alignment work. We need to make sure everyone has bioclassifiers.
Those are the immediate things we need to do. I agree that that doesn't solve the problem inÂ 
the long run, particularly if the ability of AI models to make other AI models proliferates,Â 
then the whole thing can become harder to solve. I think in the long run we needÂ 
some architecture of governance. We need some architecture of governanceÂ 
that preserves human freedom, but also allows us to govern a very largeÂ 
number of human systems, AI systems, hybrid human-AI companies or economic units.
So we're gonna need to think about: how do we protect the world against bioterrorism?
How do we protect the world against mirror life? Probably we're gonna need someÂ 
kind of AI monitoring system that monitors for all of these things.
But then we need to build this in a way that preserves civil libertiesÂ 
and our constitutional rights. So I think just as anything else, it's aÂ 
new security landscape with a new set of tools and a new set of vulnerabilities.
My worry is, if we had 100 years for this to happen all very slowly, we'd get used to it.
We've gotten used to the presence of explosives in society or the presence of various newÂ 
weapons or the presence of video cameras. We would get used to it over 100 years andÂ 
weâ€™d develop governance mechanisms. We'd make our mistakes. My worry is justÂ 
that this is happening all so fast. So maybe we need to do our thinking faster aboutÂ 
how to make these governance mechanisms work. It seems like in an offense-dominant world, overÂ 
the course of the next centuryâ€”the idea is that AI is making the progress that would happen over theÂ 
next century happen in some period of five to ten yearsâ€”we would still need the same mechanisms, orÂ 
balance of power would be similarly intractable, even if humans were the only game in town.
I guess we have the advice of AI. But it fundamentally doesn't seem likeÂ 
a totally different ball game here. If checks and balances were going toÂ 
work, they would work with humans as well. If they aren't going to work, theyÂ 
wouldn't work with AIs as well. So maybe this just dooms humanÂ 
checks and balances as well. Again, I think there's someÂ 
way to make this happen. The governments of the world may haveÂ 
to work together to make it happen. We may have to talk to AIs about buildingÂ 
societal structures in such a way that these defenses are possible. I don't know. I donâ€™tÂ 
want to say this is so far ahead in time, but itâ€™s so far ahead in technological abilityÂ 
that may happen over a short period of time, that it's hard for us to anticipate it in advance.
Speaking of governments getting involved, on December 26, the Tennessee legislatureÂ 
introduced a bill which said, "It would be an offense for a person to knowinglyÂ 
train artificial intelligence to provide emotional support, including throughÂ 
open-ended conversations with a user." Of course, one of the things that Claude attemptsÂ 
to do is be a thoughtful, knowledgeable friend. In general, it seems like we're goingÂ 
to have this patchwork of state laws. A lot of the benefits that normal people couldÂ 
experience as a result of AI are going to be curtailed, especially when we get into theÂ 
kinds of things you discuss in "Machines of Loving Grace": biological freedom,Â 
mental health improvements, et cetera. It seems easy to imagine worlds in which theseÂ 
get Whac-A-Moled away by different laws, whereas bills like this don't seem to address the actualÂ 
existential threats that you're concerned about. I'm curious to understand, in the contextÂ 
of things like this, Anthropic's position against the federal moratorium on state AI laws.
There are many different things going on at once. I think that particular law is dumb.
It was clearly made by legislators who just probably had little ideaÂ 
what AI models could do and not do. They're like, "AI models servingÂ 
us, that just sounds scary. I don't want that to happen."
So we're not in favor of that. But that wasn't the thing that was being voted on.
The thing that was being voted on is: we're going to ban all state regulation of AIÂ 
for 10 years with no apparent plan to do any federal regulation of AI, which would takeÂ 
Congress to pass, which is a very high bar. So the idea that we'd ban states from doingÂ 
anything for 10 yearsâ€¦ People said they had a plan for the federal government, but thereÂ 
was no actual proposal on the table. There was no actual attempt. Given the serious dangersÂ 
that I lay out in "Adolescence of Technology" around things like biological weaponsÂ 
and bioterrorism autonomy risk, and the timelines we've been talking aboutâ€”10 years isÂ 
an eternityâ€”I think that's a crazy thing to do. So if that's the choice, if that's whatÂ 
you force us to choose, then we're going to choose not to have that moratorium.
I think the benefits of that position exceed the costs, but it's not aÂ 
perfect position if that's the choice. Now, I think the thing that we should do, theÂ 
thing that I would support, is the federal government should step in, not saying "states youÂ 
can't regulate", but "Here's what we're going to do, and states you can't differ from this."
I think preemption is fine in the sense of saying that the federal government says, "HereÂ 
is our standard. This applies to everyone. States can't do something different."Â 
That would be something I would support if it would be done in the right way.
But this idea of states, "You can't do anything and we're not doing anything either,"Â 
that struck us as very much not making sense. I think it will not age well, it isÂ 
already starting to not age well with all the backlash that you've seen.
Now, in terms of what we would want, the things we've talked about are starting withÂ 
transparency standards in order to monitor some of these autonomy risks and bioterrorism risks.
As the risks become more serious, as we get more evidence for them, then I think we could be moreÂ 
aggressive in some targeted ways and say, "Hey, AI bioterrorism is really a threat.
Let's pass a law that forces people to have classifiers."
I could even imagineâ€¦ It depends. It depends how serious the threat it ends upÂ 
being. We don't know for sure. We need to pursue this in an intellectually honest way where we sayÂ 
that ahead of time, the risk has not emerged yet. But I could certainly imagine, withÂ 
the pace that things are going at, a world where later this year we say, "Hey,Â 
this AI bioterrorism stuff is really serious. We should do something about it.
We should put it in a federal standard. If the federal government won't act, we should putÂ 
it in a state standard." I could totally see that. I'm concerned about a world where if you justÂ 
consider the pace of progress you're expecting, the life cycle of legislation...
The benefits are, as you say because of diffusion lag, slow enough that IÂ 
really do think this patchwork of state laws, on the current trajectory, would prohibit.
I mean if having an emotional chatbot friend is something that freaks people out, then justÂ 
imagine the kinds of actual benefits from AI we want normal people to be able to experience.
From improvements in health and healthspan and improvements in mental health and so forth.
Whereas at the same time, it seems like you think the dangers are already on the horizon andÂ 
I just don't see that muchâ€¦ It seems like it would be especially injurious to the benefitsÂ 
of AI as compared to the dangers of AI. So that's maybe where the costÂ 
benefit makes less sense to me. So there's a few things here.
People talk about there being thousands of these state laws.
First of all, the vast, vast majority of them do not pass.
The world works a certain way in theory, but just because a law has been passedÂ 
doesn't mean it's really enforced. The people implementing it may beÂ 
like, "Oh my God, this is stupid. It would mean shutting off everythingÂ 
that's ever been built in Tennessee." Very often, laws are interpreted in a wayÂ 
that makes them not as dangerous or harmful. On the same side, of course, you have to worryÂ 
if you're passing a law to stop a bad thing; you have this problem as well.
My basic view is that if we could decide what laws were passed and how thingsÂ 
were doneâ€”and weâ€™re only one small input into thatâ€”I would deregulate a lot of theÂ 
stuff around the health benefits of AI. I don't worry as much about the chatbot laws.
I actually worry more about the drug approval process, where I think AI models are going toÂ 
greatly accelerate the rate at which we discover drugs, and the pipeline will get jammed up.
The pipeline will not be prepared to process all the stuff that's going through it.
I think reform of the regulatory process should bias more towards the fact that we haveÂ 
a lot of things coming where the safety and efficacy is actually going to be really crisp andÂ 
clear, a beautiful thing, and really effective. Maybe we don't need all this superstructure aroundÂ 
it that was designed around an era of drugs that barely work and often have serious side effects.
At the same time, I think we should be ramping up quite significantly theÂ 
safety and security legislation. Like I've said, starting with transparency isÂ 
my view of trying not to hamper the industry, trying to find the right balance. I'mÂ 
worried about it. Some people criticize my essay for saying, "That's too slow.
The dangers of AI will come too soon if we do that."
Well, basically, I think the last six months and maybe the nextÂ 
few months are going to be about transparency. Then, if these risks emerge whenÂ 
we're more certain of themâ€”which I think we might be as soon as later thisÂ 
yearâ€”then I think we need to act very fast in the areas where we've actually seen the risk.
I think the only way to do this is to be nimble. Now, the legislative process is normallyÂ 
not nimble, but we need to emphasize the urgency of this to everyone involved.
That's why I'm sending this message of urgency. That's why I wrote Adolescence of Technology.
I wanted policymakers, economists, national security professionals, and decision-makers toÂ 
read it so that they have some hope of acting faster than they would have otherwise.
Is there anything you can do or advocate that would make it more certain that theÂ 
benefits of AI are better instantiated? I feel like you have workedÂ 
with legislatures to say, "Okay, we're going to prevent bioterrorism here.
We're going to increase transparency, we're going to increase whistleblower protection."
But I think by default, the actual benefits we're looking forward to seem very fragileÂ 
to different kinds of moral panics or political economy problems.
I don't actually agree that much regarding the developed world.
I feel like in the developed world, markets function pretty well.
When there's a lot of money to be made on something and it's clearly the bestÂ 
available alternative, it's actually hard for the regulatory system to stop it.
We're seeing that in AI itself. A thing I've been trying to fight forÂ 
is export controls on chips to China. That's in the nationalÂ 
security interest of the US. That's squarely within the policy beliefs ofÂ 
almost everyone in Congress of both parties. The case is very clear. The counterargumentsÂ 
against it, I'll politely call them fishy. Yet it doesn't happen and we sell the chipsÂ 
because there's so much money riding on it. That money wants to be made.
In that case, in my opinion, that's a bad thing. But it also applies when it's a good thing.
So if we're talking about drugs and benefits of the technology, I am not as worried about thoseÂ 
benefits being hampered in the developed world. I am a little worried about them going too slow.
As I said, I do think we should work to speed the approval process in the FDA.
I do think we should fight against these chatbot bills that you're describing.Â 
Described individually, I'm against them. I think they're stupid. But I actually think theÂ 
bigger worry is the developing world, where we don't have functioning markets and where we oftenÂ 
can't build on the technology that we've had. I worry more that thoseÂ 
folks will get left behind. And I worry that even if the cures areÂ 
developed, maybe there's someone in rural Mississippi who doesn't get it as well.
That's a smaller version of the concern we have in the developing world.
So the things we've been doing are working with philanthropists.
We work with folks who deliver medicine and health interventions to the developing world,Â 
to sub-Saharan Africa, India, Latin America, and other developing parts of the world.
That's the thing I think that won't happen on its own.
You mentioned export controls. Why shouldn't the US and China both haveÂ 
a "country of geniuses in a data center"? Why wonâ€™t it happen or why shouldn't it happen?
Why shouldn't it happen. If this does happen, weÂ 
could have a few situations. If we have an offense-dominantÂ 
situation, we could have a situation like nuclear weapons, but more dangerous.
Either side could easily destroy everything. We could also have a world where it's unstable.
The nuclear equilibrium is stable because it's deterrence.
But let's say there was uncertainty about, if the two AIs fought, which AI would win?Â 
That could create instability. You often have conflict when the two sides have a differentÂ 
assessment of their likelihood of winning. If one side is like, "Oh yeah, there's a 90%Â 
chance I'll win," and the other side thinks the same, then a fight is much more likely.
They can't both be right, but they can both think that.
But this seems like a fully general argument against the diffusion of AI technology.
That's the implication of this world. Let me just go on, because I thinkÂ 
we will get diffusion eventually. The other concern I have is that governmentsÂ 
will oppress their own people with AI. I'm worried about a world where you have a countryÂ 
in which thereâ€™s already a government that's building a high-tech authoritarian state.
To be clear, this is about the government. This is not about the people.
We need to find a way for people everywhere to benefit.
My worry here is about governments. My worry is if the world gets carved upÂ 
into two pieces, one of those two pieces could be authoritarian or totalitarian inÂ 
a way that's very difficult to displace. Now, will governments eventually get powerfulÂ 
AI, and is there a risk of authoritarianism? Yes. Will governments eventually getÂ 
powerful AI, and is there a risk of bad equilibria? Yes, I think both things. But theÂ 
initial conditions matter. At some point, we're going to need to set up the rules of the road.
I'm not saying that one country, either the United States or a coalition of democraciesâ€”whichÂ 
I think would be a better setup, although it requires more international cooperation than weÂ 
currently seem to want to makeâ€”should just say, "These are the rules of the road."
There's going to be some negotiation. The world is going to have to grapple with this.
What I would like is for the democratic nations of the worldâ€”those whose governments representÂ 
closer to pro-human valuesâ€”are holding the stronger hand and have more leverageÂ 
when the rules of the road are set. So I'm very concerned aboutÂ 
that initial condition. I was re-listening to the interview fromÂ 
three years ago, and one of the ways it aged poorly is that I kept asking questionsÂ 
assuming there was going to be some key fulcrum moment two to three years from now.
In fact, being that far out, it just seems like progress continues, AI improves, AI is moreÂ 
diffused, and people will use it for more things. It seems like you're imagining a world in theÂ 
future where the countries get together, and "Here's the rules of the road, here's the leverageÂ 
we have, and here's the leverage you have." But on the current trajectory,Â 
everybody will have more AI. Some of that AI will be usedÂ 
by authoritarian countries. Some of that within the authoritarianÂ 
countries will be used by private actors versus state actors.
It's not clear who will benefit more. It's always unpredictable to tell in advance.
It seems like the internet privileged authoritarian countries moreÂ 
than you would've expected. Maybe AI will be the opposite way around.
I want to better understand what you're imagining here.
Just to be precise about it, I think the exponential of the underlyingÂ 
technology will continue as it has before. The models get smarter and smarter, even when theyÂ 
get to a "country of geniuses in a data center." I think you can continueÂ 
to make the model smarter. There's a question of getting diminishingÂ 
returns on their value in the world. How much does it matter afterÂ 
you've already solved human biology? At some point you can do harder, more abstruseÂ 
math problems, but nothing after that matters. Putting that aside, I do think the exponentialÂ 
will continue, but there will be certain distinguished points on the exponential.
Companies, individuals, and countries will reach those points at different times.
In "The Adolescence of Technology" I talk about: Is a nuclear deterrent stillÂ 
stable in the world of AI? I don't know, but that's an exampleÂ 
of one thing we've taken for granted. The technology could reach such a levelÂ 
that we can no longer be certain of it. Think of others. There are points where if youÂ 
reach a certain level, maybe you have offensive cyber dominance, and every computer systemÂ 
is transparent to you after that unless the other side has an equivalent defense.
I don't know what the critical moment is or if there's a single critical moment.
But I think there will be either a critical moment, a small number of critical moments,Â 
or some critical window where AI confers some large advantage from the perspectiveÂ 
of national security, and one country or coalition has reached it before others.
I'm not advocating that they just say, "Okay, we're in charge now."
That's not how I think about it. The other side is always catching up.
There are extreme actions you're not willing to take, and it's not rightÂ 
to take complete control anyway. But at the point that happens, people areÂ 
going to understand that the world has changed. There's going to be some negotiation,Â 
implicit or explicit, about what the post-AI world order looks like.
My interest is in making that negotiation be one in which classicalÂ 
liberal democracy has a strong hand. I want to understand what that betterÂ 
means, because you say in the essay, "Autocracy is simply not a form of government thatÂ 
people can accept in the post-powerful AI age." That sounds like you're saying the CCP as anÂ 
institution cannot exist after we get AGI. That seems like a very strong demand, and itÂ 
seems to imply a world where the leading lab or the leading country will be able toâ€”andÂ 
by that language, should get toâ€”determine how the world is governed or what kindsÂ 
of governments are, and are not, allowed. I believe that paragraph said something like,Â 
"You could take it even further and say X." I wasn't necessarily endorsing that view.
I was saying, "Here's a weaker thing that I believe.
We have to worry a lot about authoritarians and we should try to check them and limit their power.
You could take this much further and have a more interventionist view that says authoritarianÂ 
countries with AI are these self-fulfilling cycles that are very hard to displace, so youÂ 
just need to get rid of them from the beginning." That has exactly all the problems you say.
If you were to make a commitment to overthrowing every authoritarian country,Â 
they would take a bunch of actions now that could lead to instability.
That just may not be possible. But the point I was making that I doÂ 
endorse is that it is quite possible that... Today, the view, my view, in most of the WesternÂ 
world is that democracy is a better form of government than authoritarianism.
But if a countryâ€™s authoritarian, we donâ€™t react the way weâ€™d react ifÂ 
they committed a genocide or something. I guess what I'm saying is I'm a little worriedÂ 
that in the age of AGI, authoritarianism will have a different meaning.
It will be a graver thing. We have to decide one way orÂ 
another how to deal with that. The interventionist view is one possible view. IÂ 
was exploring such views. It may end up being the right view, or it may end up being too extreme.Â 
But I do have hope. One piece of hope I have is that we have seen that as new technologies areÂ 
invented, forms of government become obsolete. I mentioned this in "Adolescence ofÂ 
Technology", where I said feudalism was basically a form of government, and whenÂ 
we invented industrialization, feudalism was no longer sustainable. It no longer made sense.
Why is that hope? Couldn't that imply that democracy is no longer goingÂ 
to be a competitive system? Right, it could go either way.
But these problems with authoritarianism get deeper.
I wonder if that's an indicator of other problems that authoritarianism will have.
In other words, because authoritarianism becomes worse, people are more afraid of it.
They work harder to stop it. You have to think in terms of total equilibrium.
I just wonder if it will motivate new ways of thinking about how to preserve andÂ 
protect freedom with the new technology. Even more optimistically, will it lead toÂ 
a collective reckoning and a more emphatic realization of how important some of theÂ 
things we take as individual rights are? A more emphatic realization thatÂ 
we really can't give these away. We've seen there's no other wayÂ 
to live that actually works. I am actually hopeful thatâ€”it sounds tooÂ 
idealistic, but I believe it could be the caseâ€”dictatorships become morally obsolete.
They become morally unworkable forms of government and the crisis that that createsÂ 
is sufficient to force us to find another way. I think there is genuinely a tough questionÂ 
here which I'm not sure how you resolve. We've had to come out one way orÂ 
another on it through history. With China in the '70s and '80s,Â 
we decided that even though it's an authoritarian system, we will engage with it.
I think in retrospect that was the right call, because itâ€™s a state authoritarian system butÂ 
a billion-plus people are much wealthier and better off than they would've otherwise been.
It's not clear that it would've stopped being an authoritarian country otherwise.
You can just look at North Korea as an example of that.
I don't know if it takes that much intelligence to remain an authoritarianÂ 
country that continues to coalesce its own power. You can imagine a North Korea with an AIÂ 
that's much worse than everybody else's, but still enough to keep power.
In general, it seems like we should just have this attitude that the benefits ofÂ 
AIâ€”in the form of all these empowerments of humanity and healthâ€”will be big.
Historically, we have decided it's good to spread the benefits of technology widely, evenÂ 
to people whose governments are authoritarian. It is a tough question, how to think about itÂ 
with AI, but historically we have said, "yes, this is a positive-sum world, and it'sÂ 
still worth diffusing the technology." There are a number of choices we have.
Framing this as a government-to-government decision in national security terms is oneÂ 
lens, but there are a lot of other lenses. You could imagine a world where weÂ 
produce all these cures to diseases. The cures are fine to sell to authoritarianÂ 
countries, but the data centers just aren't. The chips and the data centers aren't,Â 
and the AI industry itself isn't. Another possibility I thinkÂ 
folks should think about is this. Could there be developments we can makeâ€”eitherÂ 
that naturally happen as a result of AI, or that we could make happen byÂ 
building technology on AIâ€”that create an equilibrium where it becomesÂ 
infeasible for authoritarian countries to deny their people private useÂ 
of the benefits of the technology? Are there equilibria where we can give everyone inÂ 
an authoritarian country their own AI model that defends them from surveillance and there isn'tÂ 
a way for the authoritarian country to crack down on this while retaining power? I don't know.Â 
That sounds to me like if that went far enough, it would be a reason why authoritarianÂ 
countries would disintegrate from the inside. But maybe there's a middle world where there'sÂ 
an equilibrium where, if they want to hold on to power, the authoritarians can't denyÂ 
individualized access to the technology. But I actually do have a hopeÂ 
for the more radical version. Is it possible that the technologyÂ 
might inherently have propertiesâ€”or that by building on it in certain waysÂ 
we could create propertiesâ€”that have this dissolving effect on authoritarian structures?
Now, we hoped originallyâ€”think back to the beginning of the Obama administrationâ€”thatÂ 
social media and the internet would have that property, and it turns out not to.
But what if we could try again with the knowledge of how many things could go wrong,Â 
and that this is a different technology? I don't know if it wouldÂ 
work, but it's worth a try. It's just very unpredictable. ThereÂ 
are first principles reasons why authoritarianism might be privileged.
It's all very unpredictable. We just have to recognize the problem and comeÂ 
up with 10 things we can try, try those, and then assess which ones are working, if any.
Then try new ones if the old ones aren't working. But I guess that nets out to today, as youÂ 
say, that we will not sell data centers, or chips, and the ability to make chips to China.
So in some sense, you are denyingâ€¦ There would be some benefits to the Chinese economy, ChineseÂ 
people, et cetera, because we're doing that. Then there'd also be benefits to the AmericanÂ 
economy because it's a positive-sum world. We could trade. They could have theirÂ 
country's data centers doing one thing. We could have ours doing another.
Already, you're saying it's not worth that positive-sum stipend to empower those countries?
What I would say is that we are about to be in a world where growth and economicÂ 
value will come very easily if we're able to build these powerful AI models.
What will not come easily is distribution of benefits, distribution ofÂ 
wealth, political freedom. These are the things that areÂ 
going to be hard to achieve. So when I think about policy, I think that theÂ 
technology and the market will deliver all the fundamental benefits, this is my fundamentalÂ 
belief, almost faster than we can take them. These questions about distribution and politicalÂ 
freedom and rights are the ones that will actually matter and that policy should focus on.
Speaking of distribution, as you were mentioning, we have developing countries.
In many cases, catch-up growth has been weaker than we would have hoped for.
But when catch-up growth does happen, it's fundamentally becauseÂ 
they have underutilized labor. We can bring the capital and know-how fromÂ 
developed countries to these countries, and then they can grow quite rapidly.
Obviously, in a world where labor is no longer the constraining factor,Â 
this mechanism no longer works. So is the hope basically toÂ 
rely on philanthropy from the people or countries who immediatelyÂ 
get wealthy from AI? What is the hope? Philanthropy should obviously playÂ 
some role, as it has in the past. But I think growth is always better andÂ 
stronger if we can make it endogenous. What are the relevant industriesÂ 
in an AI-driven world? I said we shouldn't build data centers inÂ 
China, but there's no reason we shouldn't build data centers in Africa.
In fact, I think it'd be great to build data centers in Africa.
As long as they're not owned by China, we should build data centers in Africa.
I think that's a great thing to do. There's no reason we can't build aÂ 
pharmaceutical industry that's AI-driven. If AI is accelerating drug discovery, thenÂ 
there will be a bunch of biotech startups. Let's make sure some of thoseÂ 
happen in the developing world. Certainly, during the transitionâ€”we canÂ 
talk about the point where humans have no roleâ€”humans will still have some role in startingÂ 
up these companies and supervising the AI models. So let's make sure some of thoseÂ 
humans are in the developing world so that fast growth can happen there as well.
You guys recently announced that Claude is going to have a constitution that's aligned to a set ofÂ 
values, and not necessarily just to the end user. There's a world I can imagine whereÂ 
if it is aligned to the end user, it preserves the balance of power we have in theÂ 
world today because everybody gets to have their own AI that's advocating for them.
The ratio of bad actors to good actors stays constant.
It seems to work out for our world today. Why is it better not to do that, but toÂ 
have a specific set of values that the AI should carry forward?
I'm not sure I'd quite draw the distinction in that way.
There may be two relevant distinctions here. I think you're talking about a mix of the two.
One is, should we give the model a set of instructions about "do this"Â 
versus "don't do this"? The other is, should we give the modelÂ 
a set of principles for how to act? It's kind of purely a practical andÂ 
empirical thing that we've observed. By teaching the model principles,Â 
getting it to learn from principles, its behavior is more consistent, it's easierÂ 
to cover edge cases, and the model is more likely to do what people want it to do.
In other words, if you give it a list of rulesâ€”"don't tell people how to hot-wireÂ 
a car, don't speak in Korean"â€”it doesn't really understand the rules, andÂ 
it's hard to generalize from them. Itâ€™s just a list of doâ€™s and donâ€™tâ€™s.
Whereas if you give it principlesâ€”it has some hard guardrails like "Don't makeÂ 
biological weapons" butâ€”overall you're trying to understand what it should be aimingÂ 
to do, how it should be aiming to operate. So just from a practical perspective, that turnsÂ 
out to be a more effective way to train the model. That's the rules versus principles trade-off.
Then there's another thing you're talking about, which is the corrigibility versusÂ 
intrinsic motivation trade-off. How much should the model be a kindÂ 
of "skin suit" where it just directly follows the instructions given to it byÂ 
whoever is giving those instructions, versus how much should the model have an inherentÂ 
set of values and go off and do things on its own? There I would actually say everything aboutÂ 
the model is closer to the direction that it should mostly do what people want.Â 
It should mostly follow instructions. We're not trying to build something thatÂ 
goes off and runs the world on its own. We're actually pretty far on the corrigible side.
Now, what we do say is there are certain things that the model won't do.
I think we say it in various ways in the constitution, that under normal circumstances, ifÂ 
someone asks the model to do a task, it should do that task. That should be the default. But ifÂ 
you've asked it to do something dangerous, or to harm someone else, then theÂ 
model is unwilling to do that. So I actually think of it as a mostlyÂ 
corrigible model that has some limits, but those limits are based on principles.
Then the fundamental question is, how are those principles determined?
This is not a special question for Anthropic. This would be a question for any AI company.
But because you have been the ones to actually write down the principles, IÂ 
get to ask you this question. Normally, a constitution is written down,Â 
set in stone, and there's a process of updating it and changing it and so forth.
In this case, it seems like a document that people at Anthropic write,Â 
that can be changed at any time, that guides the behavior of systems that are goingÂ 
to be the basis of a lot of economic activity. How do you think about howÂ 
those principles should be set? I think there are maybe three sizesÂ 
of loop here, three ways to iterate. One is we iterate within Anthropic.
We train the model, we're not happy with it, and we change the constitution.
I think that's good to do. Putting out public updates to theÂ 
constitution every once in a while is good because people can comment on it.
The second level of loop is different companies having different constitutions. I think itâ€™sÂ 
useful. Anthropic puts out a constitution, Gemini puts out a constitution, andÂ 
other companies put out a constitution. People can look at them and compare.
Outside observers can critique and say, "I like this thing from this constitutionÂ 
and this thing from that constitution." That creates a soft incentive andÂ 
feedback for all the companies to take the best of each element and improve.
Then I think there's a third loop, which is society beyond the AI companies and beyondÂ 
just those who comment without hard power. There we've done some experiments. A couple yearsÂ 
ago, we did an experiment with the Collective Intelligence Project to basically poll people andÂ 
ask them what should be in our AI constitution. At the time, we incorporatedÂ 
some of those changes. So you could imagine doing somethingÂ 
like that with the new approach we've taken to the constitution.
It's a little harder because it was an easier approach to take when theÂ 
constitution was a list of dos and don'ts. At the level of principles, it has toÂ 
have a certain amount of coherence. But you could still imagine gettingÂ 
views from a wide variety of people. You could also imagineâ€”and thisÂ 
is a crazy idea, but this whole interview is about crazy ideasâ€”systems ofÂ 
representative government having input. I wouldn't do this today becauseÂ 
the legislative process is so slow. This is exactly why I think we should be carefulÂ 
about the legislative process and AI regulation. But there's no reason you couldn't, in principle,Â 
say, "All AI models have to have a constitution that starts with these things, and then you canÂ 
append other things after it, but there has to be this special section that takes precedence."Â 
I wouldn't do that. That's too rigid and sounds overly prescriptive in a way that IÂ 
think overly aggressive legislation is. But that is a thing you could try to do.
Is there some much less heavy-handed version of that? Maybe.
I really like control loop two. Obviously, this is not how constitutionsÂ 
of actual governments do or should work. There's not this vague sense in which theÂ 
Supreme Court will feel out how people are feelingâ€”what are the vibesâ€”andÂ 
update the constitution accordingly. With actual governments, there'sÂ 
a more formal, procedural process. But you have a vision of competition betweenÂ 
constitutions, which is actually very reminiscent of how some libertarian charter cities people usedÂ 
to talk, about what an archipelago of different kinds of governments would look like.
There would be selection among them of who could operate the most effectivelyÂ 
and where people would be the happiest. In a sense, you're recreating thatÂ 
vision of a utopia of archipelagos. I think that vision has things to recommendÂ 
it and things that will go wrong with it. It's an interesting, in some waysÂ 
compelling, vision, but things will go wrong that you hadn't imagined.
So I like loop two as well, but I feel like the whole thing has got toÂ 
be some mix of loops one, two, and three, and it's a matter of the proportions.
I think that's gotta be the answer. When somebody eventually writes the equivalentÂ 
of The Making of the Atomic Bomb for this era, what is the thing that will be hardestÂ 
to glean from the historical record that they're most likely to miss?
I think a few things. One is, at every moment of this exponential, the extent toÂ 
which the world outside it didn't understand it. This is a bias that's often present in history.
Anything that actually happened looks inevitable in retrospect.
When people look back, it will be hard for them to put themselves in the placeÂ 
of people who were actually making a bet on this thing to happen that wasn't inevitable, that weÂ 
had these arguments like the arguments I make for scaling or that continual learning will be solved.
Some of us internally put a high probability on this happening, but there's a worldÂ 
outside us that's not acting on that at all. I think the weirdness of it,Â 
unfortunately the insularity of it... If we're one year or twoÂ 
years away from it happening, the average person on the street has no idea.
That's one of the things I'm trying to change with the memos, with talking to policymakers.
I donâ€™t know but I think that's just a crazy thing.
Finally, I would sayâ€”and this probably applies to almost all historical momentsÂ 
of crisisâ€”how absolutely fast it was happening, how everything was happening all at once.
Decisions that you might think were carefully calculated, well actuallyÂ 
you have to make that decision, and then you have to make 30 other decisions onÂ 
the same day because it's all happening so fast. You don't even know which decisions areÂ 
going to turn out to be consequential. One of my worriesâ€”although it's also anÂ 
insight into what's happeningâ€”is that some very critical decision will be some decisionÂ 
where someone just comes into my office and is like, "Dario, you have two minutes.
Should we do thing A or thing B on this?" Someone gives me this random half-page memoÂ 
and asks, "Should we do A or B?" I'm like, "I don't know. I have to eat lunch. Let's do B." ThatÂ 
ends up being the most consequential thing ever. So final question. There aren't tech CEOs who areÂ 
usually writing 50-page memos every few months. It seems like you have managed to buildÂ 
a role for yourself and a company around you which is compatible with thisÂ 
more intellectual-type role of CEO. I want to understand how you construct that.Â 
How does that work? Do you just go away for a couple of weeks and then you tell yourÂ 
company, "This is the memo. Here's what we're doing"? It's also reported thatÂ 
you write a bunch of these internally. For this particular one, IÂ 
wrote it over winter break. I was having a hard time findingÂ 
the time to actually write it. But I think about this in a broader way.
I think it relates to the culture of the company. I probably spend a third, maybe 40%, of my timeÂ 
making sure the culture of Anthropic is good. As Anthropic has gotten larger, it's gottenÂ 
harder to get directly involved in the training of the models, the launch of the models,Â 
the building of the products. It's 2,500 people. I have certain instincts, but it's veryÂ 
difficult to get involved in every single detail. I try as much as possible, but one thing that'sÂ 
very leveraged is making sure Anthropic is a good place to work, people like working there, everyoneÂ 
thinks of themselves as team members, and everyone works together instead of against each other.
We've seen as some of the other AI companies have grownâ€”without naming any namesâ€”we're startingÂ 
to see decoherence and people fighting each other. I would argue there was even a lot of thatÂ 
from the beginning, but it's gotten worse. I think we've done an extraordinarily goodÂ 
job, even if not perfect, of holding the company together, making everyone feel theÂ 
mission, that we're sincere about the mission, and that everyone has faith that everyoneÂ 
else there is working for the right reason. That we're a team, that people aren't tryingÂ 
to get ahead at each other's expense or backstab each other, which again, I thinkÂ 
happens a lot at some of the other places. How do you make that the case?Â 
It's a lot of things. It's me, it's Daniela, who runs the companyÂ 
day to day, it's the co-founders, it's the other people we hire, it'sÂ 
the environment we try to create. But I think an important thing in the culture isÂ 
that the other leaders as well, but especially me, have to articulate what the company isÂ 
about, why it's doing what it's doing, what its strategy is, what its values are,Â 
what its mission is, and what it stands for. When you get to 2,500 people, youÂ 
can't do that person by person. You have to write, or you haveÂ 
to speak to the whole company. This is why I get up in front of the wholeÂ 
company every two weeks and speak for an hour. I wouldn't say I write essays internally.Â 
I do two things. One, I write this thing called a DVQ, Dario Vision Quest.
I wasn't the one who named it that. That's the name it received, and it's one of theseÂ 
names that I tried to fight because it made it sound like I was going off and smoking peyote orÂ 
something. But the name just stuck. So I get up in front of the company every two weeks.
I have a three or four-page document, and I just talk through three or four differentÂ 
topics about what's going on internally, the models we're producing, the products,Â 
the outside industry, the world as a whole as it relates to AI and geopoliticallyÂ 
in general. Just some mix of that. I go through very honestly and I say, "This is what I'mÂ 
thinking, and this is what Anthropic leadership is thinking," and then I answer questions.
That direct connection has a lot of value that is hard to achieve when you're passingÂ 
things down the chain six levels deep. A large fraction of the company comes toÂ 
attend, either in person or virtually. It really means that you can communicate a lot.
The other thing I do is I have a channel in Slack where I just write a bunchÂ 
of things and comment a lot. Often that's in response to things I'm seeingÂ 
at the company or questions people ask. We do internal surveys and there are things peopleÂ 
are concerned about, and so I'll write them up. I'm just very honest about these things.
I just say them very directly. The point is to get a reputation of telling theÂ 
company the truth about what's happening, to call things what they are, to acknowledge problems,Â 
to avoid the sort of corpo speak, the kind of defensive communication that often is necessary inÂ 
public because the world is very large and full of people who are interpreting things in bad faith.
But if you have a company of people who you trust, and we try to hire people that we trust, thenÂ 
you can really just be entirely unfiltered. I think that's an enormousÂ 
strength of the company. It makes it a better place to work, it makesÂ 
people more than the sum of their parts, and increases the likelihood that we accomplishÂ 
the mission because everyone is on the same page about the mission, and everyone is debating andÂ 
discussing how best to accomplish the mission. Well, in lieu of an external DarioÂ 
Vision Quest, we have this interview. This interview is a little like that.
This has been fun, Dario. Thanks for doing it. Thank you, Dwarkesh.

</details>
