---
layout: publication
title: 'Agentless: Demystifying Llm-based Software Engineering Agents'
authors: Chunqiu Steven Xia, Yinlin Deng, Soren Dunn, Lingming Zhang
conference: No Venue
year: 2024
bibkey: xia2024agentless
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6684e6b6c1cbe5e008dbf284'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2407.01489'}]
tags: ["Agentic", "Llm For Code"]
short_authors: Xia et al.
---
Recent advancements in large language models (LLMs) have significantly advanced the automation of software development tasks, including code synthesis, program repair, and test generation. More recently, researchers and industry practitioners have developed various autonomous LLM agents to perform end-to-end software development tasks. These agents are equipped with the ability to use tools, run commands, observe feedback from the environment, and plan for future actions. However, the complexity of these agent-based approaches, together with the limited abilities of current LLMs, raises the following question: Do we really have to employ complex autonomous software agents? To attempt to answer this question, we build Agentless -- an agentless approach to automatically solve software development problems. Compared to the verbose and complex setup of agent-based approaches, Agentless employs a simplistic two-phase process of localization followed by repair, without letting the LLM decide future actions or operate with complex tools. Our results on the popular SWE-bench Lite benchmark show that surprisingly the simplistic Agentless is able to achieve both the highest performance (27.33%) and lowest cost (\$0.34) compared with all existing open-source software agents! Furthermore, we manually classified the problems in SWE-bench Lite and found problems with exact ground truth patch or insufficient/misleading issue descriptions. As such, we construct SWE-bench Lite-S by excluding such problematic issues to perform more rigorous evaluation and comparison. Our work highlights the current overlooked potential of a simple, interpretable technique in autonomous software development. We hope Agentless will help reset the baseline, starting point, and horizon for autonomous software agents, and inspire future work along this crucial direction.

https://huggingface.co/discussions/paper/6684e6b6c1cbe5e008dbf284