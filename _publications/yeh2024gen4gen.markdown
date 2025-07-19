---
layout: publication
title: 'Gen4gen: Generative Data Pipeline For Generative Multi-concept Composition'
authors: Yeh et al.
conference: IEEE Transactions on Cybernetics
year: 2024
bibkey: yeh2024gen4gen
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.15504'}]
tags: [Model Architecture, Prompting, Merging, Training Techniques, Evaluation, Ethics
    and Bias, Datasets]
---
Recent text-to-image diffusion models are able to learn and synthesize images
containing novel, personalized concepts (e.g., their own pets or specific
items) with just a few examples for training. This paper tackles two
interconnected issues within this realm of personalizing text-to-image
diffusion models. First, current personalization techniques fail to reliably
extend to multiple concepts -- we hypothesize this to be due to the mismatch
between complex scenes and simple text descriptions in the pre-training dataset
(e.g., LAION). Second, given an image containing multiple personalized
concepts, there lacks a holistic metric that evaluates performance on not just
the degree of resemblance of personalized concepts, but also whether all
concepts are present in the image and whether the image accurately reflects the
overall text description. To address these issues, we introduce Gen4Gen, a
semi-automated dataset creation pipeline utilizing generative models to combine
personalized concepts into complex compositions along with text-descriptions.
Using this, we create a dataset called MyCanvas, that can be used to benchmark
the task of multi-concept personalization. In addition, we design a
comprehensive metric comprising two scores (CP-CLIP and TI-CLIP) for better
quantifying the performance of multi-concept, personalized text-to-image
diffusion methods. We provide a simple baseline built on top of Custom
Diffusion with empirical prompting strategies for future researchers to
evaluate on MyCanvas. We show that by improving data quality and prompting
strategies, we can significantly increase multi-concept personalized image
generation quality, without requiring any modifications to model architecture
or training algorithms.