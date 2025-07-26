---
layout: publication
title: Llms Can Easily Learn To Reason From Demonstrations Structure, Not Content,
  Is What Matters!
authors: Dacheng Li, Shiyi Cao, Tyler Griggs, Shu Liu, Xiangxi Mo, Shishir G. Patil,
  Matei Zaharia, Joseph E. Gonzalez, Ion Stoica
conference: No Venue
year: 2025
bibkey: li2025llms
additional_links: [{name: Code, url: 'https://github.com/NovaSky-AI/SkyThought'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67ac1c6536464325ebe3c723'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.07374'}]
tags: ["Fine-Tuning", "Has Code", "Prompting", "Training Techniques"]
short_authors: Li et al.
---
Large reasoning models (LRMs) tackle complex reasoning problems by following long chain-of-thoughts (Long CoT) that incorporate reflection, backtracking, and self-validation. However, the training techniques and data requirements to elicit Long CoT remain poorly understood. In this work, we find that a Large Language model (LLM) can effectively learn Long CoT reasoning through data-efficient supervised fine-tuning (SFT) and parameter-efficient low-rank adaptation (LoRA). With just 17k long CoT training samples, the Qwen2.5-32B-Instruct model achieves significant improvements on a wide range of math and coding benchmarks, including 56.7% (+40.0%) on AIME 2024 and 57.0% (+8.1%) on LiveCodeBench, competitive to the proprietary o1-preview model's score of 44.6% and 59.1%. More importantly, we find that the structure of Long CoT is critical to the learning process, whereas the content of individual reasoning steps has minimal impact. Perturbations affecting content, such as training on incorrect samples or removing reasoning keywords, have little impact on performance. In contrast, structural modifications that disrupt logical consistency in the Long CoT, such as shuffling or deleting reasoning steps, significantly degrade accuracy. For example, a model trained on Long CoT samples with incorrect answers still achieves only 3.2% lower accuracy compared to training with fully correct samples. These insights deepen our understanding of how to elicit reasoning capabilities in LLMs and highlight key considerations for efficiently training the next generation of reasoning models. This is the academic paper of our previous released Sky-T1-32B-Preview model. Codes are available at https://github.com/NovaSky-AI/SkyThought.

https://huggingface.co/discussions/paper/67ac1c6536464325ebe3c723