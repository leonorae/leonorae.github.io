+++
title = "Week 8 Update"
date = "2025-10-23T17:05:32-05:00"
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
# Week 8 Update
## This week
- Added sections to my project org file documenting installaton prerequisites (eg. I had to install the `libgraphviz-pkg` on my system to get the `cgraph.h` library rather than the `graphviz` package) as well as errors that I encounter and their fixes. This will help me with my final README targeted to users wishing to use my code as well as "future me." It will also help me create a Dockerfile or similar in the future.
- Discovered `bnlearn` python package (not the R one, which also seems good; I don't know if they are affiliated). It seems to be quite actively maintained and has a lot of helpful introductory material. It has an accessible API and good documentation which has made a lot of the implementation easier. However, this leaves me feeling like I will have to expand the scope of my project in some way, as a lot of my functions can be now reduced to a few lines of standard `model.fit; plot(model)` type code; I don't exactly mind having this problem, as it opens up the possibility to explore higher level ideas.
- Implemented basic discovery model usage with Sachs (2005) dataset
- Added more directory/module structure and stub files for planning/organization

## Next week
- Continue to implement basic features of API with
- Research and begin to implement more interesting combinations of algorithms (averaging models, meta-analysis, etc.) to implement in the API.


## Obstacles
- More dependency compatibility issues and changing APIs: quite a few of the relevant packages are in their 0.xx stage of development and have changed their dependency requirements and/or APIs since available example code has been written. Some of them seem to have been effectively abandoned with nothing to make this clear to prospective users, leading to wasted time trying to get them set up. Thankfully, the functionality I need seems to exist in newer, maintained packages.

## Process
The project update and the feedback I received really helped me feel more focused and directional this week. I think that iteratively creating project structure with directories and stubs and filling them out with implementation is helping me to stay congizant of where I am going while I am working and is helping me to avoid getting lost in unfocused exploration and/or stuck not knowing where to go next. I am also enjoying the process of using notebooks to explore/document, then moving that code to a more structured system.
