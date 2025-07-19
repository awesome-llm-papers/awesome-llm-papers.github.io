---
layout: publication
title: Unlocking Spatial Comprehension In Text-to-image Diffusion Models
authors: Derakhshani et al.
conference: Discourse Processes
year: 2023
bibkey: derakhshani2023unlocking
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.17937'}]
tags: [RAG, Training Techniques, Merging]
---
We propose CompFuser, an image generation pipeline that enhances spatial
comprehension and attribute assignment in text-to-image generative models. Our
pipeline enables the interpretation of instructions defining spatial
relationships between objects in a scene, such as `An image of a gray cat on
the left of an orange dog', and generate corresponding images. This is
especially important in order to provide more control to the user. CompFuser
overcomes the limitation of existing text-to-image diffusion models by decoding
the generation of multiple objects into iterative steps: first generating a
single object and then editing the image by placing additional objects in their
designated positions. To create training data for spatial comprehension and
attribute assignment we introduce a synthetic data generation process, that
leverages a frozen large language model and a frozen layout-based diffusion
model for object placement. We compare our approach to strong baselines and
show that our model outperforms state-of-the-art image generation models in
spatial comprehension and attribute assignment, despite being 3x to 5x smaller
in parameters.