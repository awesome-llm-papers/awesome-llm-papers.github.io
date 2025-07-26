---
layout: publication
title: Learning Conditioned Graph Structures For Interpretable Visual Question Answering
authors: Will Norcliffe-brown, Efstathios Vafeias, Sarah Parisot
conference: Arxiv
year: 2018
bibkey: norcliffebrown2018learning
citations: 114
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1806.07243'}]
tags: ["Model Architecture"]
short_authors: Will Norcliffe-brown, Efstathios Vafeias, Sarah Parisot
---
Visual Question answering is a challenging problem requiring a combination of
concepts from Computer Vision and Natural Language Processing. Most existing
approaches use a two streams strategy, computing image and question features
that are consequently merged using a variety of techniques. Nonetheless, very
few rely on higher level image representations, which can capture semantic and
spatial relationships. In this paper, we propose a novel graph-based approach
for Visual Question Answering. Our method combines a graph learner module,
which learns a question specific graph representation of the input image, with
the recent concept of graph convolutions, aiming to learn image representations
that capture question specific interactions. We test our approach on the VQA v2
dataset using a simple baseline architecture enhanced by the proposed graph
learner module. We obtain promising results with 66.18% accuracy and
demonstrate the interpretability of the proposed method. Code can be found at
github.com/aimbrain/vqa-project.