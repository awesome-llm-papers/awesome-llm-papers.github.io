---
layout: publication
title: Do Pre-trained Vision-language Models Encode Object States?
authors: Newman et al.
conference: Proceedings of the Thirty-First International Joint Conference on Artificial
  Intelligence
year: 2024
bibkey: newman2024do
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2409.10488'}]
tags: [Model Architecture, Prompting, AAAI, Multimodal Models, IJCAI, Datasets, Reinforcement
    Learning]
---
For a vision-language model (VLM) to understand the physical world, such as
cause and effect, a first step is to capture the temporal dynamics of the
visual world, for example how the physical states of objects evolve over time
(e.g. a whole apple into a sliced apple). Our paper aims to investigate if VLMs
pre-trained on web-scale data learn to encode object states, which can be
extracted with zero-shot text prompts. We curate an object state recognition
dataset ChangeIt-Frames, and evaluate nine open-source VLMs, including models
trained with contrastive and generative objectives. We observe that while these
state-of-the-art vision-language models can reliably perform object
recognition, they consistently fail to accurately distinguish the objects'
physical states. Through extensive experiments, we identify three areas for
improvements for VLMs to better encode object states, namely the quality of
object localization, the architecture to bind concepts to objects, and the
objective to learn discriminative visual and language encoders on object
states. Data and code are released.