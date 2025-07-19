---
layout: publication
title: Semi-parametric Video-grounded Text Generation
authors: Kim et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2023
bibkey: kim2023semi
citations: 125
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2301.11507'}]
tags: [Attention Mechanism, Transformer, Model Architecture, Language Modeling, Multimodal
    Models, AAAI, Datasets, Merging]
---
Efficient video-language modeling should consider the computational cost
because of a large, sometimes intractable, number of video frames. Parametric
approaches such as the attention mechanism may not be ideal since its
computational cost quadratically increases as the video length increases.
Rather, previous studies have relied on offline feature extraction or frame
sampling to represent the video efficiently, focusing on cross-modal modeling
in short video clips. In this paper, we propose a semi-parametric
video-grounded text generation model, SeViT, a novel perspective on scalable
video-language modeling toward long untrimmed videos. Treating a video as an
external data store, SeViT includes a non-parametric frame retriever to select
a few query-relevant frames from the data store for a given query and a
parametric generator to effectively aggregate the frames with the query via
late fusion methods. Experimental results demonstrate our method has a
significant advantage in longer videos and causal video understanding.
Moreover, our model achieves the new state of the art on four video-language
datasets, iVQA (+4.8), Next-QA (+6.9), and Activitynet-QA (+4.8) in accuracy,
and MSRVTT-Caption (+3.6) in CIDEr.