---
layout: publication
title: Opcap:object-aware Prompting Captioning
authors: Huang Feiyang
conference: IEEE Transactions on Neural Networks and Learning Systems
year: 2024
bibkey: huang2024opcap
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.00095'}]
tags: [Datasets, Prompting, Ethics And Bias]
---
In the field of image captioning, the phenomenon where missing or nonexistent
objects are used to explain an image is referred to as object bias (or
hallucination). To mitigate this issue, we propose a target-aware prompting
strategy. This method first extracts object labels and their spatial
information from the image using an object detector. Then, an attribute
predictor further refines the semantic features of the objects. These refined
features are subsequently integrated and fed into the decoder, enhancing the
model's understanding of the image context. Experimental results on the COCO
and nocaps datasets demonstrate that OPCap effectively mitigates hallucination
and significantly improves the quality of generated captions.