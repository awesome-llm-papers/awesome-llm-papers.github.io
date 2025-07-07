---
layout: publication
title: 'Swiftsage: A Generative Agent With Fast And Slow Thinking For Complex Interactive
  Tasks'
authors: Bill Yuchen Lin et al.
conference: Arxiv
year: 2023
citations: 17
bibkey: lin2023generative
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.17390'}]
tags: [GPT, ACL, Tools, Agentic, Reinforcement Learning, Prompting, Model Architecture]
---
We introduce SwiftSage, a novel agent framework inspired by the dual-process
theory of human cognition, designed to excel in action planning for complex
interactive reasoning tasks. SwiftSage integrates the strengths of behavior
cloning and prompting large language models (LLMs) to enhance task completion
performance. The framework comprises two primary modules: the Swift module,
representing fast and intuitive thinking, and the Sage module, emulating
deliberate thought processes. The Swift module is a small encoder-decoder LM
fine-tuned on the oracle agent's action trajectories, while the Sage module
employs LLMs such as GPT-4 for subgoal planning and grounding. We develop a
heuristic method to harmoniously integrate the two modules, resulting in a more
efficient and robust problem-solving process. In 30 tasks from the ScienceWorld
benchmark, SwiftSage significantly outperforms other methods such as SayCan,
ReAct, and Reflexion, demonstrating its effectiveness in solving complex
interactive tasks.