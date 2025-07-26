---
layout: publication
title: 'DAE-GAN: Dynamic Aspect-aware GAN For Text-to-image Synthesis'
authors: Shulan Ruan, Yong Zhang, Kun Zhang, Yanbo Fan, Fan Tang, Qi Liu, Enhong Chen
conference: 2021 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2021
bibkey: ruan2021dae
citations: 90
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2108.12141'}]
tags: ["ICCV"]
short_authors: Ruan et al.
---
Text-to-image synthesis refers to generating an image from a given text
description, the key goal of which lies in photo realism and semantic
consistency. Previous methods usually generate an initial image with sentence
embedding and then refine it with fine-grained word embedding. Despite the
significant progress, the 'aspect' information (e.g., red eyes) contained in
the text, referring to several words rather than a word that depicts 'a
particular part or feature of something', is often ignored, which is highly
helpful for synthesizing image details. How to make better utilization of
aspect information in text-to-image synthesis still remains an unresolved
challenge. To address this problem, in this paper, we propose a Dynamic
Aspect-awarE GAN (DAE-GAN) that represents text information comprehensively
from multiple granularities, including sentence-level, word-level, and
aspect-level. Moreover, inspired by human learning behaviors, we develop a
novel Aspect-aware Dynamic Re-drawer (ADR) for image refinement, in which an
Attended Global Refinement (AGR) module and an Aspect-aware Local Refinement
(ALR) module are alternately employed. AGR utilizes word-level embedding to
globally enhance the previously generated image, while ALR dynamically employs
aspect-level embedding to refine image details from a local perspective.
Finally, a corresponding matching loss function is designed to ensure the
text-image semantic consistency at different levels. Extensive experiments on
two well-studied and publicly available datasets (i.e., CUB-200 and COCO)
demonstrate the superiority and rationality of our method.