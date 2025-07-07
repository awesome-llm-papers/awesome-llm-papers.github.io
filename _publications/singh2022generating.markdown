---
layout: publication
title: 'Progprompt: Generating Situated Robot Task Plans Using Large Language Models'
authors: Ishika Singh et al.
conference: Arxiv
year: 2022
citations: 229
bibkey: singh2022generating
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2209.11302'}]
tags: [Reinforcement Learning, Prompting]
---
Task planning can require defining myriad domain knowledge about the world in
which a robot needs to act. To ameliorate that effort, large language models
(LLMs) can be used to score potential next actions during task planning, and
even generate action sequences directly, given an instruction in natural
language with no additional domain information. However, such methods either
require enumerating all possible next steps for scoring, or generate free-form
text that may contain actions not possible on a given robot in its current
context. We present a programmatic LLM prompt structure that enables plan
generation functional across situated environments, robot capabilities, and
tasks. Our key insight is to prompt the LLM with program-like specifications of
the available actions and objects in an environment, as well as with example
programs that can be executed. We make concrete recommendations about prompt
structure and generation constraints through ablation experiments, demonstrate
state of the art success rates in VirtualHome household tasks, and deploy our
method on a physical robot arm for tabletop tasks. Website at
progprompt.github.io