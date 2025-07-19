---
layout: publication
title: Open-source Frame Semantic Parsing
authors: Chanin David
conference: Computational Linguistics
year: 2023
bibkey: chanin2023open
citations: 97
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.12788'}]
tags: [Security, Model Architecture, Tools, Training Techniques, TACL, ACL, Reinforcement
    Learning, Transformer, NAACL, EACL, COLING]
---
While the state-of-the-art for frame semantic parsing has progressed
dramatically in recent years, it is still difficult for end-users to apply
state-of-the-art models in practice. To address this, we present Frame Semantic
Transformer, an open-source Python library which achieves near state-of-the-art
performance on FrameNet 1.7, while focusing on ease-of-use. We use a T5 model
fine-tuned on Propbank and FrameNet exemplars as a base, and improve
performance by using FrameNet lexical units to provide hints to T5 at inference
time. We enhance robustness to real-world data by using textual data
augmentations during training.