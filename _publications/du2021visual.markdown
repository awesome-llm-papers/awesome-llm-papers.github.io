---
layout: publication
title: Visual Grounding With Transformers
authors: Du et al.
conference: 2021 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2021
bibkey: du2021visual
citations: 224
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2105.04281'}]
tags: [ICCV, Tools, Evaluation, Transformer, Model Architecture, Datasets]
---
In this paper, we propose a transformer based approach for visual grounding.
Unlike previous proposal-and-rank frameworks that rely heavily on pretrained
object detectors or proposal-free frameworks that upgrade an off-the-shelf
one-stage detector by fusing textual embeddings, our approach is built on top
of a transformer encoder-decoder and is independent of any pretrained detectors
or word embedding models. Termed VGTR -- Visual Grounding with TRansformers,
our approach is designed to learn semantic-discriminative visual features under
the guidance of the textual description without harming their location ability.
This information flow enables our VGTR to have a strong capability in capturing
context-level semantics of both vision and language modalities, rendering us to
aggregate accurate visual clues implied by the description to locate the
interested object instance. Experiments show that our method outperforms
state-of-the-art proposal-free approaches by a considerable margin on five
benchmarks while maintaining fast inference speed.