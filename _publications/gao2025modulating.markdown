---
layout: publication
title: Modulating CNN Features With Pre-trained Vit Representations For Open-vocabulary
  Object Detection
authors: Gao et al.
conference: Lecture Notes in Computer Science
year: 2025
bibkey: gao2025modulating
citations: 144
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.16981'}]
tags: [Training Techniques, Evaluation, Datasets]
---
Owing to large-scale image-text contrastive training, pre-trained vision
language model (VLM) like CLIP shows superior open-vocabulary recognition
ability. Most existing open-vocabulary object detectors attempt to utilize the
pre-trained VLMs to attain generalized representation. F-ViT uses the
pre-trained visual encoder as the backbone network and freezes it during
training. However, its frozen backbone doesn't benefit from the labeled data to
strengthen the representation for detection. Therefore, we propose a novel
two-branch backbone network, named as \textbf\{V\}iT-Feature-\textbf\{M\}odulated
Multi-Scale \textbf\{C\}onvolutional Network (VMCNet), which consists of a
trainable convolutional branch, a frozen pre-trained ViT branch and a VMC
module. The trainable CNN branch could be optimized with labeled data while the
frozen pre-trained ViT branch could keep the representation ability derived
from large-scale pre-training. Then, the proposed VMC module could modulate the
multi-scale CNN features with the representations from ViT branch. With this
proposed mixed structure, the detector is more likely to discover objects of
novel categories. Evaluated on two popular benchmarks, our method boosts the
detection performance on novel category and outperforms state-of-the-art
methods. On OV-COCO, the proposed method achieves 44.3
AP\\(_\{50\}^\{\mathrm\{novel\}\}\\) with ViT-B/16 and 48.5 AP\\(_\{50\}^\{\mathrm\{novel\}\}\\)
with ViT-L/14. On OV-LVIS, VMCNet with ViT-B/16 and ViT-L/14 reaches 27.8 and
38.4 mAP\\(_\{r\}\\).