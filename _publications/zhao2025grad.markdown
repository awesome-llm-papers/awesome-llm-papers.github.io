---
layout: publication
title: 'Grad-eclip: Gradient-based Visual And Textual Explanations For CLIP'
authors: Zhao et al.
conference: International Journal of Computer Vision
year: 2025
bibkey: zhao2025grad
citations: 3733
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.18816'}]
tags: [Interpretability And Explainability, Training Techniques, Attention Mechanism,
  Evaluation, Transformer, Model Architecture, Fine Tuning, Multimodal Models]
---
Significant progress has been achieved on the improvement and downstream
usages of the Contrastive Language-Image Pre-training (CLIP) vision-language
model, while less attention is paid to the interpretation of CLIP. We propose a
Gradient-based visual and textual Explanation method for CLIP (Grad-ECLIP),
which interprets the matching result of CLIP for specific input image-text
pair. By decomposing the architecture of the encoder and discovering the
relationship between the matching similarity and intermediate spatial features,
Grad-ECLIP produces effective heat maps that show the influence of image
regions or words on the CLIP results. Different from the previous Transformer
interpretation methods that focus on the utilization of self-attention maps,
which are typically extremely sparse in CLIP, we produce high-quality visual
explanations by applying channel and spatial weights on token features.
Qualitative and quantitative evaluations verify the effectiveness and
superiority of Grad-ECLIP compared with the state-of-the-art methods.
Furthermore, a series of analysis are conducted based on our visual and textual
explanation results, from which we explore the working mechanism of image-text
matching, the strengths and limitations in attribution identification of CLIP,
and the relationship between the concreteness/abstractness of a word and its
usage in CLIP. Finally, based on the ability of explanation map that indicates
text-specific saliency region of input image, we also propose an application
with Grad-ECLIP, which is adopted to boost the fine-grained alignment in the
CLIP fine-tuning. The code of Grad-ECLIP is available here:
https://github.com/Cyang-Zhao/Grad-Eclip.