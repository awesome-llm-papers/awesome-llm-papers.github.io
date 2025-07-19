---
layout: publication
title: 'Colmdriver: Llm-based Negotiation Benefits Cooperative Autonomous Driving'
authors: Liu et al.
conference: 16th International IEEE Conference on Intelligent Transportation Systems
  (ITSC 2013)
year: 2025
bibkey: liu2025colmdriver
citations: 80
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.08683'}]
tags: [Datasets, Agentic, Evaluation, Reinforcement Learning, Responsible AI]
---
Vehicle-to-vehicle (V2V) cooperative autonomous driving holds great promise
for improving safety by addressing the perception and prediction uncertainties
inherent in single-agent systems. However, traditional cooperative methods are
constrained by rigid collaboration protocols and limited generalization to
unseen interactive scenarios. While LLM-based approaches offer generalized
reasoning capabilities, their challenges in spatial planning and unstable
inference latency hinder their direct application in cooperative driving. To
address these limitations, we propose CoLMDriver, the first full-pipeline
LLM-based cooperative driving system, enabling effective language-based
negotiation and real-time driving control. CoLMDriver features a parallel
driving pipeline with two key components: (i) an LLM-based negotiation module
under an actor-critic paradigm, which continuously refines cooperation policies
through feedback from previous decisions of all vehicles; and (ii) an
intention-guided waypoint generator, which translates negotiation outcomes into
executable waypoints. Additionally, we introduce InterDrive, a CARLA-based
simulation benchmark comprising 10 challenging interactive driving scenarios
for evaluating V2V cooperation. Experimental results demonstrate that
CoLMDriver significantly outperforms existing approaches, achieving an 11%
higher success rate across diverse highly interactive V2V driving scenarios.
Code will be released on https://github.com/cxliu0314/CoLMDriver.