---
layout: publication
title: 'Deepspeed-visualchat: Multi-round Multi-image Interleave Chat Via Multi-modal
  Causal Attention'
authors: Yao et al.
conference: Medical Image Analysis
year: 2023
bibkey: yao2023deepspeed
citations: 59
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2309.14327'}]
tags: [Training Techniques, Attention Mechanism, Tools, Model Architecture, Reinforcement
    Learning, Fine Tuning, Datasets]
---
Most of the existing multi-modal models, hindered by their incapacity to
adeptly manage interleaved image-and-text inputs in multi-image, multi-round
dialogues, face substantial constraints in resource allocation for training and
data accessibility, impacting their adaptability and scalability across varied
interaction realms. To address this, we present the DeepSpeed-VisualChat
framework, designed to optimize Large Language Models (LLMs) by incorporating
multi-modal capabilities, with a focus on enhancing the proficiency of Large
Vision and Language Models in handling interleaved inputs. Our framework is
notable for (1) its open-source support for multi-round and multi-image
dialogues, (2) introducing an innovative multi-modal causal attention
mechanism, and (3) utilizing data blending techniques on existing datasets to
assure seamless interactions in multi-round, multi-image conversations.
Compared to existing frameworks, DeepSpeed-VisualChat shows superior
scalability up to 70B parameter language model size, representing a significant
advancement in multi-modal language models and setting a solid foundation for
future explorations.