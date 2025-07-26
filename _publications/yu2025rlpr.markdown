---
layout: publication
title: 'RLPR: Extrapolating RLVR To General Domains Without Verifiers'
authors: Tianyu Yu, Bo Ji, Shouli Wang, Shu Yao, Zefan Wang, Ganqu Cui, Lifan Yuan,
  Ning Ding, Yuan Yao, Zhiyuan Liu, Maosong Sun, Tat-seng Chua
conference: No Venue
year: 2025
bibkey: yu2025rlpr
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/685a39d80e4ad7e21975862e'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2506.18254'}]
tags: ["Reinforcement Learning"]
short_authors: Yu et al.
---
Reinforcement Learning with Verifiable Rewards (RLVR) demonstrates promising potential in advancing the reasoning capabilities of LLMs. However, its success remains largely confined to mathematical and code domains. This primary limitation stems from the heavy reliance on domain-specific verifiers, which results in prohibitive complexity and limited scalability. To address the challenge, our key observation is that LLM's intrinsic probability of generating a correct free-form answer directly indicates its own evaluation of the reasoning reward (i.e., how well the reasoning process leads to the correct answer). Building on this insight, we propose RLPR, a simple verifier-free framework that extrapolates RLVR to broader general domains. RLPR uses the LLM's own token probability scores for reference answers as the reward signal and maximizes the expected reward during training. We find that addressing the high variance of this noisy probability reward is crucial to make it work, and propose prob-to-reward and stabilizing methods to ensure a precise and stable reward from LLM intrinsic probabilities. Comprehensive experiments in four general-domain benchmarks and three mathematical benchmarks show that RLPR consistently improves reasoning capabilities in both areas for Gemma, Llama, and Qwen based models. Notably, RLPR outperforms concurrent VeriFree by 7.6 points on TheoremQA and 7.5 points on Minerva, and even surpasses strong verifier-model-dependent approaches General-Reasoner by 1.6 average points across seven benchmarks.

https://huggingface.co/discussions/paper/685a39d80e4ad7e21975862e