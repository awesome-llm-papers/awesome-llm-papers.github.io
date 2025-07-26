---
layout: publication
title: 'Multimodal Explanations: Justifying Decisions And Pointing To The Evidence'
authors: Dong Huk Park, Lisa Anne Hendricks, Zeynep Akata, Anna Rohrbach, Bernt Schiele,
  Trevor Darrell, Marcus Rohrbach
conference: 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition
year: 2018
bibkey: park2018multimodal
citations: 336
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1802.08129'}]
tags: ["CVPR"]
short_authors: Park et al.
---
Deep models that are both effective and explainable are desirable in many
settings; prior explainable models have been unimodal, offering either
image-based visualization of attention weights or text-based generation of
post-hoc justifications. We propose a multimodal approach to explanation, and
argue that the two modalities provide complementary explanatory strengths. We
collect two new datasets to define and evaluate this task, and propose a novel
model which can provide joint textual rationale generation and attention
visualization. Our datasets define visual and textual justifications of a
classification decision for activity recognition tasks (ACT-X) and for visual
question answering tasks (VQA-X). We quantitatively show that training with the
textual explanations not only yields better textual justification models, but
also better localizes the evidence that supports the decision. We also
qualitatively show cases where visual explanation is more insightful than
textual explanation, and vice versa, supporting our thesis that multimodal
explanation models offer significant benefits over unimodal approaches.