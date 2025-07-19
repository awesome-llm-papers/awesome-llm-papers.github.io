---
layout: publication
title: Neural Story Planning
authors: Ye et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2022
bibkey: ye2022neural
citations: 104
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.08718'}]
tags: [Reinforcement Learning, Tools, Evaluation, EMNLP]
---
Automated plot generation is the challenge of generating a sequence of events
that will be perceived by readers as the plot of a coherent story. Traditional
symbolic planners plan a story from a goal state and guarantee logical causal
plot coherence but rely on a library of hand-crafted actions with their
preconditions and effects. This closed world setting limits the length and
diversity of what symbolic planners can generate. On the other hand,
pre-trained neural language models can generate stories with great diversity,
while being generally incapable of ending a story in a specified manner and can
have trouble maintaining coherence. In this paper, we present an approach to
story plot generation that unifies causal planning with neural language models.
We propose to use commonsense knowledge extracted from large language models to
recursively expand a story plot in a backward chaining fashion. Specifically,
our system infers the preconditions for events in the story and then events
that will cause those conditions to become true. We performed automatic
evaluation to measure narrative coherence as indicated by the ability to answer
questions about whether different events in the story are causally related to
other events. Results indicate that our proposed method produces more coherent
plotlines than several strong baselines.