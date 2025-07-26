---
layout: publication
title: Zero-shot Text-guided Object Generation With Dream Fields
authors: Ajay Jain, Ben Mildenhall, Jonathan T. Barron, Pieter Abbeel, Ben Poole
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: jain2021zero
citations: 279
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2112.01455'}]
tags: ["CVPR"]
short_authors: Jain et al.
---
We combine neural rendering with multi-modal image and text representations
to synthesize diverse 3D objects solely from natural language descriptions. Our
method, Dream Fields, can generate the geometry and color of a wide range of
objects without 3D supervision. Due to the scarcity of diverse, captioned 3D
data, prior methods only generate objects from a handful of categories, such as
ShapeNet. Instead, we guide generation with image-text models pre-trained on
large datasets of captioned images from the web. Our method optimizes a Neural
Radiance Field from many camera views so that rendered images score highly with
a target caption according to a pre-trained CLIP model. To improve fidelity and
visual quality, we introduce simple geometric priors, including
sparsity-inducing transmittance regularization, scene bounds, and new MLP
architectures. In experiments, Dream Fields produce realistic, multi-view
consistent object geometry and color from a variety of natural language
captions.