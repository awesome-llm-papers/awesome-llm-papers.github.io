---
layout: publication
title: 'Tips And Tricks For Visual Question Answering: Learnings From The 2017 Challenge'
authors: Damien Teney, Peter Anderson, Xiaodong He, Anton van Den Hengel
conference: 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition
year: 2018
bibkey: teney2017tips
citations: 407
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1708.02711'}]
tags: ["Applications", "CVPR", "Evaluation"]
short_authors: Teney et al.
---
This paper presents a state-of-the-art model for visual question answering
(VQA), which won the first place in the 2017 VQA Challenge. VQA is a task of
significant importance for research in artificial intelligence, given its
multimodal nature, clear evaluation protocol, and potential real-world
applications. The performance of deep neural networks for VQA is very dependent
on choices of architectures and hyperparameters. To help further research in
the area, we describe in detail our high-performing, though relatively simple
model. Through a massive exploration of architectures and hyperparameters
representing more than 3,000 GPU-hours, we identified tips and tricks that lead
to its success, namely: sigmoid outputs, soft training targets, image features
from bottom-up attention, gated tanh activations, output embeddings initialized
using GloVe and Google Images, large mini-batches, and smart shuffling of
training data. We provide a detailed analysis of their impact on performance to
assist others in making an appropriate selection.