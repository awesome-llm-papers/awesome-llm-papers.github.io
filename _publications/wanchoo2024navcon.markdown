---
layout: publication
title: 'NAVCON: A Cognitively Inspired And Linguistically Grounded Corpus For Vision
  And Language Navigation'
authors: Wanchoo et al.
conference: 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition
year: 2024
bibkey: wanchoo2024navcon
citations: 598
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.13026'}]
tags: [GPT, Agentic, Evaluation, CVPR, Model Architecture, Few Shot, Multimodal Models,
  Datasets]
---
We present NAVCON, a large-scale annotated Vision-Language Navigation (VLN)
corpus built on top of two popular datasets (R2R and RxR). The paper introduces
four core, cognitively motivated and linguistically grounded, navigation
concepts and an algorithm for generating large-scale silver annotations of
naturally occurring linguistic realizations of these concepts in navigation
instructions. We pair the annotated instructions with video clips of an agent
acting on these instructions. NAVCON contains 236, 316 concept annotations for
approximately 30, 0000 instructions and 2.7 million aligned images (from
approximately 19, 000 instructions) showing what the agent sees when executing
an instruction. To our knowledge, this is the first comprehensive resource of
navigation concepts. We evaluated the quality of the silver annotations by
conducting human evaluation studies on NAVCON samples. As further validation of
the quality and usefulness of the resource, we trained a model for detecting
navigation concepts and their linguistic realizations in unseen instructions.
Additionally, we show that few-shot learning with GPT-4o performs well on this
task using large-scale silver annotations of NAVCON.