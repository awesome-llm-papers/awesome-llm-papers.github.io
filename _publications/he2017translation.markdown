---
layout: publication
title: Translation-based Recommendation
authors: Ruining He, Wang-cheng Kang, Julian Mcauley
conference: Proceedings of the Eleventh ACM Conference on Recommender Systems
year: 2017
bibkey: he2017translation
citations: 390
additional_links: [{name: Code, url: 'https://sites.google.com/a/eng.ucsd.edu/ruining-he/'},
  {name: Paper, url: 'https://arxiv.org/abs/1707.02410'}]
tags: ["Datasets"]
short_authors: Ruining He, Wang-cheng Kang, Julian Mcauley
---
Modeling the complex interactions between users and items as well as amongst
items themselves is at the core of designing successful recommender systems.
One classical setting is predicting users' personalized sequential behavior (or
`next-item' recommendation), where the challenges mainly lie in modeling
`third-order' interactions between a user, her previously visited item(s), and
the next item to consume. Existing methods typically decompose these
higher-order interactions into a combination of pairwise relationships, by way
of which user preferences (user-item interactions) and sequential patterns
(item-item interactions) are captured by separate components. In this paper, we
propose a unified method, TransRec, to model such third-order relationships for
large-scale sequential prediction. Methodologically, we embed items into a
`transition space' where users are modeled as translation vectors operating on
item sequences. Empirically, this approach outperforms the state-of-the-art on
a wide spectrum of real-world datasets. Data and code are available at
https://sites.google.com/a/eng.ucsd.edu/ruining-he/.