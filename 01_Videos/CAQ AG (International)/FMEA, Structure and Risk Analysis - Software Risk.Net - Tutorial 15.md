---
title: "FMEA, Structure and Risk Analysis - Software Risk.Net - Tutorial 1/5"
people_mentioned: ["New Structure", "Create Structure Tree", "New Structure Element", "Structure Element", "New Function", "Function Structure Element", "Selected Structure Element", "Risk Evaluation"]
channel: "CAQ AG (International)"
video_id: "GSCaVJiwHZo"
url: "https://www.youtube.com/watch?v=GSCaVJiwHZo"
publish_date: 2020-10-30
duration: "16:00"
word_count: 1827
content_type: "tutorial"
delivery_mode: "technique"
broad_category: "finance-investing"
subcategories: ["valuation", "risk-management"]
series_name: ""
episode_id: ""
primary_person: "New Structure"
host_names: []
interviewer_names: []
interviewee_profiles: []
speaker_profiles: ["New Structure"]
organizations_mentioned: ["CAQ AG (International)"]
locations_mentioned: []
tools_mentioned: []
companies_mentioned: []
topics: ["valuation", "risk-management", "ai-safety", "product-management"]
tags: ["valuation", "risk-management", "ai-safety", "product-management"]
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

The discussion centers on structure, analysis, function. Every time you create or update a risk analysis based on an element of a structure analysis, Risk.Net will automatically create a new risk. In order to perform a structure analysis, you will first have to create a new structure world, that is the object that is to. The process tab "Structure Analysis" now allows you to determine which element of the structure analysis will be examined.

## Key Insights


- Every time you create or update a risk analysis based on an element of a structure analysis, Risk.Net will automatically create a new risk analysis position.
- In order to perform a structure analysis, you will first have to create a new structure world, that is the object that is to be examined.
- The process tab "Structure Analysis" now allows you to determine which element of the structure analysis will be examined.
- After the structure analysis is complete, the next step will be the function analysis, which is used to describe the various functions of the individual structure.
- This concludes the failure analysis and the structure analysis of the coolant pump is complete.
- You will first have to select the structure world containing the relevant structure analysis â€“ in this case, this is the structure world "Pump".

## People Mentioned


- [[New Structure]]

- [[Create Structure Tree]]

- [[New Structure Element]]

- [[Structure Element]]

- [[New Function]]

- [[Function Structure Element]]

- [[Selected Structure Element]]




## Full Transcript

<details>
<summary>Click to expand full transcript (1827 words)</summary>

