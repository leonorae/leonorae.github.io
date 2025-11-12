+++
title = "Week 10 Update"
date = "2025-11-11T22:33:32-06:00"
author = ""
authorTwitter = "" #do not include @
cover = ""
coverCaption = ""
tags = ["", ""]
keywords = ["", ""]
description = ""
showFullContent = false
readingTime = false
hideComments = false
color = "" #color from the theme settings
+++
## This Week
### API Improvements
- Multiple dataset selection

Just the example datasets included with bnlearn for now, but began scaffolding to implement adding new datasets using a simple dataset registry with json with tags. Endpoint for listing available datasets, which will be expanded to display more statistics.

- Comparison endpoint

Gives results from multiple specified discovery algorithms in a convenient report, so far just with pure algorithmic discovery. This isn't that useful for many datasets; I will need to add functionality for incorporating domain knowledge constraints, which is more practically useful.

- Began Final Report

Began outlining topics to cover in final report, mainly the high-level conceptual topics I have researched about how causality relates to the AI field more broadly. Main topic of research recently has been the relationship and subtle differences between causality and RL. In a sense, the Bellman equation learns causal knowledge through the agent's actions. The most obvious difference is that RL is mostly an online process, but causality learns from statistical relationships in observed data. 

## Next Week
- Polish and expand API features
- More robust testing and verification
- Further research on open research problems (mainly relation to interpretable models / agent explainability) to write about in report, possibly with code as well 
- Clean up and remove old dependencies from requirements, test reproducibility of dependencies and environment on other machines, look into containerization if time/necessary

## Impediments
Right now my main impediment with the project is the large gap between simply applying causal discovery and inference methods to data and more interesting research questions. I doubt I will have enough time to explore them with this project, so I will focus on creating a minimal finished product and learning more about the frameworks and libraries that I am using.

## Process
I think that streamlining my environment and dependency management more will make a big difference, as right now I can only work on the project directly from one computer, which obviously isn't ideal, and would make working in a team very difficult. I should have taken more care from the start with this, but I don't think that it will be difficult.
