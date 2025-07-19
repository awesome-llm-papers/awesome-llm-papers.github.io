---
layout: publication
title: What Happens When Generative AI Models Train Recursively On Each Others' Generated
  Outputs?
authors: Vu Hung Anh, Reeves Galen, Wenger Emily
conference: Nature
year: 2025
bibkey: vu2025what
citations: 178
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.21677'}]
tags: [Tools, Training Techniques]
---
The internet is full of AI-generated content while also serving as a common source of training data for generative AI (genAI) models. This duality raises the possibility that future genAI models may be trained on other models' generated outputs. Prior work has studied consequences of models training on their own generated outputs, but limited work has considered what happens if models ingest content produced by other models. Given society's increasing dependence on genAI tools, understanding downstream effects of such data-mediated model interactions is critical. To this end, we provide empirical evidence for how data-mediated interactions might unfold in practice, develop a theoretical model for this interactive training process, and show experimentally possible long-term results of such interactions. We find that data-mediated interactions can benefit models by exposing them to novel concepts perhaps missed in original training data, but also can homogenize their performance on shared tasks.