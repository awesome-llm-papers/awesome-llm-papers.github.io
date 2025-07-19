---
layout: publication
title: Turning A CLIP Model Into A Scene Text Detector
authors: Yu et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: yu2023turning
citations: 57
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2302.14338'}]
tags: [RAG, Training Techniques, Tools, CVPR, Evaluation, Few Shot, Reinforcement
    Learning, Fine Tuning, Datasets]
---
The recent large-scale Contrastive Language-Image Pretraining (CLIP) model
has shown great potential in various downstream tasks via leveraging the
pretrained vision and language knowledge. Scene text, which contains rich
textual and visual information, has an inherent connection with a model like
CLIP. Recently, pretraining approaches based on vision language models have
made effective progresses in the field of text detection. In contrast to these
works, this paper proposes a new method, termed TCM, focusing on Turning the
CLIP Model directly for text detection without pretraining process. We
demonstrate the advantages of the proposed TCM as follows: (1) The underlying
principle of our framework can be applied to improve existing scene text
detector. (2) It facilitates the few-shot training capability of existing
methods, e.g., by using 10% of labeled data, we significantly improve the
performance of the baseline method with an average of 22% in terms of the
F-measure on 4 benchmarks. (3) By turning the CLIP model into existing scene
text detection methods, we further achieve promising domain adaptation ability.
The code will be publicly released at https://github.com/wenwenyu/TCM.