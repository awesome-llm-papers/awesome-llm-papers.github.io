---
layout: publication
title: On The Tool Manipulation Capability Of Open-source Large Language Models
authors: Xu et al.
conference: SSRN Electronic Journal
year: 2023
bibkey: xu2023tool
citations: 99
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.16504'}]
tags: [Training Techniques, GPT, Prompting, Tools, Evaluation, Model Architecture,
  Reinforcement Learning, Security, Datasets]
---
Recent studies on software tool manipulation with large language models
(LLMs) mostly rely on closed model APIs. The industrial adoption of these
models is substantially constrained due to the security and robustness risks in
exposing information to closed LLM API services. In this paper, we ask can we
enhance open-source LLMs to be competitive to leading closed LLM APIs in tool
manipulation, with practical amount of human supervision. By analyzing common
tool manipulation failures, we first demonstrate that open-source LLMs may
require training with usage examples, in-context demonstration and generation
style regulation to resolve failures. These insights motivate us to revisit
classical methods in LLM literature, and demonstrate that we can adapt them as
model alignment with programmatic data generation, system prompts and
in-context demonstration retrievers to enhance open-source LLMs for tool
manipulation. To evaluate these techniques, we create the ToolBench, a tool
manipulation benchmark consisting of diverse software tools for real-world
tasks. We demonstrate that our techniques can boost leading open-source LLMs by
up to 90% success rate, showing capabilities competitive to OpenAI GPT-4 in 4
out of 8 ToolBench tasks. We show that such enhancement typically requires
about one developer day to curate data for each tool, rendering a recipe with
practical amount of human supervision.