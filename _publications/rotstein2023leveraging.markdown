---
layout: publication
title: 'Fusecap: Leveraging Large Language Models For Enriched Fused Image Captions'
authors: Noam Rotstein, David Bensaid, Shaked Brody, Roy Ganz, Ron Kimmel
conference: Arxiv
year: 2023
citations: 30
bibkey: rotstein2023leveraging
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.17718'}]
tags: [RAG, Pre-Training, Training Techniques, Multimodal Models]
---
The advent of vision-language pre-training techniques enhanced substantial
progress in the development of models for image captioning. However, these
models frequently produce generic captions and may omit semantically important
image details. This limitation can be traced back to the image-text datasets;
while their captions typically offer a general description of image content,
they frequently omit salient details. Considering the magnitude of these
datasets, manual reannotation is impractical, emphasizing the need for an
automated approach. To address this challenge, we leverage existing captions
and explore augmenting them with visual details using "frozen" vision experts
including an object detector, an attribute recognizer, and an Optical Character
Recognizer (OCR). Our proposed method, FuseCap, fuses the outputs of such
vision experts with the original captions using a large language model (LLM),
yielding comprehensive image descriptions. We automatically curate a training
set of 12M image-enriched caption pairs. These pairs undergo extensive
evaluation through both quantitative and qualitative analyses. Subsequently,
this data is utilized to train a captioning generation BLIP-based model. This
model outperforms current state-of-the-art approaches, producing more precise
and detailed descriptions, demonstrating the effectiveness of the proposed
data-centric approach. We release this large-scale dataset of enriched
image-caption pairs for the community.