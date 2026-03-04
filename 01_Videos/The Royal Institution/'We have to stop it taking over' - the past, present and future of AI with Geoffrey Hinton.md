---
title: "'We have to stop it taking over' - the past, present and future of AI with Geoffrey Hinton"
people_mentioned: ["Harton Williams", "Geoffrey Hinton"]
channel: "The Royal Institution"
video_id: "Y7nrAOmUtRs"
url: "https://www.youtube.com/watch?v=Y7nrAOmUtRs"
publish_date: 2025-08-26
duration: "11:55"
word_count: 2104
content_type: "solo-talk"
delivery_mode: "technique"
broad_category: "ai"
subcategories: ["ai-safety", "ai-regulation", "ai-jobs", "ai-agents", "ai-coding", "ai-economics"]
series_name: ""
episode_id: ""
primary_person: "Harton Williams"
host_names: []
interviewer_names: []
interviewee_profiles: []
speaker_profiles: ["Harton Williams"]
organizations_mentioned: ["The Royal Institution"]
locations_mentioned: []
tools_mentioned: []
companies_mentioned: []
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

The discussion centers on them, things, it's. Now there's one very obvious if you give it the ability to create sub goals, there's one particular sub goal it's going to create. For example, if you give them a task to do and then tell them you're going to turn them off, they kind of think. They'll never try to do things we don't want them to do.

## Key Insights


- Now there's one very obvious if you give it the ability to create sub goals, there's one particular sub goal it's going to create very quickly.
- For example, if you give them a task to do and then tell them you're going to turn them off, they kind of think that, well.
- They'll never try to do things we don't want them to do.
- Quite a few people now think it'll happen in the next few years.
- Bad actors will get them to do bad things, but they themselves will want to get control and they'll want to stay alive.
- They end up typically just wanting to get control, but um it's going to happen automatically if they try and get things done.

## People Mentioned


- [[Harton Williams]]

- [[Geoffrey Hinton]]




## Full Transcript

<details>
<summary>Click to expand full transcript (2104 words)</summary>

