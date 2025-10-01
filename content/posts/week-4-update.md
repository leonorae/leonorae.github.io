+++
title = "Week 4 Update"
date = "2025-09-25T18:06:52-05:00"
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
This week I:

- set up a repo and preliminary environment: https://github.com/leonorae/enter-causal
- while I have used venv and uv before, reinforced knowledge of environment setup with [this post](https://medium.com/codecodecode/uv-virtualenv-direnv-a-fast-reproducible-python-workflow-with-envrc-36da47ce1f4b)
- gathered learning resources and learned high-level concepts of causal inference
- collected a set of “canonical” datasets for possible use later
- organized learning resources and notes, project goals and intermediate tasks, and detailed weekly plan, into a planning document

Next week:

- Complete dowhy tutorial and implement a minimal pipeline of my own with synthetic/simple data
- Complete a basic fastapi inference endpoint 
- Write basic tests 
- Update and expand personal website, maybe an overview/intro article if time



Process:

I was much more organized this week, and I feel like the project direction is clearer thanks to helpful feedback on my proposal. I need to follow my own advice of sticking to completing the set goal before going too far into research rabbitholes a little bit more, but next week’s goals are very tangible so it should be reasonably easy to complete them and still have time to brainstorm.
## Knowledge Update
I learned about the overall process of creating a causal model, estimation of causal effect, inference, refutation tests.

I learned that the [causal diagram is essentially a prior assumption](https://causalwizard.app/inference/article/causal-diagram) that is somewhat subjective. This reinforces my prior assumption that I should choose a relatively well understood, normalized, and simple dataset(s), because it would be difficult to generalize and construct complex causal models for domains I am speculating about.

I was very curious about the idea of "discovering" causal effects from essentially unstructured data, but I will assume that this is not a basic topic and leave it to research after this project has helped me to understand the basics.

## Code Update
Established that I will focus on using `dowhy` first, implement `causalnex` primarily as a comparison, use `econml` for
