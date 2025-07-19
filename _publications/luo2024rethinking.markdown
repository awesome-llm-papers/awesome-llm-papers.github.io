---
layout: publication
title: Rethinking 3D Dense Caption And Visual Grounding In A Unified Framework Through
  Prompt-based Localization
authors: Luo et al.
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: luo2024rethinking
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2404.11064'}]
tags: [Training Techniques, Prompting, Tools, CVPR, Applications, Datasets]
---
3D Visual Grounding (3DVG) and 3D Dense Captioning (3DDC) are two crucial
tasks in various 3D applications, which require both shared and complementary
information in localization and visual-language relationships. Therefore,
existing approaches adopt the two-stage "detect-then-describe/discriminate"
pipeline, which relies heavily on the performance of the detector, resulting in
suboptimal performance. Inspired by DETR, we propose a unified framework,
3DGCTR, to jointly solve these two distinct but closely related tasks in an
end-to-end fashion. The key idea is to reconsider the prompt-based localization
ability of the 3DVG model. In this way, the 3DVG model with a well-designed
prompt as input can assist the 3DDC task by extracting localization information
from the prompt. In terms of implementation, we integrate a Lightweight Caption
Head into the existing 3DVG network with a Caption Text Prompt as a connection,
effectively harnessing the existing 3DVG model's inherent localization
capacity, thereby boosting 3DDC capability. This integration facilitates
simultaneous multi-task training on both tasks, mutually enhancing their
performance. Extensive experimental results demonstrate the effectiveness of
this approach. Specifically, on the ScanRefer dataset, 3DGCTR surpasses the
state-of-the-art 3DDC method by 4.3% in CIDEr@0.5IoU in MLE training and
improves upon the SOTA 3DVG method by 3.16% in Acc@0.25IoU. The codes are at
https://github.com/Leon1207/3DGCTR.