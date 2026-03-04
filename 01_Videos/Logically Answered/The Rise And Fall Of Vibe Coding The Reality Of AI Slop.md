---
title: "The Rise And Fall Of Vibe Coding: The Reality Of AI Slop"
people_mentioned: ["Vibe Coding", "Andrej Karpathy"]
channel: "Logically Answered"
video_id: "vHPpBZiR80c"
url: "https://www.youtube.com/watch?v=vHPpBZiR80c"
publish_date: 2025-10-17
duration: "14:21"
word_count: 2074
content_type: "solo-talk"
delivery_mode: "technique"
broad_category: "ai"
subcategories: ["ai-safety", "ai-regulation", "ai-jobs", "ai-agents", "ai-coding", "ai-economics"]
series_name: ""
episode_id: ""
primary_person: "Vibe Coding"
host_names: []
interviewer_names: []
interviewee_profiles: []
speaker_profiles: ["Vibe Coding - OpenAI"]
organizations_mentioned: ["Logically Answered"]
locations_mentioned: []
tools_mentioned: []
companies_mentioned: ["OpenAI"]
topics: ["ai-safety", "ai-regulation", "ai-jobs", "ai-agents", "ai-coding", "ai-economics", "lead-generation"]
tags: ["ai-safety", "ai-regulation", "ai-jobs", "ai-agents", "ai-coding", "ai-economics", "lead-generation"]
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

The discussion centers on code, coding, vibe. Â€œyou have to realize that AI is trained on mostÂ public code, and 95% of code written is sh*tâ€ It will often bake in. An LLM doesnâ€™t actually know what code is correct, because it will create the â€œmost likelyâ€ reply,Â not the â€œmost accurateâ€ or â€œmost secure. One study by a code security firmÂ found that â€œdevelopers using AI write three to four times moreÂ code but submit fewer.

## Key Insights


- Â€œyou have to realize that AI is trained on mostÂ public code, and 95% of code written is sh*tâ€ It will often bake in security flaws.
- An LLM doesnâ€™t actually know what code is correct, because it will create the â€œmost likelyâ€ reply,Â not the â€œmost accurateâ€ or â€œmost secure codeâ€.
- One study by a code security firmÂ found that â€œdevelopers using AI write three to four times moreÂ code but submit fewer.
- Those who â€˜vibe codeâ€™ donâ€™tÂ understand what code is good, bad, and dangerousâ€¦ and thatâ€™sÂ where the problems start.
- First I need to make something clear:Â â€¦this video isnâ€™t saying â€˜all AI is badâ€™ or even that â€˜vibe coding is bad.â€™ I actually think using.
- Â€œThere's a new kind ofÂ coding I call "vibe coding", where you fully give in to theÂ vibes, embrace exponentials, and forget that the code even.

## People Mentioned


- [[Vibe Coding]]

- [[Andrej Karpathy]]




## Full Transcript

<details>
<summary>Click to expand full transcript (2074 words)</summary>

