---
title: "How to Export Data from MetaTrader 5 and Import it to StrategyQuant X"
people_mentioned: []
channel: "StrategyQuant"
video_id: "EEBXfv8DwrY"
url: "https://www.youtube.com/watch?v=EEBXfv8DwrY"
publish_date: 2024-08-05
duration: "8:25"
word_count: 1246
content_type: "tutorial"
delivery_mode: "technique"
broad_category: "finance-investing"
subcategories: ["options-trading", "market-data"]
series_name: ""
episode_id: ""
primary_person: ""
host_names: []
interviewer_names: []
interviewee_profiles: []
speaker_profiles: []
organizations_mentioned: ["StrategyQuant"]
locations_mentioned: []
tools_mentioned: []
companies_mentioned: ["Meta"]
topics: ["options-trading", "market-data", "data"]
tags: ["options-trading", "market-data", "data"]
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

The discussion centers on data, click, select. In case you don't see app data you need to go to you and click on show hidden items and we are going to. The advantage of MetaTrader 5 over MetaTrader 4 is that MetaTrader 5 contains this tick data already. We are going to wait a little bit for the data to be imported and then I will show you how to check the.

## Key Insights


- In case you don't see app data you need to go to you and click on show hidden items and we are going to go to app data, roaming, metaquals, tester here and then it's going to be one of these directories.

- You will switch to the hourly time frame, wait a moment for the data to recalculate and now you can see that the data here is loaded from the beginning of the moment we set it which was at the beginning of the year 2023 and the data is exported for the last date we selected.

- The only other thing that I always do manually just to be sure and not leave it up to auto detection is that I check the tick here or the particular file to make sure that the data is supported the way I need it to be and the robot is in the European DST time zone so I choose UDC plus two.

- So we are going to wait a little bit for the data to be imported and then I will show you how to check the data directly in StrategicQuant to see if everything went as it should.

- It's worth mentioning that exporting tick data can take a really long time as this data contains all the history and every movement in the market.

- You click on open data folder then tester and sometimes it happens that it's not in that first agent directory which is based on the backtest nodes but you need to look in the second one for example.




## Key Quotes


> In this video I will show you how to export data from MetaTrader 5 and import it into StrategyQuant.


> For this export you will need an automated strategy which you can find directly in the StrategyQuant installation directory, under custom indicators, MetaTrader 5 and experts.


> You can copy the strategy into MetaTrader and compile it or you can restart the whole MetaTrader and then this EA or expert advisor will appear directly in the tester.


> To launch the tester either use the CTRL plus R keyboard shortcut or click menu, U and strategy tester.






## Full Transcript

<details>
<summary>Click to expand full transcript (1246 words)</summary>

In this video I will show you how to export data from MetaTrader 5 and import it into StrategyQuant. For this export you will need an automated strategy which you can find directly in the StrategyQuant installation directory, under custom indicators, MetaTrader 5 and experts. You can copy the strategy into MetaTrader and compile it or you can restart the whole MetaTrader and then this EA or expert advisor will appear directly in the tester. To launch the tester either use the CTRL plus R keyboard shortcut or click menu, U and strategy tester. To export the data you can also select the symbol you want to export. Select time frame M1 because we are interested in the smallest one. You also select the from to range. I'm going to select a short period of time here for demonstration purposes so that the export doesn't take so long. However, it should be mentioned that tick data contains absolutely all market movements. The advantage of MetaTrader 5 over MetaTrader 4 is that MetaTrader 5 contains this tick data already. It then depends on the broker how long a history it allows you to download. For robomarkets it is sometime since 2017 which at least for some verification of the bill on ducas copy data will be amply sufficient. I've served only half a year here. For this testing we don't care about latency at the moment so we'll put zero latency and choose the every tick option. I don't care about the other options at this step because I won't use them. And once you have those parameters set click start. It's worth mentioning that exporting tick data can take a really long time as this data contains all the history and every movement in the market. So you also need to make sure before you start exporting this data that you have enough disk space because for a single currency pair or market the data can be in the tens of gigabytes. So I will wait until the testing is complete and then I will show you how to load the data directly into StrategyQuant. The tick data has been exported and now I need to find this file. You click on open data folder then tester and sometimes it happens that it's not in that first agent directory which is based on the backtest nodes but you need to look in the second one for example. Anyway it's usually in the first agent 127.0013000 but in this case it's stored here. In case you are not using the portable version it's quite possible that this csv file will be in a different directory. The entire path is then marked directly in the strategy except for the id of the metatrader itself. Let's try to find this path here. You need to go to see users, administrator, app data. In case you don't see app data you need to go to you and click on show hidden items and we are going to go to app data, roaming, metaquals, tester here and then it's going to be one of these directories. I've got more than one here and it's just because I installed the classic version first and then I switched metatrader to portable mode. However if you have one metatrader you should only have one terminal here and then there will only be one agent and one file. So in the directory you will find the csv if you are not using the portable version. And now I will show you how to import data into strategy quant. So this is the path you are going to copy ctrl plus c. Now you are going to go into strategy quant and before you start importing the data you need to create a symbol. I, to make it a little bit easier for you and not have to manually retype it, I'll share this setup with you and the link will be available for download somewhere below this video. Anyway you downloaded the zip file and you need to import these instruments or instrument settings where there are some recommended default spreads and also point value and tick, pip, step and size. Then you download that zip file, unzip it, go to instruments and sessions, click on load and select instruments, robo, indices. You will then import this table. Same thing if you are missing symbols right here you go to data, sources and click load and select that particular instrument file. Then the data will be loaded and you will have the symbols ready. I'm going to show you how to add a symbol if you add any more symbols so you know how to do that. To import a csv file you need to click on file, add symbol, you will choose here for example enqueue, tick, robo. I will select the instrument which in this case is USA tech and click on save. The symbol is shown to me in the menu and by the fact that you guys will already have prefilled symbol names here so to import data into that symbol you need to select it. For now I'm going to select the symbol that I created a moment ago and click import on that. I will select the file, in this case I will use the keyboard shortcut ctrl plus v so I don't have to search for that path and StrategicQuant will open the directory directly and I click on select. Then I load the data. I see that the beginning starts in 2023 right at the beginning of that year. I can see that all the columns are correctly labeled and then that it's the correctly recognized format. The only other thing that I always do manually just to be sure and not leave it up to auto detection is that I check the tick here or the particular file to make sure that the data is supported the way I need it to be and the robot is in the European DST time zone so I choose UDC plus two. I just do a quick check, see that everything's okay and click on start. Now it's running. StrategicQuant actually checks the data first to see if there are any gaps and once it finished checking then it imports the data. So we are going to wait a little bit for the data to be imported and then I will show you how to check the data directly in StrategicQuant to see if everything went as it should. The import is complete now and I'm going to show you how to check the data. You select the symbol, click on tools and click on view and analyze. You will switch to the hourly time frame, wait a moment for the data to recalculate and now you can see that the data here is loaded from the beginning of the moment we set it which was at the beginning of the year 2023 and the data is exported for the last date we selected. When I look at the chart I can still check it afterwards for example against MetaTrader 5 Robo4x but I'm very very sure that this method using EA the data fits within the OHLC values and tick testing. And that's it for today's lesson. If you have any questions please post them in the discord and I look forward to seeing you in future lessons.

</details>
