---
layout: publication
title: Iterative Graph Alignment
authors: Yu Fangyuan, Arora Hardeep Singh, Johnson Matt
conference: Proceedings 2006 IEEE International Conference on Robotics and Automation,
  2006. ICRA 2006.
year: 2024
bibkey: yu2024iterative
citations: 408
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2408.16667'}]
tags: [ICRA, Training Techniques, Prompting, Evaluation, Reinforcement Learning, Fine
    Tuning]
---
By compressing diverse narratives, LLMs go beyond memorization, achieving
intelligence by capturing generalizable causal relationships. However, they
suffer from local 'representation gaps' due to insufficient training data
diversity, limiting their real-world utility, especially in tasks requiring
strict alignment to rules. Traditional alignment methods relying on heavy human
annotations are inefficient and unscalable. Recent self-alignment techniques
also fall short, as they often depend on self-selection based prompting and
memorization-based learning. To address these issues, we introduce Iterative
Graph Alignment (IGA), an annotation-free rule-based alignment algorithm. A
teacher model (VLM) employs Iterative Graph Prompting (IGP) to create logical
graphs and reference answers. The student model (LLM) identifies local
knowledge gaps by attempting to align its responses with these references,
collaborating with helper models to generate diverse answers. These aligned
responses are then used for iterative supervised fine-tuning (SFT). Our
evaluations across five rule-based scenarios demonstrate IGP's effectiveness,
with a 73.12% alignment improvement in Claude Sonnet 3.5, and
Llama3-8B-Instruct achieving an 86.20% improvement, outperforming Claude
Sonnet 3.5 in rule-based alignment.