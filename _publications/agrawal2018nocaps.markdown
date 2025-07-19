---
layout: publication
title: 'Nocaps: Novel Object Captioning At Scale'
authors: Agrawal et al.
conference: 2019 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2018
bibkey: agrawal2018nocaps
citations: 267
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1812.08658'}]
tags: [RAG, ICCV, Training Techniques, Alt, Evaluation, Reinforcement Learning, Datasets]
---
Image captioning models have achieved impressive results on datasets
containing limited visual concepts and large amounts of paired image-caption
training data. However, if these models are to ever function in the wild, a
much larger variety of visual concepts must be learned, ideally from less
supervision. To encourage the development of image captioning models that can
learn visual concepts from alternative data sources, such as object detection
datasets, we present the first large-scale benchmark for this task. Dubbed
'nocaps', for novel object captioning at scale, our benchmark consists of
166,100 human-generated captions describing 15,100 images from the OpenImages
validation and test sets. The associated training data consists of COCO
image-caption pairs, plus OpenImages image-level labels and object bounding
boxes. Since OpenImages contains many more classes than COCO, nearly 400 object
classes seen in test images have no or very few associated training captions
(hence, nocaps). We extend existing novel object captioning models to establish
strong baselines for this benchmark and provide analysis to guide future work
on this task.