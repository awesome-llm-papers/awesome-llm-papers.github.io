---
layout: publication
title: Text-conditional Contextualized Avatars For Zero-shot Personalization
authors: Azadi et al.
conference: 'Proceedings of the 16th Conference of the European Chapter of the Association
  for Computational Linguistics: Main Volume'
year: 2023
bibkey: azadi2023text
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.07410'}]
tags: [Merging, Prompting, Training Techniques, Datasets, ACL, RAG, EACL]
---
Recent large-scale text-to-image generation models have made significant
improvements in the quality, realism, and diversity of the synthesized images
and enable users to control the created content through language. However, the
personalization aspect of these generative models is still challenging and
under-explored. In this work, we propose a pipeline that enables
personalization of image generation with avatars capturing a user's identity in
a delightful way. Our pipeline is zero-shot, avatar texture and style agnostic,
and does not require training on the avatar at all - it is scalable to millions
of users who can generate a scene with their avatar. To render the avatar in a
pose faithful to the given text prompt, we propose a novel text-to-3D pose
diffusion model trained on a curated large-scale dataset of in-the-wild human
poses improving the performance of the SOTA text-to-motion models
significantly. We show, for the first time, how to leverage large-scale image
datasets to learn human 3D pose parameters and overcome the limitations of
motion capture datasets.