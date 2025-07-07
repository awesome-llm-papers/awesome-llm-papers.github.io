---
layout: publication
title: 'Ask The Right Questions: Active Question Reformulation With Reinforcement
  Learning'
authors: Christian Buck et al.
conference: Sixth International Conference on Learning Representations (ICLR) 2018
year: 2017
citations: 96
bibkey: buck2017ask
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1705.07830'}]
tags: [Reinforcement Learning, Agentic]
---
We frame Question Answering (QA) as a Reinforcement Learning task, an
approach that we call Active Question Answering. We propose an agent that sits
between the user and a black box QA system and learns to reformulate questions
to elicit the best possible answers. The agent probes the system with,
potentially many, natural language reformulations of an initial question and
aggregates the returned evidence to yield the best answer. The reformulation
system is trained end-to-end to maximize answer quality using policy gradient.
We evaluate on SearchQA, a dataset of complex questions extracted from
Jeopardy!. The agent outperforms a state-of-the-art base model, playing the
role of the environment, and other benchmarks. We also analyze the language
that the agent has learned while interacting with the question answering
system. We find that successful question reformulations look quite different
from natural language paraphrases. The agent is able to discover non-trivial
reformulation strategies that resemble classic information retrieval techniques
such as term re-weighting (tf-idf) and stemming.