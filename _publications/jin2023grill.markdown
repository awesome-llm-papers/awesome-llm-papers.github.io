---
layout: publication
title: 'GRILL: Grounded Vision-language Pre-training Via Aligning Text And Image Regions'
authors: Jin et al.
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: jin2023grill
citations: 520
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.14676'}]
tags: [Training Techniques, CVPR, Few Shot, Multimodal Models]
---
Generalization to unseen tasks is an important ability for few-shot learners
to achieve better zero-/few-shot performance on diverse tasks. However, such
generalization to vision-language tasks including grounding and generation
tasks has been under-explored; existing few-shot VL models struggle to handle
tasks that involve object grounding and multiple images such as visual
commonsense reasoning or NLVR2. In this paper, we introduce GRILL, GRounded
vIsion Language aLigning, a novel VL model that can be generalized to diverse
tasks including visual question answering, captioning, and grounding tasks with
no or very few training instances. Specifically, GRILL learns object grounding
and localization by exploiting object-text alignments, which enables it to
transfer to grounding tasks in a zero-/few-shot fashion. We evaluate our model
on various zero-/few-shot VL tasks and show that it consistently surpasses the
state-of-the-art few-shot methods.