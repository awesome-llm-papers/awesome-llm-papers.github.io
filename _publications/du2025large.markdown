---
layout: publication
title: Large Language Model For Lossless Image Compression With Visual Prompts
authors: Du et al.
conference: CHI Conference on Human Factors in Computing Systems Extended Abstracts
year: 2025
bibkey: du2025large
citations: 103
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.16163'}]
tags: [RAG, Prompting, Evaluation, Reinforcement Learning, Datasets]
---
Recent advancements in deep learning have driven significant progress in
lossless image compression. With the emergence of Large Language Models (LLMs),
preliminary attempts have been made to leverage the extensive prior knowledge
embedded in these pretrained models to enhance lossless image compression,
particularly by improving the entropy model. However, a significant challenge
remains in bridging the gap between the textual prior knowledge within LLMs and
lossless image compression. To tackle this challenge and unlock the potential
of LLMs, this paper introduces a novel paradigm for lossless image compression
that incorporates LLMs with visual prompts. Specifically, we first generate a
lossy reconstruction of the input image as visual prompts, from which we
extract features to serve as visual embeddings for the LLM. The residual
between the original image and the lossy reconstruction is then fed into the
LLM along with these visual embeddings, enabling the LLM to function as an
entropy model to predict the probability distribution of the residual.
Extensive experiments on multiple benchmark datasets demonstrate our method
achieves state-of-the-art compression performance, surpassing both traditional
and learning-based lossless image codecs. Furthermore, our approach can be
easily extended to images from other domains, such as medical and screen
content images, achieving impressive performance. These results highlight the
potential of LLMs for lossless image compression and may inspire further
research in related directions.