---
layout: publication
title: Relationship-based Neural Baby Talk
authors: Fu et al.
conference: 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition
year: 2021
bibkey: fu2021relationship
citations: 307
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.04846'}]
tags: [Datasets, Model Architecture, CVPR, Attention Mechanism]
---
Understanding interactions between objects in an image is an important
element for generating captions. In this paper, we propose a relationship-based
neural baby talk (R-NBT) model to comprehensively investigate several types of
pairwise object interactions by encoding each image via three different
relationship-based graph attention networks (GATs). We study three main
relationships: \textit\{spatial relationships\} to explore geometric
interactions, \textit\{semantic relationships\} to extract semantic interactions,
and \textit\{implicit relationships\} to capture hidden information that could
not be modelled explicitly as above. We construct three relationship graphs
with the objects in an image as nodes, and the mutual relationships of pairwise
objects as edges. By exploring features of neighbouring regions individually
via GATs, we integrate different types of relationships into visual features of
each node. Experiments on COCO dataset show that our proposed R-NBT model
outperforms state-of-the-art models trained on COCO dataset in three image
caption generation tasks.