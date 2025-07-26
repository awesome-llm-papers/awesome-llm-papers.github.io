---
layout: publication
title: 'Xolver: Multi-agent Reasoning With Holistic Experience Learning Just Like
  An Olympiad Team'
authors: Md Tanzib Hosain, Salman Rahman, Md Kishor Morol, Md Rizwan Parvez
conference: No Venue
year: 2025
bibkey: hosain2025xolver
additional_links: [{name: Code, url: 'https://kagnlp.github.io/xolver.github.io/'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/68522d7f0164cd13167104f2'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2506.14234'}]
tags: ["Agentic", "Evaluation", "Has Code", "Tools", "Training Techniques"]
short_authors: Hosain et al.
---
Despite impressive progress on complex reasoning, current large language models (LLMs) typically operate in isolation - treating each problem as an independent attempt, without accumulating or integrating experiential knowledge. In contrast, expert problem solvers - such as Olympiad or programming contest teams - leverage a rich tapestry of experiences: absorbing mentorship from coaches, developing intuition from past problems, leveraging knowledge of tool usage and library functionality, adapting strategies based on the expertise and experiences of peers, continuously refining their reasoning through trial and error, and learning from other related problems even during competition. We introduce Xolver, a training-free multi-agent reasoning framework that equips a black-box LLM with a persistent, evolving memory of holistic experience. Xolver integrates diverse experience modalities, including external and self-retrieval, tool use, collaborative interactions, agent-driven evaluation, and iterative refinement. By learning from relevant strategies, code fragments, and abstract reasoning patterns at inference time, Xolver avoids generating solutions from scratch - marking a transition from isolated inference toward experience-aware language agents. Built on both open-weight and proprietary models, Xolver consistently outperforms specialized reasoning agents. Even with lightweight backbones (e.g., QWQ-32B), it often surpasses advanced models including Qwen3-235B, Gemini 2.5 Pro, o3, and o4-mini-high. With o3-mini-high, it achieves new best results on GSM8K (98.1%), AIME'24 (94.4%), AIME'25 (93.7%), Math-500 (99.8%), and LiveCodeBench-V5 (91.6%) - highlighting holistic experience learning as a key step toward generalist agents capable of expert-level reasoning. Code and data are available at https://kagnlp.github.io/xolver.github.io/.

https://huggingface.co/discussions/paper/68522d7f0164cd13167104f2