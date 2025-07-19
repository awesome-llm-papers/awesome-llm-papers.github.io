---
layout: publication
title: 'Dygenc: Encoding A Sequence Of Textual Scene Graphs To Reason And Answer Questions
  In Dynamic Scenes'
authors: Linok et al.
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: linok2025dygenc
citations: 164
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.03581'}]
tags: [Agentic, Tools, CVPR, Evaluation, Datasets]
---
The analysis of events in dynamic environments poses a fundamental challenge
in the development of intelligent agents and robots capable of interacting with
humans. Current approaches predominantly utilize visual models. However, these
methods often capture information implicitly from images, lacking interpretable
spatial-temporal object representations. To address this issue we introduce
DyGEnc - a novel method for Encoding a Dynamic Graph. This method integrates
compressed spatial-temporal structural observation representation with the
cognitive capabilities of large language models. The purpose of this
integration is to enable advanced question answering based on a sequence of
textual scene graphs. Extended evaluations on the STAR and AGQA datasets
indicate that DyGEnc outperforms existing visual methods by a large margin of
15-25% in addressing queries regarding the history of human-to-object
interactions. Furthermore, the proposed method can be seamlessly extended to
process raw input images utilizing foundational models for extracting explicit
textual scene graphs, as substantiated by the results of a robotic experiment
conducted with a wheeled manipulator platform. We hope that these findings will
contribute to the implementation of robust and compressed graph-based robotic
memory for long-horizon reasoning. Code is available at
github.com/linukc/DyGEnc.