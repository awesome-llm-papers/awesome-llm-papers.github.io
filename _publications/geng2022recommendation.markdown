---
layout: publication
title: 'Recommendation As Language Processing (RLP): A Unified Pretrain, Personalized
  Prompt & Predict Paradigm (P5)'
authors: Shijie Geng, Shuchang Liu, Zuohui Fu, Yingqiang Ge, Yongfeng Zhang
conference: Arxiv
year: 2022
citations: 239
bibkey: geng2022recommendation
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.13366'}, {name: Code,
    url: 'https://github.com/jeykigung/P5'}]
tags: [Training Techniques, Fine-Tuning, Few-Shot, Tools, RecSys, Reinforcement Learning,
  Has Code, Survey Paper, Prompting, Model Architecture]
---
For a long time, different recommendation tasks typically require designing
task-specific architectures and training objectives. As a result, it is hard to
transfer the learned knowledge and representations from one task to another,
thus restricting the generalization ability of existing recommendation
approaches, e.g., a sequential recommendation model can hardly be applied or
transferred to a review generation method. To deal with such issues,
considering that language can describe almost anything and language grounding
is a powerful medium to represent various problems or tasks, we present a
flexible and unified text-to-text paradigm called "Pretrain, Personalized
Prompt, and Predict Paradigm" (P5) for recommendation, which unifies various
recommendation tasks in a shared framework. In P5, all data such as user-item
interactions, user descriptions, item metadata, and user reviews are converted
to a common format -- natural language sequences. The rich information from
natural language assists P5 to capture deeper semantics for personalization and
recommendation. Specifically, P5 learns different tasks with the same language
modeling objective during pretraining. Thus, it serves as the foundation model
for various downstream recommendation tasks, allows easy integration with other
modalities, and enables instruction-based recommendation based on prompts. P5
advances recommender systems from shallow model to deep model to big model, and
will revolutionize the technical form of recommender systems towards universal
recommendation engine. With adaptive personalized prompt for different users,
P5 is able to make predictions in a zero-shot or few-shot manner and largely
reduces the necessity for extensive fine-tuning. On several recommendation
benchmarks, we conduct experiments to show the effectiveness of P5. We release
the source code at https://github.com/jeykigung/P5.