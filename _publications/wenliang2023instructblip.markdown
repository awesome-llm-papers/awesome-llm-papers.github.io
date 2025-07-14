---
layout: publication
title: 'Instructblip: Towards General-purpose Vision-language Models With Instruction
  Tuning'
authors: Wenliang Dai, Junnan Li, Dongxu Li, Anthony Meng Huat Tiong, Junqi Zhao,
  Weisheng Wang, Boyang Li, Pascale Fung, Steven Hoi
conference: Arxiv
year: 2023
bibkey: wenliang2023instructblip
citations: 222
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2305.06500v2'}]
tags: [Model Architecture, Multimodal Models, Transformer, Datasets, Alt, Training
    Techniques]
---
Large-scale pre-training and instruction tuning have been successful at
creating general-purpose language models with broad competence. However,
building general-purpose vision-language models is challenging due to the rich
input distributions and task diversity resulting from the additional visual
input. Although vision-language pretraining has been widely studied,
vision-language instruction tuning remains under-explored. In this paper, we
conduct a systematic and comprehensive study on vision-language instruction
tuning based on the pretrained BLIP-2 models. We gather 26 publicly available
datasets, covering a wide variety of tasks and capabilities, and transform them
into instruction tuning format. Additionally, we introduce an instruction-aware
Query Transformer, which extracts informative features tailored to the given
instruction. Trained on 13 held-in datasets, InstructBLIP attains
state-of-the-art zero-shot performance across all 13 held-out datasets,
substantially outperforming BLIP-2 and larger Flamingo models. Our models also
lead to state-of-the-art performance when finetuned on individual downstream
tasks (e.g., 90.7% accuracy on ScienceQA questions with image contexts).
Furthermore, we qualitatively demonstrate the advantages of InstructBLIP over
concurrent multimodal models. All InstructBLIP models are open-sourced at
https://github.com/salesforce/LAVIS/tree/main/projects/instructblip.