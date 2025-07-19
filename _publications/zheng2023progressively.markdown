---
layout: publication
title: Progressively Efficient Learning
authors: Zheng et al.
conference: Data Mining and Knowledge Discovery
year: 2023
bibkey: zheng2023progressively
citations: 217
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.13004'}]
tags: [RAG, Agentic, Tools, Efficiency And Optimization, Reinforcement Learning]
---
Assistant AI agents should be capable of rapidly acquiring novel skills and
adapting to new user preferences. Traditional frameworks like imitation
learning and reinforcement learning do not facilitate this capability because
they support only low-level, inefficient forms of communication. In contrast,
humans communicate with progressive efficiency by defining and sharing abstract
intentions. Reproducing similar capability in AI agents, we develop a novel
learning framework named Communication-Efficient Interactive Learning (CEIL).
By equipping a learning agent with an abstract, dynamic language and an
intrinsic motivation to learn with minimal communication effort, CEIL leads to
emergence of a human-like pattern where the learner and the teacher communicate
progressively efficiently by exchanging increasingly more abstract intentions.
CEIL demonstrates impressive performance and communication efficiency on a 2D
MineCraft domain featuring long-horizon decision-making tasks. Agents trained
with CEIL quickly master new tasks, outperforming non-hierarchical and
hierarchical imitation learning by up to 50% and 20% in absolute success rate,
respectively, given the same number of interactions with the teacher.
Especially, the framework performs robustly with teachers modeled after human
pragmatic communication behavior.