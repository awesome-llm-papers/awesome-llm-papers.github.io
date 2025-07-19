---
layout: publication
title: A Benchmark For Compositional Visual Reasoning
authors: Zerroug et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: zerroug2022benchmark
citations: 94
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2206.05379'}]
tags: [RAG, Tools, Evaluation, CVPR, Transformer, Model Architecture, Efficiency And
    Optimization, Datasets]
---
A fundamental component of human vision is our ability to parse complex
visual scenes and judge the relations between their constituent objects. AI
benchmarks for visual reasoning have driven rapid progress in recent years with
state-of-the-art systems now reaching human accuracy on some of these
benchmarks. Yet, a major gap remains in terms of the sample efficiency with
which humans and AI systems learn new visual reasoning tasks. Humans'
remarkable efficiency at learning has been at least partially attributed to
their ability to harness compositionality -- such that they can efficiently
take advantage of previously gained knowledge when learning new tasks. Here, we
introduce a novel visual reasoning benchmark, Compositional Visual Relations
(CVR), to drive progress towards the development of more data-efficient
learning algorithms. We take inspiration from fluidic intelligence and
non-verbal reasoning tests and describe a novel method for creating
compositions of abstract rules and associated image datasets at scale. Our
proposed benchmark includes measures of sample efficiency, generalization and
transfer across task rules, as well as the ability to leverage
compositionality. We systematically evaluate modern neural architectures and
find that, surprisingly, convolutional architectures surpass transformer-based
architectures across all performance measures in most data regimes. However,
all computational models are a lot less data efficient compared to humans even
after learning informative visual representations using self-supervision.
Overall, we hope that our challenge will spur interest in the development of
neural architectures that can learn to harness compositionality toward more
efficient learning.