---
layout: publication
title: 'Mvbench: A Comprehensive Multi-modal Video Understanding Benchmark'
authors: Kunchang Li et al.
conference: Arxiv
year: 2023
citations: 39
bibkey: li2023comprehensive
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.17005'}, {name: Code,
    url: 'https://github.com/OpenGVLab/Ask-Anything'}]
tags: [Ethics and Bias, Training Techniques, Fine-Tuning, Tools, Reinforcement Learning,
  Has Code, Fairness, Bias Mitigation]
---
With the rapid development of Multi-modal Large Language Models (MLLMs), a
number of diagnostic benchmarks have recently emerged to evaluate the
comprehension capabilities of these models. However, most benchmarks
predominantly assess spatial understanding in the static image tasks, while
overlooking temporal understanding in the dynamic video tasks. To alleviate
this issue, we introduce a comprehensive Multi-modal Video understanding
Benchmark, namely MVBench, which covers 20 challenging video tasks that cannot
be effectively solved with a single frame. Specifically, we first introduce a
novel static-to-dynamic method to define these temporal-related tasks. By
transforming various static tasks into dynamic ones, we enable the systematic
generation of video tasks that require a broad spectrum of temporal skills,
ranging from perception to cognition. Then, guided by the task definition, we
automatically convert public video annotations into multiple-choice QA to
evaluate each task. On one hand, such a distinct paradigm allows us to build
MVBench efficiently, without much manual intervention. On the other hand, it
guarantees evaluation fairness with ground-truth video annotations, avoiding
the biased scoring of LLMs. Moreover, we further develop a robust video MLLM
baseline, i.e., VideoChat2, by progressive multi-modal training with diverse
instruction-tuning data. The extensive results on our MVBench reveal that, the
existing MLLMs are far from satisfactory in temporal understanding, while our
VideoChat2 largely surpasses these leading models by over 15% on MVBench. All
models and data are available at https://github.com/OpenGVLab/Ask-Anything.