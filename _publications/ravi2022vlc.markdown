---
layout: publication
title: 'VLC-BERT: Visual Question Answering With Contextualized Commonsense Knowledge'
authors: Sahithya Ravi, Aditya Chinchure, Leonid Sigal, Renjie Liao, Vered Shwartz
conference: 2023 IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)
year: 2022
citations: 25
bibkey: ravi2022vlc
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.13626'}]
tags: [Model Architecture, Transformer, Multimodal Models, BERT, Evaluation]
---
There has been a growing interest in solving Visual Question Answering (VQA)
tasks that require the model to reason beyond the content present in the image.
In this work, we focus on questions that require commonsense reasoning. In
contrast to previous methods which inject knowledge from static knowledge
bases, we investigate the incorporation of contextualized knowledge using
Commonsense Transformer (COMET), an existing knowledge model trained on
human-curated knowledge bases. We propose a method to generate, select, and
encode external commonsense knowledge alongside visual and textual cues in a
new pre-trained Vision-Language-Commonsense transformer model, VLC-BERT.
Through our evaluation on the knowledge-intensive OK-VQA and A-OKVQA datasets,
we show that VLC-BERT is capable of outperforming existing models that utilize
static knowledge bases. Furthermore, through a detailed analysis, we explain
which questions benefit, and which don't, from contextualized commonsense
knowledge from COMET.