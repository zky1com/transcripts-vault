---
title: "Portfolio Risk Management with AI on the OpenBB Workspace"
people_mentioned: ["Kenneet French"]
channel: "OpenBB"
video_id: "77cDGi29a-c"
url: "https://www.youtube.com/watch?v=77cDGi29a-c"
publish_date: 2025-05-20
duration: "7:54"
word_count: 1245
content_type: "solo-talk"
delivery_mode: "knowledge"
broad_category: "finance-investing"
subcategories: ["portfolio-management", "stock-analysis", "risk-management", "market-data"]
series_name: ""
episode_id: ""
primary_person: "Kenneet French"
host_names: []
interviewer_names: []
interviewee_profiles: []
speaker_profiles: ["Kenneet French"]
organizations_mentioned: ["OpenBB"]
locations_mentioned: []
tools_mentioned: []
companies_mentioned: []
topics: ["portfolio-management", "stock-analysis", "risk-management", "market-data", "ai-safety", "ai-coding"]
tags: ["portfolio-management", "stock-analysis", "risk-management", "market-data", "ai-safety", "ai-coding"]
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

The discussion centers on let's, client, some. Let's take a look at client 3 portfolio. I'm going to add it to context the industry and let's say let's just keep the industry only. Now in the second tab of my custom application, let's pick a client.

## Key Insights


- Let's take a look at client 3 portfolio.
- I'm going to add it to context the industry and let's say let's just keep the industry only.
- Now in the second tab of my custom application, let's pick a client.
- I'm going to add this French factor data to opex and going to ask let's just go to my prompt library.
- I wanted to ask how I've diversified is this client by let's remove the separate just by industry and I wanted to ask for some recommendations.
- If you want to explain this to a client, you can have the copilot to essentially draft some sort of like a client memo for example.

## People Mentioned


- [[Kenneet French]]




## Full Transcript

<details>
<summary>Click to expand full transcript (1245 words)</summary>

Hi everyone. In this demo, I'll show you how OpenB can modernize risk management applications powered by your sensitive data running on prem, fully customizable and with the AI built into the application. So I have a dashboard here that we put together and in this first tab we're pulling some publicly available data from Kenneet French's website about from French factor returns. So everything here is custom. So you can uh choose which factor returns that you would like to look whatever is relevant for you at whatever frequencies and so on and so forth. You can move things around, reshape them, restructure them, regroup them whichever way you would like to. And here's a very simple example how you can use the copilot. So I'm going to add this French factor data to opex and going to ask let's just go to my prompt library. I want to compute log returns for each vector and plon time series. I want to switch from row values to some sort of chart. You can build the chart manually using the controls here, but these are index values. They're not returned. So you somehow need to do the computation. You can just ask a do the computation for you. So I created the chart here based on my prompt. I'm using openb pilot in this case. And here's a nice thing. Everything that the chat panel has, you can export it as a new widget. So now AI computed the log returns and exported everything. So now I can add this to context and ask another question if I want to. Now in the second tab of my custom application, let's pick a client. Let's assume that this application is running on prem. So you can bring sensitive data to OpenB without OpenB or anybody else taking a peek at your data. So this is a customuilt chart/analysis tool. So it could be customized with code to whichever way you would like to see data. So let's say I'm looking at my three fake clients that whose identities I have masked. Um, I put a drop-own menu to see the portfolio performance as well as the individual holdings and how some of the individual stocks uh in this portfolio are doing. Let's just go back to the portfolio. Um, I added my own drop-down for the horizons. I could switch to returns if I want to. Again, the whole point is you customize and build with code whatever functionality that you would have here. None of these things are coming out of the box. You can customize the application whichever you would like. You can toggle between the row values versus some sort of chart view. You can also just customize the chart settings if you want to switch to something else. But I wanted to show here how to interact with the copilot. Right? So let's say that I want to add this to context. I just want to ask a question. What is average daily volatility of returns for this portfolio? So for any computation that you want to do on the fly, you don't need to go back to some sort of coding or put it to Excel. You can just basically ask AI to answer simple questions like this. Next up, I created a tab to explore exposures by country, sector, and industry. Again, so I did some grouping so that you can browse and update the different clients. Let's just focus on client number two. And this is a good point to maybe also show the copilot menu. So you're not limited to OpenB copilot. You can actually connect any copilot to open BB. And in this particular example, for instance, I've developed my own custom agent. And this agent is using deepseek under the hood and also has access to perplexity API so that it can do web searches. So let's use this as my main cop pilot for this part of the demo. So I'm going to add it to context the industry and let's say let's just keep the industry only. And I wanted to ask how I've diversified is this client by let's remove the separate just by industry and I wanted to ask for some recommendations for diversification targets and ideas. So let's see what we can come up with. Okay. So you can go through the stepby-step reasoning. So you see it actually access this particular widget and this is how the reasoning model operates. So it's basically saying heavy concentration in industrials top five industries that they invest is more than half the portfolio. Here are some more custom screens that you can build. So in this case you choose a client and you can see their top holdings. You can ask copilot some insights around what are their biggest holdings. You can add more customizations here in the code say what are my top holdings by a certain industry by market cap and so on and so forth. So you can make it part of the budget or you can ask AI to do it. The point for this particular tab is that you're not limited to the visualization that we provided. You can also bring custom visualizations. So here's a very custom correlation matrix for example that is done with plotly it's colorcoded and pixelate nature. So in this case for example you're look you're choosing a client and with all the holdings that they have you visualize the entire correlation matrix. So you can essentially do all this custom work and still access them through OPB. In this final screen we're going to get very custom. So you're not limited to just having data applications on OpenB. You can also bring machine learning models, prediction models in general, run those things under the hood and expose the results and visualize them and make these models available for end users to share and manipulate. So in this case, we're doing an attribution analysis, right? So I'm basically running a client returns against the farmer French factor models which we have shown over here. So you can choose which models to run it against, which factors that you would like to use, which client portfolio you would like to run it against. And under the hood, there's actually a little API that I've custom built to run these regressions and then show the output and colorcoded by P value. So let's take a look at client 3 portfolio. So the constant is typically interpreted as the alpha component. And this is where the AI is actually quite helpful. People always forget how to interpret the P values and things of that nature. So how do I interpret the constant coefficients in form of French regressions using five model suppose that I have -0.08% 08% coefficient and p value of 0022. How do I read this out to the client? So let's see what it came up with. It suggests that the average portfolio underperformed the model's predictions and the p value suggests that the alpha is not statistically significant. Right? So if you want to explain this to a client, you can have the copilot to essentially draft some sort of like a client memo for example. So this basically suggests that after accounting for blah blah blah it underperformed. The next steps are this and this and so on and so forth.

</details>
