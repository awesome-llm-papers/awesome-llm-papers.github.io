---
layout: publication
title: Transformed Low-rank Adaptation Via Tensor Decomposition And Its Applications
  To Text-to-image Models
authors: Tao et al.
conference: IEEE Journal of Selected Topics in Applied Earth Observations and Remote
  Sensing
year: 2025
bibkey: tao2025transformed
citations: 379
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.08727'}]
tags: [Training Techniques, Attention Mechanism, Model Architecture, Efficiency And
    Optimization, Applications, Fine Tuning, Merging]
---
Parameter-Efficient Fine-Tuning (PEFT) of text-to-image models has become an
increasingly popular technique with many applications. Among the various PEFT
methods, Low-Rank Adaptation (LoRA) and its variants have gained significant
attention due to their effectiveness, enabling users to fine-tune models with
limited computational resources. However, the approximation gap between the
low-rank assumption and desired fine-tuning weights prevents the simultaneous
acquisition of ultra-parameter-efficiency and better performance. To reduce
this gap and further improve the power of LoRA, we propose a new PEFT method
that combines two classes of adaptations, namely, transform and residual
adaptations. In specific, we first apply a full-rank and dense transform to the
pre-trained weight. This learnable transform is expected to align the
pre-trained weight as closely as possible to the desired weight, thereby
reducing the rank of the residual weight. Then, the residual part can be
effectively approximated by more compact and parameter-efficient structures,
with a smaller approximation error. To achieve ultra-parameter-efficiency in
practice, we design highly flexible and effective tensor decompositions for
both the transform and residual adaptations. Additionally, popular PEFT methods
such as DoRA can be summarized under this transform plus residual adaptation
scheme. Experiments are conducted on fine-tuning Stable Diffusion models in
subject-driven and controllable generation. The results manifest that our
method can achieve better performances and parameter efficiency compared to
LoRA and several baselines.