The structure analysis allows you to perform a comprehensive examination of the structure, the function, and potential sources of failures of any given object. The results of such an examination can then be evaluated in a risk analysis. In this example, the structure of a coolant pump will be examined, followed by the creation of a risk analysis based on the results. In order to perform a structure analysis, you will first have to create a new structure world, that is the object that is to be examined, in the "Structure Analysis" view. To do this, mark the topmost node in the tree structure, and then click "New" â€“ "New Structure". This will open the "Create Structure Tree World" window, in which you will have to enter a name for the structure world. In this example, the structure world will simply be called "Pump". The "Risk Evaluation" field allows you to define a risk evaluation. Selecting a risk evaluation at this point will later aid you in creating failures, as it allows you to not only define a name for them, but also to select a failure severity. Once all entries are made, click the "Ok" button to create the structure world. The actual structure analysis will then be conducted in the right-hand side of the window. It consists of three steps: The examination of the structural makeup of the object, the function analysis of its elements, and the failure analysis. The first step is the examination of the structure. In this step, the examined object will be "mentally disassembled" into its individual parts piece by piece. In this example, a coolant pump will be analysed, meaning this pump will serve as the basis of the examination. In order to add it to the analysis, first select the structure world in the tree and then click the "New Structure Element" button. This will open the "Structure Element" window, in which you will have to define the name of the new element. The coolant pump is the starting point of the structure analysis. Its structure will now be described by adding further structure elements. In this example, it will consist of a casing and a rotor. These elements can also be created via the "New Structure Element" button. Once the makeup of the pump has been defined, the same needs to be done for its elements. In this example, the casing consists of a carcass, a cover, a cover seal, and cover bolting. These elements will now be added to the structure. The keystroke combination "Ctrl+E" allows you to comfortably create several structure elements directly one after another. In this way, the structure analysis allows you to describe an arbitrarily complex structure for any given object, which allows for a risk evaluation of each of its components. After the structure analysis is complete, the next step will be the function analysis, which is used to describe the various functions of the individual structure elements. The function of the coolant pump itself, for example, is to provide a steady supply of coolant. In order to add this function to the pump, select the corresponding structure element, and then click the "New Function" button. This will open the "Function Structure Element" window, in which the function needs to be described. The new function has now been added to the element and is listed in the "Functions of Selected Structure Element" section. In this way you can determine the functions of all structure elements. The next element is the casing. Its function is to hold the coolant. Additionally, it is physically the largest part of the pump, which is why it should have an attractive design, if possible. Like structure elements, functions can also be created using a keystroke combination, in this case using the keys "Ctrl+F". This concludes the definition of the functions of the casing. The functions of the remaining elements can be defined in the same way. The next step of the function analysis is to determine the correlation of the individual functions, that is to describe which functions of a given element are facilitated by which function of its sub-elements. The function of the coolant pump in this example is to provide a reliable supply of coolant. This function is shown in the "Functions of Selected Structure Element" section. To the right of this section, all sub-elements of the coolant pump and their respective functions are listed â€“ in this case this is the casing whose function is to hold the coolant. The coolant supply provided by the pump is directly dependent on the casing actually holding coolant. In order to determine this correlation, the functions will be linked. To do this, click and hold the "Holds Coolant" function of the casing and then drag it onto the "Coolant Provision" function of the coolant pump. The two functions are now linked and the subordinate function is listed underneath the "Coolant Provision" function. The same procedure is used to establish links between all functions of all structure elements which correlate with one another. As for the casing, all of its elements have functions that are directly involved in facilitating its function of safely and reliably providing coolant. Once all dependencies between the various functions have been determined, the function analysis is complete, and you can proceed to the failure analysis. In a failure analysis, you define the failures that might occur at the individual structure elements and have an adverse effect on the functions. For example, an obvious failure occurring at the pump might be that it does not deliver any coolant. To create this failure, first mark the function you want to add it to in the "Failures of Selected Function" section and then either click the "New Failure" button or press the keystroke combination "Ctrl+F". This will open the "Failure Structure Element" window, in which you will have to enter a name for the failure. This window also allows you to define a severity and a failure type for the failure, which will be relevant later when creating a risk analysis. Follow the same procedure to define all potential failures that might occur for the remaining elements of the pump. Failures that might occur for the casing, thus preventing it from being able to hold or conserve the coolant, might be for example leakiness or breakage of the casing. Lastly, you will have to define possible failures for the sub-elements of the casing. In order to conclude the failure analysis, the correlation between the individual failures need to be determined just like the correlations between the functions had to be determined in the function analysis. That means you will have to define which failures of a subordinate element cause which failures of its superordinate element. To do this, select the structure element and function for which you want to define the failure correlations. The "Failures of Selected Function" section shows the failures that have been defined for the function. To the right of this section, the failures of those functions will be displayed that have been linked to the currently selected function during the function analysis. Failures are linked to each other in the same way as functions are linked â€“ by dragging the failures of the linked functions onto the failures of the selected function. In case of the coolant pump, for example, both leakiness and breakage of the casing would result in the pump not being able to provide coolant anymore. As for the casing, a malfunction of any one of its components would always result in it becoming leaky. Additionally, loose cover bolting or breakage of the carcass might result in damage to the entire component. This concludes the failure analysis and the structure analysis of the coolant pump is complete. This analysis can now be used to conduct a risk analysis for each of the examined elements. To do this, first switch to the "Details" view and create a new risk analysis. The process tab "Structure Analysis" now allows you to determine which element of the structure analysis will be examined. You will first have to select the structure world containing the relevant structure analysis â€“ in this case, this is the structure world "Pump". You will then have to use the "Focus Element" field to select the focus element for the risk analysis, that is you will have to select the element of the structure analysis that will be examined. In this example, the focus element of the risk analysis will be the casing of the coolant pump. Once the focus element has been selected, you can create a risk analysis by clicking the "Create/Update Risk Analysis" button. This will open the "Create/Update Risk Analysis" window, which shows the structure of the new risk analysis. Every time you create or update a risk analysis based on an element of a structure analysis, Risk.Net will automatically create a new risk analysis position containing all elements that will be created. If, for the creation of the new records, information is required that is not provided by the structure analysis, this information needs to be added now. Relevant records are marked with an exclamation mark in the tree structure and can be opened and edited by double-clicking them. In this example, the failure type for the two failures created for the casing of the coolant pump in the structure analysis has not yet been defined. In order to be able to create the risk analysis, the failure type has to be determined now. When all required data has been added, click the "Ok" button to create the risk analysis. This concludes the creation of the risk analysis based on a structure analysis. The risk analysis structure will be the following: The failures in the risk analysis will be the failures that have been created for the selected focus element in the structure analysis â€“ in this case, these are the leakiness of and the damage to the casing of the coolant pump. In the structure analysis, these failures have been linked to other failures in two directions: On the one hand, they have been linked to the failures of the functions of the subordinate structure elements, which might cause them. On the other hand, they have been linked to the failures of the superordinate structure element, which they in turn might cause themselves. In the risk analysis, these failures are now used as root causes on the one hand, and as failure consequences on the other hand. For example, breakage of the carcass of the casing of the coolant pumpâ€¦ â€¦ is a cause for the occurrence of the failure of damage to the casing â€¦ â€¦ which in turn might lead to the consequence that the coolant provision through the coolant pump cannot be guaranteed anymore. In this way, structure analyses allow you to perform structure, function, and error analyses for any given object and then evaluate the results in a risk analysis.

</details>
