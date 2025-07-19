---
layout: publication
title: Llm-based Interactive Imitation Learning For Robotic Manipulation
authors: Werner et al.
conference: International Journal of Intelligent Robotics and Applications
year: 2025
bibkey: werner2025llm
citations: 120
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.21769'}]
tags: [RAG, Training Techniques, Prompting, Agentic, Tools, Applications]
---
Recent advancements in machine learning provide methods to train autonomous
agents capable of handling the increasing complexity of sequential
decision-making in robotics. Imitation Learning (IL) is a prominent approach,
where agents learn to control robots based on human demonstrations. However, IL
commonly suffers from violating the independent and identically distributed
(i.i.d) assumption in robotic tasks. Interactive Imitation Learning (IIL)
achieves improved performance by allowing agents to learn from interactive
feedback from human teachers. Despite these improvements, both approaches come
with significant costs due to the necessity of human involvement. Leveraging
the emergent capabilities of Large Language Models (LLMs) in reasoning and
generating human-like responses, we introduce LLM-iTeach -- a novel IIL
framework that utilizes an LLM as an interactive teacher to enhance agent
performance while alleviating the dependence on human resources. Firstly,
LLM-iTeach uses a hierarchical prompting strategy that guides the LLM in
generating a policy in Python code. Then, with a designed similarity-based
feedback mechanism, LLM-iTeach provides corrective and evaluative feedback
interactively during the agent's training. We evaluate LLM-iTeach against
baseline methods such as Behavior Cloning (BC), an IL method, and CEILing, a
state-of-the-art IIL method using a human teacher, on various robotic
manipulation tasks. Our results demonstrate that LLM-iTeach surpasses BC in the
success rate and achieves or even outscores that of CEILing, highlighting the
potential of LLMs as cost-effective, human-like teachers in interactive
learning environments. We further demonstrate the method's potential for
generalization by evaluating it on additional tasks. The code and prompts are
provided at: https://github.com/Tubicor/LLM-iTeach.