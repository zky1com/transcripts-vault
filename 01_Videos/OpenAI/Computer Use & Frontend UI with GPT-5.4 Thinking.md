---
title: Computer Use & Frontend UI with GPT-5.4 Thinking
people_mentioned: [SQ, Nancy]
channel: OpenAI
video_id: YICiHiU2GBU
url: "https://www.youtube.com/watch?v=YICiHiU2GBU"
publish_date: 2026-03-05
duration: 3:03
word_count: 617
content_type: product_demo
delivery_mode: demo
broad_category: ai
subcategories: [computer use, frontend development, multimodal ai]
series_name: OpenAI
episode_id: YICiHiU2GBU
primary_person: SQ
host_names: [SQ]
interviewer_names: []
interviewee_profiles: []
speaker_profiles: [SQ]
organizations_mentioned: [OpenAI]
locations_mentioned: []
tools_mentioned: [Codex, GPT-5.4 Thinking, computer use, image generation]
companies_mentioned: [OpenAI]
topics: [computer use, frontend ui, self-checking, image-driven development]
tags: [ai, frontend, computer-use]
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

SQ presents GPT-5.4 Thinking as a model that is materially better at checking its own app-development work through persistent computer use and image-based comparison. The demo ties two capabilities together: interacting with software the way a human would through a live UI, and using design images plus image generation to create and then visually verify front-end work, making development cheaper, faster, and more reliable.

## Key Insights

- The demo treats self-checking as a primary product capability rather than a side effect.
- Persistent computer use is presented as a way to lower token cost while improving testing realism.
- Frontend fidelity depends on the model being able to compare rendered output against a visual target.
- The model is shown generating assets concurrently to improve end-to-end efficiency.
- The chess and coffee-shop demos both frame UI interaction as necessary for validating human-facing software.

## Claims

- [[SQ - Models need to be good at checking their own work because building software for humans requires validating real user-facing behavior]]
- [[SQ - Persistent computer use can make testing cheaper and more efficient because the model does not need to recreate a fresh environment every time]]
- [[SQ - Strong computer-use models can test complex interactive apps by manipulating the UI instead of relying only on code-level assumptions]]
- [[SQ - Image-based website building improves when the model can use design context to generate and choose assets that fit the intended aesthetic]]
- [[SQ - Frontend replication gets more reliable when the model can compare the target image and the built site side by side using computer use]]

## Full Transcript

<details>
<summary>Click to expand full transcript (617 words)</summary>

We want models to be like really good at checking its own work, especially as the things we ask our models to build become more complex. My name is SQ and I work on training the models to be better at web development, app development, anything that really requires some sort of user experience. Today we're talking about the launch of our new model GP 5.4 thinking and two of its app development related capabilities. One, it's it ability to use kua or computer use. And two, it's its ability to make great websites using an image input. When we ask the model to use kua compared to 5.3 codecs, it doesn't have to spin up like a new environment to do it. It's more like how URI would interact with a computer. With persistent kua, we're seeing in some cases when we ask the model test work that the token use has actually dropped by 2/3, which is quite exciting. So, I brought some examples to show today. I'm going to open Codeex. I'm going to use GPD 5.4 Thinking and I'm going to use the high reasoning level build and test a 3D chess game uh electron app. I'm going to add just a little bit of more of a challenge for the model as well and ask it to make two effects, glass and marble. It's cooking. This is a challenging use case for KUA because there's so many pieces. You have to click the right pieces. Are like reflections working? The model needs to have a good sense of like all the rules and then how like manipulating those pieces will lead to a state where you can actually test out those rules. Like castling for instance, right? Where do you drag the king or the rook to get it to the right place where it'll actually castle correctly? That was castling that just happened. That was on what was it doing now? So Kua is clicking through the game and moving the pawn on the other side. It's actually playing the game. We're building software for humans to use and humans use software with user interfaces and so we want the model to be able to check its own work like a human would. The second thing I want to talk about is website replication and in particular image gen and image search. My partner Nancy has always wanted to start her own coffee shop. She's not a coder and so she gave me a design that she wanted for a website and we're going to use codeex and 5.4 thinking to make that into a reality. For this example, I'm using codecs, but it works just as well in chat GPT. The model is better able to understand the context of the design, like what kind of uh images that actually would be most appropriate given the style and will prompt image genen to make images that are more in line and aesthetically cohesive. So, right now it's calling the image genen tool and it has a smart use of image gen as well because images take a while to generate. So, it's actually doing all four of these images concurrently, which is pretty neat. Now the model is able to check its own work using Kua. What KUA did here is like open up the image, inspect it, open up the website, also look at it, compare them side by side, and make sure that the website created is as close as possible to the image that put. With this update, it makes the work a lot cheaper, a lot more efficient, and also ultimately helps you do better work.

</details>

