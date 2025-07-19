---
layout: publication
title: LLM Guided Inductive Inference For Solving Compositional Problems
authors: Sodani Abhigya, Moos Lauren, Mirman Matthew
conference: IEEE Transactions on Pattern Analysis and Machine Intelligence
year: 2023
bibkey: sodani2023llm
citations: 305
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2309.11688'}]
tags: [Reinforcement Learning, LLM for Code, Tools, Training Techniques]
---
While large language models (LLMs) have demonstrated impressive performance
in question-answering tasks, their performance is limited when the questions
require knowledge that is not included in the model's training data and can
only be acquired through direct observation or interaction with the real world.
Existing methods decompose reasoning tasks through the use of modules invoked
sequentially, limiting their ability to answer deep reasoning tasks. We
introduce a method, Recursion based extensible LLM (REBEL), which handles
open-world, deep reasoning tasks by employing automated reasoning techniques
like dynamic planning and forward-chaining strategies. REBEL allows LLMs to
reason via recursive problem decomposition and utilization of external tools.
The tools that REBEL uses are specified only by natural language description.
We further demonstrate REBEL capabilities on a set of problems that require a
deeply nested use of external tools in a compositional and conversational
setting.