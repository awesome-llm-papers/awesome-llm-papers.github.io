---
layout: publication
title: Grounding Language For Transfer In Deep Reinforcement Learning
authors: Narasimhan Karthik, Barzilay Regina, Jaakkola Tommi
conference: Journal of Artificial Intelligence Research
year: 2017
bibkey: narasimhan2017grounding
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1708.00133'}]
tags: [RAG, Agentic, Reinforcement Learning]
---
In this paper, we explore the utilization of natural language to drive
transfer for reinforcement learning (RL). Despite the wide-spread application
of deep RL techniques, learning generalized policy representations that work
across domains remains a challenging problem. We demonstrate that textual
descriptions of environments provide a compact intermediate channel to
facilitate effective policy transfer. Specifically, by learning to ground the
meaning of text to the dynamics of the environment such as transitions and
rewards, an autonomous agent can effectively bootstrap policy learning on a new
domain given its description. We employ a model-based RL approach consisting of
a differentiable planning module, a model-free component and a factorized state
representation to effectively use entity descriptions. Our model outperforms
prior work on both transfer and multi-task scenarios in a variety of different
environments. For instance, we achieve up to 14% and 11.5% absolute improvement
over previously existing models in terms of average and initial rewards,
respectively.