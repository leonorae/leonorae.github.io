+++
title = "Causal Inference Package Comparison"
date = "2025-10-02T18:34:23-05:00"
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


https://pgmpy.org/
Lower level implementations of algorithms used in bnlearn

https://www.pywhy.org/dowhy/v0.8/getting_started/comparison.html

https://causalnex.readthedocs.io/en/latest/05_resources/05_faq.html#what-are-the-benefits-of-using-causalnex

https://www.pywhy.org/dowhy/v0.13/

https://github.com/mckinsey/causalnex

**** tigramite
https://jakobrunge.github.io/tigramite/


**** scikit-uplift

https://www.uplift-modeling.com/en/latest/index.html
## Bayesian Networks



## Causal Discovery
### [bnlearn](https://github.com/erdogant/bnlearn)
This seems to be the most complete, well designed, and well-documented package for discovery methods. The API is simple and there are many good examples provided.

### [causal-learn](https://causal-learn.readthedocs.io/en/latest/)

Based on Tetrad Java project. Contains some methods that aren't in bnlearn.



### dodiscover
dodiscover is a Python package for representing causal graphs. For example, Acyclic Directed Mixed Graphs (ADMG), also known as causal DAGs and Partial Ancestral Graphs (PAGs). It is largely an API wrapper around algorithms implemented in `causal-learn` and other libraries.

Incomplete, experimental, and not released; it doesn't seem to be maintained nor has it been updated in the past year.
