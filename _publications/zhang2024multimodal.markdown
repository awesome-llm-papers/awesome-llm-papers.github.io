---
layout: publication
title: 'Multimodal Self-instruct: Synthetic Abstract Image And Visual Reasoning Instruction
  Using Language Model'
authors: Wenqi Zhang, Zhenglin Cheng, Yuanyu He, Mengna Wang, Yongliang Shen, Zeqi
  Tan, Guiyang Hou, Mingqian He, Yanna Ma, Weiming Lu, Yueting Zhuang
conference: No Venue
year: 2024
bibkey: zhang2024multimodal
additional_links: [{name: Code, url: 'https://github.com/zwq2018/Multi-modal-Self-instruct'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/668df565b09a05f3d7e46d17'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2407.07053'}]
tags: ["Model Architecture"]
short_authors: Zhang et al.
---
Although most current large multimodal models (LMMs) can already understand photos of natural scenes and portraits, their understanding of abstract images, e.g., charts, maps, or layouts, and visual reasoning capabilities remains quite rudimentary. They often struggle with simple daily tasks, such as reading time from a clock, understanding a flowchart, or planning a route using a road map. In light of this, we design a multi-modal self-instruct, utilizing large language models and their code capabilities to synthesize massive abstract images and visual reasoning instructions across daily scenarios. Our strategy effortlessly creates a multimodal benchmark with 11,193 instructions for eight visual scenarios: charts, tables, simulated maps, dashboards, flowcharts, relation graphs, floor plans, and visual puzzles. This benchmark, constructed with simple lines and geometric elements, exposes the shortcomings of most advanced LMMs like Claude-3.5-Sonnet and GPT-4o in abstract image understanding, spatial relations reasoning, and visual element induction. Besides, to verify the quality of our synthetic data, we fine-tune an LMM using 62,476 synthetic chart, table and road map instructions. The results demonstrate improved chart understanding and map navigation performance, and also demonstrate potential benefits for other visual reasoning tasks. Our code is available at: https://github.com/zwq2018/Multi-modal-Self-instruct.

https://huggingface.co/discussions/paper/668df565b09a05f3d7e46d17