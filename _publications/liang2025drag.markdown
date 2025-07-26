---
layout: publication
title: 'Drag-and-drop Llms: Zero-shot Prompt-to-weights'
authors: "Zhiyuan Liang, Dongwen Tang, Yuhao Zhou, Xuanlei Zhao, Mingjia Shi, Wangbo\
  \ Zhao, Zekai Li, Peihao Wang, Konstantin Sch\xFCrholt, Damian Borth, Michael M.\
  \ Bronstein, Yang You, Zhangyang Wang, Kai Wang"
conference: No Venue
year: 2025
bibkey: liang2025drag
additional_links: [{name: Code, url: 'https://jerryliang24.github.io/DnD\{https://jerryliang24.github.io/DnD\'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/6858d099c0c8e29df8ea3cd9'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2506.16406'}]
tags: ["Prompting"]
short_authors: Liang et al.
---
Modern Parameter-Efficient Fine-Tuning (PEFT) methods such as low-rank adaptation (LoRA) reduce the cost of customizing large language models (LLMs), yet still require a separate optimization run for every downstream dataset. We introduce Drag-and-Drop LLMs (\textit\{DnD)\}, a prompt-conditioned parameter generator that eliminates per-task training by mapping a handful of unlabeled task prompts directly to LoRA weight updates. A lightweight text encoder distills each prompt batch into condition embeddings, which are then transformed by a cascaded hyper-convolutional decoder into the full set of LoRA matrices. Once trained in a diverse collection of prompt-checkpoint pairs, DnD produces task-specific parameters in seconds, yielding i) up to 12,000times lower overhead than full fine-tuning, ii) average gains up to 30% in performance over the strongest training LoRAs on unseen common-sense reasoning, math, coding, and multimodal benchmarks, and iii) robust cross-domain generalization despite never seeing the target data or labels. Our results demonstrate that prompt-conditioned parameter generation is a viable alternative to gradient-based adaptation for rapidly specializing LLMs. Our project is available at https://jerryliang24.github.io/DnD\{https://jerryliang24.github.io/DnD\}.

https://huggingface.co/discussions/paper/6858d099c0c8e29df8ea3cd9