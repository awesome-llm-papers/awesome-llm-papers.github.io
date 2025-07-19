---
layout: publication
title: 'MATATA: Weakly Supervised End-to-end Mathematical Tool-augmented Reasoning
  For Tabular Applications'
authors: "Vinayagame Vishnou, Senay Gregory, Mart\xED Luis"
conference: 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition
year: 2024
bibkey: vinayagame2024matata
citations: 123
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.18915'}]
tags: [Training Techniques, GPT, Alt, Prompting, Agentic, Tools, CVPR, Model Architecture,
  Reinforcement Learning, Applications, Datasets]
---
Business documents often contain substantial tabular and textual information
with numerical values, requiring mathematical reasoning for effective document
understanding. While Small Language Models (SLMs) still struggle at this task,
tool-augmented multi-step agents perform better, at the cost of relying on
closed-source or larger models, external data, or extensive prompt-engineering.
This work introduces MATATA, a novel weakly supervised end-to-end approach to
train multi-step reasoning language agents for document tabular applications.
MATATA presents an annotation-free paradigm for each agent to enhance 3.8B/8B
SLMs. During its two-stage training, MATATA uses the final outcome of the
multi-step reasoning chain as weak supervision. This approach avoids having to
individually supervise each intermediate agent in the reasoning chain. By
employing an adaptive planner and shared tools across different datasets,
MATATA shows robust performance. Experiments demonstrate that MATATA achieves
state-of-the-art on FinQA, and on TAT-QA among reasoning methods based on
open-source SLMs. Although being SLM-based, MATATA closely matches GPT-4-based
frameworks on TabMWP. This novel weakly supervised approach enables training an
end-to-end multi-step reasoning agent without intermediate supervision,
supporting future developments of cost-effective powerful agentic systems.