---
title: "Bloomberg Terminal Essentials Charting"
people_mentioned: []
channel: "Bloomberg"
video_id: "CoRvxW2eUqM"
url: "https://www.youtube.com/watch?v=CoRvxW2eUqM"
publish_date: 2024-08-06
duration: "6:40"
word_count: 1179
content_type: "tutorial"
delivery_mode: "instructional"
broad_category: "investment"
subcategories: ["terminal-workflows", "charting", "market-data", "analysis"]
series_name: "Bloomberg Terminal Essentials"
episode_id: ""
primary_person: ""
host_names: []
interviewer_names: []
interviewee_profiles: []
speaker_profiles: []
organizations_mentioned: ["Bloomberg"]
locations_mentioned: []
tools_mentioned: ["Bloomberg Terminal", "GP", "GPO", "GPC", "GGO"]
companies_mentioned: ["Apple", "Home Depot"]
topics: ["terminal-workflows", "charting", "market-data", "comparative-analysis", "saved-workspaces"]
tags: ["terminal-workflows", "charting", "market-data", "comparative-analysis", "saved-workspaces"]
pipeline_stage: speech_done
claims_status: done
evidence_status: pending
claims_count: 8
evidence_count: 0
batch_id: ""
last_processed_at: "2026-03-18"
speech_status: pending
world_status: pending
speech_evidence_count: 0
world_evidence_count: 0
---

## Summary

This Bloomberg Terminal Essentials tutorial explains how Bloomberg's charting tools can turn raw financial data into reusable research views. The walkthrough starts with GP as a flexible scratchpad for chart building, then shows how to layer in benchmarks, peer comparisons, and statistical studies like averages and standard deviations. It also emphasizes saved templates, smart chart behavior, and graph management as ways to turn one-off chart exploration into a repeatable workflow.

## Key Insights

- GP is framed as the core scratchpad for flexible chart experimentation.
- The terminal adapts chart options based on the loaded security type, which makes the same charting workflow useful across assets.
- Adding peers and benchmarks can create relative-strength context without rebuilding a chart from scratch.
- Smart chart behavior keeps comparison logic relevant when the primary security changes.
- Studies like historical averages and deviation bands help turn a basic chart into a more interpretable analytical view.
- The side panel is the main control surface for editing layers, styling, and applied studies.
- Saved charts matter because they preserve research workflows, not just images.
- GGO is useful for organizing, recalling, sharing, and reusing chart work over time.

## People Mentioned

## Claims

- [[Bloomberg Terminal Essentials - GP works best as a scratchpad for quickly building and modifying charts around a loaded security]]
- [[Bloomberg Terminal Essentials - Bloomberg charting tools become more powerful when users add benchmarks peers and related data instead of viewing one series in isolation]]
- [[Bloomberg Terminal Essentials - Smart chart behavior can automatically keep sector and comparison logic relevant when the primary security changes]]
- [[Bloomberg Terminal Essentials - Historical averages and deviation studies help convert a simple chart into a more interpretable valuation or relative-strength view]]
- [[Bloomberg Terminal Essentials - The side panel is the key place to manage chart layers data fields studies and styling choices]]
- [[Bloomberg Terminal Essentials - Saving a chart as a template preserves the workflow and formatting while letting future users swap in a different loaded security]]
- [[Bloomberg Terminal Essentials - Saved charts are more useful when users treat them as living workspaces that retain later edits rather than as static snapshots]]
- [[Bloomberg Terminal Essentials - GGO is the organizing hub for managing sharing and reopening saved Bloomberg graphs]]

## Full Transcript
<details>
<summary>Click to expand full transcript (1179 words)</summary>

