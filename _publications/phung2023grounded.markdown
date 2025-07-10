---
layout: publication
title: Grounded Text-to-image Synthesis With Attention Refocusing
authors: Quynh Phung, Songwei Ge, Jia-bin Huang
conference: 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
citations: 21
bibkey: phung2023grounded
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.05427'}]
tags: [Model Architecture, Attention Mechanism, Transformer, Prompting, Evaluation,
  Merging]
---
Driven by the scalable diffusion models trained on large-scale datasets,
text-to-image synthesis methods have shown compelling results. However, these
models still fail to precisely follow the text prompt involving multiple
objects, attributes, or spatial compositions. In this paper, we reveal the
potential causes in the diffusion model's cross-attention and self-attention
layers. We propose two novel losses to refocus attention maps according to a
given spatial layout during sampling. Creating the layouts manually requires
additional effort and can be tedious. Therefore, we explore using large
language models (LLM) to produce these layouts for our method. We conduct
extensive experiments on the DrawBench, HRS, and TIFA benchmarks to evaluate
our proposed method. We show that our proposed attention refocusing effectively
improves the controllability of existing approaches.