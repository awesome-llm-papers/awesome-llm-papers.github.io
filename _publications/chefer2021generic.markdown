---
layout: publication
title: Generic Attention-model Explainability For Interpreting Bi-modal And Encoder-decoder
  Transformers
authors: Hila Chefer, Shir Gur, Lior Wolf
conference: 2021 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2021
bibkey: chefer2021generic
citations: 176
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.15679'}]
tags: ["ICCV", "Model Architecture"]
short_authors: Hila Chefer, Shir Gur, Lior Wolf
---
Transformers are increasingly dominating multi-modal reasoning tasks, such as
visual question answering, achieving state-of-the-art results thanks to their
ability to contextualize information using the self-attention and co-attention
mechanisms. These attention modules also play a role in other computer vision
tasks including object detection and image segmentation. Unlike Transformers
that only use self-attention, Transformers with co-attention require to
consider multiple attention maps in parallel in order to highlight the
information that is relevant to the prediction in the model's input. In this
work, we propose the first method to explain prediction by any
Transformer-based architecture, including bi-modal Transformers and
Transformers with co-attentions. We provide generic solutions and apply these
to the three most commonly used of these architectures: (i) pure
self-attention, (ii) self-attention combined with co-attention, and (iii)
encoder-decoder attention. We show that our method is superior to all existing
methods which are adapted from single modality explainability.