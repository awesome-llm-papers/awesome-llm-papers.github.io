---
layout: publication
title: 'Clip-event: Connecting Text And Images With Event Structures'
authors: Li et al.
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: li2022clip
citations: 84
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2201.05078'}]
tags: [Training Techniques, Prompting, Tools, CVPR, Evaluation, Reinforcement Learning,
  Applications, Multimodal Models, Datasets]
---
Vision-language (V+L) pretraining models have achieved great success in
supporting multimedia applications by understanding the alignments between
images and text. While existing vision-language pretraining models primarily
focus on understanding objects in images or entities in text, they often ignore
the alignment at the level of events and their argument structures. In this
work, we propose a contrastive learning framework to enforce vision-language
pretraining models to comprehend events and associated argument (participant)
roles. To achieve this, we take advantage of text information extraction
technologies to obtain event structural knowledge, and utilize multiple prompt
functions to contrast difficult negative descriptions by manipulating event
structures. We also design an event graph alignment loss based on optimal
transport to capture event argument structures. In addition, we collect a large
event-rich dataset (106,875 images) for pretraining, which provides a more
challenging image retrieval benchmark to assess the understanding of
complicated lengthy sentences. Experiments show that our zero-shot CLIP-Event
outperforms the state-of-the-art supervised model in argument extraction on
Multimedia Event Extraction, achieving more than 5% absolute F-score gain in
event extraction, as well as significant improvements on a variety of
downstream tasks under zero-shot settings.