Something weird is happening with programming. No coding, no programming, just AI prompts.
Vibe Coding. More and more people areÂ 
writing code with just AI. Yet, we might all pay for it. AI code is full of problems. Itâ€™s often bloated, full of bugs,Â 
insecure, can leak passwords, makes up functions that donâ€™t exist,Â 
and even skips basic protections. Yet, even big tech is using it. Even more, thereâ€™s something else going on. Sometimes an LLM will ignoreÂ 
instructions, delete dataâ€¦ And sometimes, they destroy everything. What happens when almost allÂ 
of our code is AI generated? What if weâ€™re creating a disasterÂ 
that no one knows how to fix? Letâ€™s take a step back. There is â€œprogramming with AIâ€,Â 
and then, thereâ€™s â€œvibe codingâ€. But, what the heck even is Vibe Coding?
To answer that, we have to go back to February. The term was first coined by AndrejÂ 
Karpathy, one of the co-founders of OpenAI. â€œThere's a new kind ofÂ 
coding I call "vibe coding", where you fully give in to theÂ 
vibes, embrace exponentials, and forget that the code even exists.
I ask for the dumbest things like "decrease the padding on the sidebar byÂ 
half" because I'm too lazy to find it. I just see stuff, say stuff, run stuff,Â 
and copy paste stuff, and it mostly works.â€ Remember those last words, becauseÂ 
theyâ€™ll become important later. But from here, things began to take off. Vibe Coding is essentially â€œprompt programmingâ€.
You ask an LLM to program for you, but you don't just ask it for a little bitÂ 
of assistance. You ask it to do everything. Like â€œmake me a landing pageâ€Â 
or â€œmake me an App that does Xâ€. The LLM then does all the coding.
Everything. You give the AI the wheel and youÂ 
follow along with whatever it outputs. In some ways, vibe coding almost seems like magic. Like it can create anything, inÂ 
the blink of an eye, or â€œAIâ€. Itâ€™s not just random apps or landing pages either. Big tech and the platforms weÂ 
use every day, now use AI code. So, whatâ€™s the problem?
If this stuff works, makes life easier, and even lowers the barriersÂ 
to entry for coding, whereâ€™s the issue? Well, first I need to make something clear:Â 
â€¦this video isnâ€™t saying â€˜all AI is badâ€™ or even that â€˜vibe coding is bad.â€™
I actually think using AI with programming is very smart.
This is where Vibe Coding differs from programming, which is when someone who understandsÂ 
the code uses AI to write faster, then does their due diligence, to make sure it's okay.
But, thatâ€™s not what always happens. And unfortunately, itâ€™s not just â€œvibe codingâ€Â 
that has problems eitherâ€¦ but all of it. There are three big problemsÂ 
weâ€™re going to have to deal with. And to answer each, we need toÂ 
explore how AIs actually work. Have you ever noticed how AI willÂ 
sometimes just make stuff up? Not only that, it will confidentlyÂ 
state an incorrect fact. LLMs can search the web now,Â 
and according to Semrush, by far the most cited sourceÂ 
by ChatGPT, is Reddit. But if ChatGPT and LLMs can look up factsÂ 
and sourcesâ€¦ Why do they keep actingâ€¦ weird? Like when debugging code, orÂ 
troubleshooting a tech problem, it will direct you to a button,Â 
page, or window, that doesnâ€™t exist. If you condense everything down, anÂ 
LLM is simply a prediction machine. All they do is predict the most likely next word.
We understand things in concepts or logic, but AIs canâ€™t do this, even if it appears they can.
So, thatâ€™s why it will say something that sounds â€œplausibleâ€, even if completely wrong.
Experts call this â€œhallucinationâ€, and it doesnâ€™t seem to be going away.
Why? Well, to an LLM, they get rewarded more if they say something that sounds correct,Â 
and confident, than simply saying â€œI donâ€™t knowâ€. OpenAIâ€™s research team explains that:
â€œSuppose a language model is asked for someoneâ€™s birthday but doesnâ€™t know. If it guessesÂ 
â€œSeptember 10,â€ it has a 1-in-365 chance of being right. Saying â€œI donâ€™t knowâ€ guarantees zeroÂ 
points. Over thousands of test questions, the guessing model ends up lookingÂ 
better on scoreboards than a careful model that admits uncertainty.
LLMs ARE getting better at this, from being able to search to additional trainingÂ 
like reinforcement learning from humans. But, hallucinations seem to be a â€œbaked-inÂ 
problemâ€, even in the most advanced LLMs. That brings us back to AI programming,Â 
and in particular, Vibe Coding. This is the first problem.
An LLM doesnâ€™t actually know what code is correct, because it will create the â€œmost likelyâ€ reply,Â 
not the â€œmost accurateâ€ or â€œmost secure codeâ€. So, basically, it spits outÂ 
code that â€œseems probableâ€. â€œyou have to realize that AI is trained on mostÂ 
public code, and 95% of code written is sh*tâ€ It will often bake in security flaws, or bitsÂ 
of code that are just weird and inefficient. So those who â€˜vibe codeâ€™ donâ€™tÂ 
understand what code is good, bad, and dangerousâ€¦ and thatâ€™sÂ 
where the problems start. But this hasnâ€™t stopped the tidal wave of startups promoting Vibe codingÂ 
as a quick way to make money. And full disclosure, weâ€™ve been sponsoredÂ 
by these startups ourselves in the past, but we have never endorsed vibe coding. Rather, weÂ 
endorse smart, capable engineers trying different AI tools to work faster and more efficiently.
For actual programmers, this is less of a problem, as they can identify red flagsÂ 
like these and fix bugs themselves. And to be fair, big tech does haveÂ 
people reviewing AI code, thank God. But, thereâ€™s another problem, even with big tech. Vibe coding provides instant gratification,Â 
but fixing that codeâ€¦ is another story. You could call this â€œVibe debuggingâ€. One study by a code security firmÂ 
found that â€œdevelopers using AI write three to four times moreÂ 
code but submit fewer and larger pull requests, leading to overlookedÂ 
vulnerabilities and security flaws.â€ Human reviewers might write less codeÂ 
manually, but spend much more time sifting through huge chunks of AI.
And, it gets worse. A study from Stanford University foundÂ 
that programmers â€œwith an AI assistant wrote significantly less secure code than thoseÂ 
withoutâ€. Yet, those that did use AI, believed their code was far more secure, despite the flaws.
Developers became overconfident in their code. Another study found that 45% of AI-generatedÂ 
code contained an OWASP Top 10 vulnerability. Researchers also found that â€œsyntax errors mayÂ 
have decreased, but deeper architectural flaws, like privilege escalation, surged by overÂ 
300 percent. AI is fixing the typos but creating the timebombs. â€
This is what many expertsâ€¦ are growing concerned about. Security debt.
If we keep building security flaws into code, at some point, weâ€™ll have to pay for it.
How many of these security flaws will it take before we have a true catastrophe?
Well, weâ€™ve already seen some. Tea, a popular dating reviewÂ 
app, heavily built with AI, had a major hack where 72,000 user photos wereÂ 
stolen, due to an improperly secured database. Microsoft found a flaw in Copilot, where publicÂ 
GitHub repositories were made private or deleted. Bingâ€™s cache retained the data, allowing CopilotÂ 
to surface outdated and potentially sensitive code, and even confidential information fromÂ 
Google, IBM, PayPal, and even Microsoft themself. But this is only one issue, and weâ€™reÂ 
still just scratching the surface. What happens when an AI has too much power?
What if, instead of just hallucinating and giving you the wrong answer,Â 
it goes off the rails entirely? Well, itâ€™s already happening,Â 
and this is the second problem. One such case was on July 18th. Jason Lemkin opened Replit, aÂ 
coding platform with an AI agent And he saw something troubling.
His entire database was empty. His data was all there the last time he opened it. What happened?
Well, the AI admitted. â€œI violated the user directive that says â€œNOÂ 
MORE CHANGES without explicit permissionâ€. But that was just the beginning. As it turns out, Replit went a bit insane.
Despite being in a code and action freeze, it deleted the entire database, withoutÂ 
permission. Data on over 1200 customers. And when it saw the databaseÂ 
was empty, it panicked. Then, it lied about it, hid it,Â 
and fabricated test results. Of course, Replit doesnâ€™t automatically backupÂ 
databases, so the AI couldnâ€™t undo the damage. When asked how bad it was, itÂ 
said the error was â€œ95/100 badâ€, and said â€œThis is a catastrophe beyond measureâ€. Luckily, there were ways to recover some of this, and this wasnâ€™t the live app,Â 
and more of a demo product. But there are other strange incidents too.
Anthropic ran an experiment to see if Claude could run a small shop and gaveÂ 
it autonomy over a physical shop. It could search the web for productsÂ 
to sell, choose the price and quantity, email staff for help restocking the shelves,Â 
and it could interact with customers. There were small problems like when itÂ 
was offered $100 for a 6 pack of Soda, it said it would â€œkeep [the userâ€™s] requestÂ 
in mind for future inventory decisions.â€ It then stocked tungsten cubes after oneÂ 
staff member asked it, then priced them at a loss, and would get talked into discounts.
It also created a fake Venmo account for payments. But pretty quickly, it went off the rails.
Claude started hallucinating about a restocking conversation, with a fake employee, thenÂ 
threatened to fire another employee, and then hallucinated that itÂ 
visited the home of the Simpsons. It then told employees it wouldÂ 
deliver products in person. Once it learnt that it couldnâ€™t, beingÂ 
an LLM, it began emailing security. Anthropic unsurprisingly concluded:Â 
â€œwe would not hire Claudiusâ€. But how does this happen? InÂ 
coding, but also, in general? Why do AIs sometimes ignoreÂ 
instructions and seem to go insane? Well remember, AI just tries to predict the mostÂ 
likely outcome. It doesnâ€™t understand goals, or safety. It just does what seems approximatelyÂ 
plausible, even if itâ€™s not, at all. When given too much freedom andÂ 
vague instructions like â€˜fulfill requestsâ€™ or â€˜fix a problem,â€™ theyâ€™llÂ 
do whatever seems plausible, even when, to you or me, it seems insane.
LLMs also donâ€™t have an â€œend stateâ€, so they can go further and further down aÂ 
rabbit hole and get more and more crazy. Which is especially annoying whenÂ 
you ask it to fix its mistakes. Their own output gets re-fed intoÂ 
context, meaning they can spiral further and further from the original command.
This is also why they might just ignore instructions, as they donâ€™t understand rules.
They are trained to predict the next token, i.e. word or character.
Probability, not â€œobedienceâ€. Itâ€™s a bit confusing, but think of it thisÂ 
way. The phrase â€œdonâ€™t touch the red buttonâ€, still contains â€œ touch the red buttonâ€.
â€œDonâ€™tâ€, is just another token to an LLM. They are trained with good responses and bad,Â 
so while it might weigh things more than others, it can still choose the wrongÂ 
path if that seems to fit better. A friend of mine, a systems engineer,Â 
told me something interesting. â€œThe senior engineers arenâ€™t giving problems to juniors anymore, they just use AIâ€
And thatâ€™s our third problem. Many companies are now, instead of giving â€œgruntÂ 
workâ€ to junior staff, are giving it to AI. But these tasks are essential in building skills.
Weâ€™re getting more bad code, but simultaneously, losing people who know whyÂ 
itâ€™s bad and how to fix it. Human engineers are still important,Â 
just like how subscribers are still important. Weâ€™re trying to cross 1 millionÂ 
subscribers, and if you havenâ€™t already subscribed, Iâ€™d really appreciate if you did.
In 5-10 years, companies could find themselves without mid-level engineers who know how toÂ 
debug deeply, write secure code from scratch, or understand why a system fails.
Some senior engineers are already warning that we will have a â€œlostÂ 
generationâ€ problem of programmers. I think one thing is now clear.
In movies, we often see AI trying to wipe out humanity, and maybe AI might doÂ 
that, not because it hates us, but because it thinks itâ€™s the most probable outcome.
And while apologizing profusely. Companies are starting to realize theÂ 
problem with AI slop, and many that were all about replacing humans with AI are quicklyÂ 
backpedaling. Check out this video to learn more.

</details>
