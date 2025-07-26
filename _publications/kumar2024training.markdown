---
layout: publication
title: Training Language Models To Self-correct Via Reinforcement Learning
authors: Aviral Kumar, Vincent Zhuang, Rishabh Agarwal, Yi Su, John D Co-reyes, Avi
  Singh, Kate Baumli, Shariq Iqbal, Colton Bishop, Rebecca Roelofs, Lei M Zhang, Kay
  Mckinney, Disha Shrivastava, Cosmin Paduraru, George Tucker, Doina Precup, Feryal
  Behbahani, Aleksandra Faust
conference: No Venue
year: 2024
bibkey: kumar2024training
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2409.12917'}]
tags: ["Fine-Tuning", "Reinforcement Learning", "Training Techniques"]
short_authors: Kumar et al.
---
Self-correction is a highly desirable capability of large language models (LLMs), yet it has consistently been found to be largely ineffective in modern LLMs. Existing approaches for training self-correction either require multiple models or rely on a more capable model or other forms of supervision. To this end, we develop a multi-turn online reinforcement learning (RL) approach, SCoRe, that significantly improves an LLM's self-correction ability using entirely self-generated data. To build SCoRe, we first show that variants of supervised fine-tuning (SFT) on offline model-generated correction traces are insufficient for instilling self-correction behavior. In particular, we observe that training via SFT either suffers from a distribution mismatch between the training data and the model's own responses or implicitly prefers only a certain mode of correction behavior that is often not effective at test time. SCoRe addresses these challenges by training under the model's own distribution of self-generated correction traces and using appropriate regularization to steer the learning process into learning a self-correction strategy that is effective at test time as opposed to simply fitting high-reward responses for a given prompt. This regularization prescribes running a first phase of RL on a base model to generate a policy initialization that is less susceptible to collapse and then using a reward bonus to amplify self-correction during training. When applied to Gemini 1.0 Pro and 1.5 Flash models, we find that SCoRe achieves state-of-the-art self-correction performance, improving the base models' self-correction by 15.6% and 9.1% respectively on the MATH and HumanEval benchmarks.

https://huggingface.co/discussions/paper/66ed017df63ffc857d30afdd