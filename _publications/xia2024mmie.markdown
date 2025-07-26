---
layout: publication
title: 'MMIE: Massive Multimodal Interleaved Comprehension Benchmark For Large Vision-language
  Models'
authors: Peng Xia, Siwei Han, Shi Qiu, Yiyang Zhou, Zhaoyang Wang, Wenhao Zheng, Zhaorun
  Chen, Chenhang Cui, Mingyu Ding, Linjie Li, Lijuan Wang, Huaxiu Yao
conference: No Venue
year: 2024
bibkey: xia2024mmie
additional_links: [{name: Code, url: 'https://mmie-bench.github.io/'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/670dc91f1fd338212b902930'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2410.10139'}]
tags: ["Applications", "Evaluation", "Has Code"]
short_authors: Xia et al.
---
Interleaved multimodal comprehension and generation, enabling models to produce and interpret both images and text in arbitrary sequences, have become a pivotal area in multimodal learning. Despite significant advancements, the evaluation of this capability remains insufficient. Existing benchmarks suffer from limitations in data scale, scope, and evaluation depth, while current evaluation metrics are often costly or biased, lacking in reliability for practical applications. To address these challenges, we introduce MMIE, a large-scale knowledge-intensive benchmark for evaluating interleaved multimodal comprehension and generation in Large Vision-Language Models (LVLMs). MMIE comprises 20K meticulously curated multimodal queries, spanning 3 categories, 12 fields, and 102 subfields, including mathematics, coding, physics, literature, health, and arts. It supports both interleaved inputs and outputs, offering a mix of multiple-choice and open-ended question formats to evaluate diverse competencies. Moreover, we propose a reliable automated evaluation metric, leveraging a scoring model fine-tuned with human-annotated data and systematic evaluation criteria, aimed at reducing bias and improving evaluation accuracy. Extensive experiments demonstrate the effectiveness of our benchmark and metrics in providing a comprehensive evaluation of interleaved LVLMs. Specifically, we evaluate eight LVLMs, revealing that even the best models show significant room for improvement, with most achieving only moderate results. We believe MMIE will drive further advancements in the development of interleaved LVLMs. We publicly release our benchmark and code in https://mmie-bench.github.io/.

https://huggingface.co/discussions/paper/670dc91f1fd338212b902930