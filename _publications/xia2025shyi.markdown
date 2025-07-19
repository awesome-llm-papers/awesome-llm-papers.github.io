---
layout: publication
title: 'SHYI: Action Support For Contrastive Learning In High-fidelity Text-to-image
  Generation'
authors: Xia et al.
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: xia2025shyi
citations: 227
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.09055'}]
tags: [Tools, CVPR, Evaluation, Reinforcement Learning, Merging]
---
In this project, we address the issue of infidelity in text-to-image
generation, particularly for actions involving multiple objects. For this we
build on top of the CONFORM framework which uses Contrastive Learning to
improve the accuracy of the generated image for multiple objects. However the
depiction of actions which involves multiple different object has still large
room for improvement. To improve, we employ semantically hypergraphic
contrastive adjacency learning, a comprehension of enhanced contrastive
structure and "contrast but link" technique. We further amend Stable
Diffusion's understanding of actions by InteractDiffusion. As evaluation
metrics we use image-text similarity CLIP and TIFA. In addition, we conducted a
user study.
  Our method shows promising results even with verbs that Stable Diffusion
understands mediocrely. We then provide future directions by analyzing the
results.
  Our codebase can be found on polybox under the link:
https://polybox.ethz.ch/index.php/s/dJm3SWyRohUrFxn