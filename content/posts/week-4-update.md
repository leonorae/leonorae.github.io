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

## Knowledge Update
I learned about the overall process of creating a causal model, estimation of causal effect, inference, refutation tests.

I learned that the [causal diagram is essentially a prior assumption](https://causalwizard.app/inference/article/causal-diagram) that is somewhat subjective. This reinforces my prior assumption that I should choose a relatively well understood, normalized, and simple dataset(s), because it would be difficult to generalize and construct complex causal models for domains I am speculating about.

I was very curious about the idea of "discovering" causal effects from essentially unstructured data, but I will assume that this is not a basic topic and leave it to research after this project has helped me to understand the basics.

## Code Update
Established that I will focus on using `dowhy` first, implement `causalnex` primarily as a comparison, use `econml` for
