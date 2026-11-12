---
title: "The AI Chip Race with Apple’s Former Chief Chip Architect | Power On with Mark Gurman"
people_mentioned: []
channel: "Bloomberg Television"
channel_id: "UCIALMKvObZNtJ6AmdCLP7Lg"
video_id: "Nh8aIlyivRY"
url: "https://www.youtube.com/watch?v=Nh8aIlyivRY"
publish_date: 2026-11-12
publish_timestamp_utc: "2026-11-12T17:09:13Z"
duration: "39:01"
duration_seconds: 2341
views_at_import: 1229
transcript_language: "en"
has_captions: null
transcript_status: "done"
word_count: 6694
content_type: ""
delivery_mode: ""
broad_category: ""
subcategories: []
series_name: ""
episode_id: ""
primary_person: ""
host_names: []
interviewer_names: []
interviewee_profiles: []
speaker_profiles: []
organizations_mentioned: []
locations_mentioned: []
tools_mentioned: []
companies_mentioned: []
topics: []
tags: []
---






## Full Transcript

<details>
<summary>Click to expand full transcript (6694 words)</summary>

Welcome to Power On. We talk about Apple
and the consumer tech industry. I'm Mark Gurman. And today we have a very interesting conversation
and a very special guest, Gerard Williams III. Joining us to talk about the
AI data center boom, what he's building at his new startup
Nuvia core, what he built at Nuvia and Qualcomm,
and of course, what he did at Apple as the chief architect
on their CPU technology. He worked on chips
starting from the A7, the first 64 bit Apple processor,
all the way up to the Apple M1 chip. We get into his time there,
we get into his thoughts on John Ternus and Johny Srouji, and what it was like
when he first came up with the idea. Almost two decades ago to build, server side CPU at Apple. And stay tuned till the end. We have another round of Apple trivia. So Gerard Williams III. So glad to have you here. Just to give some background
to to those listening. Gerard has had an amazing career,
and there's probably
no one better to talk to right now. About the AI data center boom, the silicon industry
and all of that coming together. Gerard, you know, as
you may be interested, if you're listening to this podcast,
he worked at Apple for a long time. Most recently, he was a senior director,
in charge of CPU work, platform work. He worked all the way up to the M1 chip. He worked on the A7 chip and newer. And so he was there from
not at the very beginning, but pretty close to the start
of this Apple silicon journey. Apple making its own chips for the iPad, for the iPhone
and the watch and the AirPods. And so forth. And after that, he went to start a company called Nuvia, which made cloud silicon. It was acquired by Qualcomm
and most recently he left Qualcomm, where he was a senior VP,
to start a new company called Nuvia Core. So Gerard,
thanks for joining the Power On podcast. Thank you so much for being here. And good to have you, man. Oh, no. It's, wonderful to finally get a chance
to, talk to you one on one. Well, let's let's talk about nouveau core. I want to dive in to exactly
what are you building today, and how does your learnings
from Apple and Nuvia and TI and Arm, how did that all come together
into what you're doing? And why is this something
that you couldn't build at Apple? Why is this something
you couldn't build at Qualcomm? Why did this require a new company? Yeah. So, Newton knew the core journey started
actually, in early April of this year. It was an opportunity to, take advantage of the explosion of AI
that we're seeing today. And bring CPU to bear to the market. That's that's
one of the interesting things that we are seeing in in
today's times that the large language models themselves are, utilizing GPUs, accelerators, AI engines themselves. And they've exposed what I've always,
I believe, to be there
since the beginning of my career. That CPU is an element that's front and center in the data
center, has been for some time. And, those high performance
CPUs are necessary in order to enable, like these large language models
to do their work. They orchestrate memory, they orchestrate, the security aspects, and do some of the fundamental work, and pretty much single
threaded performance as a predominant element of that CPU
that makes it great and efficiency. And throughout my career,
that's been something that I've tried to do
every step of the way is to bring, high performance compute to every platform
that I was able to partake in. And new a core is, beginning that journey
as we and it's, it's it's, performing that journey as we speak today,
but everyone is all in on GPUs. Obviously. Nvidia has talked up
GPUs. Everyone's talking about GPUs. And so what was the the moment
where you decided we're going to do CPUs instead and leave the GPUs to others? There wasn't for me, actually. There wasn't a magical moment that I said,
I'm going to leave GPU behind, and focus on CPU. CPU has been something that I have focused on almost
since the beginning of my career. Very early day one. I've always believed that, that compute, and the CPU that you build
has the ability to scale, and that's one of,
nova core fundamental, testaments is that we want to build a great core,
we call it our core first technology. It's basically focusing on the fundamental, capabilities of a CPU,
what it offers, how it explores,
the fundamentals of an OS. And we want to bring
really solid performance to the end user and to the data center,
which is what LMS today are mandating. Can you get a little bit nerdy
and technical on this exact first product that you're building this exact chip,
like, how many cores are we talking about? What are the technologies? What instruction set are you using? I know there's been some talk that you're trying to lock in on arm versus risk five. Right. So what exactly
from a technical standpoint in terms of what you can share,
is this first product going to look like? We are trying to focus on a clean sheet
design. That's number one. And what does that mean exactly. It basically means starting at first
principles of what makes a CPU great. That means understanding things
like, in technical parlance that means, good prefectures, good branch predictors, a fundamental sound pipeline, a, a pipeline that understands,
the fundamentals of computer science, things like graph theory, pointers, linked lists, elements like that
that make up everyday programing that we all get to experience
when we are using a computer. Clean sheet design, fundamentally says, I'm
going to explore all these attributes. I'm going to look at the processes
that are available in the industry, companies like TSMC, Samsung, Intel,
all the different processes that we have, the ability to partake in
and marry these two philosophies together. High performance process with, sound and reasonable CPU architecture. And then the the last ingredient,
which is what core first is trying to do,
is to basically say, I want to understand the available ISIS in the ecosystem
and you name two of them. There's basically three kind of, two more
prominent ones and one upcoming one, x86 arm and one that's being worked on
is risk five. But understand
the properties of those ISIS and make sure the CPU's fundamental
principles that we build are held, so that they can be targeted at any one of the three
at the time that we want to do our final, I'll call it final optimization
for a core that targets that ISIS. I want to circle back to, to Apple because they did a very interesting thing,
and you were obviously still very much in the thick of things there. So the iPhone ten gets announced in 2017
and everyone's very focused on the new design. Face ID, the lack of the home button, but there was some special sauce in there
that doesn't get much attention. That's the neural, that neural engine. My understanding is that the origin story
for the neural Engine comes from the self-driving car project,
where they were trying to build a car, and they need a gigantic computer system
to do the live processing for autonomy. And they ended up with the realization
that this block is going to need to be in the consumer devices, in the phone
at some point in order to power something. Can you talk me through the origin story
of the Neural Engine at Apple, how it finally landed and what the
thinking behind it was at the time. Obviously,
this has become a magical piece of technology that is enabling
so many on device workflows right now. But nobody was thinking about that
a decade ago. Yeah. I mean, it's I can't speak a lot about
the internal workings of the projects. As, as I no longer work there. And I'm, it's it's just not an area
I can go into. But what I,
what I, what I will say at a high level, every company right now on
the planet is actually focused on, on trying to build accelerators, for a variety of different things, knowing that the AI boom is what it is. And, yeah, I think I think I'm going
to leave it at that. No, I got you. For you, though, what are your thoughts on, you know, on
device compute versus on cloud compute? I mean, obviously the big difference is
how much performance you're able to get if you're putting it in the data
center versus on the phone itself. But I would like your philosophy on that. Yeah, I, I think there is a natural desire for every end user
to be able, to utilize the, the silicon that they have in the, in the,
in the products that they have. I think that is a huge opportunity for, the engineering community, including the up and coming engineers,
those students that are in, elementary, high school
and university level to be able to understand and experiment
with those technologies. So to me, I think it's a it's, it's a, it's a beautiful property
to end up with, and it allows you to scale
to eventually one day exploiting, I'll call it the very large models
that may live in the cloud, how it does what you're building
and this AI data center boom. How does it accelerate that? And, you know, as more people use
this stuff, is this going to slow down over time? Because right now I feel like, you know,
you and I, others may be listening to this. We're on the cutting edge,
but at some point everyone is going to use this stuff.
Is there going to be enough bandwidth? No, that's that's a that's
a lot of good points that you brought up. But what I will tell you is, I came from old school engineering
where you sat down with pen and paper. Maybe it's, modern times.
It's a whiteboard. Our marker board. And I was hesitant to step in a few, I'd say a few years ago
when when these models were ramping. Just because I didn't understand. Exactly. All right. What is it?
Is it going to benefit? Is it not going to benefit
what I have found? And with the, new the core
engineering team, what we have found is that these models, to be honest,
are actually an extent you should think of them
as an extension of your design team. It does not replace your design team,
but it's an extension of your design team. And what I mean by that is
you still need experience. Engineers brought into the company. Every day we we look
and look for, talented people. They are necessary in order to vet,
a lot of what these models, expose, or introduce as capabilities
because you want to make sure that the product
that you're building is robust. We've been in the business
now for about seven months. But we're seeing huge benefits, for our engineering, personnel. I look at it
this way. It raises the bar for everyone. You know, Apple, you know, likes to say
that it has no problem putting a competing product out because, two products
that are within the same company competing with each other,
it just makes the products better. And so I think that I it's just forcing
people to read up, to learn more, to get better at their jobs and push people,
to sort of beat out this technology. And at the same time,
you can't always trust these models. It can never be.
You can never do what I do. It can never. You do, but it can help give us time back
to focus on our strengths. Right. Can you go a little bit deeper
about how AI is actually helping with the nitty gritty development process
of programing, manufacturing, testing, making these chips more secure
and comparing it to even what you were doing a few years ago
at Nuvia and farther behind that at Apple. How has the chip development
process changed and has accelerated your, your roadmap
and your ability to bring silicon out? And has it helped defeat this idea
where you've seen CPU gains slow down? Right? I mean, if you look at the initial charts,
when Apple released the the first iPad, and then you look at the jump to the iPad
to the GPU acceleration they had on that, I think it was 8 or 9 x now
the year over year gains or 1,015%. But do you think with AI we're going to
go back to the old days here? Yeah. Many, many, many good points you brought
up going back to, for instance, Nuvia, because I've got two startup experiences
that I can, I can relate to. Nuvia was pre, the dawn of I mean, I was there, but
it was made a minority, in the ecosystem. Not really used during development time. It was engineers, going to the what? Like I said, going to the whiteboard,
doing design, exploring. Today
that has changed pretty dramatically. So comparing and contrasting,
if you were to go through the design process, developing a CPU
and it's made up of many parts, and you want a little techie,
so I'll dive in a little bit. There are phases to CPU development
that we all like to understand. There is what I call the performance
phase, where you're studying, researching, trying to understand
what you go to develop. Sometimes that could take two months. Sometimes it could take seven months
to a year. An extended research may take multi year. Once you're done with and having a have created a view of what
that performance wants to look like. There's a design process, a verification
process, and a physical design process that you go through
which eventually turns this, creative, concept of a CPU. If I use that as the example,
into a final piece of silicon that I try to ship in, in into a product, without the advent of AI. And what we're,
what we're experiencing at nouveau core without that event of AI,
that development cycle and it's best typically was around
two and a half to three years. Okay. That's basically clean sheet design going to an end product
two and a half to three years in nouveau core. What we have experienced actually,
in these early phases and we're still developing the CPU,
as we speak. But I can tell you in these early phases
of performance and performance
modeling and characterization of a design, what would have taken seven months
to 12 months to get to a point where you, are ready to start the design process? We've actually collapsed that down to a 2
or 3, 2 or 3 month window. Which is very, I'd say unexpected,
but a positive. It's a positive because now
that gives me time and the engineering team time to focus on, potentially other ideas. And that gets to one of your fundamental
things that you talked about, which is it looks like there's a slowdown
in the industry. What I will tell you, in my experience, that Slow down is really about your ability to explore and know what to explore
and how to apply it with the end goal being that you compress that entire two and a half to three year
schedule into something that may look like a two year type of design point
that would be ideal. Year and a half would be beautiful. If design teams can do that. And there have been a few examples
out in the field recently where AI has been applied
and accelerated, the timeline, and high performance,
very high performance CPU design. I think the answer is just time, to to actually show
that the full clean sheet endpoint can actually be compressed to something,
that is reasonable for the market. Does a complex compress to a year. Today I can't answer that question,
but I think given Gen one, Gen two of our timeline, there's a possibility
for that to become true. I still want to go a little bit deeper
on why focusing specifically on the CPU versus the complete stack,
because obviously one of the big, you know, inventions at Apple,
one of the big innovations was sort of the system on a chip design. We were bringing together
a full SoC with the CPU, with the GPU, with the Neural Engine,
the memory and everything together. So can you go a little bit deeper on there
and how this is one block and how that will fit in
with other companies here, and how your strategy's really comparing
to what you're seeing from Apple with its private cloud compute that they've been pushing
for the security optimizations for AI. Obviously
Nvidia is working on their own cloud CPU. And what you did at Qualcomm
with with Nuvia. Yeah. So at Nova Core, our, our long term ambition is
to basically one day get to end product. It's performance has to be good. It's power efficiency has to be good. We're working with a variety of end
customers to try to understand, how they want to integrate that. And ultimately
that could turn into a chiplet form of silicon with many CPUs on a die
that's co integrated with accelerators. It could turn into a full scale end
product, like you see in classical data center and Hyperscaler,
which is a blade based, compute device. But yeah, it's, it's, it's ultimately
where we want to go. So I hear technical details, I hear AI features, I hear how my computing
is going to improve. But investors, they hear dollar signs and,
supposedly you're about to raise a whole bunch of money at a valuation
between 2 and $3 billion. Are you able to give me
a little bit on that, of what your investors
are putting into the company and how this thing is going to grow
and really get off the ground here. In terms of the exact
financial investment in the company. We have not made any of that public. And I won't go into that right now. But what I will tell you is the investors
that we have brought on board have been involved actively with silicon, the strategic players that
we're bringing on board have actively been involved in silicon, and they know that
this is a long term journey. And how far you off
from actually going into production? As I said, we're seven, seven months into the journey. Full silicon is somewhere between a 2 to 3 year journey, in order to create that silicon. So, it's it's it's roughly around that time frame. Let's get to your journey at Apple. So Gerard Williams III
you show up at Apple in what year? 2000, 2010, 2010. And so that silicon in the cloud
was one of your first ideas. So, who hired you? Who brought you on? What was the mission? Was this to develop the, the A7? Was that the first thing,
the first 64 bit Apple chip? Tell me. Tell me about getting to Apple
getting started and and what you did there from the beginning. Yeah, I joined Apple. And, I think it was February of 2010. Basically I joined, as, as as,
as you rightly pointed out early on, I joined a team
called Platform Architecture. In the early days of Apple
that was a very small engineering team that was focused on, literally looking at all silicon, and
hardware being designed in the company. And I was one of a handful of those
engineers, that was a part of that team. And we explored every design, that would come across the desk of, of the senior exacts and decide, with them whether or not that
that was a possible thing that could be, developed and, and, and created in, in an Apple product. And, along that journey, I had the opportunity to, become Apple's
chief architect of CPU development. As you pointed out, the first product
that, saw the light of day that
I worked on was the Apple A7. And, I was able to work on many other products
after that, but, but yeah, the engineering team, we focused
pretty heavily in silicon development, understanding that silicon
developing a roadmap for that silicon and trying to make sure
that the products year on year, showed benefit. Apple really pushes this narrative about
performance per watt on all its silicon. And when the M1 came out, which you worked
on, I want to get into that. They were really pushing performance
for wall versus Intel. It's not only about the speeds and feeds,
but it's about the power efficiency. It's about battery life. Was that something
that you were pushing from the beginning? Was that sort
of one of your early innovations? I would say that even predates Apple. It was tell me about that,
because you were a tie in arm as well. I want to hear about the pioneer
of this performance per watt idea, because it's it's the biggest thing
and on device silicon right now. Yeah. So, yeah, even predating Apple,
if you go all the way back to, during the arm days when I was there,
we used to look at devices and,
the products that we were shipping and, and in those days, back in the,
I call it late 90s, early 2000, you were talking about devices
that were sipping 50mW, 100mW. So to you as an engineer
spending 1 million, what was was huge. It was huge. It was a large percentage of the, the,
the the core itself that grew over time. But that philosophy never changed. And in the world of computing, everyday
life, us as users, I carry around laptops. We all do. We carry around cell phones, watches. They all have batteries in them. So, burning micro watts milliwatts
is fundamental to those products because it basically means
at the end of the day, can I make it through the working day
with my product, doing everything that I want to do,
and it still survives. And if that's the case, if succeeded,
we all sleep at night, we all go to bed, we can plug our device,
let it charge again. We wake up in the morning and we run
all day and do everything that we do. The beauty of that is the moment
when once you understand those those fundamental properties
about how and where power goes and why, you can bring that to the data center. Okay. It's a it's a property
that people don't think about. They you hear people throw out numbers
like gigawatts and multi gigawatts. I will tell you that milliwatts
are still a part of that number. And if you can, if you, if you, you can save milliwatts
and every CPU that you constructed by the time you multiply that out by tens,
hundreds, thousands, if not millions, of course, it's
a material change that you can make. And so one of the fundamental
things that we I've always done, I did it at Nuvia, I've done it
at every company I've been at, and I'm doing it again at Nouveau
Core on this clean sheet design approach. Power is fundamental, okay. Even though we don't think of it
as a giant battery. It's a it's a property
that you want to lower as much as you can
because at the end of the day, if the engines, as we are
seeing are driving up the core count, demand and making CPUs what I call
front and center in the data center, if I can lower the power
and I can suddenly squeeze two, three x the number of cores
into that data center, building I've won. So obviously you worked very closely
with your product design, with your, electrical engineering,
with your hardware engineering teams. When when you were at Apple, do you feel
like you were kind of handing them a gift? It was sort of like a magic bullet. You were handing them those chips,
allowing them to design devices. They wanted to design and implement
features they wanted to implement. They couldn't necessarily do with Intel. Was it seen that way
internally that you guys were the Wizards really making this happen,
but not getting the credit? I don't think about it that way. I mean, reality is
what and what I will tell you, fundamentally,
a CPU is not designed by one person. It's not. And some of the ideas come from a person,
but it comes from the team. It's fundamentally a team, and it's how
you build that team, organize that team, and give them the freedom to explore. That's actually what, at the end of
the day, makes products great. And, and makes engineers want to come to work every day, wake up
and and do amazing things. And that's
one of the fundamental properties that I've tried to instill in every team
that I've created. Obviously, being in that silicon group, I have to ask you about a couple people
first. John Ternus,
obviously the new CEO of Apple. What do you think coming from an Apple
that was, you know, you started it was run by visionary. Then it was run by an operations guy
for, you know, 95% of your career there. And now it's being run
by a hardware engineer who rose up the ranks very quickly. I mean, by the time you left
Apple in 2019, like, really, no one's ever heard of the guy. Even when I was talking about him. Starting to tell people 2 or 3 years ago,
starting to break the news that, hey, John Ternus is going to be the next CEO.
This is happening. Everyone's like, who the hell is this guy? No one's ever heard of him, right? Okay. You having been there,
did you work closely with him? Was this a shock to you?
Does this make sense? What do you think of a bore?
Engineering led apple? Tell me if you have one. An interesting
turn of story, because obviously you were the guy
making the chips. He was the guy, you know, pulling together
the chips with the other components and the product design and all that. Yeah, I won't go into personal details about, my,
my time there, but I think, you named off to it
two of the past, folks, putting names to the two
who you mentioned. Obviously, there was Steve Jobs
and an obvious visionary. The world sees him that way. You've got Tim Cook,
the financial individual, and and then effectively, now, John Ternus,
who you who you were just asking about. I believe they all have
their different strengths. And they, in turn,
this is case times going to answer that question, really,
at the end of the day about the decisions he makes,
how he utilizes the engineering team. But as to his strengths and weaknesses, I'm not going to elaborate about that. I did work with him while I was there. Very good person. I will say that he is a good person and, works with his people, but beyond that,
I'm not going to dive any deeper. I wish him the best in what he's doing,
and I honestly do hope that he succeeds at everything that he does and what he
what he can pull off for the company. Maybe. Now, two more questions.
Johnny Srouji. You know, he's known for running that team
with, with an with an iron fist. Anything. Any thoughts on him? And how is he's doing and how he runs
the team and his management style. Do you have any learnings or takeaways
from working under him for so long? Yeah, I mean, I've known Johnny
for quite a long time. Probably about 20 or 20 years
of my career. I've known him. I have the utmost respect for him
and what he's built at Apple. Amazing organization, year on year. They're they're they're delivering
and developing. And I, I wish him the best
and hope they continue to do so, as, as as I do with many, many of my colleagues and friends that, that are still there. So I, I wish him the best and you left Apple in 2019
right on the cusp of the M1. Why did you decide to leave at the time? And what was that process like? And then how did you jump into into Nuvia? It's the process. The answer is yes. It was it was, I believe, February of 2019
that I stepped away. And you were a senior director
at the time, which I was just to explain to the audience. Senior director. There's about 300 of them across
the whole company. It's a very, very high level position. There's the CEO, there's a senior VP, there's the VP's,
and then there's the senior directors. But then there's a large tier of senior directors,
which are essentially in the VP tier. And I guess that's sort of the,
you know, Venn diagram. You were part of that. Yeah. You've aptly described it. Yes. Yes. Departing any company
where you've you've kind of, enjoyed the experience of working
on the products, developing the products. I mean, you end up, you want to give everything that you can
to the company as you're progressing. So at the end of the day, when I did
walk away, yeah, it was heartbreaking. I mean, it is for many people that
walk away that that invest a lot of time. And, and they were pretty heartbroken to
I hear, that they were, they were, they were but and ultimately I walked away because of an opportunity
that turned into nuvia, and, that opportunity opened doors for me to experience things in my career path
that I wasn't able to experience. I'll say, being an engineer, things like, at the time, I was the CEO of the company, and you are out raising money funding, which is,
the money side of the equation, making sure EDA agreements
are put in place a variety of things hiring people, building a team,
making sure that we have direction set so that that's something
that you can't experience as an engineer inside of an organization. And it was an opportunity
for me to potentially, call it, spread my wings and,
and kind of take flight, so to speak. In a startup world,
was it easy to step away from, from that that that Apple journey? No, it was not. I should note for the record
that Apple did to you and Nuvia, after you, you know, started the company,
they accused you of hiring engineers, inappropriately and trade secrets
and what have you. And then, as we see
in a lot of these lawsuits, courts determined
to a large degree of being frivolous. And, you and Nuvia obviously came out on top here and had a very successful
launch at Qualcomm. And now you're on to your next thing. Tell me about the chips
you ended up launching at Qualcomm. What do you see as the success there? What do you see
as the differentiator there? And what do you think it's doing
for the PC market and for competition? Yeah, I would and on the lawsuit side,
what I will tell you, I can't go into that, just, just,
just for, just for the viewers. I can't dive into that and ask you to. I just have to. I just have to, You'd be weird. Someone watching this is like. How did he have an hour conversation
with you, Roger Williams
the third, and not mention the lawsuit. So I have to get out there now, circling back to where we started,
obviously you leave. Qualcomm was at the beginning
of this year. Yes, it was the end of January
actually into January. You said you, left because you needed
to finish painting up your new house. How did that go? I like that story. It's it's
made its way around the industry. Is it finished? I'm. Well, if you want the honest truth,
I'm actually still painting to this day. I, I recently, have painted my daughter's bedroom. And I'm still doing it. I enjoy, this is the other side of me. I enjoy the
the relaxing it to me, that's relaxing. I was going to say, at this point,
I feel like you could hire someone to paint it for you. Like, I probably could, but, honestly,
that's me being an engineer. At the end of the day, you know, I,
I like the details, and I, I enjoy it. I get that you were asking about, like,
my early, early career. I had the opportunity. And many don't have this opportunity. As a small child, I got lucky. My my father was into construction and a variety of things like that,
so I learned, honestly, if I wasn't doing CPAs my day job,
I could go into construction. And a lot of people don't know that. So. Yeah, it's, it's it's it's a nice, relaxing pastime. I love that. And last question for you on this podcast,
we focus a lot on the hardware itself, on the products,
the physical devices people can buy. What does the industry shift
look like in 3 to 5 years
with a big offload of CPU into the cloud? I mean, I'm
imagining things like AR glasses finally being able to be enabled,
but what is this future that you think you're going to enable
for hardware customers? Yeah, and by customers I'm talking about,
you know, me and you and listeners not like you know
your in videos and open eyes of the world. Yeah. I think at the end of the day, bringing CPU technology
to bear to in a market like this 2 to 3 years down the road
or five years down the road, I think what we're
going to discover is this, this utilization of LMS and CPU and compute technology
that every end user will get to experience, not just
and you talked about glasses or devices. It's basically everyday ordinary people
picking up these devices and exploring these devices. And utilizing, being able to access things that that
normally you'd have to go to a library and research and try to figure out,
you can ask the language model, these questions, you can even do it today. And my hope is that that
that actually is what happens with all the end users, not this fear
that you see in the industry. Wherever AI is going to do this
or do that. No, it's about can it me, my working life
that much better, my daily life? And if the answer is yes,
we've done something pretty amazing. Cool. So we'll leave it at that. Gerard Williams III. Thank you so much for your time. What an interesting conversation. I think it's really important,
given everything going on in the industry right now, and I'm glad
we were able to tie it back to to Apple, to Qualcomm
to arm all the hot buttons right now. So thank you very much. Thank you. Thank you for the opportunity. Okay. It's Apple trivia time. Our producer
Alexis is going to try to stump me. What do you have Alexis? Well it's just you. So you really on the spot with this one? But, you know, I like to go thematic. So yes, I'm
going to ask you a question about chips. Okay. If you're ready. It's very it's very chip
very chip related episode. Okay. So the question is
how many of the Apple A-series chips carry the pro name? Ooh. Let me know if you want
the multiple choice. Okay. I'm trying to think
when did they start giving the pro name? Well,
there was definitely the well, they did, fusion once there was the A10 fusion,
I think it was the A11 fusion. There was the A or maybe the A11 Bionic. They went from fusion to Bionic
and then they started doing the pro chips. Was it the A15 Pro A16 Pro I would say so A16 Pro A17 Pro, A18 Pro A19 Pro A20 Pro okay. Give me the multiple choices okay. So I'm gonna I'm going to give you the
these numbers correlate with the number of chips
with the pro name okay. So is it A. 5, B. 4, C. 3 or D. 10? It's not ten. It's not three. It's 4 or 5. I'm going to bet five. Oh so close. No it's four. It's four okay. What was the first pro chip okay. So the first A17 Pro A17. Yeah A17 Pro 1718 1920. Yeah exactly. I was off
and then okay. You were off by one. Do you remember what year
they switched from Bionic to Pro. So A17 Pro were in 26, 25, 24 I guess would be 2023. Yes. Correct. And that was when they split the chip
into two variations having the low end for the regular chip
and having the high end, for the Pro line. So and they eventually put the Pro chip,
in the iPad mini. And now they've, you know, expanded it,
obviously the iPhone duo and the 18 Pro and Pro Max have the iPhone's,
A20 Pro chip and then the iPhone 18 and iPhone 18 E in the spring next
year, we'll have the regular A20. Well, I'll give you a half a point back
because we've got the follow up question, but I'm going to count this
as a win for myself. Okay. You go ahead. Okay. So the next question I've noticed that you really like talking
about different colors of products. So I oh gosh,
I had to throw a color question in here. Okay. So in 2023, Tim Cook was asked
what color of the iPhone Pro Max he preferred and chose for himself
the natural titanium. Yes, yes, that was the same color I got. It was it was the nicest color that year. I, a family member of mine has the natural titanium, phone right
now, like a couple generations old. I don't really
don't like it at this point. But it was a good color back then. What is your favorite color
of the iPhone of all time? Oh. I really liked the midnight green iPhone 11 Pro from 2019, and I really liked the Pacific Blue of the iPhone 12 Pro in 2020. And this might be a little controversial, but I am really digging the night sky
iPhone duo. I think I went with the right color a lot of people really wanted the white,
but I, I like my I like my night sky. That's not the first time
you've said that on this phone, I guess. But I like, that you
that you point that out. Okay, well,
we got Tim Cook's favorite color. Me also got yours. So this is another round of the apple
trivia in the bag. Thanks, Alexis. Okay, we have several more
exciting episodes in the coming weeks, including a mailbag episode, so please
send in all your questions to PowerOn@bloomberg.net or post them
in the new podcast channel in our discord. The Power On Discord. And we will try to get to all
your questions in that mailbag episode, so stay tuned for that.

</details>
