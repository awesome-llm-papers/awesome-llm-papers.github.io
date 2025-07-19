---
layout: publication
title: 'SA-VQA: Structured Alignment Of Visual And Semantic Representations For Visual
  Question Answering'
authors: Xiong et al.
conference: International Journal of Computer Vision
year: 2022
bibkey: xiong2022sa
citations: 229
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2201.10654'}]
tags: [Interpretability And Explainability, Training Techniques, Attention Mechanism,
  Model Architecture, Multimodal Models, Datasets]
---
Visual Question Answering (VQA) attracts much attention from both industry
and academia. As a multi-modality task, it is challenging since it requires not
only visual and textual understanding, but also the ability to align
cross-modality representations. Previous approaches extensively employ
entity-level alignments, such as the correlations between the visual regions
and their semantic labels, or the interactions across question words and object
features. These attempts aim to improve the cross-modality representations,
while ignoring their internal relations. Instead, we propose to apply
structured alignments, which work with graph representation of visual and
textual content, aiming to capture the deep connections between the visual and
textual modalities. Nevertheless, it is nontrivial to represent and integrate
graphs for structured alignments. In this work, we attempt to solve this issue
by first converting different modality entities into sequential nodes and the
adjacency graph, then incorporating them for structured alignments. As
demonstrated in our experimental results, such a structured alignment improves
reasoning performance. In addition, our model also exhibits better
interpretability for each generated answer. The proposed model, without any
pretraining, outperforms the state-of-the-art methods on GQA dataset, and beats
the non-pretrained state-of-the-art methods on VQA-v2 dataset.