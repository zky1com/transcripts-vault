---
title: Intro to Agent Builder
people_mentioned: [Christina]
channel: OpenAI
video_id: 44eFf-tRiSg
url: "https://www.youtube.com/watch?v=44eFf-tRiSg"
publish_date: ""
duration: 5:30
word_count: 809
content_type: tutorial
delivery_mode: teaching
broad_category: ai
subcategories: [agents, workflow builders, product tutorials]
series_name: OpenAI
episode_id: 44eFf-tRiSg
primary_person: Christina
host_names: [Christina]
interviewer_names: []
interviewee_profiles: []
speaker_profiles: [Christina]
organizations_mentioned: [OpenAI]
locations_mentioned: []
tools_mentioned: [Agent Builder, Agents SDK, ChatKit, web search]
companies_mentioned: [OpenAI]
topics: [agent builder, workflow design, visual programming, travel agent demo]
tags: [ai, agents, agent-builder]
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

Christina introduces Agent Builder as a visual layer for designing, testing, and shipping multi-step AI workflows without starting in code. The tutorial shows a small travel assistant with a classifier and two specialized agents, using that example to argue that visual branching, structured outputs, widgets, and built-in evals make it easier to assemble and deploy agentic systems quickly while still leaving a path to export and integrate them into real products.

## Key Insights

- The product is framed as an all-in-one visual space for design, testing, and launch.
- The demo emphasizes specialization and routing rather than one giant general-purpose agent.
- Structured outputs are treated as the main way to make branching logic reliable.
- Widgets are used to enrich the output format when plain text is not enough.
- The product is positioned as fast to deploy but still compatible with code-based integration later.

## Claims

- [[Christina - Agent Builder lowers the barrier to creating agentic workflows by making them visual instead of code-first]]
- [[Christina - Specialized sub-agents plus a classifier are a practical way to improve agent behavior for mixed tasks]]
- [[Christina - Structured outputs are essential because they let visual workflows branch and pass state reliably]]
- [[Christina - Rich widgets matter when the agent's output needs to function like a product surface instead of plain text]]
- [[Christina - Visual workflow tools are most useful when they still leave a path to export code and ship into real products]]

## Full Transcript

<details>
<summary>Click to expand full transcript (809 words)</summary>

Hey everyone, this is Christina from OpenAI. Welcome to Agent Builder 101. Agent Builder is a new visual tool for building AI workflows. You connect nodes and create agents without writing any code. So you can start from templates or build your own from scratch. And it also comes with built-in eval so you can test and understand how your agents perform. When you're ready, you can export the workflow as code or drop it straight into your product. Basically, it's your all-in-one space to design, test, and launch AI agents visually and fast. So, today we're going to show you how to build your first agentic workflow, a helpful travel agent that will help you either build an itinerary or look up flight information. So, we're starting here in the OpenAI platform. Every workflow starts with a start node where you can set input variables or state variables. And today for the travel agent, the defaults are great. Next, I'll connect a classifier agent. I'm going to be building a specialized itinerary agent in addition to a specialized flight agent. And so, I want to first determine which agent I should route to. So, I'll call this classifier. So, you are a helpful travel assistant for classifying whether a message is about an itinerary or a flight. And here I'll specify the output format as JSON. And I'll add a property called classification which will have two options either flight info or itinerary. Great. Next, I'll add in an if else node um to branch based off of the classification. So if put pars.classification classification is flight info then we want to branch to the flight agent and otherwise we want to branch into the um the itinerary agent. So from the flight agent we'll create a new node and we'll call this flight agent. You are a travel assistant. always recommend a specific flight to go to. Use airport codes. And here I'll also give it access to web search so I can have the most up-to-date information about flights. Great. For the itinerary agent, I'll build um an itinerary agent with a new agent node. You are a travel assistant. So build a concise itinerary. Great. I think that's everything we need to get started with our travel agent. So here in run preview, I'll ask it what should I do in a day in Tokyo. And I can see the message going through the workflow that we just created. going through the classifier agent, deciding which category it should go to, seeing that I asked about an itinerary, and then passing it on to the itinerary agent, whereas come up with a concise one-day itinerary for Tokyo. Looks like a great day. Now, for the flight agent, I actually want a richer experience for showing flight information instead of just plain text. And so, I can do that by going and building a widget in our widget studio. Here I've actually already designed um a widget for showing flight information to go from one location to the next with um all the details about the flight. So I can just click download um to download this entire template and then bring that directly to the agent um that we just created here. I'll add it in as the widgets output format. I'll upload this flight widget that we just pulled. Preview it. Everything looks great. And I actually want this to be a bit more customized. Um, and so I will tell it to choose a background color creatively based on the destination. And I'll also ask it to include time zones A.M. or PM. Great. Let's test it out. SFO to Tokyo on October 7th. So here again, we see it moving through the classifier agent um determining whether I'm asking about um a flight or an itinerary, deciding that I'm asking about a flight agent um or deciding that I'm asking about a flight, searching the web, finding a flight for me, and then showing it to me in this rich interactive way. In this case, it's decided that yellow is the color of Tokyo. Um, and so showed that as the background color. Great. So I've now built an agent that I'm happy with and I can publish it directly. Let's call it travel agent here. And I now have a fully deployed agent that is ready to go. Um, I can either use the agents SDK. And here you can see that this is quite a bit of code um for me to manage myself or I can simply take this workflow ID and put it in my product directly using jacket. So that's all. Hope that was helpful and please leave any feedback in the comments and don't forget to subscribe to OpenAI devs for more product updates. Thank you.

</details>

