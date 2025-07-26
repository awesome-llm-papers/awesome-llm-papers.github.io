---
layout: publication
title: 'Visual Planning: Let''s Think Only With Images'
authors: "Yi Xu, Chengzu Li, Han Zhou, Xingchen Wan, Caiqi Zhang, Anna Korhonen, Ivan\
  \ Vuli\u0107"
conference: No Venue
year: 2025
bibkey: xu2025visual
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/682abb7c84695084c1a48fb4'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.11409'}]
tags: ["Reinforcement Learning", "Tools", "Training Techniques"]
short_authors: Xu et al.
---
Recent advancements in Large Language Models (LLMs) and their multimodal extensions (MLLMs) have substantially enhanced machine reasoning across diverse tasks. However, these models predominantly rely on pure text as the medium for both expressing and structuring reasoning, even when visual information is present. In this work, we argue that language may not always be the most natural or effective modality for reasoning, particularly in tasks involving spatial and geometrical information. Motivated by this, we propose a new paradigm, Visual Planning, which enables planning through purely visual representations, independent of text. In this paradigm, planning is executed via sequences of images that encode step-by-step inference in the visual domain, akin to how humans sketch or visualize future actions. We introduce a novel reinforcement learning framework, Visual Planning via Reinforcement Learning (VPRL), empowered by GRPO for post-training large vision models, leading to substantial improvements in planning in a selection of representative visual navigation tasks, FrozenLake, Maze, and MiniBehavior. Our visual planning paradigm outperforms all other planning variants that conduct reasoning in the text-only space. Our results establish Visual Planning as a viable and promising alternative to language-based reasoning, opening new avenues for tasks that benefit from intuitive, image-based inference.

https://huggingface.co/discussions/paper/682abb7c84695084c1a48fb4