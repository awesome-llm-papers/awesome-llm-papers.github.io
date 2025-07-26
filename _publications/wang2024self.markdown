---
layout: publication
title: Self-taught Evaluators
authors: Tianlu Wang, Ilia Kulikov, Olga Golovneva, Ping Yu, Weizhe Yuan, Jane Dwivedi-yu,
  Richard Yuanzhe Pang, Maryam Fazel-zarandi, Jason Weston, Xian Li
conference: No Venue
year: 2024
bibkey: wang2024self
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2408.02666'}]
tags: ["Evaluation"]
short_authors: Wang et al.
---
Model-based evaluation is at the heart of successful model development -- as a reward model for training, and as a replacement for human evaluation. To train such evaluators, the standard approach is to collect a large amount of human preference judgments over model responses, which is costly and the data becomes stale as models improve. In this work, we present an approach that aims to im-prove evaluators without human annotations, using synthetic training data only. Starting from unlabeled instructions, our iterative self-improvement scheme generates contrasting model outputs and trains an LLM-as-a-Judge to produce reasoning traces and final judgments, repeating this training at each new iteration using the improved predictions. Without any labeled preference data, our Self-Taught Evaluator can improve a strong LLM (Llama3-70B-Instruct) from 75.4 to 88.3 (88.7 with majority vote) on RewardBench. This outperforms commonly used LLM judges such as GPT-4 and matches the performance of the top-performing reward models trained with labeled examples.

https://huggingface.co/discussions/paper/66b18cfd973a754d6822770c