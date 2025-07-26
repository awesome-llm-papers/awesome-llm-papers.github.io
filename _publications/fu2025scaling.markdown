---
layout: publication
title: 'Scaling Reasoning, Losing Control: Evaluating Instruction Following In Large
  Reasoning Models'
authors: Tingchen Fu, Jiawei Gu, Yafu Li, Xiaoye Qu, Yu Cheng
conference: No Venue
year: 2025
bibkey: fu2025scaling
additional_links: [{name: Code, url: 'https://github.com/TingchenFu/MathIF'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/682ea2b550671dc82688b8e2'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2505.14810'}]
tags: ["Evaluation", "Instruction Following"]
short_authors: Fu et al.
---
Instruction-following is essential for aligning large language models (LLMs) with user intent. While recent reasoning-oriented models exhibit impressive performance on complex mathematical problems, their ability to adhere to natural language instructions remains underexplored. In this work, we introduce MathIF, a dedicated benchmark for evaluating instruction-following in mathematical reasoning tasks. Our empirical analysis reveals a consistent tension between scaling up reasoning capacity and maintaining controllability, as models that reason more effectively often struggle to comply with user directives. We find that models tuned on distilled long chains-of-thought or trained with reasoning-oriented reinforcement learning often degrade in instruction adherence, especially when generation length increases. Furthermore, we show that even simple interventions can partially recover obedience, though at the cost of reasoning performance. These findings highlight a fundamental tension in current LLM training paradigms and motivate the need for more instruction-aware reasoning models. We release the code and data at https://github.com/TingchenFu/MathIF.

https://huggingface.co/discussions/paper/682ea2b550671dc82688b8e2