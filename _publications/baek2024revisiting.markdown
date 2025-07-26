---
layout: publication
title: Revisiting In-context Learning With Long Context Language Models
authors: Jinheon Baek, Sun Jae Lee, Prakhar Gupta, Geunseob, Oh, Siddharth Dalmia,
  Prateek Kolhar
conference: No Venue
year: 2024
bibkey: baek2024revisiting
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2412.16926'}]
tags: ["In Context Learning", "Memory & Context"]
short_authors: Baek et al.
---
In-Context Learning (ICL) is a technique by which language models make predictions based on examples provided in their input context. Previously, their context window size imposed a limit on the number of examples that can be shown, making example selection techniques crucial for identifying the maximally effective set of examples. However, the recent advent of Long Context Language Models (LCLMs) has significantly increased the number of examples that can be included in context, raising an important question of whether ICL performance in a many-shot regime is still sensitive to the method of sample selection. To answer this, we revisit these approaches in the context of LCLMs through extensive experiments on 18 datasets spanning 4 tasks. Surprisingly, we observe that sophisticated example selection techniques do not yield significant improvements over a simple random sample selection method. Instead, we find that the advent of LCLMs has fundamentally shifted the challenge of ICL from that of selecting the most effective examples to that of collecting sufficient examples to fill the context window. Specifically, in certain datasets, including all available examples does not fully utilize the context window; however, by augmenting the examples in context with a simple data augmentation approach, we substantially improve ICL performance by 5%.

https://huggingface.co/discussions/paper/676a211fb161811335476846