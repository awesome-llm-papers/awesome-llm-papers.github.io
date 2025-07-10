---
layout: publication
title: Set-of-mark Prompting Unleashes Extraordinary Visual Grounding In GPT-4V
authors: Jianwei Yang et al.
conference: Arxiv
year: 2023
citations: 16
bibkey: yang2023set
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.11441'}, {name: Code,
    url: 'https://github.com/microsoft/SoM'}]
tags: [Has Code, Model Architecture, Reinforcement Learning, Multimodal Models, Prompting,
  GPT]
---
We present Set-of-Mark (SoM), a new visual prompting method, to unleash the
visual grounding abilities of large multimodal models (LMMs), such as GPT-4V.
As illustrated in Fig. 1 (right), we employ off-the-shelf interactive
segmentation models, such as SEEM/SAM, to partition an image into regions at
different levels of granularity, and overlay these regions with a set of marks
e.g., alphanumerics, masks, boxes. Using the marked image as input, GPT-4V can
answer the questions that require visual grounding. We perform a comprehensive
empirical study to validate the effectiveness of SoM on a wide range of
fine-grained vision and multimodal tasks. For example, our experiments show
that GPT-4V with SoM in zero-shot setting outperforms the state-of-the-art
fully-finetuned referring expression comprehension and segmentation model on
RefCOCOg. Code for SoM prompting is made public at:
https://github.com/microsoft/SoM.