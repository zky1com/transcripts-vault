---
title: Using OpenAI Codex CLI with GPT-5-Codex
people_mentioned: [Roma, Eson]
channel: OpenAI
video_id: iqNzfK4_meQ
url: "https://www.youtube.com/watch?v=iqNzfK4_meQ"
publish_date: ""
duration: 5:43
word_count: 1103
content_type: tutorial
delivery_mode: demo
broad_category: ai
subcategories: [coding agents, cli tools, developer workflow]
series_name: OpenAI
episode_id: iqNzfK4_meQ
primary_person: Roma
host_names: [Roma]
interviewer_names: [Roma]
interviewee_profiles: [Eson]
speaker_profiles: [Roma, Eson]
organizations_mentioned: [OpenAI, Vercel]
locations_mentioned: []
tools_mentioned: [Codex CLI, GPT-5-Codex, ChatGPT, Vercel]
companies_mentioned: [OpenAI, Vercel]
topics: [terminal workflow, sandboxing, model switching, deployment]
tags: [ai, codex, cli]
pipeline_stage: video_only
claims_status: done
speech_status: pending
world_status: pending
evidence_status: pending
claims_count: 5
speech_evidence_count: 0
world_evidence_count: 0
evidence_count: 0
batch_id: ""
last_processed_at: "2026-03-19"
---

## Summary

Roma and Eson demo Codex CLI as a terminal-based interface for GPT-5-Codex that can plan, edit, inspect, and deploy software tasks with varying levels of autonomy. The walkthrough argues that the CLI is not only useful for direct coding but for broader developer operations like planning, log inspection, deployment, and context-dependent model selection, with sandbox controls and transcript views helping users choose how much detail and freedom they want the agent to have.

## Key Insights

- The demo presents Codex CLI as an agent workflow surface, not just a command wrapper.
- Model selection and reasoning level are treated as practical workflow controls rather than niche expert settings.
- Approval modes are central because the tool balances productivity against sandbox boundaries.
- Web search is positioned as a way to keep coding tasks grounded in current external documentation.
- The multiplayer game example is used to show that the same interface can move from planning to implementation to deployment quickly.

## Claims

- [[Eson - GPT-5-Codex is useful because it can handle both fast simple tasks and much longer coding tasks in the same workflow]]
- [[Eson - Transcript mode matters because users sometimes need visibility into the agent's process rather than only the final output]]
- [[Eson - Sandbox approval modes are important because coding agents need different trust boundaries for different kinds of work]]
- [[Roma - Codex CLI is broader than coding assistance because it can support operational tasks like debugging, deployment, and infrastructure investigation]]
- [[Eson - Web search is important in Codex CLI because some coding tasks depend on the latest external documentation rather than only local repo context]]

## Full Transcript

<details>
<summary>Click to expand full transcript (1103 words)</summary>

Hey, what are you working on? I'm trying to find a good demo. Something that Codex can modify. We could make this little ball thing multiplayer. That sounds very cool. Let's do it. Codeex CL164. Mark. Hey everyone, Roma here. Recently, we ship GP5 and GP5 codecs and we've also released a ton of improvements to Codex CLI to better harness the agentic coding capabilities of these models. And today I'm sitting with Eson who led a lot of this effort on the CLI. Do you want to give us a quick tour? Yeah, I'd love to. Um, we have tons of really cool updates. You can install it really easily with either mpm or brew and log in with your chat GPT account. So here you're in your terminal and you just have to launch it with by codex. That's all there is to it. So we'll say make a plan for making this game multiplayer. What's funny is like this game was one of the very many examples we shipped completely built by GPT5 in one prompt. Yes. Like and now we can start building up upon it. So what it's thinking tell us a little more like about what's happening which model you're using here. Yeah. So this is uh going to be GPT5 codeex which is our new model and it's really good for any sort of coding task. So here it's like currently crafting the plan. I see it's laying out the steps of what it's supposed to do. Yep. Can you expand what's happening here? Yeah, totally. So, we can go into transcript mode with control T and that gives you things that are super useful like the uh the chain of thought, the sort of the exact code that it's doing. If you don't not interested into the the whole details, you can just like let it uh run at a very high level telling you like what it's doing. Yes, exactly. Okay. So, while it's working on this like kind of multiplayer feature, why don't you kind of open up a second codeex to give us maybe a quick tour of some of your favorite commands? Yeah, so I'm a huge fan of the model switcher. You sometimes want to use one model for one thing, one model for another. This allows you to change the reasoning level, right? Because with the new GP5 codeex model, the very simple task can go very fast. Yes. But for the more advanced one, now Codex can work on for like up to hours at a time. Okay. So that's SL model. What else? Yeah. Uh approvals is really useful. So this is where you kind of get into the sandboxing features of codecs which are very cool, very powerful. We have three modes. We have read only, we have auto, and we have full access. Auto is the default. And that allows codeex to read files and make changes to files within the current directory. So by default, it stays in the boundaries of your project. It's not going to affect anything else on your laptop. Exactly. And then if you want to be in readon, that's kind of useful for, for example, running outside of a git repository. Y or if you're like, I only care about planning. I actually don't want Codex get distracted by trying to edit things. And then we have Codex resume. And that allows you to pick up from any previous session. Super nice. Why don't you uh go check back on the status of this multiplayer game? Yeah, it looks like we've got a plan. So why don't we tell Codeex to do that? Great. So one of the things that I think is really interesting that people sort of miss about Codeex is that it's useful for these coding tasks, but you can also deploy things with it. You can use it for S sur type things. You can figure out like, oh, we're seeing these, you know, this bug show up for our users. Why is this showing up? Go look at the logs. Um, take these disparate data sources, combine them. Um, it's surprisingly very, very, very good at that sort of thing. How are we doing on the game? Yeah, I think the game is probably good to go. So, it sounds like the the moment of truth is to play the game, but maybe before we need to deploy it. Yeah. So what I'm going to say for this app, let's maybe uh deploy it on Versal. Yep. And let's use code- search in order to tell it to hey look up the latest versal docs. Yeah. In case like you want to deploy something very specific and you need persistence or maybe you want to look up the latest changes of like an API. Yeah, exactly. We should go to approval. We should switch it to full access. And then we'll tell it use the Versel command line tool to deploy this app. Cool. Sounds like it's deployed. Yeah, let's do it. Should we try it? Yeah, let's give it a shot. So, I guess I can take over this laptop. If you want to bring yours, I'm going to have to ping you the link. Yep. There you go. You should have it. Ready to start. Let's go. Oh my god, this is awesome. We are really in sync. Yeah, super in sync. Incredible. This is all real time. Who's going to be the best at this? I don't know. You seem pretty good. Ah, okay. To wrap us up, what have we seen? So, we saw Codex CLI logged into your chat GPD subscription starting to like change a game. Yep. Make a plan to implement like a full multiplayer game. Yep. We saw a quick tour of the commands, but more interestingly, you use web search to kind of like fetch information from the internet. You change approval modes. We deployed this game and we're now able to to play it. Yeah, it's super easy. This is the exact same flow that I use to, you know, do pretty serious stuff just across like a wide variety of languages, a wide variety of frameworks, wide variety of projects. Amazing. Well, as you can tell, we're shipping a ton of improvements across all codec surfaces. So you can have this AI teammate at your disposal wherever you work and in this case right in the terminal. And we can't wait to see what you build with Codex CLI. See you next time.

</details>

