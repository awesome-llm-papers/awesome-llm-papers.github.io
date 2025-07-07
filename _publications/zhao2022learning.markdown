---
layout: publication
title: Learning Video Representations From Large Language Models
authors: "Yue Zhao, Ishan Misra, Philipp Kr\xE4henb\xFChl, Rohit Girdhar"
conference: Arxiv
year: 2022
citations: 75
bibkey: zhao2022learning
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.04501'}]
tags: [RAG, Pre-Training, Training Techniques]
---
We introduce LaViLa, a new approach to learning video-language
representations by leveraging Large Language Models (LLMs). We repurpose
pre-trained LLMs to be conditioned on visual input, and finetune them to create
automatic video narrators. Our auto-generated narrations offer a number of
advantages, including dense coverage of long videos, better temporal
synchronization of the visual information and text, and much higher diversity
of text. The video-text embedding learned contrastively with these additional
auto-generated narrations outperforms the previous state-of-the-art on multiple
first-person and third-person video tasks, both in zero-shot and finetuned
setups. Most notably, LaViLa obtains an absolute gain of 10.1% on EGTEA
classification and 5.9% Epic-Kitchens-100 multi-instance retrieval benchmarks.
Furthermore, LaViLa trained with only half the narrations from the Ego4D
dataset outperforms baseline models trained on the full set, and shows positive
scaling behavior on increasing pre-training data and model size.