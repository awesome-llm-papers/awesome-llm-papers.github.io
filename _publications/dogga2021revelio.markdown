---
layout: publication
title: 'Revelio: Ml-generated Debugging Queries For Distributed Systems'
authors: Dogga et al.
conference: Communications of the ACM
year: 2021
bibkey: dogga2021revelio
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.14347'}]
tags: [Tools, Training Techniques, Applications]
---
A major difficulty in debugging distributed systems lies in manually
determining which of the many available debugging tools to use and how to query
its logs. Our own study of a production debugging workflow confirms the
magnitude of this burden. This paper explores whether a machine-learning model
can assist developers in distributed systems debugging. We present Revelio, a
debugging assistant which takes user reports and system logs as input, and
outputs debugging queries that developers can use to find a bug's root cause.
The key challenges lie in (1) combining inputs of different types (e.g.,
natural language reports and quantitative logs) and (2) generalizing to unseen
faults. Revelio addresses these by employing deep neural networks to uniformly
embed diverse input sources and potential queries into a high-dimensional
vector space. In addition, it exploits observations from production systems to
factorize query generation into two computationally and statistically simpler
learning tasks. To evaluate Revelio, we built a testbed with multiple
distributed applications and debugging tools. By injecting faults and training
on logs and reports from 800 Mechanical Turkers, we show that Revelio includes
the most helpful query in its predicted list of top-3 relevant queries 96% of
the time. Our developer study confirms the utility of Revelio.