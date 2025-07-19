---
layout: publication
title: 'Fmoe: Fine-grained Expert Offloading For Large Mixture-of-experts Serving'
authors: Yu et al.
conference: 2019 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2025
bibkey: yu2025fmoe
citations: 153
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.05370'}]
tags: [ICCV, Training Techniques, Prompting, Transformer, Model Architecture, Efficiency
    And Optimization, Reinforcement Learning, Applications]
---
Large Language Models (LLMs) have gained immense success in revolutionizing
various applications, including content generation, search and recommendation,
and AI-assisted operation. To reduce high training costs, Mixture-of-Experts
(MoE) architecture has become a popular backbone for modern LLMs. However,
despite the benefits, serving MoE-based LLMs experience severe memory
inefficiency due to sparsely activated experts. Recent studies propose to
offload inactive experts from GPU memory to CPU memory to improve the serving
efficiency of MoE models. However, they either incur high inference latency or
high model memory footprints due to coarse-grained designs. To tame the
latency-memory trade-off in MoE serving, we present fMoE, a fine-grained expert
offloading system for MoE serving that achieves low inference latency with
memory efficiency. We design fMoE to extract fine-grained expert selection
patterns from MoE models and semantic hints from input prompts to efficiently
guide expert prefetching, caching, and offloading decisions. fMoE is prototyped
on top of HuggingFace Transformers and deployed on a six-GPU testbed.
Experiments with open-source MoE models and real-world workloads show that fMoE
reduces inference latency by 47% and improves expert hit rate by 36% over
state-of-the-art solutions.