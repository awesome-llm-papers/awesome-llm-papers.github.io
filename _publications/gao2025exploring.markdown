---
layout: publication
title: 'Exploring Hallucination Of Large Multimodal Models In Video Understanding:
  Benchmark, Analysis And Mitigation'
authors: Hongcheng Gao, Jiashu Qu, Jingyi Tang, Baolong Bi, Yue Liu, Hongyu Chen,
  Li Liang, Li Su, Qingming Huang
conference: No Venue
year: 2025
bibkey: gao2025exploring
additional_links: [{name: Code, url: 'https://github.com/Hongcheng-Gao/HAVEN'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/67e3706dc9d8214b5e2191e0'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2503.19622'}]
tags: ["Efficiency", "Ethics & Fairness", "Evaluation", "Fine-Tuning", "Has Code", "Reinforcement Learning"]
short_authors: Gao et al.
---
The hallucination of large multimodal models (LMMs), providing responses that appear correct but are actually incorrect, limits their reliability and applicability. This paper aims to study the hallucination problem of LMMs in video modality, which is dynamic and more challenging compared to static modalities like images and text. From this motivation, we first present a comprehensive benchmark termed HAVEN for evaluating hallucinations of LMMs in video understanding tasks. It is built upon three dimensions, i.e., hallucination causes, hallucination aspects, and question formats, resulting in 6K questions. Then, we quantitatively study 7 influential factors on hallucinations, e.g., duration time of videos, model sizes, and model reasoning, via experiments of 16 LMMs on the presented benchmark. In addition, inspired by recent thinking models like OpenAI o1, we propose a video-thinking model to mitigate the hallucinations of LMMs via supervised reasoning fine-tuning (SRFT) and direct preference optimization (TDPO)-- where SRFT enhances reasoning capabilities while TDPO reduces hallucinations in the thinking process. Extensive experiments and analyses demonstrate the effectiveness. Remarkably, it improves the baseline by 7.65% in accuracy on hallucination evaluation and reduces the bias score by 4.5%. The code and data are public at https://github.com/Hongcheng-Gao/HAVEN.

https://huggingface.co/discussions/paper/67e3706dc9d8214b5e2191e0