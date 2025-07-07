---
layout: publication
title: Counterfactual Story Reasoning And Generation
authors: Lianhui Qin et al.
conference: Arxiv
year: 2019
citations: 24
bibkey: qin2019counterfactual
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.04076'}]
tags: [Language Modeling, Reinforcement Learning]
---
Counterfactual reasoning requires predicting how alternative events, contrary
to what actually happened, might have resulted in different outcomes. Despite
being considered a necessary component of AI-complete systems, few resources
have been developed for evaluating counterfactual reasoning in narratives.
  In this paper, we propose Counterfactual Story Rewriting: given an original
story and an intervening counterfactual event, the task is to minimally revise
the story to make it compatible with the given counterfactual event. Solving
this task will require deep understanding of causal narrative chains and
counterfactual invariance, and integration of such story reasoning capabilities
into conditional language generation models.
  We present TimeTravel, a new dataset of 29,849 counterfactual rewritings,
each with the original story, a counterfactual event, and human-generated
revision of the original story compatible with the counterfactual event.
Additionally, we include 80,115 counterfactual "branches" without a rewritten
storyline to support future work on semi- or un-supervised approaches to
counterfactual story rewriting.
  Finally, we evaluate the counterfactual rewriting capacities of several
competitive baselines based on pretrained language models, and assess whether
common overlap and model-based automatic metrics for text generation correlate
well with human scores for counterfactual rewriting.