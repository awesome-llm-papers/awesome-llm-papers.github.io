---
layout: publication
title: End-to-end Task-completion Neural Dialogue Systems
authors: Li et al.
conference: Arxiv
year: 2017
bibkey: li2017end
citations: 249
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1703.01008'}]
tags: [Agentic, Tools, Evaluation, Reinforcement Learning]
---
One of the major drawbacks of modularized task-completion dialogue systems is
that each module is trained individually, which presents several challenges.
For example, downstream modules are affected by earlier modules, and the
performance of the entire system is not robust to the accumulated errors. This
paper presents a novel end-to-end learning framework for task-completion
dialogue systems to tackle such issues. Our neural dialogue system can directly
interact with a structured database to assist users in accessing information
and accomplishing certain tasks. The reinforcement learning based dialogue
manager offers robust capabilities to handle noises caused by other components
of the dialogue system. Our experiments in a movie-ticket booking domain show
that our end-to-end system not only outperforms modularized dialogue system
baselines for both objective and subjective evaluation, but also is robust to
noises as demonstrated by several systematic experiments with different error
granularity and rates specific to the language understanding module.