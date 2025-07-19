---
layout: publication
title: Sentence-level Reward Model Can Generalize Better For Aligning LLM From Human
  Preference
authors: Qiu et al.
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2025
bibkey: qiu2025sentence
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.04793'}]
tags: [ICCV, Attention Mechanism, Agentic, Evaluation, Transformer, Model Architecture,
  Reinforcement Learning, Datasets]
---
Learning reward models from human preference datasets and subsequently optimizing language models via reinforcement learning has emerged as a fundamental paradigm for aligning LLMs with human preferences. The performance of the reward model plays a crucial role in the effectiveness of alignment. Previous reward models operate at a coarse-grained level, requiring the generation of a complete response to obtain a reward value. The sparse reward may present challenges for downstream reinforcement learning. While recent efforts have attempted to learn token-level reward models, the lack of explicit semantic information makes it difficult to model the credit of every individual token. In this paper, we propose assigning scores to every sentence, introducing an intermediate-grained reward model. By segmenting the complete response into sentences and applying differential operations to reward output at the start and end positions of each sentence, we can effectively model the rewards of sentences. Moreover, a novel attention mechanism is introduced to aggregate the scores of all sentences into a response-level score, which allows it to be trained using the Bradley-Terry model. On common benchmarks, our method outperforms the response-level reward model by 2.7% on RewardBench (for reward modeling evaluation) and surpasses all baselines on AlpacaEval (for alignment evaluation).