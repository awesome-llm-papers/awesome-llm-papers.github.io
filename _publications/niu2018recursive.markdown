---
layout: publication
title: Recursive Visual Attention In Visual Dialog
authors: Yulei Niu, Hanwang Zhang, Manli Zhang, Jianhong Zhang, Zhiwu Lu, Ji-rong
  Wen
conference: 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2019
bibkey: niu2018recursive
citations: 139
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1812.02664'}]
tags: ["CVPR", "Has Code", "Model Architecture"]
short_authors: Niu et al.
---
Visual dialog is a challenging vision-language task, which requires the agent
to answer multi-round questions about an image. It typically needs to address
two major problems: (1) How to answer visually-grounded questions, which is the
core challenge in visual question answering (VQA); (2) How to infer the
co-reference between questions and the dialog history. An example of visual
co-reference is: pronouns (\eg, ``they'') in the question (\eg, ``Are they on
or off?'') are linked with nouns (\eg, ``lamps'') appearing in the dialog
history (\eg, ``How many lamps are there?'') and the object grounded in the
image. In this work, to resolve the visual co-reference for visual dialog, we
propose a novel attention mechanism called Recursive Visual Attention (RvA).
Specifically, our dialog agent browses the dialog history until the agent has
sufficient confidence in the visual co-reference resolution, and refines the
visual attention recursively. The quantitative and qualitative experimental
results on the large-scale VisDial v0.9 and v1.0 datasets demonstrate that the
proposed RvA not only outperforms the state-of-the-art methods, but also
achieves reasonable recursion and interpretable attention maps without
additional annotations. The code is available at
https://github.com/yuleiniu/rva.