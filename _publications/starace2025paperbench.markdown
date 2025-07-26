---
layout: publication
title: 'Paperbench: Evaluating Ai''s Ability To Replicate AI Research'
authors: Giulio Starace, Oliver Jaffe, Dane Sherburn, James Aung, Jun Shern Chan,
  Leon Maksin, Rachel Dias, Evan Mays, Benjamin Kinsella, Wyatt Thompson, Johannes
  Heidecke, Amelia Glaese, Tejal Patwardhan
conference: No Venue
year: 2025
bibkey: starace2025paperbench
additional_links: [{name: Code, url: 'https://github.com/openai/preparedness\{open-source'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67edf3d679018bf61e0504c0'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.01848'}]
tags: ["Evaluation"]
short_authors: Starace et al.
---
We introduce PaperBench, a benchmark evaluating the ability of AI agents to replicate state-of-the-art AI research. Agents must replicate 20 ICML 2024 Spotlight and Oral papers from scratch, including understanding paper contributions, developing a codebase, and successfully executing experiments. For objective evaluation, we develop rubrics that hierarchically decompose each replication task into smaller sub-tasks with clear grading criteria. In total, PaperBench contains 8,316 individually gradable tasks. Rubrics are co-developed with the author(s) of each ICML paper for accuracy and realism. To enable scalable evaluation, we also develop an LLM-based judge to automatically grade replication attempts against rubrics, and assess our judge's performance by creating a separate benchmark for judges. We evaluate several frontier models on PaperBench, finding that the best-performing tested agent, Claude 3.5 Sonnet (New) with open-source scaffolding, achieves an average replication score of 21.0%. Finally, we recruit top ML PhDs to attempt a subset of PaperBench, finding that models do not yet outperform the human baseline. We https://github.com/openai/preparedness\{open-source our code\} to facilitate future research in understanding the AI engineering capabilities of AI agents.

https://huggingface.co/discussions/paper/67edf3d679018bf61e0504c0