you know the Bloomberg terminal gives you unparalleled access to financial data but can you make that data come to life through advanced charting [Music] tools welcome back to terminal Essentials this series walks you through the terminal's most used functions so that you can navigate them with confidence there are many charging tools on the terminal running any of these will create a simple chart that you can modify and save for future use GP is for line charts GPO is for bar charts and GPC builds candle charts we're just going to focus on GP in this video but once you know your way around one you'll be confident with all three okay let's run GP go think of this as a scratch Pad a place for you to explore ideas and quickly spot opportunities and events the terminal will adjust the contents of this window to fit the type of security you're working with we've got an apple us Equity loaded so this box can be adjusted from price to popular fundamental metrics and estimates given that the screen understands we have an equity loaded if we had a bond loaded this is where you could adjust to see various yields or relevant spreads these are just suggestions though we could also just start typing in this box and autocomplete will surface more options we'll use best PE ratio that's our Bloomberg estimate and it's a sside consensus that we've aggregated for your use now that we've selected best PE ratio an additional drop down has appeared it's default to the current fiscal year but you can adjust to see the kind of estimates you like such as the next 12 months forward GP and the other charting tools I've mentioned aren't limited to a single security or data set at a time we can add to this chart with the add data field in the top right or the related data box to the left let's start there this will suggest benchmarks and peers let's see the relevant sector here this will add the S&P infotech index to the chart using the same metric the estimated PE ratio it also adds a new panel below that shows the relationship between the two tickers we're monitoring this ratio can help us assess our selected Security's relative strength or weakness compared to a benchmark you probably also notice that when we added the second ticker for comparison we got a new right side panel this is where you can see all data sets on your chart and edit the chart you're viewing is click the pencil icon to adjust the security data series and even the design of the chart note that by adding the series via the related data box for an equity we've made the chart smart here too if I change the ticker in the top left to something different Like Home Depot both the sector in the top Pane and in the denominator of the ratio are smart enough to adjust to something relevant here it'll shift the comparison to the consumer discretionary sector instead of infotech one popular way to modify a chart like this is to add historical averages and standard deviation levels we'll type deviation in the ad data box and select the study we're looking for average and deviation lines we have the option to select which data set to apply it to let's add this study to the security we started with and now we can see that data is on our chart along with the ability to toggle any of these data sets on and off for example I can hide the index for now but easily be able to recall it later this gives us a clear picture of Apple it's 12month forward estimated PE sat over two standard deviations away from its one-ear average at the time of the screen capture let's take a closer look at the side panel we can tick or untick each of these three layers the security then the data field and then the study we're applying each one is indented to show its relationship to the data above it those pencils to the right are where you can further customize any of the data even if you just want to change the colors you can quickly toggle the time frame in the upper left to see that over a 5year period these estimates are actually in line with the average you've probably used the Red Ribbon to edit defaults and other functions it's where you can do things like save adjust and Export the screen or data you're viewing we can set your defaults to fit your needs maybe you prefer your charts to always load with moving averages or maybe you want to remove the shading under price or the volume displayed below Equity prices there's a lot to explore here we've already made a chart that we're happy with though so let's save this unique chart for later click actions save as and give your chart a name we can save the chart as a template as a template we can open this chart again in the future and it will use the same data types and formatting but we'll use whatever loaded security we have instead of the one we built the chart with if you selected to save the chart with displayed Securities on the other hand that chart will always load the tickers used during the initial build after you click save you'll notice that each chart gets assigned a unique number for quick referencing it's important to note that you only need to save a chart once save charts automatically retain future tweaks don't worry save charts give you undo and redo buttons in the top right so that you can adjust them without fear another benefit of save charts is the option to change the color scheme Bloomberg's signature charcoal background may be great for monitoring throughout the day as it's easy on the eyes but if your goal is to get this chart into a report you may want to try other color schemes to see all your saved charts and graphs run goo this is where you can organize share and delete your saved graphs notice that each chart has its own shortcut we can access it by typing it in the command line or we can even type the name of the chart and natural language processing will pull up the relevant view we've covered a lot today in case you weren't taking perfect notes there's an easy way to get more details about any function just go to the question mark in the top right corner and select help page for detailed explanations you can also select Live help here or press the help key twice on the Bloomberg keyboard to open a 24/7 Live support chat with our product experts for more terminal Essentials videos like these subscribe to this channel we can't wait to see you

</details>

