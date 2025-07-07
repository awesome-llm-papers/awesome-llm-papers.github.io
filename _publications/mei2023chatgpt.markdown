---
layout: publication
title: 'Wavcaps: A Chatgpt-assisted Weakly-labelled Audio Captioning Dataset For Audio-language
  Multimodal Research'
authors: Xinhao Mei et al.
conference: Arxiv
year: 2023
citations: 48
bibkey: mei2023chatgpt
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.17395'}, {name: Code,
    url: 'https://github.com/XinhaoMei/WavCaps'}]
tags: [GPT, RAG, Has Code, Multimodal Models, Model Architecture]
---
The advancement of audio-language (AL) multimodal learning tasks has been
significant in recent years. However, researchers face challenges due to the
costly and time-consuming collection process of existing audio-language
datasets, which are limited in size. To address this data scarcity issue, we
introduce WavCaps, the first large-scale weakly-labelled audio captioning
dataset, comprising approximately 400k audio clips with paired captions. We
sourced audio clips and their raw descriptions from web sources and a sound
event detection dataset. However, the online-harvested raw descriptions are
highly noisy and unsuitable for direct use in tasks such as automated audio
captioning. To overcome this issue, we propose a three-stage processing
pipeline for filtering noisy data and generating high-quality captions, where
ChatGPT, a large language model, is leveraged to filter and transform raw
descriptions automatically. We conduct a comprehensive analysis of the
characteristics of WavCaps dataset and evaluate it on multiple downstream
audio-language multimodal learning tasks. The systems trained on WavCaps
outperform previous state-of-the-art (SOTA) models by a significant margin. Our
aspiration is for the WavCaps dataset we have proposed to facilitate research
in audio-language multimodal learning and demonstrate the potential of
utilizing ChatGPT to enhance academic research. Our dataset and codes are
available at https://github.com/XinhaoMei/WavCaps.