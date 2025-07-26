---
layout: publication
title: Improved Fusion Of Visual And Language Representations By Dense Symmetric Co-attention
  For Visual Question Answering
authors: Duy-kien Nguyen, Takayuki Okatani
conference: 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition
year: 2018
bibkey: nguyen2018improved
citations: 335
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1804.00775'}]
tags: ["CVPR", "Model Architecture"]
short_authors: Duy-kien Nguyen, Takayuki Okatani
---
A key solution to visual question answering (VQA) exists in how to fuse
visual and language features extracted from an input image and question. We
show that an attention mechanism that enables dense, bi-directional
interactions between the two modalities contributes to boost accuracy of
prediction of answers. Specifically, we present a simple architecture that is
fully symmetric between visual and language representations, in which each
question word attends on image regions and each image region attends on
question words. It can be stacked to form a hierarchy for multi-step
interactions between an image-question pair. We show through experiments that
the proposed architecture achieves a new state-of-the-art on VQA and VQA 2.0
despite its small size. We also present qualitative evaluation, demonstrating
how the proposed attention mechanism can generate reasonable attention maps on
images and questions, which leads to the correct answer prediction.