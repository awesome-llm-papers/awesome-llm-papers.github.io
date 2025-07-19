---
layout: publication
title: Understanding Attention For Vision-and-language Tasks
authors: Cao et al.
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: cao2022understanding
citations: 115
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2208.08104'}]
tags: [Training Techniques, Attention Mechanism, CVPR, Transformer, Model Architecture]
---
Attention mechanism has been used as an important component across
Vision-and-Language(VL) tasks in order to bridge the semantic gap between
visual and textual features. While attention has been widely used in VL tasks,
it has not been examined the capability of different attention alignment
calculation in bridging the semantic gap between visual and textual clues. In
this research, we conduct a comprehensive analysis on understanding the role of
attention alignment by looking into the attention score calculation methods and
check how it actually represents the visual region's and textual token's
significance for the global assessment. We also analyse the conditions which
attention score calculation mechanism would be more (or less) interpretable,
and which may impact the model performance on three different VL tasks,
including visual question answering, text-to-image generation, text-and-image
matching (both sentence and image retrieval). Our analysis is the first of its
kind and provides useful insights of the importance of each attention alignment
score calculation when applied at the training phase of VL tasks, commonly
ignored in attention-based cross modal models, and/or pretrained models. Our
code is available at: https://github.com/adlnlp/Attention_VL