---
layout: publication
title: More Grounded Image Captioning By Distilling Image-text Matching Model
authors: Yuanen Zhou, Meng Wang, Daqing Liu, Zhenzhen Hu, Hanwang Zhang
conference: 2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2020
bibkey: zhou2020more
citations: 122
additional_links: [{name: Code, url: 'https://github.com/YuanEZhou/Grounded-Image-Captioning\'},
  {name: Paper, url: 'https://arxiv.org/abs/2004.00390'}]
tags: ["CVPR"]
short_authors: Zhou et al.
---
Visual attention not only improves the performance of image captioners, but
also serves as a visual interpretation to qualitatively measure the caption
rationality and model transparency. Specifically, we expect that a captioner
can fix its attentive gaze on the correct objects while generating the
corresponding words. This ability is also known as grounded image captioning.
However, the grounding accuracy of existing captioners is far from
satisfactory. To improve the grounding accuracy while retaining the captioning
quality, it is expensive to collect the word-region alignment as strong
supervision. To this end, we propose a Part-of-Speech (POS) enhanced image-text
matching model (SCAN \cite\{lee2018stacked\}): POS-SCAN, as the effective
knowledge distillation for more grounded image captioning. The benefits are
two-fold: 1) given a sentence and an image, POS-SCAN can ground the objects
more accurately than SCAN; 2) POS-SCAN serves as a word-region alignment
regularization for the captioner's visual attention module. By showing
benchmark experimental results, we demonstrate that conventional image
captioners equipped with POS-SCAN can significantly improve the grounding
accuracy without strong supervision. Last but not the least, we explore the
indispensable Self-Critical Sequence Training (SCST) \cite\{Rennie_2017_CVPR\} in
the context of grounded image captioning and show that the image-text matching
score can serve as a reward for more grounded captioning
\footnote\{https://github.com/YuanEZhou/Grounded-Image-Captioning\}.