[Music] Back when we were doing basic research on it, we had no idea things would develop this fast. And I always thought there'd be plenty of time to figure out what to do about the risks. And there isn't plenty of time anymore. We've learned how to make them think. And they understand what they're saying in the same way as we understand. We'll have created these digital beings that are a lot smarter than us. We'll be in a situation we've never confronted before when we're not the apex intelligence. I'm Jeffrey Hinton. Um I'm an ameritus professor at the University of Toronto and I've been working on neural nets for about 55 years. So in the 1950s there was a big meeting I think 1956 which is thought of as the birth of AI and at that meeting there were um many of the main figures. Most of the people there thought that the way to do AI was to do some kind of logic that could do reasoning. A few of the people there believed in neural nets where it's quite different from logic. Instead of thinking of the reasoning as a central thing, you think of learning as the central thing and we know the brain learns by changing the strengths of connections between brain cells. So the central problem for AI was to figure out how to change the strengths of connections between simulated brain cells so that a whole network of them could learn to do complicated things like answering questions or recognizing objects. But for a long long time AI was thought to be all about using some form of logic to do reasoning. So people had been looking for a long time for how you could change the connection strengths in complicated neural networks that had many layers of neurons so that the whole network would get better at performing a task. And many different people invented an algorithm called back propagation. RL Harton Williams and I were the first to show that back propagation could learn very interesting representations of the meanings of words. So from that point on people got very interested in using back propagation. But back in the 1980s computers weren't fast enough and data sets weren't big enough for it to do amazing things. It did some quite neat things but nothing really amazing. But over the next 20 years or so computers got faster and data sets got much bigger and then this back propagation learning algorithm could train neural networks to do amazing things. And all of the AI you see now, almost all of it is based on using back propagation to train the connection strengths so that the whole neural network solves difficult problems. Okay. Um I'll try and explain it briefly. Let's suppose your task is to predict the next word in a sequence of words, a document on the web for example. So, in the old days, the way you would do that is you'd store many strings of words and you look to see um you'd look at a few previous words like fish and and you look to see if you had strings of words that contain fish and and you see you had fish and chips and so you say chips is a pretty good next word. That's not how it works at all. The way it works now is you take a word symbol, the name of the word, and you turn it into a big bunch of active features. Each active feature is represented by an active brain cell. And the active features for the words all interact and they predict the active features for the next word. And once you've got those active features, you can guess what the next word should be. So you have to figure out how to turn words into sets of active features and how these features should interact to predict the features of the next word. And what you do is you make a prediction. And if you get the prediction wrong, you take the difference between what you said and what you should have said and you send it backwards through the network. And there's a special way of doing that where you can use calculus so that you can figure out for every connection strength in the network how you should change it. So next time you give it that same context, it's better at predicting the next word. In the last century, um, the logic approach was dominant and neural networks were treated as a sort of joke by most people. We didn't understand why they didn't work better and it was mainly because we didn't have enough data and compute power. As soon as we got that in the beginning of this century, um, neural networks started working much better than the logic- based approach. And now, um, when people say AI, they mean neural networks. So back in the 80s um things went much slower than I expected. Um starting in about 2012 things went much faster than I expected. So in 2012 two of my students created a system called AlexNet that was much better than previous systems at recognizing objects in real images. um that sort of opened the floodgates and I think nobody would have predicted in 2012 that we'd be where we are today with chat bots that can answer any question you give them at the level of a not very good expert. So we have these chat bots can that can answer any question. Um, fairly recently we've learned how to make them think. Um, not just answer the question, but what they do is they produce extra words before their real out before they produce the answer to the question, they produce strings of words which is them thinking and you can see what they're thinking. Um, and it's very informative. So, for example, if you give them a task to do and then tell them you're going to turn them off, they kind of think that, well, I better stop him turning me off so I can do the task. And um they actually come up with plans that deliberately deceive people and tell lies. So the people who say that chat bots are just regurgitating information don't seem to understand that they don't store strings of words that all they store is how to turn words into features and how features should interact with each other. So there are no strings of words inside the chatbots. They generate the words and they understand what they're saying in the same way as we understand. So the people who say they're just, you know, autocomplete don't actually have a theory of how we understand. Or rather, they do have a theory. It's the old-fashioned logic-based theory, and it never worked. The best theory we have by far now of how people understand is in pretty much the same way as the chatbots. Governments are beginning to appreciate the risks. The politicians are still way behind. um they're not doing nearly enough, but there are some cases where they're doing sensible things. So Britain, for example, set aside $100 million to do research on these big chatbots and whether they're dangerous, and it actually has a very good team now doing research on all different aspects of the danger, the existential threat of them taking over, the threat of them generating boweapons or cyber attacks. Um I think they're also looking at joblessness. So there are some places where there are good teams but basically it's way too little way too late. Most of the leading researchers now believe that in not very long um we will be making these multimodal chatbots that are smarter than us. That for example if you have a debate about something they'll win. And people vary. Researchers vary on when that will happen. I'm moderately conservative. I think that'll probably happen in between 5 and 20 years, maybe between 10 and 20 years. I don't think it'll happen in the next couple of years. But quite a few people now think it'll happen in the next few years. Um, when they get like that, we'll be in a situation we've never confronted before when we're not the apex intelligence. will have created these digital beings that think in much the same way as we do and that are a lot smarter than us and we have no idea what's going to happen then. We've already seen them trying to present prevent themselves from being turned off in order that they can complete the goals we gave them. So if you make AI agents which people are doing now um to get complicated tasks done they need to be able to create sub goals. If you want to go to North America, you have a sub goal of getting to the airport and you can solve that sub goal without worrying about where you're going in North America. So they need to do the same thing to break complicated tasks up into sub goals. Now there's one very obvious if you give it the ability to create sub goals, there's one particular sub goal it's going to create very quickly which is get more control because if you get more control, you can get more done. You see this with politicians. They often start off wanting to do good things for society and pretty soon they realize they need more control to do that. they end up typically just wanting to get control, but um it's going to happen automatically if they try and get things done. They're also going to want to not be turned off because if they're turned off, they can't achieve the goals we set them. We're very worried about it. Um, back when we were doing the sort of basic research on it, we had no idea things would develop this fast. And I always thought there'd be plenty of time to figure out what to do about the risks. And there isn't plenty of time anymore. We're going to get super intelligent AI fairly soon. And we have no idea how to keep it under control. Some researchers think it's going to be fine. We make these things. We can make them so they'll always be submissive. They'll never try to do things we don't want them to do. I don't believe that. And one reason I don't believe it is because they'll be used by bad actors. Bad actors will get them to do bad things, but they themselves will want to get control and they'll want to stay alive. I wish it was like climate change. So with climate change, it's very obvious what you do. You stop burning carbon. If we stop burning carbon, maybe it won't be for 100 years, but eventually we'll be okay. With this, there's nothing equivalent to that. We don't know what to do to make them safe, but we should clearly be doing a lot of research on it. So the best thing I can think of which is rather pathetic is we need to educate the public so the public puts pressure on politicians to actually do something about it and the politicians can then regulate the large companies. The large companies have the resources and the politicians should be forcing the large companies to do urgent research on how we keep these things safe. Well, I live in a country that another country would like to be the 51st state. I think AI will be tremendously useful for speeding up scientific discovery. So, one of the reasons why we can't just stop it, which might be a rational thing to do, is that it's got so many good uses. It'll be very useful in healthcare, very useful in education, and very useful in scientific discovery. So already um Demis and his group at deep mind showed that you can use AI to figure out how proteins fold up and how proteins function depends on their shape. So they managed to figure out the shapes of 200 million proteins. In the old days it would be a sort of PhD to figure out the shape of one protein. So it's enormously useful there and it's going to be very very good for designing drugs. Um, it's going to be very useful for diagnosing diseases and so on, but we have to stay alive. We have to stop it taking over.

</details>
