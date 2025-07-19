---
layout: publication
title: 'CPS-LLM: Large Language Model Based Safe Usage Plan Generator For Human-in-the-loop
  Human-in-the-plant Cyber-physical System'
authors: Banerjee et al.
conference: Robotics and Computer-Integrated Manufacturing
year: 2024
bibkey: banerjee2024cps
citations: 183
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.11458'}]
tags: [Prompting, Tools, Reinforcement Learning]
---
We explore the usage of large language models (LLM) in human-in-the-loop
human-in-the-plant cyber-physical systems (CPS) to translate a high-level
prompt into a personalized plan of actions, and subsequently convert that plan
into a grounded inference of sequential decision-making automated by a
real-world CPS controller to achieve a control goal. We show that it is
relatively straightforward to contextualize an LLM so it can generate
domain-specific plans. However, these plans may be infeasible for the physical
system to execute or the plan may be unsafe for human users. To address this,
we propose CPS-LLM, an LLM retrained using an instruction tuning framework,
which ensures that generated plans not only align with the physical system
dynamics of the CPS but are also safe for human users. The CPS-LLM consists of
two innovative components: a) a liquid time constant neural network-based
physical dynamics coefficient estimator that can derive coefficients of
dynamical models with some unmeasured state variables; b) the model
coefficients are then used to train an LLM with prompts embodied with traces
from the dynamical system and the corresponding model coefficients. We show
that when the CPS-LLM is integrated with a contextualized chatbot such as BARD
it can generate feasible and safe plans to manage external events such as meals
for automated insulin delivery systems used by Type 1 Diabetes subjects.